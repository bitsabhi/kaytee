# Android Cryptocurrency Project Structure

```kotlin
/app
    /data
        /api          # API clients
        /db          # Room database
        /repository  # Repositories
        /models     # Data models
    /domain
        /usecase    # Business logic
        /models     # Domain models
    /presentation
        /ui         # UI components
        /viewmodel  # ViewModels
    /di            # Dependency injection
    /utils         # Utilities
/core
    /network       # Network handling
    /security      # Security utilities
    /analytics     # Analytics
/features
    /auth         # Authentication
    /wallet       # Wallet management
    /trading      # Trading features
    /settings     # App settings
/buildSrc        # Build configuration
```

## Architecture Components
1. Clean Architecture
2. MVVM
3. Kotlin Coroutines
4. StateFlow
5. Jetpack Compose
6. Navigation Component
7. Room Database
8. WorkManager

## Security Features
1. Biometric auth
2. Encrypted storage
3. SSL pinning
4. Root detection
5. Screenshot prevention
6. Proguard rules

## Core Libraries
1. Retrofit
2. Room
3. Hilt
4. Navigation
5. Compose
6. Material3
7. WorkManager
8. Security-Crypto
