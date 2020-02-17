## Detector events viewer app 

The app that can connects to server, get detector events and show them to user.
UI similar to instagram. 
* Feed
* Search/Filter
* Detail view with hi resolution snapshot
* History/statistics/charts/day-by-day compare by events count of the selected type 

### Coding Spec:
* create prototype with screens and navigation between them
* create network layer to fetch the feed and all other things the will be required
* choose architecture
* create tests
* create app
* create ui tests
* create build script

### Details:
Data fetch API: 
[version](https://doc.axxonsoft.com/confluence/display/next436en/Get+info+about+Server+version),
[events](https://doc.axxonsoft.com/confluence/display/next436en/Get+list+of+detection+tools+events), 
[cameras](https://doc.axxonsoft.com/confluence/pages/viewpage.action?pageId=168661886),
[frames/snapshots](https://doc.axxonsoft.com/confluence/display/next436en/Review+video+footage+by+frame)


Tools/Libraries: 
[Carthage](https://github.com/Carthage/Carthage)
[SnapKit](https://github.com/SnapKit/SnapKit)
[Swinject](https://github.com/Swinject/Swinject)
[Alamofire](https://github.com/Alamofire/Alamofire)
[RxSwift](https://github.com/ReactiveX/RxSwift)
[stephencelis/SQLite.swift](https://github.com/stephencelis/SQLite.swift)
[garriguv/SQLiteMigrationManager.swift](https://github.com/garriguv/SQLiteMigrationManager.swift)
[xmartlabs/Eureka](https://github.com/xmartlabs/Eureka)
[lkzhao/Hero](https://github.com/lkzhao/Hero)

