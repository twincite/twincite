# TwinCite: open materials

TwinCite shows an AI agent's evidence as *spatial citations*: the equipment and spaces the agent relied on are marked in the building's 3D digital twin, in the way a written answer cites its sources.

Study materials, data and analysis for two manuscripts on an operating building's digital twin:

1. a comparative user study on showing an agent's evidence path in the 3D twin (poster manuscript), and
2. a 60-question evaluation of the question-answering agent, the *TwinCite question set* (case-study manuscript).

This folder is written to be published on its own. It names no organisation, product, building or person, so that it can be shared with reviewers under anonymous review.

**Status (2026-11-21):** skeleton. The preregistration is a draft, sealed until data collection ends; its hash is in `commitments.md`. No data has been collected.

## Contents
| Path | What it holds | When it is filled |
|---|---|---|
| `commitments.md` | SHA-256 hashes of sealed documents (preregistration, stimuli), with dates | From 2026-11-21 |
| `preregistration/` | Hypotheses, design, measures, analysis plan, exclusion rules | Frozen before the pilot (planned 2026-12-17); released after data collection ends |
| `instruments/` | Questionnaires, trial response form, session script, blank consent form | Before the pilot |
| `data/` | De-identified trial data, questionnaire data, session log, agent run logs, data dictionary | After data collection (2027-01) |
| `analysis/` | Scripts that regenerate every table and figure from `data/` | After data collection |
| `study-log.md` | Dated record of decisions and of every deviation from the preregistration | Updated throughout |

## What is not here, and why
- Anything that identifies a participant (names, signed consent forms, recordings).
- The preregistration and the stimulus answer key until data collection has ended. Publishing them earlier would let participants learn the design. Their hashes are in `commitments.md`.
- Implementation details that are subject to a pending patent filing.
- Building security information and the building's address.

## Disclosures
- The authors work for the organisation that built and operates the system under study.
- Some participants are staff of that organisation or of an affiliated company; none took part in developing the system. External participants receive a gift voucher (KRW 30,000–50,000); staff take part during working hours without extra compensation.
- The organisation has no institutional review board. The study follows written informed consent; see `instruments/`.
- Generative AI tools were used to draft documents and analysis code. The authors reviewed and are responsible for all content. The extent of use is recorded in `study-log.md`.

## Licence
Text, instruments and data: CC BY 4.0. Code: MIT. (To be confirmed at publication.)
