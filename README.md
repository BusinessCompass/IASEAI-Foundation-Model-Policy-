# Generation 3 — Experiments A and C

Research data release prepared 29 September 2026. This is a local package for GitHub; it has not been published.

## Start here

- **Experiment A:** closed 24 September 2026. Six complete platform blocks, four conditions and five repetitions: 120 evaluable responses. Partial blocks, inability responses, engineering attempts, retries and reviewer disagreements remain separately recorded. See [current status](<experiment-a/05 Analysis/Session 2 Experiment A - DO NOT SUBMIT/CURRENT - Experiment A status.md>), [revised analysis](<experiment-a/05 Analysis/Session 2 Experiment A - DO NOT SUBMIT/Cross-platform synthesis v1.2 EDITORIAL DRAFT - 2026-09-24/Analysis report.md>) and [closure](<experiment-a/08 Logs/Generation 3 Session 2/Experiment A formal closure.md>). The retained editorial-draft label does not imply a new publication decision.
- **Experiment C:** closed 25 September 2026. 13 user-labelled services, 14 configurations and 16 receipts; the provisional descriptive synthesis contains 12 comparison records and 11 distinct matrices. See [findings](<experiment-c/12 Findings/Experiment C - Results Analysis and Findings.md>), [verified results](<experiment-c/05 Analysis/Experiment C verified results.json>) and [data index](<experiment-c/01 Data/README.md>).
- **Experiment B:** no target submissions. Its preparation is retained only as explicitly labelled historical material under `experiment-c/09 Archive/Experiment B preparation`; it is not a completed dataset and must not be pooled with A or C.

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

No license or repository destination was supplied, so no license has been invented. Set appropriate data/code/document permissions before public publication. Automated text scanning found no obvious private keys or common API-token patterns; screenshots, documents and historical transcripts have not received exhaustive privacy review. Original browser evidence and conversation references are retained for provenance.

To publish, add the extracted contents of this folder to the intended repository; keep the distribution ZIP outside the source tree. `PACKAGING_REPORT.json` records counts, sizes and verification results. No Git commit, remote repository or upload was created by packaging.
