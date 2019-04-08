
 # KSUID
 A Swift implementation of K-Sortable Globally Unique IDs.
 For more information,you can visit [Segment's KSUID library](https://github.com/segmentio/ksuid) and [Segment's Blog](https://segment.com/blog/a-brief-history-of-the-uuid/).
 
 # Quick Start
 Swift:
 ```swift
 let ksuid = KUUID()
 let ksuidString = ksuid.kuuidString // 001gCRD90IkZgb3UOkPb3FwLxT2
 let timestamp = ksuid.timestamp // 1553703483
 ```
 
 You can create a ksuid with desired epoch timestamp like this:
 
 ```swift
 let kuid = KUUID(timeInterval: 107608047000)
 let kuidString = kuid.kuuidString // 0006KljD4BgixB1EXiwp2qadbU1
 let timestamp = kuid.timestamp // 107608047
 ```
 
 # Update Log
 - 1.0.0: Initial public release
