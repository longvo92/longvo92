# Long Vo Thien

**Embedded Software Engineer — Automotive / Model-Based Design**

I build the tooling that keeps generated code honest. Currently working on EV Charge
Controller software at VinFast: AUTOSAR, Simulink/Stateflow codegen, CAN networks,
and the CI pipelines that glue them together.

---

### What I work on

| Area | Stack |
|---|---|
| Model-Based Design | MATLAB / Simulink / Stateflow, Embedded Coder |
| AUTOSAR | ARXML, SWC mapping, RTE interfaces |
| Vehicle networks | CAN / CAN-FD, DBC, diagnostics |
| CI / Automation | Azure DevOps YAML, Python, codegen quality gates |
| Languages | C, Python, MATLAB |

---

### Selected work

**[codegen-compare-tool](https://github.com/longvo92/codegen-compare-tool)** · Python
Diffs two AUTOSAR/Simulink codegen folders and surfaces only the *real* changes —
timestamp and checksum noise filtered out. Outputs a self-contained HTML report,
zero dependencies. Built because reviewing 4,000 regenerated files by hand doesn't scale.

**[dbc-compare-tool](https://github.com/longvo92/dbc-compare-tool)** · Python
Compares CAN DBC baselines and produces an engineering-grade Excel change report.
Detects renamed files, messages and signals instead of reporting them as delete + add.

---

### Why these tools exist

In MBD workflows the generated code is the deliverable, but the review tools assume
hand-written code. Most of what I publish here closes that gap: making codegen diffs
reviewable, making network changes auditable, making traceability something you
generate rather than maintain by hand.

---

📍 Hanoi, Vietnam · [LinkedIn](https://www.linkedin.com/in/longvo92)
