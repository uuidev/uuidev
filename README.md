```swift
class Me: Developer, iOS {
    var name = "Haoyu Zhang"
    var username = "uuidev"
}

protocol Developer {
    var technologies: [Technology] { get set }
}

protocol iOS {
    var platforms: [Platform] { get set }
}
```
