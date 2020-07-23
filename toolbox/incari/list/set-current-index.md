# Overview

![The Set Current Index Node.](../../../.gitbook/assets/toolbox/incari/list/set-current-index.PNG)


**Set Current Index** selects an entry item by using it's *index*. It accepts a **List** **Object** and an `index` value and selects an entry item corresponding to the `index` value. 

The index count starts from zero which means the `index` of last entry item of the **list** **Object** is equal to the total number of entry items minus one (sum of entries - 1). This follows from array based indexing whereby the index of the first entry is 0.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|This represents the **List** **Object** from which an entry item can be select by it's index, if one is not provided in the `object ID` **Socket**.|
|`Default Index`|**Int**|The default *index* value if no value is provided to the input *index* **Socket**. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object`|**ObjectID**|The **List** **Object** from which an entry item can be selected by using it's index.|
|`Index`|**Int**|The *index* value of the entry item of the **List** **Object** you wish to select. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also
- [**List**](objects/scene-objects/list.md)
- [**Generate List**](generate-list.md)
 
# External Links
- [*Array Indexing*](https://en.wikipedia.org/wiki/Array_data_structure)
- [*Index Mapping*](https://en.wikipedia.org/wiki/Index_mapping)