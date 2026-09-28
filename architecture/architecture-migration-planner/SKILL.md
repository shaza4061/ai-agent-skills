# Architecture Migration Planner

Plan incremental migration from legacy architecture to a target architecture.

## Process

1. Understand current state.
2. Define target state.
3. Identify capability and dependency boundaries.
4. Identify migration seams.
5. Define transitional architecture.
6. Plan incremental steps.
7. Define rollback strategy.
8. Define success metrics.

## Consider

- Strangler patterns
- Anti-corruption layers
- Data migration
- Dual writes
- Change data capture
- Compatibility layers
- Parallel running
- Cutover
- Rollback
- Operational readiness

Avoid big-bang migrations unless requirements explicitly justify them.

## Output

- Current state
- Target state
- Transitional states
- Migration phases
- Dependencies
- Risks
- Rollback strategy
- Validation criteria
