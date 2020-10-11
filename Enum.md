# Enum

```swift
enum AppLanguage: String {
    case zhHant = "正體"
    case english = "ENG"
    
    var displayString: String {
        get {
            switch self {
            case .zhHant:
                return "正體中文"
            case .english:
                return "English"
            }
        }
    }
}
```
