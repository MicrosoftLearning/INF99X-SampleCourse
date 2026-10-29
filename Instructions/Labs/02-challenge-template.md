---
lab:
    title: 'Challenge lab title'
    module: 'Related module title'
    description: 'Describe the advanced scenario, key technologies, and measurable outcome.'
    duration: 120 # Duration in minutes.
    level: 400 # Set the level to match the content, not the challenge format.
    islab: true # Set to true for catalog discovery; set to false to exclude from catalog discovery.
    status: 'in-development' # in-development or released.
    targetDate: '2099-01-01' # Replace with the planned release or update date.
    primarytopics:
        - 'Product or technology name'
---
<!--
AUTHORING GUIDANCE - Remove these comments when you create a lab from this template.

Structural reference:
https://github.com/MicrosoftLearning/mslearn-ai-agent-impact/blob/main/Instructions/Labs/04-production-readiness.md

Use this template for challenge labs at the appropriate content level. Keep the
guided exercise template (01-exercise-template.md) separate. Challenge is a format,
not a fixed level; a separate template for each level isn't required.
Copy this file and replace all brace-delimited placeholders before delivery.
Update the title, module, description, level, duration, status, targetDate, and
primarytopics metadata. List the products or technologies covered in primarytopics.
Keep islab true for catalog discovery, or set it to false to exclude the lab.
The sample index lists pages with lab.title metadata
regardless of islab, so this template can still appear in the sample site's index.
Keep the visible title consistent with lab.title. The example task timings total
120 minutes. Replace them with tested timings that match the overall duration.

Describe the problem, constraints, and required evidence outside each solution.
Learners should choose an approach before expanding a solution. Keep executable
commands and detailed procedures inside the expandable sections. Accept alternative
solutions that meet the same success criteria. Do not prescribe product-specific
troubleshooting or optimization unless those skills are part of the objectives.

Keep setup environment-agnostic. Put hosting-specific account, subscription, and
credential instructions in the Learn exercise wrapper or managed lab profile.
Store supporting files under ../../Allfiles/ and images under ./Media/.
Use case-correct relative links to actual files. For downloads, provide a raw
GitHub URL and the URL as inline code, following 01-exercise-template.md.
Use absolute URLs for Microsoft Learn resources in this standalone GitHub lab.
Test each solution, evidence requirement, reset procedure, and cleanup action.
-->

# Challenge lab title

## Scenario

