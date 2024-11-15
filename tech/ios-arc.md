# iOS Cryptocurrency Project Structure

```swift
/App
    /Sources
        /Core
            /DI          # Dependency injection
            /Network     # Networking layer
            /Security    # Security services
            /Storage    # Data persistence
        /Data
            /Repository  # Data repositories
            /Models     # Data models
            /Services   # API services
        /Domain
            /UseCases   # Business logic
            /Entities   # Domain models
        /Presentation
            /Scenes     # UI screens
            /ViewModels # ViewModels
            /Components # Reusable UI
        /Utils
            /Extensions
            /Helpers
    /Resources
        /Configuration
        /Assets
    /Tests
        /UnitTests
        /IntegrationTests

/Features
    /Auth
    /Wallet
    /Trading
    /Settings
```

## Architecture
1. Clean Swift (VIP)
2. Combine
3. SwiftUI
4. Core Data
5. BackgroundTasks

## Security
1. Keychain Services
2. CryptoKit
3. Face/TouchID
4. Jailbreak Detection
5. SSL Pinning

## Dependencies
1. Alamofire
2. KeychainAccess
3. SwiftLint
4. Quick/Nimble
5. Swinject

## Best Practices
1. SwiftUI + UIKit Interop
2. MVVM + Coordinator
3. Protocol-Oriented
4. Reactive Programming
5. Dependency Injection
