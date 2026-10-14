# Customizable parameters

## Overview

This appendix lists the customizable parameters of NFS. Parameters are grouped by area (`MY_ACTIONS`, `OTHERS`) and, for custom actions, by object (appointment, customer). Each group is identified by a key such as `appointment.list.myAction1`. For each group, a table gives the name, description and default value of every parameter.

{% hint style="info" %}
A default value of **Not set** means that the parameter has no default value.
{% endhint %}

<!-- REVIEW: the PROJECT and UNAVAILABILITY headings under MY_ACTIONS were empty in the source and were removed; the icon parameter has no description in the source; the preventM5429 description refers to issue m5426#54641 (number differs from the parameter name) -->

## MY_ACTIONS

### APPOINTMENT

#### `appointment.list.myAction1`

Custom for myAction 1 button below the appointment lists.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.list.myAction2`

Custom for myAction 2 button below the appointment lists.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.list.myAction3`

Custom for myAction 3 button below the appointment lists.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.list.myAction4`

Custom for myAction 4 button below the appointment lists.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.list.myAction5`

Custom for myAction 5 button below the appointment lists.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.listColumn.myAction1`

Custom for myAction 1 column (header and cells) in appointment lists.

| Parameter | Description | Default value |
|---|---|---|
| `additionalCustom1` | The tooltip of the column header, when `useInternationalization` is false. | Not set |
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. Sample: `WORKSITEID,APPOINTMENTID,CUSTOMER.CUSTOMERNAME`. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | The label of the column header, when `useInternationalization` is false. | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the column cell; values that are already possible: `myaction-blue,myaction-arrow1-blue,myaction-arrow2-blue,myaction-arrow3-blue,myaction-arrow4-blue,myaction-direction-blue,myaction-info-blue,myaction-share-blue,myaction-speechbubble-blue,myaction-view-blue,myaction-warning-blue,myaction-window1-blue,myaction-window2-blue,myaction-window3-blue`. Several classes names may be given, separated by whitespace. | `myaction-blue` |
| `tooltip` | The tooltip of the column cell, when `useInternationalization` is false. | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. Sample: `/otgs/pages/portions/myAction/myactionpage-sample01.html`. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.listColumn.myAction2`

Custom for myAction 2 column (header and cells) in appointment lists.

| Parameter | Description | Default value |
|---|---|---|
| `additionalCustom1` | The tooltip of the column header, when `useInternationalization` is false. | Not set |
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | The label of the column header, when `useInternationalization` is false. | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the column cell; values that are already possible: `myaction-blue,myaction-arrow1-blue,myaction-arrow2-blue,myaction-arrow3-blue,myaction-arrow4-blue,myaction-direction-blue,myaction-info-blue,myaction-share-blue,myaction-speechbubble-blue,myaction-view-blue,myaction-warning-blue,myaction-window1-blue,myaction-window2-blue,myaction-window3-blue`. Several classes names may be given, separated by whitespace. | `myaction-blue` |
| `tooltip` | The tooltip of the column cell, when `useInternationalization` is false. | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.listColumn.myAction3`

Custom for myAction 3 column (header and cells) in appointment lists.

| Parameter | Description | Default value |
|---|---|---|
| `additionalCustom1` | The tooltip of the column header, when `useInternationalization` is false. | Not set |
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | The label of the column header, when `useInternationalization` is false. | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the column cell; values that are already possible: `myaction-blue,myaction-arrow1-blue,myaction-arrow2-blue,myaction-arrow3-blue,myaction-arrow4-blue,myaction-direction-blue,myaction-info-blue,myaction-share-blue,myaction-speechbubble-blue,myaction-view-blue,myaction-warning-blue,myaction-window1-blue,myaction-window2-blue,myaction-window3-blue`. Several classes names may be given, separated by whitespace. | `myaction-blue` |
| `tooltip` | The tooltip of the column cell, when `useInternationalization` is false. | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.listColumn.myAction4`

Custom for myAction 4 column (header and cells) in appointment lists.

