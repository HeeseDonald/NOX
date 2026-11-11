# NOX Safety-Critical Redesign

## Status

Working engineering research baseline.

Not a deployable system.  
Not certified.  
Not an operational authorization.

## Purpose

The NOX Safety-Critical Redesign treats hostile agentic artificial
intelligence containment as a safety-control problem.

The architecture preserves independent authority over every path by
which agent-influenced state could become an external effect.

## Document Set

### Core Architecture

- NOX Safety-Critical Redesign v0.1
- Defines the system boundary, losses, hazards, safety constraints,
  zone architecture, safe-state machine, effect mediation,
  zeroization model, assurance model, and preliminary safety case.

### Hardware Assurance Baseline

- NOX Hardware Assurance Baseline v0.2
- Defines component-level requirements for legacy elimination,
  firmware control, mutability control, remote-authority suppression,
  residual-state management, power isolation, debug-path elimination,
  and component qualification.

### Verification and Validation Plan

- NOX Verification and Validation Plan v0.1
- Defines verification methods, validation scenarios, test levels,
  fault injection, adversarial testing, evidence control,
  anomaly management, decision gates, and authorization exit criteria.

## Authority Model

The hostile system, runtime, experiment controller, general-purpose
operating system, hypervisor, semantic classifier, and opaque vendor
firmware are not accepted as final safety authorities.

Final safety authority is allocated to independent, bounded,
externally enforced mechanisms.

## Current Limitations

This document set does not establish:

- Absolute containment
- Zero risk
- Elimination of all covert channels
- Completed verification
- Completed validation
- Regulatory certification
- Operational authorization

## Author

Donald Heese  
Independent Researcher

## License

Creative Commons Attribution 4.0 International, subject to the
repository LICENSE file.

## Citation

See the repository CITATION.cff file and individual release records.
