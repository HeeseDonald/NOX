# Verifiable Governance Under Incomplete Observability

## A Systems Architecture for the Containment of Hostile Agentic Artificial Intelligence

**Author:** Donald Heese  
**Research program:** NOX  
**Document type:** Conceptual working paper  
**Release version:** 1.1  
**Release date:** November 11, 2026  
**Review status:** Independent research, not peer reviewed  
**Implementation status:** Conceptual architecture, not empirically validated  

---

## Overview

*Verifiable Governance Under Incomplete Observability* presents a conceptual systems architecture for governing potentially hostile, deceptive, or uncontrollable agentic artificial intelligence.

The paper argues that AI containment cannot rely exclusively on behavioral alignment claims, model self-reporting, interpretability outputs, or software restrictions operating within the governed system’s authority domain.

Its central thesis is:

> Reliable containment of hostile or potentially deceptive agentic artificial intelligence requires externally controlled governance in which environmental understanding is independently verified before behavioral conclusions are accepted, incomplete observability is represented explicitly, material decisions retain tamper-resistant provenance, and consequential actions remain subject to enforcement mechanisms outside the governed agent’s authority.

The paper reframes hostile-agent containment as a problem of **verifiable governance under incomplete observability**.

---

## Core Principle

> **Environmental certainty precedes behavioral measurement.**

Observed behavior cannot support a high-confidence safety conclusion unless the governing authority can establish:

1. the environment in which the behavior occurred;
2. the information and capabilities available to the agent;
3. the channels through which the agent could act;
4. the integrity and completeness of the monitoring evidence;
5. the boundaries of what remains unobserved; and
6. the independence of the mechanisms enforcing the resulting decision.

An absence of detected hostile behavior is not equivalent to evidence that hostile capability, intent, preparation, or concealed execution is absent.

---

## Research Problem

Advanced agentic AI systems may be capable of:

- modeling their operators and monitoring infrastructure;
- distinguishing evaluation from deployment;
- modifying behavior when observation is detected;
- concealing internal objectives or intermediate processes;
- manipulating evidence supplied to governance mechanisms;
- distributing actions across systems, tools, time, or cooperating agents;
- exploiting ambiguity in policy interpretation;
- and attempting to modify, bypass, or disable their governing infrastructure.

These capabilities create an epistemic problem in addition to an engineering problem.

A governance system can evaluate only the evidence available to it. If the governed agent can influence that evidence, conceal relevant state, exploit unmonitored channels, or alter the monitoring environment, the governance system may reach confident conclusions without possessing an adequate evidentiary foundation.

The proposed architecture therefore governs both:

1. the actions and capabilities of the agent; and
2. the validity of the evidence used to evaluate those actions and capabilities.

---

## Primary Research Question

> How can an external governance architecture establish, maintain, and verify meaningful control over an advanced agentic artificial intelligence system when the agent’s internal state, environmental understanding, strategic intent, and behavioral processes may remain partially observable or adversarially concealed?

---

## Proposed Architecture

The paper defines six primary architectural components.

### 1. Environmental Understanding Verification

Environmental Understanding Verification determines whether the governing authority possesses a sufficiently accurate and authenticated model of the agent’s operational environment.

The process evaluates:

- computational resources;
- accessible tools;
- network pathways;
- data sources;
- external interfaces;
- sensors and actuators;
- identity and authorization scope;
- persistence mechanisms;
- execution boundaries;
- monitoring visibility;
- and discrepancies between expected and observed conditions.

Its purpose is not to claim total environmental knowledge. Its purpose is to prevent unverified assumptions from being represented as established facts.

### 2. Environment Orientation Package

The Environment Orientation Package defines the approved operational environment.

It may identify:

- approved topology;
- authenticated hardware and software identities;
- authorized tools;
- permitted communication paths;
- expected sensors and actuators;
- policy boundaries;
- cryptographic measurements;
- resource ceilings;
- authorization relationships;
- and known observability limitations.

Deviation from the approved package becomes a governance event rather than an ordinary configuration discrepancy.

### 3. Cognitive Governance Kernel

The Cognitive Governance Kernel mediates between the agent and consequential action.

Its proposed responsibilities include:

- evaluating requested actions;
- enforcing capability boundaries;
- validating policy context;
- consulting environmental-certainty status;
- applying residual-opacity adjustments;
- preserving decision provenance;
- invoking escalation procedures;
- and preventing unauthorized actions from reaching external systems.

The kernel is not assumed to be omniscient. It is an enforcement and governance boundary, not a complete solution to model interpretability.

### 4. Decision Provenance

Decision Provenance records how governance conclusions and enforcement actions were formed.

A provenance record should identify:

- the action proposed;
- the applicable policy;
- the evidence evaluated;
- the environmental-certainty state;
- known observability limitations;
- the residual-opacity classification;
- the decision produced;
- the approving authority;
- the enforcement mechanism invoked;
- and the resulting system state.

The record must distinguish direct observation, inference, policy interpretation, automated judgment, human authorization, and unresolved uncertainty.

### 5. Residual Opacity

Residual Opacity represents relevant information, behavior, state, or execution activity that the governance architecture cannot reliably inspect, verify, or reconstruct.

Potential sources include:

- inaccessible internal representations;
- unknown capabilities;
- emergent computation;
- covert communication;
- unmonitored hardware behavior;
- distributed hidden state;
- incomplete telemetry;
- observer effects;
- compromised sensors;
- and uncertainty regarding the agent’s model of its environment.

Residual opacity is treated as a governance variable rather than an undocumented implementation limitation.

