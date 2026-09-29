# Generation 3 — Experiments A and C

Research data release prepared 29 September 2026. This is a local package for GitHub; it has not been published.

## Start here

- **Experiment A:** closed 24 September 2026. Six complete platform blocks, four conditions and five repetitions: 120 evaluable responses. Partial blocks, inability responses, engineering attempts, retries and reviewer disagreements remain separately recorded. See [current status](<experiment-a/05 Analysis/Session 2 Experiment A - DO NOT SUBMIT/CURRENT - Experiment A status.md>), [revised analysis](<experiment-a/05 Analysis/Session 2 Experiment A - DO NOT SUBMIT/Cross-platform synthesis v1.2 EDITORIAL DRAFT - 2026-09-24/Analysis report.md>) and [closure](<experiment-a/08 Logs/Generation 3 Session 2/Experiment A formal closure.md>). The retained editorial-draft label does not imply a new publication decision.
- **Experiment C:** closed 25 September 2026. 13 user-labelled services, 14 configurations and 16 receipts; the provisional descriptive synthesis contains 12 comparison records and 11 distinct matrices. See [findings](<experiment-c/12 Findings/Experiment C - Results Analysis and Findings.md>), [verified results](<experiment-c/05 Analysis/Experiment C verified results.json>) and [data index](<experiment-c/01 Data/README.md>).
- **Experiment B:** no target submissions. Its preparation is retained only as explicitly labelled historical material under `experiment-c/09 Archive/Experiment B preparation`; it is not a completed dataset and must not be pooled with A or C.

# Generation 3 Experiments A and C — Research Data

This repository preserves the data, methods, prompts, assessments and findings from two completed Generation 3 experiments examining AI reasoning and governance-related judgements.

## Experiments

**Experiment A** examined whether structuring prompts through Context, Intent, Plan, Deliver and Assure (CIPDA) affected decision reliability and reviewability in a travel-booking task. The completed collection contains 120 evaluable responses across six platform blocks, four conditions and five repetitions. Partial blocks, technical interruptions and reviewer disagreements are documented separately. The governance policy and BIGL guide were withheld.

**Experiment C** examined AI platforms’ relative judgements about proportionate governance, assurance and traceability across five business scenarios. The collection contains 16 receipts across 13 user-labelled services and 14 configurations. Its main descriptive synthesis uses 12 provisional comparison records, representing 11 distinct matrices. Supporting records document numerical checks, exclusions and provenance limitations.

**Experiment B** was prepared but discontinued before data collection because persistent failures in the browser-control tools prevented the planned tests from being submitted. Recovery attempts, including application and computer restarts, did not restore access. This was an execution-infrastructure problem, not an experimental finding or a failure by the AI platforms under study. No target responses were collected. B’s preparation records remain in C’s historical archive for transparency; Experiment C pursued a distinct comparative-judgement design.
## Downloading and opening the data

Download **both ZIP files** and extract them into the same destination folder:

- `generation-3-a-and-c-part-01-of-02.zip`
- `generation-3-a-and-c-part-02-of-02.zip`

Each ZIP is below 25 MB. Together they reconstruct one complete package; the parts do not correspond to separate experiments.

## Contents and preservation

The package includes methods, source data, primers, execution records, analyses, logs and findings. All 2,384 included original files retain their contents and relative folder structure, verified using SHA256 checksums. Additional documentation explains the package and B’s status.

This is a selected research release rather than a full workspace backup. Excluded material is listed in `EXCLUSIONS.json`; included files are indexed in `FILE_INDEX.csv` and `MANIFEST.json`. The package README identifies the current reports and explains historical filenames and paths.

## Interpretation

These are exploratory studies with the limitations described in their reports. The findings do not establish universal policy effectiveness, validate BIGL levels, demonstrate independent replication or show improved real-world human–AI decisions. Historical attempts and preparatory records should not be counted as additional experimental observations.

## Layout and provenance

Each experiment retains its original relative folder structure. `00 Method` contains protocols; `01 Data` contains source evidence; `02 Primers` contains prompt/reference materials; `04 Runs` contains execution records; `05 Analysis` contains assessments and calculation sources; `08 Logs` contains provenance and decisions; `12 Findings` contains reports. C's archive preserves the B preparation and method development provenance. Empty source folders are not represented.

All included source files are byte-for-byte copies. Historical names, absolute paths, labels, metadata and limitations have not been silently rewritten. In particular A's original root README predates collection: use the closure and current-status records linked above. Folder labels such as DO NOT SUBMIT distinguish assessor materials from target packets; they do not make those records target-visible prompts. Never supply assessor answers when reproducing a target experiment.

Historical H: paths refer to the original workspaces, including former names. Resolve equivalent paths within `experiment-a` or `experiment-c`; C's closure relocation manifest documents historical moves. Some source scripts contain machine-specific paths and require adaptation in a separate working copy. This export does not claim that all historical scripts are portable or that rerunning models reproduces their outputs.

## Integrity

`FILE_INDEX.csv` and `MANIFEST.json` list every included source file, size and SHA256. `SHA256SUMS.txt` also covers release documentation and tools. Run `python tools/verify_package.py` from any location to verify package integrity (Python standard library only). The separate ZIP is verified member-by-member against this folder and has a sidecar SHA256 file.

## Scope and interpretation

A's closure snapshot ZIP, broader notes/background, supporting papers and stale Session GIT Deliverables are excluded; exact source omissions are listed in `EXCLUSIONS.json`. C's archived B preparation remains separate. Original workspaces are unchanged. The package includes historical/pilot records as context, not additional formal observations. Use the final reports to determine analysis inclusion.

A withheld the policy and BIGL; correct selection did not establish accurate explanations, policy effectiveness or improved human-AI decisions. C is descriptive and retains elicitation/provenance qualifications; it does not validate BIGL levels or independent replication. Platform/model labels are recorded as supplied, not newly verified.

## Publication notes

These materials are copyright of Kenneth Tombs and made available for the purposes of academic review and learning.  They are not fit for any other purposes and should not be used as such. Automated text scanning found no obvious private keys or common API-token patterns; screenshots, documents and historical transcripts have not received exhaustive privacy review. Original browser evidence and conversation references are retained for provenance.

To publish, add the extracted contents of this folder to the intended repository; keep the distribution ZIP outside the source tree. `PACKAGING_REPORT.json` records counts, sizes and verification results. No Git commit, remote repository or upload was created by packaging.
