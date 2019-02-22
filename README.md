Logger
-------

Simple logger class to log info and errors. It uses apple's latesting logging classes (`os.log`)

### Examples:
```swift
Logger.log("Value not good, bro", type: .error)
```
```swift
Logger.log("Couldn't load that request, oops :P", type: .error, category: .network)
```
