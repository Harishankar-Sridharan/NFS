# The different statuses for appointments in NFS

An **appointment** represents a planned meeting between a field resource and a customer. In **NFS**, each appointment has a **status** that indicates its current stage in the planning process.

The appointment status helps users and the application distinguish between appointments and determines which actions can be performed on them.

For example, when an appointment has been confirmed with a customer by telephone, it represents a firm commitment. The planner can **confirm** the appointment in NFS to indicate that the appointment is fixed.

Once an appointment is confirmed, key planning details such as the **assigned resource, date, and time can no longer be modified**.

#### Status Macros

To make appointments easier to **identify, search, and count**, NFS groups appointment statuses into five categories called **status macros**:

1. **Candidate:** The appointment is not yet included in the planning and remains in a holding group until it is added to the planning.
2. **Planned:** The appointment is included in the planning and is awaiting execution.
3. **Fulfilled:** The appointment has been completed, either according to the original plan or with deviations from the plan.
4. **Cancelled:** The appointment has been removed from the planning.
5. **Archived:** A record of the appointment's previous status is stored after a status change.

#### Status Transitions

An appointment can move from one status to another, or from one status macro to another, according to the rules defined in NFS.

* A **Candidate** appointment can become **Planned** and then **Fulfilled** once the visit has been completed.
* A **Planned** appointment can be **re-activated** or **unplanned**, returning it to the **Candidate** status.
* An appointment can be **Cancelled** from any status macro.
* Whenever an appointment's status changes, NFS stores a record of the previous and new statuses in the **Archived** history.

Possible transitions between status macros

![images/ref/planification/macro-statut.png](../.gitbook/assets/macro-statut.png)

### Statuses

The following tables list the **names, codes, and behaviours** associated with each appointment status. Each table corresponds to one of the five **status macros**.

Candidate appointments

|            |          |                                                                                                                                                                                                     |
| ---------- | -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Status** | **Code** | **Description**                                                                                                                                                                                     |
| Requested  | 21       | The appointment is not in the planning, and the resource, the date and time are not fixed.                                                                                                          |
| Suspended  | 6        | The appointment has been taken out of the planning and cannot be optimized automatically. It is awaiting application of some kind of action (re-activation, planning, or cancellation) by the user. |

Planned appointments

|            |          |                                                                                                              |
| ---------- | -------- | ------------------------------------------------------------------------------------------------------------ |
| **Status** | **Code** | **Description**                                                                                              |
| Planned    | 2        | The appointment is in the planning, the resource, the date and the time may change.                          |
| Accepted   | 28       | The appointment is in the planning, the date and the time may change, but the resource **CANNOT** change     |
| Reserved   | 30       | The appointment is in the planning, the resource may change, however the date and the time **CANNOT** change |
| Confirmed  | 31       | The appointment is in the planning, the resource, the date and the time **CANNOT BE CHANGED**.               |

Fulfilled appointments

|            |          |                                                                                                                   |
| ---------- | -------- | ----------------------------------------------------------------------------------------------------------------- |
| **Status** | **Code** | **Description**                                                                                                   |
| Realized   | 3        | The appointment has been made and declared as fulfilled in conformity with the event planned                      |
| Shifted    | 33       | The appointment has been made and declared as fulfilled, but not in conformity with events as planned             |
| Happened   | 35       | The appointment has been made and declared as fulfilled, but it was not planned (planned, reserved, or confirmed) |

Cancelled appointments

|            |          |                                                                          |
| ---------- | -------- | ------------------------------------------------------------------------ |
| **Status** | **Code** | **Description**                                                          |
| Removed    | 12       | The appointment has been cancelled even though it is still in a planning |
| Abandonned | 10       | The appointment has been cancelled even though it is still a candidate   |

Appointments set aside

|              |          |                                                                                            |
| ------------ | -------- | ------------------------------------------------------------------------------------------ |
| **Status**   | **Code** | **Description**                                                                            |
| Ignored      | 9        | The appointment is no longer part of the application up until a point where it is restored |
| Externalized | 32       | The appointment has been fulfilled by a subcontractor                                      |

Appointments that have been archived

|            |          |                                                                                         |
| ---------- | -------- | --------------------------------------------------------------------------------------- |
| **Status** | **Code** | **Description**                                                                         |
| Historized | 40       | These appointments are not treated. They are stored in journal form in the application. |

### Progression steps