| Parameter | Description | Default value |
|---|---|---|
| `additionalCustom1` | The tooltip of the column header, when `useInternationalization` is false. | Not set |
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | The label of the column header, when `useInternationalization` is false. | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the column cell; values that are already possible: `myaction-blue,myaction-arrow1-blue,myaction-arrow2-blue,myaction-arrow3-blue,myaction-arrow4-blue,myaction-direction-blue,myaction-info-blue,myaction-share-blue,myaction-speechbubble-blue,myaction-view-blue,myaction-warning-blue,myaction-window1-blue,myaction-window2-blue,myaction-window3-blue`. Several classes names may be given, separated by whitespace. | `myaction-blue` |
| `tooltip` | The tooltip of the column cell, when `useInternationalization` is false. | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.listColumn.myAction5`

Custom for myAction 5 column (header and cells) in appointment lists.

| Parameter | Description | Default value |
|---|---|---|
| `additionalCustom1` | The tooltip of the column header, when `useInternationalization` is false. | Not set |
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | The label of the column header, when `useInternationalization` is false. | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the column cell; values that are already possible: `myaction-blue,myaction-arrow1-blue,myaction-arrow2-blue,myaction-arrow3-blue,myaction-arrow4-blue,myaction-direction-blue,myaction-info-blue,myaction-share-blue,myaction-speechbubble-blue,myaction-view-blue,myaction-warning-blue,myaction-window1-blue,myaction-window2-blue,myaction-window3-blue`. Several classes names may be given, separated by whitespace. | `myaction-blue` |
| `tooltip` | The tooltip of the column cell, when `useInternationalization` is false. | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.map.myAction1`

Custom for myAction 1 link (image+label) for appointment sheet in map.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the icon; values that are already possible: `myaction,myaction-arrow1,myaction-arrow2,myaction-arrow3,myaction-arrow4,myaction-direction,myaction-info,myaction-share,myaction-speechbubble,myaction-view,myaction-warning,myaction-window1,myaction-window2,myaction-window3`. Several classes names may be given, separated by whitespace. | `myaction` |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.map.myAction2`

Custom for myAction 2 link (image+label) for appointment sheet in map.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the icon; values that are already possible: `myaction,myaction-arrow1,myaction-arrow2,myaction-arrow3,myaction-arrow4,myaction-direction,myaction-info,myaction-share,myaction-speechbubble,myaction-view,myaction-warning,myaction-window1,myaction-window2,myaction-window3`. Several classes names may be given, separated by whitespace. | `myaction` |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.map.myAction3`

Custom for myAction 3 link (image+label) for appointment sheet in map.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the icon; values that are already possible: `myaction,myaction-arrow1,myaction-arrow2,myaction-arrow3,myaction-arrow4,myaction-direction,myaction-info,myaction-share,myaction-speechbubble,myaction-view,myaction-warning,myaction-window1,myaction-window2,myaction-window3`. Several classes names may be given, separated by whitespace. | `myaction` |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.map.myAction4`

Custom for myAction 4 link (image+label) for appointment sheet in map.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the icon; values that are already possible: `myaction,myaction-arrow1,myaction-arrow2,myaction-arrow3,myaction-arrow4,myaction-direction,myaction-info,myaction-share,myaction-speechbubble,myaction-view,myaction-warning,myaction-window1,myaction-window2,myaction-window3`. Several classes names may be given, separated by whitespace. | `myaction` |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.map.myAction5`

Custom for myAction 5 link (image+label) for appointment sheet in map.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the icon; values that are already possible: `myaction,myaction-arrow1,myaction-arrow2,myaction-arrow3,myaction-arrow4,myaction-direction,myaction-info,myaction-share,myaction-speechbubble,myaction-view,myaction-warning,myaction-window1,myaction-window2,myaction-window3`. Several classes names may be given, separated by whitespace. | `myaction` |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.planningTooltip.myAction1`

Custom for myAction 1 button in the appointment planning tooltip.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the tooltip button; values that are already possible: `myaction,myaction-arrow1,myaction-arrow2,myaction-arrow3,myaction-arrow4,myaction-direction,myaction-info,myaction-share,myaction-speechbubble,myaction-view,myaction-warning,myaction-window1,myaction-window2,myaction-window3`. Several classes names may be given, separated by whitespace. | `myaction` |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.planningTooltip.myAction2`

