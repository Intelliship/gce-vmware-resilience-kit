# GCE + VMware Resilience Kit

This project simulates a lightweight disaster recovery (DR) trigger between VMware and Google Cloud VMware Engine (GCVE).

The intent is not to provide full-scale automation—but to demonstrate fast, judgment-based response logic in scenarios where on-prem infrastructure fails and cloud recovery must take over.

## 1. Scenario

> VMware heartbeat check fails → Simulate GCE fallback instance creation

This repo includes:

- A shell script to simulate failure detection and DR orchestration
- Logging and output for clarity
- A minimal example of cloud-provider-agnostic thinking

## 2. Files

- `simulate_dr_trigger.sh` — Simulates DR failover logic
- `orchestration_plan.md` — Narrative on how this simulation could evolve into a full orchestration strategy

## 3. Why This Matters

FTD’s environment calls for hybrid infrastructure agility. This repo demonstrates:
- Situational awareness
- Simulated HA/DR readiness
- Platform abstraction

> Designed for validation in under 15 minutes.

