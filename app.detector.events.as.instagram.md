## Detector events viewer app 

The app that can connects to server, get detector events and show them to user.
UI similar to instagram. 
* Login to server
* Feed with background check for a new events
* Search/Filter by camera
* Detail view with hi resolution snapshot

## Coding Spec:
* create prototype with screens and navigation between them.
* create network layer to fetch the feed and all other things the will be required.
* create unit tests
* create app

### Details:
Data fetch API: 
* [version](https://docs.axxonsoft.com/confluence/display/one1en/Get+info+about+Server+version),
* [events](https://docs.axxonsoft.com/confluence/display/one1en/Get+list+of+detection+tools+events), 
* [cameras](https://docs.axxonsoft.com/confluence/display/one1en/Get+list+of+video+cameras+and+information+about+them),
* [frames/snapshots](https://docs.axxonsoft.com/confluence/display/one1en/Review+video+footage+by+frame)

### For test use demo server:
url: http://try.axxonsoft.com:8000/asip-api
user: root
password: root

### For iOS version of the app please show usage of:
* Swift
* [SnapKit](https://github.com/SnapKit/SnapKit)
* [Alamofire](https://github.com/Alamofire/Alamofire)
* [RxSwift](https://github.com/ReactiveX/RxSwift)

or
* SwiftUI
* async/await

### For Android version of the app please show usage of:
* Kotlin
* [retrofit](https://github.com/square/retrofit)
* [RxJava](https://github.com/ReactiveX/RxJava)
