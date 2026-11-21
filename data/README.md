# Data

No data yet (2026-11-21). Planned files and columns:

| File | One row per | Columns |
|---|---|---|
| `sessions.csv` | session | participant_id (P01…), session_date, participant_type (staff/external), practitioner (yes/no), cell (1–12), condition_order (AB/BA), facilitator (F1/F2), completed (yes/no), excluded (yes/no), exclusion_reason |
| `trials.csv` | trial | participant_id, trial_index, item_id (1–12), condition (A/B), answer_version (correct/incorrect), manipulation (categories are published after data collection), decision (accept/reject), appropriate (0/1), confidence (1–7), clicked_object_id, localisation_correct (0/1), decision_time_s, timed_out (0/1) |
| `questionnaires.csv` | participant × condition | participant_id, condition, trust_1…trust_12, tlx_mental … tlx_frustration, and once per participant: umux_1, umux_2 |
| `background.csv` | participant | participant_id and the banded background answers |
| `qa_runs.jsonl` | agent run | run_id, question_id, condition (full/no_graph), repetition, timestamps, model and prompt version, graph version, tool calls (name, input, result summary, duration), viewer actions (type, object IDs), final answer, error |
| `qa_scores.csv` | run × rater | run_id, rater (R1/R2), score (0/1/2), failure_type |

De-identification: no names; roles are published as broad categories; experience as bands; session dates are kept, session times are not.
