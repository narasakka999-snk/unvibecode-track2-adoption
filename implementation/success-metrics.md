# UnvibeCode PR Intelligence – Success Metrics

## 1. Objective

This document defines how the proposed PR Intelligence feature can be evaluated after implementation.

The primary objective is to measure meaningful developer adoption and repeat usage rather than simply counting installations or first-time analyses.

These metrics are proposed evaluation criteria, not results from an existing deployment.

## 2. Primary Success Metrics

### 2.1 Returning Repositories

**Definition:** Number and percentage of repositories that use PR Intelligence again after their first successful analysis.

**Why it matters:** Indicates whether teams find enough ongoing value to return.

### 2.2 Repeat Pull-Request Analyses

**Definition:** Number of repositories that successfully analyze multiple distinct pull requests over a measurement period.

**Why it matters:** Measures whether the feature becomes part of recurring code-review activity.

### 2.3 Weekly Active Repositories

**Definition:** Number of unique repositories that receive at least one successful PR analysis during a week.

**Why it matters:** Helps evaluate sustained product activity.

### 2.4 Report Engagement

**Definition:** Percentage of generated reports that developers open, review, or interact with.

**Why it matters:** Helps determine whether the analysis provides useful information rather than generating ignored notifications.

### 2.5 Repeat Usage After First Analysis

**Definition:** Percentage of repositories that complete another successful analysis within a defined period after their first analysis.

**Why it matters:** Directly measures whether initial interest develops into repeated usage.

## 3. Supporting Quality Metrics

The following indicators help explain the quality of the experience:

- **Analysis completion rate:** Percentage of accepted analysis requests that complete successfully.
- **Analysis response time:** Time taken to publish a report after a pull-request event.
- **Report usefulness:** Developer feedback on the relevance and accuracy of findings.
- **Failure rate:** Percentage of analyses that fail or produce incomplete results.
- **Opt-out rate:** Percentage of repositories that disable the integration after installation.

These metrics help identify technical and user-experience problems that may prevent repeat usage.

## 4. Measurement Approach

A pilot evaluation can follow these steps:

1. Record the first successful analysis for each participating repository.
2. Track subsequent analyses across distinct pull requests.
3. Measure returning repositories over weekly and monthly periods.
4. Track report views and developer feedback.
5. Compare repeat usage before and after improvements to the integration.
6. Investigate why developers stop using the feature.

Where possible, compare results across different repository sizes and development activity levels.

## 5. Privacy and Measurement Principles

- Collect only the usage information required for product evaluation.
- Avoid collecting unnecessary source-code content for analytics.
- Use aggregated reporting wherever possible.
- Respect repository permissions and developer privacy choices.
- Provide clear controls for disabling the integration.

## 6. What Success Looks Like

PR Intelligence should demonstrate that:

- Developers return to analyze subsequent pull requests.
- Repositories continue using the integration over time.
- Reports are reviewed and considered useful.
- Analysis is reliable and does not unnecessarily interrupt development.
- Developers recognize UnvibeCode as the source of the repository intelligence.

## 7. Conclusion

The success of PR Intelligence should be measured by sustained, meaningful usage rather than initial interest alone.

Returning repositories, repeated pull-request analyses, and report engagement will provide evidence of whether the proposed integration helps UnvibeCode become part of developers' regular workflows.
