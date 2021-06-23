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
* [version](https://doc.axxonsoft.com/confluence/display/next45en/Get+info+about+Server+version),
* [events](https://doc.axxonsoft.com/confluence/display/next45en/Get+list+of+detection+tools+events), 
* [cameras](https://doc.axxonsoft.com/confluence/pages/viewpage.action?pageId=184378390),
* [frames/snapshots](https://doc.axxonsoft.com/confluence/display/next45en/Review+video+footage+by+frame)

### For test use demo server:
url: http://try.axxonsoft.com:8000/asip-api
user: root
password: root

### For iOS version of the app please show usage of:
* Swift
* [SnapKit](https://github.com/SnapKit/SnapKit)
* [Alamofire](https://github.com/Alamofire/Alamofire)
* [RxSwift](https://github.com/ReactiveX/RxSwift)

### For Android version of the app please show usage of:
* Kotlin
* [retrofit](https://github.com/square/retrofit)
* [RxJava](https://github.com/ReactiveX/RxJava)
