# UnvibeCode PR Intelligence – Developer User Workflow

## 1. Purpose

This document describes the proposed developer experience when using UnvibeCode PR Intelligence through GitHub.

The goal is to make repository intelligence accessible during normal code review activities.

## 2. Primary User

A software developer who:

- Maintains a GitHub repository.
- Regularly creates or updates pull requests.
- Wants to understand how code changes affect other parts of the application.
- Needs useful information without repeatedly starting a separate analysis tool.

## 3. Initial Setup

1. The developer visits the UnvibeCode integration page.
2. The developer installs the proposed GitHub App.
3. The developer authorizes access to selected repositories.
4. UnvibeCode establishes the repository connection.
5. The system generates or retrieves the necessary repository context.

## 4. Everyday Workflow

### Step 1: Create a Pull Request

The developer modifies application code and opens a pull request in GitHub.

Example: A developer changes the payment-processing module.

### Step 2: Detect Code Changes

The proposed GitHub App receives the pull-request event and identifies the modified files.

### Step 3: Retrieve Relevant Context

UnvibeCode retrieves relevant repository context and identifies connected components that may be affected by the changes.

### Step 4: Analyze Potential Impacts

The analysis engine examines relevant code relationships and prepares potential impact findings.

### Step 5: Publish the Report

A GitHub Check or pull-request comment displays the report.

Example report:

**Analyzed by UnvibeCode**

- Changed area: Payment processing
- Potentially affected area: Order processing
- Observation: A change in payment status handling may affect downstream order-status logic.
- Evidence: Relevant source files and code references.
- Status: Analysis completed.

This is an illustrative report, not an actual analysis result.

### Step 6: Review Findings

The developer examines the findings, checks the source references, and decides whether any additional code review or testing is necessary.

### Step 7: Update the Pull Request

If the developer pushes new commits, the integration can analyze the updated changes and publish a refreshed report.

## 5. Handling Failures

The integration should not silently fail.

It should communicate:

- Analysis in progress.
- Analysis completed.
- Partial analysis available.
- Analysis temporarily unavailable.
- Analysis failed with an understandable reason.

When analysis fails, developers should be able to retry it without unnecessary duplicate processing.

## 6. Developer Control

The proposed integration should provide:

- Repository selection and permission controls.
- An option to disable automatic analysis.
- Manual analysis when needed.
- Clear access to detailed reports.
- Protection of repository data.

## 7. Repeat-Usage Mechanism

The recurring trigger is a new or updated pull request.

Each relevant code change creates an opportunity for UnvibeCode to provide new code-impact information.

The developer receives value within the existing GitHub workflow and can revisit the detailed report when needed.

## 8. Expected User Experience

The desired experience is:

1. Familiar: Developers continue working in GitHub.
2. Convenient: Analysis starts through a normal development event.
3. Relevant: Reports focus on the changes and connected code.
4. Transparent: Findings include evidence and clear analysis status.
5. Recognizable: UnvibeCode branding remains visible.

## 9. Conclusion

The proposed workflow integrates repository intelligence into an activity developers already perform.

By making useful analysis available during pull-request reviews, UnvibeCode can create recurring opportunities for product engagement without requiring developers to adopt an entirely separate daily routine.
