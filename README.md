# teamwork

## Strategies for Enhancing 3-Person Team Collaboration within a Larger Scrum Framework

To improve collaboration and a sense of "team combat" for a 3-person sub-team operating within a larger 20-person Scrum development team, consider the following strategies:

### 1. Collaborative Jira Ticket Management (Jira Ticket 的協同管理)
- **Joint Planning and Breakdown:**
    - After Sprint Planning or when a large user story/task is assigned to the small team, collectively discuss and break it down into smaller, manageable sub-tasks.
    - Assign these sub-tasks within the small team.
- **Handling Externally Assigned Tickets:**
    - When a ticket is assigned directly to an individual by a PM, team lead, or client, the assignee should:
        - Promptly share the ticket with the small team (e.g., in a quick huddle or via the team chat).
        - Facilitate a brief discussion to ensure shared understanding, identify potential collaboration points, or break it down further if needed.
        - Ensure the small team's specific Jira label/component is applied for visibility.
- **Use of Labels/Components:**
    - Create a unique Jira label (e.g., `team-uds`) or a specific component for your small team's tasks.
    - This allows for easy filtering and tracking of the small team's overall progress and workload.
- **Informal Ticket Reviews:**
    - Before creating complex or critical tickets, have a quick sync-up within the small team to ensure clarity, consistency in requirements, and to avoid duplication.
- **Cross-linking and Watching:**
    - For tickets with dependencies within the small team, ensure they are linked.
    - Encourage team members to "watch" relevant tickets of other small team members to stay informed.
- **Benefit:** Creates a shared understanding of the work, improves visibility into each other's tasks, and fosters a more unified approach to tackling sprint goals.

### 2. Reinforcing Small Team Goals (強化小組目標感)
- **Sub-Team Sprint Goals:**
    - In addition to the overall Sprint Goal of the larger team, define 1-2 specific, achievable goals for the 3-person team within the sprint.
    - These goals should contribute to the main Sprint Goal but provide a more focused objective for the small team.
- **Celebrate Small Wins:**
    - Acknowledge and celebrate when the small team achieves its specific goals.
- **Benefit:** Provides a shared sense of purpose and accomplishment, boosting morale and team cohesion.

### 3. Coordinating Diagnostic Specification Updates
This document is updated by many teams in our organization every three-week sprint and is used by `team-uds` to generate libraries and tests for others.

#### I. Internal `team-uds` Coordination
- **Pre-Sprint Spec Review & Planning:**
    - **Activity:** Before or early in sprint planning, dedicate 30-60 minutes for `team-uds` to discuss the Diagnostic Specification.
    - **Focus:** Identify likely changes, review past changes from other teams, and anticipate impacts on library/test generation.
    - **Output:** Clear spec-related tasks, dependencies, and clarification needs.
- **Dedicated Spec Update Tasks:**
    - **Activity:** Create specific Jira tasks (labeled `team-uds`) for updating sections of the spec.
    - **Benefit:** Treats spec updates as trackable work, ensuring time allocation and progress visibility.
- **Internal Review of `team-uds` Contributions:**
    - **Activity:** Conduct internal peer review within `team-uds` before contributions are merged/published.
    - **Focus:** Check for clarity, accuracy, completeness, and consistency.
    - **Benefit:** Improves contribution quality and catches errors early.
- **Continuous Impact Assessment for Libraries/Tests:**
    - **Activity:** As spec updates become known, immediately assess the impact on library/test generation.
    - **Focus:** "How does this change affect what we need to build or test?"
    - **Benefit:** Allows early adjustments to development plans.

#### II. Coordination with Other Teams & Broader Organization
- **`team-uds` Spec Point Person (Optional & Rotational):**
    - **Activity:** Consider a rotating sprint role for a "spec liaison" within `team-uds`.
    - **Focus:** Proactively check for updates, attend cross-team spec meetings, and channel info back to `team-uds`.
    - **Benefit:** Streamlines communication.
- **Active Monitoring of Spec Changes:**
    - **Activity:** Establish a clear method to stay informed (e.g., system notifications, changelog checks, dedicated channels).
- **Proactive Clarification & Feedback Loop:**
    - **Activity:** If ambiguities or issues are identified, proactively seek clarification from relevant teams/owners. Provide feedback on how spec changes impact your deliverables.
    - **Benefit:** Improves overall spec quality and prevents rework.
- **Understand the "Why" Behind Changes:**
    - **Activity:** When other teams make changes, try to understand the underlying reasons.
    - **Benefit:** Helps anticipate spec direction and make informed design decisions.

#### III. Integrating Spec Updates into Workflow
- **Early Spec-Driven Development:**
    - **Activity:** Begin using stable spec sections to drive library/test development as soon as possible.
    - **Benefit:** Provides early feedback on spec implementability.
- **Regular Sync on Spec Status:**
    - **Activity:** Briefly mention critical spec updates/blockers in larger team stand-ups if they impact broader goals. Ensure spec status is a check-in point for internal `team-uds` discussions.

### General Principles for the Small Team:
- **Proactive Communication:** Encourage open and frequent updates, even if informal.
- **Shared Responsibility:** Foster a sense that everyone is responsible for the small team's success.
- **Regular Mini-Retrospectives:** Periodically (e.g., weekly or bi-weekly for 15-30 minutes), the small team can reflect on what’s working well in their collaboration and what could be improved.
