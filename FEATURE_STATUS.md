# Feature status — Home care, hospice & elder care

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 122 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 2 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 1 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 2 | 0 | Native records/view |
| Reports & analytics | report | 2 | 0 | Native records/view |
| Activity & audit trail | audit | 0 | 0 | Native records/view |
| Provider connections | integration | 0 | 0 | Provider request records only |
| Contractors | records | 1 | 0 | Native records/view |
| Evacuation readiness | records | 1 | 0 | Native records/view |
| Care enrollments | records | 1 | 0 | Native records/view |
| Care plans | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Care incidents | records | 1 | 0 | Native records/view |
| Care dispatch requests | integration | 1 | 0 | Provider request records only |
| Devices | records | 2 | 0 | Native records/view |
| Rooms | records | 2 | 0 | Native records/view |
| Automations | records | 2 | 0 | Native records/view |
| Scenes | records | 2 | 0 | Native records/view |
| Energy | records | 2 | 0 | Native records/view |
| Security | records | 2 | 0 | Native records/view |
| Sensors | records | 2 | 0 | Native records/view |
| Schedules | records | 2 | 0 | Native records/view |
| Maintenance | records | 2 | 0 | Native records/view |
| Profiles | records | 2 | 0 | Native records/view |
| Shopping | records | 2 | 0 | Native records/view |
| Recipes | records | 2 | 0 | Native records/view |
| Meal Plans | records | 2 | 0 | Native records/view |
| Chores | records | 2 | 0 | Native records/view |
| Budget | records | 2 | 0 | Native records/view |
| Pantry | records | 2 | 0 | Native records/view |
| Weather | records | 2 | 0 | Native records/view |
| Pets | records | 2 | 0 | Native records/view |
| Plants | records | 2 | 0 | Native records/view |
| Guests | records | 2 | 0 | Native records/view |
| Media | records | 2 | 0 | Native records/view |
| Laundry | records | 2 | 0 | Native records/view |
| Packages | records | 2 | 0 | Native records/view |
| Warranty | records | 2 | 0 | Native records/view |
| Emergency | records | 2 | 0 | Native records/view |
| Intercom | records | 2 | 0 | Native records/view |
| Robot Status | records | 2 | 0 | Native records/view |
| Robot Tasks | records | 2 | 0 | Native records/view |
| Voice | records | 2 | 0 | Native records/view |
| Faces | records | 2 | 0 | Native records/view |
| Emotions | records | 2 | 0 | Native records/view |
| Gestures | records | 2 | 0 | Native records/view |
| Objects | records | 2 | 0 | Native records/view |
| Patrol | records | 2 | 0 | Native records/view |
| Navigation | records | 2 | 0 | Native records/view |
| Companion | records | 2 | 0 | Native records/view |
| Sleep | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Anomalies | records | 2 | 0 | Native records/view |
| Predictive AI | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Recommendations | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Expense Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Occupancy Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Routine Learning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proactive Maintenance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Guest Profiling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Emergency Response Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Family permissions | records | 1 | 0 | Native records/view |
| agentic household orchestrator autonomou | records | 1 | 0 | Native records/view |
| real time energy demand shifting auto | records | 1 | 0 | Native records/view |
| proactive maintenance prediction from ap | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| voice video multimodal ai understanding | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multi home energy arbitrage with demand | records | 1 | 0 | Native records/view |
| family activity clustering auto creating | records | 1 | 0 | Native records/view |
| expense optimizer for service cancell | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| occupancy prediction model | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| guest profiling ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| emergency response coordination ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| routine learning new automation sugge | records | 1 | 0 | Native records/view |
| device marketplace integration | integration | 1 | 0 | Provider request records only |
| vendor service booking | records | 1 | 0 | Native records/view |
| multi home management | records | 1 | 0 | Native records/view |
| audit log 0 references | records | 1 | 0 | Native records/view |
| webhook surface | integration | 1 | 0 | Provider request records only |
| websocket real time device updates | records | 1 | 0 | Native records/view |
| Medication reminder escalation | records | 1 | 0 | Native records/view |
| Patient Management | records | 1 | 0 | Native records/view |
| Visit Scheduling | records | 1 | 0 | Native records/view |
| Medications | records | 1 | 0 | Native records/view |
| Symptom Tracking | records | 1 | 0 | Native records/view |
| Family & Caregivers | records | 1 | 0 | Native records/view |
| Bereavement Program | records | 1 | 0 | Native records/view |
| Spiritual Care | records | 1 | 0 | Native records/view |
| Social Work | records | 1 | 0 | Native records/view |
| Volunteer Coordination | records | 1 | 0 | Native records/view |
| Staff Scheduling | records | 1 | 0 | Native records/view |
| DME Orders | records | 1 | 0 | Native records/view |
| Supply Management | records | 1 | 0 | Native records/view |
| GIP Bed Management | records | 1 | 0 | Native records/view |
| Certifications | records | 1 | 0 | Native records/view |
| Quality Measures | records | 1 | 0 | Native records/view |
| Compliance Docs | records | 1 | 0 | Native records/view |
| IDT Meetings | records | 1 | 0 | Native records/view |
| Family Surveys | records | 1 | 0 | Native records/view |
| Comfort Kit Refill | records | 1 | 0 | Native records/view |
| Advance Directive Summarizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Family Meeting Agenda Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Care Plan Narrative | records | 1 | 0 | Native records/view |
| Symptom Recommendations | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Comfort Measure Suggestions | records | 1 | 0 | Native records/view |
| Family Communication Draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance Documentation | records | 1 | 0 | Native records/view |
| Bereavement Resources | records | 1 | 0 | Native records/view |
| Predictive Decline Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Contact Script (Next Milestone) | records | 1 | 0 | Native records/view |
| Generate Meeting Summary | records | 1 | 0 | Native records/view |
| Ihss scheduling work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Optimize Schedule | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Demand | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Find Backup Resource | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Skill Gap Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Labor Cost Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 122 feature pages were visited in the browser; 120 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 30 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

30 original AI entries are now grouped into **6 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
