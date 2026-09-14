# Methodology

## Purpose

This case study reconstructs the SolarWinds Orion supply-chain compromise as a trust-boundary and incident-response problem rather than as a simple malware profile.

The analysis is organized around four questions:

1. **Where was trust established?**
2. **Which trust boundary was compromised?**
3. **How did the actor reduce visibility after initial access?**
4. **Which controls would have increased the cost of the operation?**

## Source hierarchy

Priority is given to:

1. regulatory disclosures and investigative updates from SolarWinds;
2. CISA, NSA, FBI and other official government guidance;
3. U.S. GAO material documenting the federal response;
4. Mandiant / FireEye technical analysis and incident reporting;
5. additional first-party research where required to explain identity/cloud behavior.

## Confidence language

The report intentionally distinguishes among:

- **confirmed** — directly supported by primary or first-party technical reporting;
- **estimated** — a number or scope estimate published by SolarWinds or another authoritative source;
- **attributed** — attribution made by a government or threat-intelligence organization;
- **analytical lesson** — a defensive or offensive-security inference derived from the incident.

## Scope limitations

The public record does not document every victim, every follow-on intrusion, or every initial-access detail with equal confidence. The report therefore avoids presenting one unverified initial-entry hypothesis as established fact.

MITRE ATT&CK mappings in the report are representative, not exhaustive. Follow-on tradecraft differed across victims.

Historical IOCs are included for study and retrospective hunting only.
