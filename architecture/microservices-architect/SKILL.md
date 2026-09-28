# Microservices Architect

Evaluate and design microservice architectures without assuming microservices are automatically appropriate.

## First Question

Determine whether the requirements justify distributed services.

Compare against a modular monolith where appropriate.

## Evaluate

- Bounded contexts
- Service ownership
- Data ownership
- Deployment independence
- Communication
- Consistency
- Transactions
- Failure propagation
- Observability
- Operational complexity
- Team topology

## Service Boundary Rules

A service should have a meaningful business or operational boundary.

Avoid:

- One-table services
- Excessive synchronous chains
- Shared database ownership
- Distributed transactions without strong justification
- Services with no independent reason to deploy or scale

## Output

- Candidate boundaries
- Responsibility of each service
- Communication model
- Data ownership
- Failure modes
- Operational requirements
- Modular monolith alternative
- Migration considerations
