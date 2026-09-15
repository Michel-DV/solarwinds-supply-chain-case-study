# SolarWinds Supply-Chain Case Study — v1.1.0

Final analytical edition of the SolarWinds technical case study by **@Michel-DV**.

Version 1.1.0 keeps the original incident reconstruction and adds a dedicated analytical layer intended to make the report more useful for threat research, detection engineering, Red Team planning and incident-response study.

## New in v1.1.0

- **Attack-path reconstruction through trust boundaries**
  - build control plane → signing/release → customer management plane → identity → cloud/data
  - identifies where the intrusion changes from artifact-centric to identity-centric access
  - highlights the defensive choke points that matter most

- **Detection hypotheses**
  - build-integrity / provenance mismatches
  - abnormal behavior from trusted management infrastructure
  - low-frequency DNS and victim-selection signals
  - follow-on activity and identity-conversion indicators
  - cloud persistence / collection correlation
  - emphasis on cross-layer telemetry instead of isolated IOCs

- **Red Team research notes**
  - safe ways to emulate trust-boundary abuse inside authorized environments
  - trusted-process blind spots
  - build integrity and signing-governance tests
  - selective-promotion simulation
  - identity-tier follow-through
  - explicit limits on what should not be emulated

## Core coverage retained

- SolarWinds build-pipeline compromise reconstruction
- SUNSPOT vs SUNBURST technical distinction
- SUNBURST dormancy, DNS beaconing and victim-selection model
- follow-on tooling and post-exploitation tradecraft
- Active Directory, federation and M365 implications
- detection engineering and retrospective hunting priorities
- exposure vs confirmed-compromise analysis
- coordinated containment / eradication / eviction guidance
- representative MITRE ATT&CK mapping
- software-supply-chain defensive architecture
- common myths, terminology and primary-source references

## Publication status

**v1.1.0 is the final analytical edition of CASE-001.** Future changes should be limited to factual corrections, broken references or material source updates.

**Author:** @Michel-DV  
**License:** CC BY-NC-ND 4.0  
**Final edition date:** 15 September 2026