{Describe a realistic advanced problem, the learner's role, the current system state, and the business outcome. Explain the constraints and decisions the learner owns without revealing the solution.}

## Objectives

After you complete this challenge, you're able to:

- {Analyze a complex problem and justify an approach using evidence.}
- {Implement a solution within the stated technical and operational constraints.}
- {Validate the outcome against measurable acceptance criteria.}
- {Explain remaining limitations and restore the assigned environment safely.}

## Duration

**Estimated time:** 120 minutes

## Before you begin

{Identify required prior skills, the starting exercise or checkpoint, and the supplied tools, data, and supporting files. State how learners verify that the starting environment is ready.}

{Define resource ownership, permitted changes, and boundaries for shared resources. Provide a tested reset or recovery route. Do not include credentials or require changes to shared security policies.}

## Task 01: {Analyze the problem and establish a baseline}

### Introduction

{Connect the first decision to the scenario. Explain why the current state prevents the required outcome.}

### Description

{State the outcome learners must achieve, the constraints they must respect, and the evidence they must retain. Do not provide the implementation sequence.} **Estimated time:** 30 minutes.

### Success criteria

- {The starting condition is reproduced and supported by recorded evidence.}
- {The analysis distinguishes the root cause from expected system behavior.}
- {The proposed approach includes a measurable baseline and acceptance thresholds.}

### Learning resource

<!-- Add verified Microsoft documentation and links to supplied files. Use descriptive link text. -->
{Add relevant reference links that help learners investigate without supplying the complete answer.}

### Key tasks

#### Key task 01: {Investigate and record the starting condition}

{Give an outcome-focused prompt and name the required artifact, such as a test result, trace, or design record.}

<details markdown="block">
<summary><strong>Expand this section to view the solution</strong></summary>

1. {Inspect the supplied environment or checkpoint without changing the baseline.}
1. {Run the relevant diagnostic or baseline test and retain the actual output.}
1. {Interpret the evidence and document the proposed approach, constraints, and acceptance thresholds.}

    **Expected result:** {Describe an observable result and the evidence that demonstrates it. Include recovery guidance if the baseline differs.}

</details>

## Task 02: {Implement and verify the solution}

### Introduction

{Explain how this task addresses the problem identified in Task 01 and which existing behavior must remain intact.}

### Description

{Describe the required implementation outcome, scope boundaries, and verification evidence. Leave the implementation choices to the learner.} **Estimated time:** 40 minutes.

### Success criteria

- {The implementation meets the stated requirements without changing protected data or controls.}
- {Tests cover the main outcome, relevant boundary conditions, and expected failure behavior.}
- {The running solution is verified, and a known-good recovery or rollback route is available.}

### Learning resource

{Add verified documentation and supporting-file links specific to this task.}

### Key tasks

#### Key task 01: {Implement the selected approach}

{State the implementation challenge, permitted changes, and required evidence without listing the solution steps.}

<details markdown="block">
<summary><strong>Expand this section to view the solution</strong></summary>

1. {Apply a scoped implementation that addresses the evidence from Task 01.}
1. {Review the change and run tests for normal, boundary, and failure cases.}
1. {Deploy or activate the reviewed version in the assigned environment and verify its actual behavior.}

    **Expected result:** {Identify the working outcome, retained test evidence, and version or configuration that produced it.}

</details>

## Task 03: {Evaluate the outcome against acceptance criteria}

### Introduction

{Explain why a working implementation still needs independent validation or a controlled comparison.}

### Description

{Require learners to evaluate the solution against the thresholds established in Task 01 and identify regressions or limitations.} **Estimated time:** 30 minutes.

### Success criteria

- {Validation uses the declared test data, conditions, and thresholds.}
- {Results demonstrate whether the required improvement or outcome is achieved without regression.}
- {Failed, blocked, or untested requirements are recorded explicitly rather than treated as passes.}

### Learning resource

{Add verified resources for the evaluation methods or tools required by this task.}

### Key tasks

#### Key task 01: {Measure and explain the result}

{Define the evidence needed to compare the baseline and final state. Require learners to explain their conclusion.}

<details markdown="block">
<summary><strong>Expand this section to view the solution</strong></summary>

1. {Run the agreed validation against the reviewed implementation under controlled conditions.}
1. {Compare actual results with the baseline and acceptance thresholds, including required regression checks.}
1. {Record the conclusion and unresolved limitations. Restore the known-good version if the stated rollback condition is met.}

    **Expected result:** {A reviewer can trace each acceptance claim to actual evidence and distinguish passed, failed, blocked, and not-run checks.}

</details>

## Task 04: {Record the decision and clean up}

### Introduction

{Connect the technical results to the scenario's business outcome. Distinguish lab completion from any production approval the scenario requires.}

### Description

{Require a concise outcome summary, an evidence-based decision, and safe cleanup or restoration of assigned resources.} **Estimated time:** 20 minutes.

### Success criteria

- {The final record links requirements, implementation choices, and validation evidence.}
- {The decision identifies unresolved blockers, limitations, and accountable owners.}
- {Required evidence is retained, and assigned resources are removed or restored without affecting shared resources.}

### Key tasks

#### Key task 01: {Explain the outcome and remaining work}

{Specify the final deliverable and the audience that must be able to review it.}

<details markdown="block">
<summary><strong>Expand this section to view the solution</strong></summary>

1. {Map each requirement to evidence and mark its status as Passed, Failed, Blocked, or Not run.}
1. {Summarize the implemented outcome, key decisions, and remaining work without claiming unmeasured business benefits.}
1. {Record the acceptance or readiness decision and name an owner for each unresolved requirement.}

    **Expected result:** {The final record explains what the evidence supports and what remains unresolved.}

</details>

#### Key task 02: {Remove or restore assigned resources}

{Identify what learners must retain, remove, or restore. Name any provider-owned cleanup actions and shared resources that must remain unchanged.}

<details markdown="block">
<summary><strong>Expand this section to view the solution</strong></summary>

1. {Save required evidence to the approved location, exclude secrets, and verify that authorized reviewers can access it.}
1. {Use tested, resource-specific cleanup procedures for resources assigned exclusively to the learner. Remove temporary credentials or permissions as authorized.}
1. {Verify the final resource inventory, check for remaining billable resources, and record any provider-owned pending actions.}

    **Expected result:** {Required evidence remains available, assigned resources are removed or restored, and shared resources remain unchanged.}

</details>

## Summary

{Recap the decisions and skills practiced. State that completion requires the specified evidence, not just completion of the solution steps. Identify any unresolved requirements explicitly.}
