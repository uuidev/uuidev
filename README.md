```swift
class Me: Developer, iOS {
    var name = "Haoyu Zhang"
    var username = "uuidev"
    
    var technologies = [.Xcode, .Swift, .UIKit, .SwiftUI]
    var platforms: [.iOS, iPadOS, .macOS, .Multiplatform]
}

protocol Developer {
    var technologies: [Technology] { get set }
}

protocol iOS {
    var platforms: [Platform] { get set }
}
```
<div id="badges" align="center">
  <a href="your-linkedin-URL">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="your-twitter-URL">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>

<img src="https://komarev.com/ghpvc/?username=uuidev&style=flat-square&color=blue" alt="Profile views counter"/>