Custom for myAction 2 button in the appointment planning tooltip.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the tooltip button; values that are already possible: `myaction,myaction-arrow1,myaction-arrow2,myaction-arrow3,myaction-arrow4,myaction-direction,myaction-info,myaction-share,myaction-speechbubble,myaction-view,myaction-warning,myaction-window1,myaction-window2,myaction-window3`. Several classes names may be given, separated by whitespace. | `myaction` |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.planningTooltip.myAction3`

Custom for myAction 3 button in the appointment planning tooltip.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the tooltip button; values that are already possible: `myaction,myaction-arrow1,myaction-arrow2,myaction-arrow3,myaction-arrow4,myaction-direction,myaction-info,myaction-share,myaction-speechbubble,myaction-view,myaction-warning,myaction-window1,myaction-window2,myaction-window3`. Several classes names may be given, separated by whitespace. | `myaction` |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.planningTooltip.myAction4`

Custom for myAction 4 button in the appointment planning tooltip.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the tooltip button; values that are already possible: `myaction,myaction-arrow1,myaction-arrow2,myaction-arrow3,myaction-arrow4,myaction-direction,myaction-info,myaction-share,myaction-speechbubble,myaction-view,myaction-warning,myaction-window1,myaction-window2,myaction-window3`. Several classes names may be given, separated by whitespace. | `myaction` |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.planningTooltip.myAction5`

Custom for myAction 5 button in the appointment planning tooltip.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the tooltip button; values that are already possible: `myaction,myaction-arrow1,myaction-arrow2,myaction-arrow3,myaction-arrow4,myaction-direction,myaction-info,myaction-share,myaction-speechbubble,myaction-view,myaction-warning,myaction-window1,myaction-window2,myaction-window3`. Several classes names may be given, separated by whitespace. | `myaction` |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.sheet.myAction1`

Custom for myAction 1 button in the appointment sheet.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.sheet.myAction2`

Custom for myAction 2 button in the appointment sheet.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.sheet.myAction3`

Custom for myAction 3 button in the appointment sheet.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.sheet.myAction4`

Custom for myAction 4 button in the appointment sheet.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `appointment.sheet.myAction5`

Custom for myAction 5 button in the appointment sheet.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

### CUSTOMER

#### `customer.list.myAction1`

Custom for myAction 1 button below the customer lists.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.list.myAction2`

Custom for myAction 2 button below the customer lists.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.list.myAction3`

Custom for myAction 3 button below the customer lists.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.list.myAction4`

Custom for myAction 4 button below the customer lists.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.list.myAction5`

Custom for myAction 5 button below the customer lists.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.listColumn.myAction1`

Custom for myAction 1 column (header and cells) in customer lists.

| Parameter | Description | Default value |
|---|---|---|
| `additionalCustom1` | The tooltip of the column header, when `useInternationalization` is false. | Not set |
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | The label of the column header, when `useInternationalization` is false. | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the column cell; values that are already possible: `myaction-blue,myaction-arrow1-blue,myaction-arrow2-blue,myaction-arrow3-blue,myaction-arrow4-blue,myaction-direction-blue,myaction-info-blue,myaction-share-blue,myaction-speechbubble-blue,myaction-view-blue,myaction-warning-blue,myaction-window1-blue,myaction-window2-blue,myaction-window3-blue`. Several classes names may be given, separated by whitespace. | `myaction-blue` |
| `tooltip` | The tooltip of the column cell, when `useInternationalization` is false. | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.listColumn.myAction2`

Custom for myAction 2 column (header and cells) in customer lists.

| Parameter | Description | Default value |
|---|---|---|
| `additionalCustom1` | The tooltip of the column header, when `useInternationalization` is false. | Not set |
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | The label of the column header, when `useInternationalization` is false. | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the column cell; values that are already possible: `myaction-blue,myaction-arrow1-blue,myaction-arrow2-blue,myaction-arrow3-blue,myaction-arrow4-blue,myaction-direction-blue,myaction-info-blue,myaction-share-blue,myaction-speechbubble-blue,myaction-view-blue,myaction-warning-blue,myaction-window1-blue,myaction-window2-blue,myaction-window3-blue`. Several classes names may be given, separated by whitespace. | `myaction-blue` |
| `tooltip` | The tooltip of the column cell, when `useInternationalization` is false. | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.listColumn.myAction3`

