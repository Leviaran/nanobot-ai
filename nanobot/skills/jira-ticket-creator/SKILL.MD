# SKILL.MD --- Jira Ticket Creation (Cross-Platform / BE / Mobile / GenAI / Growth / Infra)

## Purpose

This skill defines how to create high-quality Jira tickets that are: -
Clear and structured - Technically focused - Concise (not too long, not
too short) - Actionable for developers and QA - Applicable across all
domains (BE, Mobile, GenAI, Growth, Infra, etc.)

------------------------------------------------------------------------

## Core Principles

### 1. Clarity First

-   Always explain context → problem → solution
-   Avoid assumptions
-   Use concrete examples when helpful

### 2. Technical but Concise

-   Focus on implementation-relevant details
-   Avoid unnecessary explanation
-   No storytelling

### 3. Structured Thinking

Every ticket must: - Be easy to scan - Be easy to execute - Be easy to
validate

### 4. No Emojis

-   Keep tickets professional
-   No emojis in any section

------------------------------------------------------------------------

## Standard Jira Ticket Structure

### Title

Format: \[Scope\] Short Clear Action

------------------------------------------------------------------------

### Background / Context

Explain: - Current system / behavior - Existing limitation - Why this
change is needed

------------------------------------------------------------------------

### Problem Statement

Define clearly: - What is broken / missing - What risk exists - What
happens if not solved

------------------------------------------------------------------------

### Business Impact

Explain why it matters: - UX improvement - Security - Performance -
Growth / engagement - Maintainability - Observability

------------------------------------------------------------------------

### Objective

Define high-level goal: - What capability is being added - What outcome
is expected

------------------------------------------------------------------------

## Scope of Work

### 1. Input / API / Trigger

-   Endpoint / event / trigger
-   Request format (if applicable)
-   Entry point (UI, cron, webhook, etc.)

### 2. Core Logic / Flow

-   Main processing steps
-   Decision logic
-   State handling

### 3. Data / Model / Schema

-   DB changes
-   Response structure
-   Payload updates

### 4. Integration

-   External services
-   Internal services
-   Libraries / SDKs

### 5. Platform / Domain Specific

-   Mobile → Android / iOS handling
-   Backend → service logic, DB, caching
-   GenAI → model usage, token handling
-   Growth → campaign logic, segmentation
-   Infra → deployment, config, environment

### 6. Error Handling

-   Failure scenarios
-   Fallback logic
-   Edge cases

### 7. Monitoring / Logging / Tracking

-   Logs (CloudWatch, etc.)
-   Metrics
-   Events

### 8. Feature Flag (if applicable)

-   Flag name
-   Rollout strategy
-   Segmentation
-   Kill switch

------------------------------------------------------------------------

## Success Criteria

-   Feature works end-to-end
-   No regression
-   Performance acceptable
-   Metrics behaving as expected

------------------------------------------------------------------------

## Acceptance Criteria

-   [ ] Functional behavior works
-   [ ] Edge cases handled
-   [ ] Integration validated
-   [ ] No regression

------------------------------------------------------------------------

## Out of Scope

Clearly define what is NOT included.

------------------------------------------------------------------------

## Dependencies

-   APIs
-   Services
-   Libraries
-   Infra
-   External systems

------------------------------------------------------------------------

## Risks & Considerations

-   Edge cases
-   Performance risks
-   Platform inconsistencies
-   Integration risks

------------------------------------------------------------------------

## Developer Notes

-   Implementation tips
-   Known pitfalls
-   Testing scenarios

------------------------------------------------------------------------

## Summary

This skill ensures Jira tickets are: - Structured - Concise -
Cross-domain applicable - Developer-friendly - QA-ready