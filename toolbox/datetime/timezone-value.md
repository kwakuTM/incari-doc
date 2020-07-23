# Overview

![](../../.gitbook/assets/node-timezone-value.png)

**Timezone Value** returns the offset of a timezone, relative to [Coordinated Universal Time](https://www.timeanddate.com/time/aboututc.html) (UTC).

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Value`|**Drop-down**|The timezone that will be used, which is an offset of the UTC.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard input **Pulse**, to trigger the execution of the **Node**.|
|`Timezone Offset (ms)`|**Int**|The offset from the UTC in milliseconds.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard output **Pulse**, to move onto the next **Node** along the *logic branch*, once this **Node** has finished its execution.|
|`Timezone Offset (ms)`|**Int**|The offset of the timezone, in milliseconds, relative to UTC.|

# See Also

- [**DateTime**](README.md)
- [**Now (UTC)**](now-utc.md)

# External Links

- [*UTC - The World's Time Standard*](https://www.timeanddate.com/time/aboututc.html) on timeanddate.com.
- [*UTC Time Offsets*](https://www.utctime.net/utc-time-zone-offsets) on utctime.net.
- [*Epoch Unix Time Stamp Converter*](https://www.unixtimestamp.com/) on unixtimestamp.com.
- [*Current Millis*](https://currentmillis.com/) on currentmillis.com.