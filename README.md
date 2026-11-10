# Hi, I'm Usada

Learning designer focused on evidence-based, accessible learning in the AI era.
I work across corporate L&D, K-12 and higher-ed curriculum, EdTech, and education research.

## Featured work

Every project below follows the same arc: **diagnose → design → build → evaluate**, with design rationale, an accessibility statement, and an honest evidence section (including what the evidence *can't* show). Live sites are on GitHub Pages.

| Project | Problem | Audience | Live |
|---|---|---|---|
| [AI Literacy Program](https://github.com/iwyusdaz/ai-literacy-program) | Staff and students need practical, risk-aware AI literacy — not prompt tips | Employees, Grade 9–12 | [Demo](https://iwyusdaz.github.io/ai-literacy-program/) |
| [Should This Be a Course?](https://github.com/iwyusdaz/should-this-be-a-course) | A request for "feedback training" hides environment, process and motivation causes | Corporate L&D, HR | [Case study](https://iwyusdaz.github.io/should-this-be-a-course/) |
| [Socratic AI Tutor](https://github.com/iwyusdaz/socratic-ai-tutor) | AI tutors must protect learning — hints over answers, with measurable guardrails | Learning engineering, EdTech | [Demo + eval suite](https://iwyusdaz.github.io/socratic-ai-tutor/) |
| [Accessibility Remediation Case Study](https://github.com/iwyusdaz/accessibility-remediation-case-study) | A real course module audited against WCAG 2.1 AA and remediated, with a scaling model | Higher ed, K-12 | [Case study](https://iwyusdaz.github.io/accessibility-remediation-case-study/) |
| [AI-Resilient Assessment Kit](https://github.com/iwyusdaz/ai-resilient-assessment-kit) | Faculty need assessment redesigns that are tested against AI, with explicit AI-use levels | Higher ed faculty | [Kit + workshop](https://iwyusdaz.github.io/ai-resilient-assessment-kit/) |
| [Research Tools Academy](https://github.com/iwyusdaz/research-tools-academy) | Graduate students need task-based Zotero training built from real support questions | Graduate students | [Academy](https://iwyusdaz.github.io/research-tools-academy/) |
| [Tutor Training Course](https://github.com/iwyusdaz/tutor-training-course) | Tutoring quality at scale needs trained tutors, observable moves and fidelity data | K-12 tutoring programs | [Program](https://iwyusdaz.github.io/tutor-training-course/) |

## Open-source tools for learning designers

*The same problems kept surfacing across the projects above — so I built the tools for them.* Each tool is tested with negative tests that prove its failure paths actually fail, and each carries an independent agent review (labeled as such) with findings fixed in public.

| Tool | What it does | Born from |
|---|---|---|
| [tracebook](https://github.com/iwyusdaz/tracebook) | Extracts every factual claim from curriculum content, verifies each against its source with quote-back matching, rewrites corrections in place with dated notes — and re-checks sources weekly for link rot via a GitHub Action | The manual claim-by-claim source verification behind the projects above |
| [slidewalk](https://github.com/iwyusdaz/slidewalk) | Lesson outline in, accessible deck out: one source of truth builds a single-file HTML deck **and** a native PPTX, with axe/keyboard/reflow gates that fail the build instead of warning | Enforcing the same WCAG 2.1 AA baseline by hand in every project |
| [chalkreel](https://github.com/iwyusdaz/chalkreel) | Learning objective in, accessible explainer video out (agent skill): captions, transcript and audio-description notes ship with the video, and every cut is QC'd against Mayer's multimedia principles | The accessibility bundle every learning video should ship with — not as an afterthought |

## Immersive 3D learning (three.js)

Five browser-based 3D learning games and mini courses. Realistic detail appears only where noticing it *is* the learning. Real data comes from NASA, USGS and the Smithsonian. No sign-up, no tracking, and every project has a text mode and full keyboard play.

**[Play them all in the Immersive Learning Lab →](https://immersive-learning-showcase.vercel.app/)**

| Project | What the learner does | Play |
|---|---|---|
| [Lunar Field Expedition](https://github.com/iwyusdaz/lunar-field-expedition) | Lands at the real Apollo 15 site, reads the terrain under changing sunlight, plans a traverse and defends the findings | [Play](https://immersive-learning-showcase.vercel.app/play/lunar-field-expedition/) |
| [The Object Detective](https://github.com/iwyusdaz/object-detective) | Examines real Smithsonian 3D scans under raking light, checks them against archives and writes an honest museum label | [Play](https://immersive-learning-showcase.vercel.app/play/object-detective/) |
| [Hazard Hunt](https://github.com/iwyusdaz/hazard-hunt) | Spots warehouse hazards in realistic 3D, replays a near-miss and practises speaking up (workplace safety) | [Play](https://immersive-learning-showcase.vercel.app/play/hazard-hunt/) |
| [Field Ecologist](https://github.com/iwyusdaz/field-ecologist) | Designs a sampling plan for a meadow, then sees the true population and how the design biased the estimate | [Play](https://immersive-learning-showcase.vercel.app/play/field-ecologist/) |
| [Glacier Time Machine](https://github.com/iwyusdaz/glacier-time-machine) | Aligns historic photos to real 3D terrain of Muir Inlet, measures glacier retreat and reasons about causes and uncertainty | [Play](https://immersive-learning-showcase.vercel.app/play/glacier-time-machine/) |

Best on a desktop or laptop browser; phones get lighter graphics. Evaluation so far is automated testing plus agent-based review. No real learners have tested these yet, and each repo's `STATUS.md` lists its known open issues.

## Instructional design case studies

Selected case studies from my instructional design portfolio. Each one includes a 3D practice scene, plus the design and evaluation reasoning behind it. All organizations and scenarios are fictional.

**[See all 27 case studies →](https://portfolio-instructional-designer.vercel.app/work)**

| Case study | What the learner does |
|---|---|
| [Wind-Turbine Alarm Calls: Restart or Hold?](https://portfolio-instructional-designer.vercel.app/work/turbine-7/) | Offshore wind control-room technicians decide whether to restart or hold across eight alarm cases, under production-desk pressure, then write a handover note |
| [Cold-Chain Goods-In: Decision Training for Dock Receivers](https://portfolio-instructional-designer.vercel.app/work/cold-chain/) | Chilled-goods dock receivers work through a 21-decision certification module and a timed dock run, checking hidden core temperatures before signing the CMR |
| [Phishing Recognition Drill: Report, Verify or Trust](https://portfolio-instructional-designer.vercel.app/work/dont-click/) | Office staff read sender addresses right to left, name the registered domain, and decide whether to report, verify or trust each message |
| [Pharmacy Double-Check Training: Errors vs Over-Flags](https://portfolio-instructional-designer.vercel.app/work/medcheck/) | Hospital pharmacy technicians flag or clear five prescriptions, name the faulty line and write the annotation |
| [Craft-Dairy Process Training: Expert Interview to Floor-Ready Kit](https://portfolio-instructional-designer.vercel.app/work/craft-dairy/) | A founder interview becomes a tank-line routine; new operators choose the record over the surface cue at four gates and write the deviation note |
| [Vetting Adjudication: Weight the Pattern, Not the Story](https://portfolio-instructional-designer.vercel.app/work/faithful-copy/) | Vetting staff tag twelve documents in a dossier, weigh a quiet pattern against one vivid disclosure, and write the conditions or the reason |
| [Async Process Handover: Built for the 22:00 Reader](https://portfolio-instructional-designer.vercel.app/work/the-handover/) | Learners build a handover document on a 15-point budget, then test it in a Friday-night replay across IST/CET time zones |
| [AI-Assisted Customer Email: Verify Before You Send](https://portfolio-instructional-designer.vercel.app/work/ai-literacy/) | Support agents find the three real risks in a confident AI draft, climb a four-rung Verify ladder and make the send decision |

## How I work

Diagnose → Design → Build → Evaluate. Every project includes design rationale and an evidence section.

I treat evaluation honestly: automated accessibility testing and structured agent-based design reviews are complete for the projects above; AI-simulated learner runs, review panels and blind scoring pipelines are **built and dry-run tested but pending API keys** — no results are filled in, and nothing is presented as human-validated when it isn't. Each repo's `evaluation/METHODS.md` states exactly what was done, by what, and what it can and cannot show.

## Licenses and AI disclosure

Content is CC BY 4.0 and code is MIT in each repo (repo 4 matches its source module's license). These projects were built with AI assistance as portfolio artifacts; each README discloses where AI was used and how the work was reviewed (including separate-context agent reviews, labeled "Agent review"). Fictional organizations, personas and simulated datasets are labeled as such.
