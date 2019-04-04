[zcash-android-wallet-sdk](../../index.md) / [cash.z.wallet.sdk.data](../index.md) / [Synchronizer](index.md) / [progress](./progress.md)

# progress

`abstract fun progress(): ReceiveChannel<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>`

A stream of progress values, typically corresponding to this Synchronizer downloading blocks. Typically, any non-
zero value below 100 indicates that progress indicators can be shown and a value of 100 signals that progress is
complete and any progress indicators can be hidden.
