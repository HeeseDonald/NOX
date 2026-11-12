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
- authenticated 
