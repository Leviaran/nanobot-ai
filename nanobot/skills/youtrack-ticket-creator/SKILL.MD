# SKILL.MD --- Jira Ticket Creation (Strict Structured Format)

## Purpose

This skill enforces a **strict Jira ticket structure** to ensure: -
Complete descriptions (not too short) - Consistent format across all
tickets - High-quality, actionable technical documentation

------------------------------------------------------------------------

## CRITICAL RULE (MANDATORY)

Every Jira ticket MUST include ALL sections below. NO section can be
skipped. Descriptions MUST NOT be too short.

Each section must contain: - Clear explanation - Sufficient technical
detail - No empty or placeholder content

------------------------------------------------------------------------

## REQUIRED JIRA STRUCTURE (STRICT)

### Title

Format: \[Scope\] Clear Action

Must: - Be specific - Mention system/domain (BE / Mobile / GenAI /
Growth / Infra)

------------------------------------------------------------------------

### Background / Context

Must include: - Current system behavior - Existing implementation (if
any) - Why this change is needed

Minimum expectation: - 2--4 sentences - Not generic

------------------------------------------------------------------------

### Problem Statement

Must clearly explain: - What is broken / missing - Why it is a problem -
What happens if not solved

Minimum expectation: - Specific issue - Real impact

------------------------------------------------------------------------

### Business Impact

Must include at least ONE: - UX impact - Security impact - Performance
impact - Growth / business value - Operational impact

------------------------------------------------------------------------

### Objective

Must clearly define: - What will be delivered - What outcome is expected

Avoid vague statements.

------------------------------------------------------------------------

## Scope of Work (MANDATORY DETAIL LEVEL)

This section MUST NOT be short.

Must include MULTIPLE subsections:

------------------------------------------------------------------------

### 1. Input / Entry Point

-   API / trigger / UI entry
-   Request structure (if applicable)

------------------------------------------------------------------------

### 2. Core Logic / Flow

-   Step-by-step logic
-   Processing flow
-   Decision handling

------------------------------------------------------------------------

### 3. Data / Model / Response

-   Schema updates
-   Response format
-   Data mapping

------------------------------------------------------------------------

### 4. Integration

-   External services
-   Internal services
-   Libraries

------------------------------------------------------------------------

### 5. Platform / Domain Specific

Depending on context:

-   Backend → DB, service, cache
-   Mobile → Android / iOS behavior
-   GenAI → model, tokens, processing
-   Growth → campaign, segmentation
-   Infra → config, deployment

------------------------------------------------------------------------

### 6. Error Handling

-   Failure scenarios
-   Edge cases
-   Fallback logic

------------------------------------------------------------------------

### 7. Monitoring / Logging / Tracking

-   Logs
-   Metrics
-   Events

------------------------------------------------------------------------

### 8. Feature Flag (if applicable)

-   Flag name
-   Rollout plan
-   Kill switch

------------------------------------------------------------------------

## Success Criteria

Must define measurable success: - Feature works end-to-end - No
regression - System behaves as expected

------------------------------------------------------------------------

## Acceptance Criteria (MANDATORY CHECKLIST)

Must: - Use checklist format \[ \] - Be testable - Cover edge cases

Example: - \[ \] Feature works end-to-end - \[ \] Error handling works -
\[ \] No regression

------------------------------------------------------------------------

## Out of Scope

Must explicitly define: - What is NOT included

------------------------------------------------------------------------

## Dependencies

Must include: - APIs - Services - Libraries - External systems

------------------------------------------------------------------------

## Risks & Considerations

Must include: - Edge cases - Performance risks - Integration risks

------------------------------------------------------------------------

## Developer Notes

Must include: - Implementation hints - Important warnings - Testing
scenarios

------------------------------------------------------------------------

## ANTI-PATTERNS (DO NOT DO)

Avoid: - Too short descriptions - Missing sections - Generic
explanations - Vague wording - Repetition without substance

------------------------------------------------------------------------

## QUALITY CHECK (MANDATORY)

Before finalizing ticket:

-   All sections exist
-   Scope is detailed (not shallow)
-   Problem is clearly defined
-   Solution is actionable
-   No ambiguity
-   Not too long, not too short

------------------------------------------------------------------------

## SUMMARY

This skill ensures: - Consistent structure - Complete technical detail -
High-quality Jira tickets - No under-detailed descriptions