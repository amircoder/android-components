[android-components](../../index.md) / [mozilla.components.concept.sync](../index.md) / [DeviceConstellation](index.md) / [sendCommandToDeviceAsync](./send-command-to-device-async.md)

# sendCommandToDeviceAsync

`abstract fun sendCommandToDeviceAsync(targetDeviceId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, outgoingCommand: `[`DeviceCommandOutgoing`](../-device-command-outgoing/index.md)`): Deferred<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` [(source)](https://github.com/mozilla-mobile/android-components/blob/master/components/concept/sync/src/main/java/mozilla/components/concept/sync/Devices.kt#L73)

Send a command to a specified device.

### Parameters

`targetDeviceId` - A device ID of the recipient.

`outgoingCommand` - An event to send.

**Return**
A [Deferred](#) that will be resolved with a success flag once operation is complete.