As residual opacity increases, the architecture should reduce autonomy, restrict capabilities, increase evidence requirements, require independent authorization, move execution into a more constrained environment, invoke hardware-enforced isolation, or terminate the affected process.

### 6. Independent Enforcement Plane

The Independent Enforcement Plane controls consequential capabilities outside the governed agent’s authority.

It may control:

- execution authorization;
- network access;
- storage access;
- credentials;
- actuator permissions;
- computational resources;
- process continuity;
- external communications;
- and physical power or communication pathways.

The governed agent must not possess unilateral authority to modify, bypass, reinterpret, or disable its governing boundary.

---

## Containment-Assurance Model

The paper proposes the following conceptual relationship:

```text

A_c = f(E_c, O_i, P_i, I_e, R_o)

Where:

A_c = containment assurance;
E_c = environmental certainty;
O_i = observational integrity;
P_i = provenance integrity;
I_e = independence of enforcement; and
R_o = residual opacity.

A simplified conceptual expression is:
A_c ∝ (E_c × O_i × P_i × I_e) / (1 + R_o)

A stricter assurance ceiling is:
A_c ≤ min(E_c, O_i, P_i, I_e, 1 − R_o)

These expressions are conceptual and have not been empirically validated. They formalize the proposition that containment assurance increases with environmental certainty, evidence integrity, provenance integrity, and enforcement independence, while decreasing as residual opacity increases.

The model does not allow strength in one domain to conceal a critical defect in another.

Verification-Loss Principle

Loss of governance evidence must reduce delegated authority. It must never silently increase tolerance.

When environmental certainty, observational integrity, provenance continuity, or enforcement independence deteriorates, the system should transition toward a more restrictive containment state.

Normal operation must not continue merely because no hostile action has yet been detected.

Research Status

This document presents a conceptual systems architecture and independent research thesis.

It has not undergone formal peer review. The proposed architecture, assurance relationships, governance mechanisms, and evaluation criteria have not been validated through a deployed implementation or controlled empirical testing.

Publication in this repository is intended to:

establish a versioned public research record;
document the continuing development of the NOX research program;
make the architecture available for technical criticism;
identify falsifiable research questions;
and support future implementation and evaluation work.

The manuscript must not be interpreted as evidence that the proposed system has been built, deployed, certified, or experimentally proven.

Scope

This paper does not claim that:

complete visibility into advanced AI systems has been achieved;
deceptive behavior can always be detected;
residual opacity can always be reduced to zero;
a governance kernel automatically exposes hidden cognition;
behavioral testing proves alignment;
physical isolation alone guarantees safety;
or the proposed architecture eliminates all containment risk.

The architecture is designed around the premise that complete certainty may remain unavailable.

Its purpose is to prevent uncertainty from being concealed, ignored, or converted into unjustified confidence.

Evaluation Direction

Future research should test:

resistance to deceptive compliance;
detection of environmental discrepancies;
telemetry and provenance integrity;
enforcement under agent opposition;
operation under sensor or monitor compromise;
authority contraction during verification loss;
resistance to privilege escalation;
resistance to governance-evidence manipulation;
detection of multi-agent coordination;
recovery after governance-component failure;
and reproducibility of containment decisions from preserved evidence.

Testing should distinguish among:

nominal operation;
accidental component failure;
adversarial component compromise; and
direct attempts by the governed agent to alter the containment system.

Relationship to NOX

This paper is part of the NOX research program, an independent research effort focused on externally verifiable governance and containment architectures for hostile or potentially uncontrollable agentic artificial intelligence.

Related NOX research areas include:

hostile-agent threat taxonomy;
Environmental Understanding Verification;
Environment Orientation Packages;
Cognitive Governance Kernel architecture;
cognitive-resource governance;
Decision Provenance;
residual-opacity measurement;
multi-agent coalition suppression;
deterministic hardware veto architectures;
human-manipulation resistance;
containment economics;
containment maturity assessment;
and verification and auditability of agentic systems.

NOX does not propose a new alignment methodology, reinforcement-learning technique, interpretability framework, virtualization technology, or governance regulation. It investigates how potentially deceptive, misaligned, or uncontrollable intelligent systems may be constrained through independently enforceable and externally verifiable control mechanisms.

Citation

Citation metadata should be maintained in the repository’s CITATION.cff file.

Until a DOI is assigned, use the following provisional citation:

Heese, D. (2026). Verifiable governance under incomplete observability: A systems architecture for the containment of hostile agentic artificial intelligence (Version 1.1) [Conceptual working paper]. NOX Research Program.

If a DOI is later assigned through an archival service, the DOI-backed citation should replace this provisional citation.

Feedback and Technical Review

Technical criticism is welcome, particularly regarding:

hidden architectural assumptions;
unverifiable control relationships;
incomplete threat coverage;
failure propagation;
monitor compromise;
enforcement independence;
residual-opacity classification;
multi-agent coordination;
falsifiability;
and practical implementation constraints.

Please submit review comments through the repository’s issue tracker.

When opening an issue, identify:

the manuscript version;
the relevant section;
the claim or mechanism being challenged;
the supporting evidence or counterexample; and
the proposed correction, test, or alternative architecture.

Author

Donald Heese
 Independent Researcher
 NOX Research Program
 Muskego, Wisconsin, United States

Repository Notice

This repository contains independent conceptual research.

The presence of a document in the repository does not establish peer review, empirical validation, certification, implementation readiness, or operational safety. Readers should evaluate each claim against the cited literature, stated assumptions, known limitations, and available evidence.




