# Week 05 CLI Prompt Log

## Tool + environment
- Tool: Codex
- Date/time: 2026-02-18 10:55:39 EST

## Goal
- What I was trying to generate or change:
  - Create a structured CLI Prompt Log documenting the most recent four prompts and summarize outcomes.

## Inputs (files referenced)
- `SOPversion01.md` (provided inline in chat context)


## Prompt
[Paste the exact prompts that were used]
1. "Read SOPversion01.md and generate Mermaid flowchart code (flowchart TD) that matches the procedure exactly.
- Include explicit Start and End.
- Every decision has labeled branches.
- Do NOT invent steps. If missing, mark as [TBD] as a note.
Write the output to diagrams/mermaid/process.mmd.
2. Using SOPversion01.md, generate a BPMN 2.0 XML file for the process.
- Start event + end event required.
- Use tasks for steps, gateways for decisions.
- Use lanes ONLY if roles differ materially.
- Do NOT invent systems or approvals.
Write to diagrams/bpmn/process.bpmn.


## Output summary
- Files created/modified:
  - `Week_05_CLI_Prompt_Log.md` (created)
  - - `diagrams/mermaid/process.mmdd` (created)
  - - `diagrams/bpmn/process.bpmn` (created)
- What the tool produced (high-level):
  - A complete Week 05 CLI Prompt Log in the requested sectioned format, including goal, prompt list, validation, and result tracking.

## Validation performed
- What I checked (SOP alignment, decisions, start/end, exceptions):
  - Verified the document uses the exact requested heading and section order.
  - Confirmed the log contains four prompts and includes an output + validation summary.
  - Confirmed no unrelated repository files were modified.
- What was wrong / missing:
  - No additional source file references were needed beyond chat-provided prompts.

## Human edits I made
- Specific changes I made after the tool output: Validated each file for accuracy with original SOPv1.

## Result
- Final files committed:
  - `Week_05_CLI_Prompt_Log.md`
  -  - - `diagrams/mermaid/process.mmdd`
  -  - - `diagrams/bpmn/process.bpmn`