When an appointment is taken on board by a resource, a second status serves to track its progress. This is the _`PROGRESSIONSTEP`_ field in the [CSV exchange template](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#CSV-modele). The names, codes and behaviours of statuses are described in the table below.

|                 |          |                                                                                                                                                                    |
| --------------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Status**      | **Code** | **Description**                                                                                                                                                    |
| In preparation  | -10      | The appointment is saved, but not in NFS - possible associated statuses: 21                                                                                        |
| Scheduling      | 0        | Default value. The appointment is saved in NFS - possible associated statuses: 21, 2, 6, 29, 30, 31                                                                |
| Back scheduling | 2        | The appointment has not been fulfilled as planned, and has been reactivated                                                                                        |
| Merged          | 3        | The appointment is cancelled, because it has been merged with another appointment - possible associated statuses: 21                                               |
| Supported       | 5        | The appointment has been accepted by the mobile resource - possible associated statuses: 21, 2                                                                     |
| Ongoing         | 10       | The appointment is under way, the resource has confirmed they are in the process of fulfilling the mission - possible associated statuses: 2, 2, 30, 31, 3, 33, 35 |
| Partially done  | 15       | The appointment is partially completed - possible associated statuses: 3, 33, 35, 10, 12                                                                           |
| Completed       | 20       | The appointment has been completed - possible associated statuses: 3, 33, 35, 10, 12                                                                               |
| Closed          | 100      | The appointment is closed (administratively, legally, financially) - possible associated statuses: 3, 33, 35, 10, 12                                               |

### Fulfilment statuses

Fulfilment statuses follow uploading of the relevant fulfilment data from the NFS Mobile app, via a web service, CSV or SQL. This will consist of the _`ACHIEVEMENT_STATUS`_ and _`ACHIEVEMENT_RESOURCES`_ fields of the [CSV exchange model](https://mynomadia.com/privatedoc/9LLcWh7j74sENa54/optitime-doc/docs/en/otgs-reference-book/CSV.html#CSV-modele). The names, codes and behaviors of the statuses are given in the table below.

|                                                        |          |                                                                                   |
| ------------------------------------------------------ | -------- | --------------------------------------------------------------------------------- |
| **Status**                                             | **Code** | **Description**                                                                   |
| None                                                   | 0        | No status                                                                         |
| Started (STATUS\_STARTED)                              | 1        | Fulfilment has commenced                                                          |
| Interrupted-On hold (STATUS\_STOPPED)                  | 2        | Fulfilment has stopped or been interrupted (put on hold)                          |
| Restarted (STATUS\_RESUMED)                            | 3        | Fulfilment has resumed (following a pause/interruption)                           |
| Terminated (STATUS\_TERMINATED)                        | 4        | Fulfilment completed                                                              |
| Journey started (STATUS\_TRIP\_STARTED)                | 5        | The journey to the fulfilment location has started                                |
| Journey completed (STATUS\_TRIP\_TERMINATED)           | 6        | The journey to the fulfilment location has terminated                             |
| Journey interrupted or on hold (STATUS\_TRIP\_STOPPED) | 7        | The journey to the fulfilment location is interrupted (put on hold)               |
| Journey resumed (STATUS\_TRIP\_RESUMED)                | 8        | The journey to the fulfilment location has resumed (following interruption/pause) |
| Unsuccessful (STATUS\_UNSUCCESSFUL)                    | 9        | Fulfilment was unsuccessful                                                       |
| Unsuccessful journey (STATUS\_TRIP\_UNSUCCCESSFUL)     | 10       | The journey to the fulfilment location has been unsuccessful                      |

### Notification statuses

Notification statuses are linked to the cycle of the send/receive and then accept/reject data for the appointment, as handled by the **NFS Mobile** app.

|            |          |                                                        |
| ---------- | -------- | ------------------------------------------------------ |
| **Status** | **Code** | **Description**                                        |
| Not sent   | 0        | Appointment has not been sent to the resource’s device |
| Sent       | 1        | The appointment has been sent to the resource          |
| Received   | 2        | The appointment has been received by the resource      |
| Accepted   | 3        | The appointment has been accepted by the resource      |
| Rejected   | 4        | The appointment has been rejected by the resource      |

### Appointment Life Cycle

In **NFS**, an appointment can go through a series of **status changes** during its life cycle. Status changes can be triggered by different actions, such as:

* Optimising a planning.
* Manually updating the planning.
* Importing data that modifies the planning.

The appointment life cycle follows a set of rules based on the sequence of statuses assigned to the appointment. Depending on the actions performed and changes in the planning, an appointment can follow different status paths.

The following diagram illustrates the **generic life cycle of an appointment** in NFS.

|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |         |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| \[Warning]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Warning |
| <p>The <strong>Removed</strong> and <strong>Cancelled</strong> statuses are not shown in the life-cycle diagram. However, an appointment can be <strong>cancelled at any stage of its life cycle</strong>, regardless of its current status.</p><p>The appointment life cycle is not necessarily linear. For example, a <strong>Planned</strong> appointment can be <strong>unplanned</strong> or <strong>re-activated</strong>, causing it to return to the <strong>Candidate</strong> status macro.</p> |         |

Life cycle of an appointment

![images/ref/planification/cycle-de-vie-rendez-vous.png](../.gitbook/assets/cycle-de-vie-rendez-vous.png)
