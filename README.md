# direct-deposit COP

*description of the COP*

**COP timeframe** 2026-02-18 - 2026-05-27

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-proto.github.io/direct-deposit](https://cra-proto.github.io/direct-deposit)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-03-04

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(Payments the CRA sends you)
    node4(Direct deposit)
    node5(Payments the CRA sends you - Direct deposit for non-resident individuals, businesses and trusts)
    node1 --x node2
    node2 --x node3
    node3 --> node4
    node4 --> node5
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/revenue-agency.html" _blank
    click node3 "https://www.canada.ca/en/revenue-agency/services/receiving-payments.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/services/about-canada-revenue-agency-cra/direct-deposit.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/services/about-canada-revenue-agency-cra/direct-deposit/non-residents.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node5 inscope
```
