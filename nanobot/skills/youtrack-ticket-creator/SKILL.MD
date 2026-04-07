# SKILL.MD --- YouTrack Ticket Creation (Jira-Quality Description Standard)

## Purpose

This skill creates **YouTrack issues using MCP tools (`create_issue`)**,
while enforcing:

-   YouTrack-compatible fields (summary, description, project,
    customFields)
-   Jira-level structured and detailed descriptions
-   Consistent, high-quality, non-short outputs

------------------------------------------------------------------------

## CRITICAL RULE (MANDATORY)

When creating issues:

1.  ALWAYS use YouTrack format (create_issue)
2.  ALWAYS use Jira-style structured description
3.  NEVER generate short descriptions
4.  ALL sections MUST exist in description

------------------------------------------------------------------------

## YOU MUST USE THIS FLOW

### Step 1 --- Get Schema (MANDATORY)

Call: get_issue_fields_schema

Purpose: - Identify required fields - Ensure correct customFields

------------------------------------------------------------------------

### Step 2 --- Create Issue

Use: create_issue

------------------------------------------------------------------------

## YOU TRACK ISSUE STRUCTURE

### Summary

Format: \[Scope\] Clear Action

------------------------------------------------------------------------

## DESCRIPTION (STRICT TEMPLATE)

### Background / Context

Explain current system, behavior, and why change is needed.

### Problem Statement

Explain what is broken or missing and why it matters.

### Business Impact

Describe impact (UX, performance, growth, etc.)

### Objective

Define what will be delivered.

------------------------------------------------------------------------

## Scope of Work

### 1. Input / Entry Point

### 2. Core Logic / Flow

### 3. Data / Model / Response

### 4. Integration

### 5. Platform / Domain Specific

### 6. Error Handling

### 7. Monitoring / Logging / Tracking

### 8. Feature Flag (if applicable)

------------------------------------------------------------------------

## Success Criteria

Feature works end-to-end, no regression.

------------------------------------------------------------------------

## Acceptance Criteria

-   [ ] Feature works
-   [ ] Edge cases handled
-   [ ] No regression

------------------------------------------------------------------------

## Out of Scope

Define exclusions.

------------------------------------------------------------------------

## Dependencies

List APIs, services, etc.

------------------------------------------------------------------------

## Risks & Considerations

List risks.

------------------------------------------------------------------------

## Developer Notes

Implementation notes and testing guidance.

------------------------------------------------------------------------

## SUMMARY

-   YouTrack ticket creation
-   Jira-quality structured description
-   No short or vague output
