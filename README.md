# UnvibeCode – Developer Adoption & Repeat Usage

**UnvibeCode Engineering Challenge 2026 – Cohort 3 | Track 2**

## Project Overview

This repository documents our research, observations, proposed solution, technical design, and implementation strategy for improving developer adoption and repeat usage of UnvibeCode.

The central objective is to make UnvibeCode a useful and recognizable part of developers' everyday software development workflows.

## Problem Statement

Developers may try a developer tool once but fail to integrate it into their regular workflow. UnvibeCode needs to provide convenient, recurring value that encourages developers to return and use the product again.

Our proposal focuses on reducing workflow friction, creating recurring usage opportunities, and maintaining visible product identity.

## Proposed Solution: UnvibeCode PR Intelligence

We propose a GitHub integration that provides code-impact intelligence directly within pull requests.

When a developer opens or updates a pull request, the proposed integration would:

- Identify changed files and relevant connected modules.
- Analyze potential impacts across the codebase.
- Present evidence-backed technical and business risk observations.
- Publish a clearly branded report in the GitHub pull-request workflow.
- Provide a link to the detailed UnvibeCode report.

This is a proposed feature, not a claim that the integration already exists.

## Why This Approach?

1. **Everyday workflow:** Pull requests are a recurring part of collaborative software development, providing natural opportunities for repeat usage.
2. **Reduced friction:** Developers can access code-impact insights inside GitHub instead of repeatedly starting a separate analysis workflow.
3. **Brand recognition:** Reports visibly identify UnvibeCode, helping developers recognize the source of the insights and return to its detailed reports.

## Trial Observations

During our UnvibeCode trial:

- We installed and launched the UnvibeCode CLI.
- We generated the Connected Code Map.
- We obtained the Complete Repository Context.
- The full analysis remained incomplete because the hosted analysis service returned an API credit exhaustion error.

These observations are recorded as a partial trial. We do not claim to have successfully generated or verified the Business Workflow Map or Business Risk Findings.

## Initial Implementation Direction

1. Develop a GitHub App that receives authorized pull-request events.
2. Reuse repository context and analyze relevant code changes.
3. Publish concise, evidence-linked reports through GitHub Checks or pull-request comments.
4. Evaluate repeat usage through returning repositories, repeated analyses, and report engagement.

## Success Metrics

- Returning repositories.
- Repeat pull-request analyses.
- Weekly active repositories.
- Report engagement.
- Repeat usage after the first analysis.

## Repository Structure

The research, solution design, implementation planning, and final proposal will be organized into separate folders as the project develops.

## Submission Note

This repository is supporting project documentation for Track 2. The official competition proposal is to be submitted through the designated Google Form.

---

**Project:** UnvibeCode Developer Adoption & Repeat Usage  
**Challenge:** Engineering Challenge 2026 – Cohort 3  
**Track:** Track 2
