# Overview

![The Next List Entry Node.](../../../.gitbook/assets/toolbox/incari/list/next-list-entry.PNG)

**Next List Entry** selects the next entry item in the **List** **Object**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The **List** **Object** of which you wish to select the next entry item. if an **Object** is provided in the `object ID` **Socket**, this attribute is not used.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object`|**ObjectID**|The **List** **Object** you wish to select the next entry item.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# Example Usage 
![The Next List Entry Usage](../../../.gitbook/assets/toolbox/incari/list/next-list-entry.gif)

# See Also
- [**List**](objects/scene-objects/list.md)
- [**Generate List**](generate-list.md)
- [**Previous List Entry**](previous-list-entry.md)