Custom for myAction 3 column (header and cells) in customer lists.

| Parameter | Description | Default value |
|---|---|---|
| `additionalCustom1` | The tooltip of the column header, when `useInternationalization` is false. | Not set |
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | The label of the column header, when `useInternationalization` is false. | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the column cell; values that are already possible: `myaction-blue,myaction-arrow1-blue,myaction-arrow2-blue,myaction-arrow3-blue,myaction-arrow4-blue,myaction-direction-blue,myaction-info-blue,myaction-share-blue,myaction-speechbubble-blue,myaction-view-blue,myaction-warning-blue,myaction-window1-blue,myaction-window2-blue,myaction-window3-blue`. Several classes names may be given, separated by whitespace. | `myaction-blue` |
| `tooltip` | The tooltip of the column cell, when `useInternationalization` is false. | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.listColumn.myAction4`

Custom for myAction 4 column (header and cells) in customer lists.

| Parameter | Description | Default value |
|---|---|---|
| `additionalCustom1` | The tooltip of the column header, when `useInternationalization` is false. | Not set |
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | The label of the column header, when `useInternationalization` is false. | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the column cell; values that are already possible: `myaction-blue,myaction-arrow1-blue,myaction-arrow2-blue,myaction-arrow3-blue,myaction-arrow4-blue,myaction-direction-blue,myaction-info-blue,myaction-share-blue,myaction-speechbubble-blue,myaction-view-blue,myaction-warning-blue,myaction-window1-blue,myaction-window2-blue,myaction-window3-blue`. Several classes names may be given, separated by whitespace. | `myaction-blue` |
| `tooltip` | The tooltip of the column cell, when `useInternationalization` is false. | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.listColumn.myAction5`

Custom for myAction 5 column (header and cells) in customer lists.

| Parameter | Description | Default value |
|---|---|---|
| `additionalCustom1` | The tooltip of the column header, when `useInternationalization` is false. | Not set |
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | The label of the column header, when `useInternationalization` is false. | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the column cell; values that are already possible: `myaction-blue,myaction-arrow1-blue,myaction-arrow2-blue,myaction-arrow3-blue,myaction-arrow4-blue,myaction-direction-blue,myaction-info-blue,myaction-share-blue,myaction-speechbubble-blue,myaction-view-blue,myaction-warning-blue,myaction-window1-blue,myaction-window2-blue,myaction-window3-blue`. Several classes names may be given, separated by whitespace. | `myaction-blue` |
| `tooltip` | The tooltip of the column cell, when `useInternationalization` is false. | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.map.myAction1`

Custom for myAction 1 link (image+label) for customer sheet in map.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the icon; values that are already possible: `myaction,myaction-arrow1,myaction-arrow2,myaction-arrow3,myaction-arrow4,myaction-direction,myaction-info,myaction-share,myaction-speechbubble,myaction-view,myaction-warning,myaction-window1,myaction-window2,myaction-window3`. Several classes names may be given, separated by whitespace. | `myaction` |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.map.myAction2`

