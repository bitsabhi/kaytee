# Golang Backend Arch

```go
/cmd
    /api         # API entry points
    /worker      # Background workers
/internal
    /core
        /blockchain  # Core blockchain logic
        /wallet     # Wallet management
        /trading    # Trading engine
    /domain
        /models     # Domain models
        /events     # Domain events
    /ports
        /http      # HTTP handlers
        /grpc      # gRPC services
        /ws        # WebSocket handlers
    /adapters
        /repository  # Data storage
        /blockchain  # Blockchain clients
        /exchange   # Exchange integrations
    /services
        /auth      # Authentication
        /orders    # Order processing
        /matching  # Order matching
/pkg
    /crypto       # Cryptography utilities
    /validator    # Input validation
    /logger       # Logging
/config          # Configuration
/scripts         # Build/deployment scripts
/docs           # Documentation
```

## Key Components
1. Clean Architecture
2. Hexagonal Design
3. Event-Driven
4. CQRS for orders/trades
5. Circuit breakers
6. Rate limiting
7. Idempotency
8. Message queues

## Security Features
1. HSM integration
2. Key rotation
3. Request signing
4. Rate limiting
5. WAF integration
