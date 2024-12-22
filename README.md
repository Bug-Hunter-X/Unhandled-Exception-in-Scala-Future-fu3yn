# Unhandled Exception in Scala Future

This example demonstrates a common issue in Scala when working with Futures: the lack of explicit exception handling.  The `myMethod` function can throw an `IllegalArgumentException`, but it's not caught within the `Future`.  This can lead to unexpected failures in production if not properly handled.