Custom for myAction 2 link (image+label) for customer sheet in map.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the icon; values that are already possible: `myaction,myaction-arrow1,myaction-arrow2,myaction-arrow3,myaction-arrow4,myaction-direction,myaction-info,myaction-share,myaction-speechbubble,myaction-view,myaction-warning,myaction-window1,myaction-window2,myaction-window3`. Several classes names may be given, separated by whitespace. | `myaction` |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.map.myAction3`

Custom for myAction 3 link (image+label) for customer sheet in map.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the icon; values that are already possible: `myaction,myaction-arrow1,myaction-arrow2,myaction-arrow3,myaction-arrow4,myaction-direction,myaction-info,myaction-share,myaction-speechbubble,myaction-view,myaction-warning,myaction-window1,myaction-window2,myaction-window3`. Several classes names may be given, separated by whitespace. | `myaction` |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.map.myAction4`

Custom for myAction 4 link (image+label) for customer sheet in map.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the icon; values that are already possible: `myaction,myaction-arrow1,myaction-arrow2,myaction-arrow3,myaction-arrow4,myaction-direction,myaction-info,myaction-share,myaction-speechbubble,myaction-view,myaction-warning,myaction-window1,myaction-window2,myaction-window3`. Several classes names may be given, separated by whitespace. | `myaction` |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.map.myAction5`

Custom for myAction 5 link (image+label) for customer sheet in map.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | CSS class name for the icon; values that are already possible: `myaction,myaction-arrow1,myaction-arrow2,myaction-arrow3,myaction-arrow4,myaction-direction,myaction-info,myaction-share,myaction-speechbubble,myaction-view,myaction-warning,myaction-window1,myaction-window2,myaction-window3`. Several classes names may be given, separated by whitespace. | `myaction` |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.sheet.myAction1`

Custom for myAction 1 button in the customer sheet.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.sheet.myAction2`

Custom for myAction 2 button in the customer sheet.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.sheet.myAction3`

Custom for myAction 3 button in the customer sheet.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.sheet.myAction4`

Custom for myAction 4 button in the customer sheet.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

#### `customer.sheet.myAction5`

Custom for myAction 5 button in the customer sheet.

| Parameter | Description | Default value |
|---|---|---|
| `destination` | Where the action is displayed. | `popup` |
| `destinationCaption` | (Optional) a label for the destination-header (titles popup and frame-wrapper, see `useInternationalization`). | Not set |
| `destinationHeight` | (Optional) the destination dimensions height, in pixels. Default = 0 (means `auto`). | `0` |
| `destinationWidth` | (Optional) the destination dimensions width, in pixels. Default = 0 (means `auto`). | `0` |
| `HTTPAdditionalParameters` | (Optional) any other information to send to destination, as HTTP parameters. Item format: `param_name=param_value`. Items are comma-separated. The escape character is backslash. | Not set |
| `HTTPListFields` | (Optional) the business model pieces of data to send to destination, as HTTP parameters (see the `exchange model` part of the app API documentation). Items are comma-separated. | Not set |
| `HTTPMethod` | The HTTP method in use to load the destination contents. | `get` |
| `HTTPParametersFormat` | (Optional) the format of the HTTP parameters sent to destination. Default = (empty) (means `standard HTTP`). | Not set |
| `icon` | No description provided in the source. | Not set |
| `label` | A label for the trigger-button (see `useInternationalization`). | Not set |
| `onCloseEvent` | (Optional) what happens once the action is terminated (incompatible with `destination=currentFrame\|newWindow\|callcenterLeftMenu`). | `nothing` |
| `style` | (Optional) CSS classes names (whitespace-delimited). | Not set |
| `tooltip` | A label for the trigger-button tooltip (see `useInternationalization`). | Not set |
| `trigger` | How is triggered: on mouse click, or mouse hover (`hover` is incompatible with `destination=newWindow`). | `click` |
| `URL` | Relative or absolute URL. | Not set |
| `useInternationalization` | A static (false) or dynamic (true, auto-referencing the language-file) strategy for labels. When using the dynamic strategy, any label-setting value is ignored. | `true` |

## OTHERS

### `default.other.custom`

Custom dedicated to temporary usages.

| Parameter | Description | Default value |
|---|---|---|
| `noMarkerTooltip` | No tooltip for marker in planning. | `false` |
| `preventM5429` | Handle the issue m5426#54641. | `true` |
