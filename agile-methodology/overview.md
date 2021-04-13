# Agile
Agile is a structured and iterative approach to project development and management and there are 2 common methodologies

1. Scrum: Great for project and feature driven work and commit to ship working software through set intervals called sprints
2. Kanban: Visualizing your work, limiting work in progress, and maximizing efficiency with the help of Kanban boards

## Agile principles
1. Break work into small pieces.
2. Define MVP (Minimum viable product)
3. Categorise work into MoSCoW - Must have | Should have | Could have | Won't have

## Scrum
- Development cycles that repeat until the project is done.
- Define the cycle duration, e.g 2 weeks
- Items can be added to backlog anytime
- Constant ongoing backlog refining

### Process steps -
1. Sprint planning
2. Daily scrums
3. Sprint review
4. Sprint retrospective

### Roles -
* Product manager: Creates and owns product idea, talks to customers and provides high level requirements to solve business case.
* Product owner: Works with Agile team constantly to facilitate, prioritise and validate user requirements and sizes, refines and prioritizes times in backlog.
* Project management office: Makes sure company procedures, practices and operations are correct, goes through planning, status reporting, risk mitigation, dependency and escalation management.
* Scrum master: Leads daily scrums, removes blockers
* Manager/Tech Lead: Code reviews, staffing, work estimation, technical coaching, supports PM/PO to provide technical inputs for product idea/vision.

### User stories -
- Describe requirements in the from of stories.
- Short, simple, descriptive.
- Include development, review, testing and deployment.
- Define **INVEST** for each story - [ Independant | Negotiable | Valuable | Estimable | Small | Testable ]

### Types of work items -
1. Story
  - Description
  - Acceptance criteria
  - Identify key stakeholders
  - Identify blockers
  - Size the issue
2. Bug
  - Define the problem
  - Mention steps to reproduce
  - Define expected behaviour
  - Capture actual behaviour
  - Could be sized after it's complete
3. Spike
  - Reseach task
  - Problem is outlined
  - Outcome for the research is defined
  - Timebox is defined in the title of the issue

#### Sizing stories -
- Story points - Unit of measure for expressing an estimate of overall effort required to fully implement item in the backlog.
- Typically sized using fibonacci series [ 0.5, 1, 2, 3, 5, 8, 13 ]
- Try to break stories to have minimum story points.
- Every member in the team votes anonymously to size the ticket.
- Most of the tickets are sized before pulling into the sprints, bugs and spikes could be an exception.

#### Definition of done -
Every story should have completed the below steps for it to be marked as complete
1. Coding
2. Review
3. Testing
4. Monitoring/Alerting
5. Evaluate if meets security criteria

### Flow of work -
1. Backlog refining
  - Complete requirements
  - Create tickets in backlog
  - Review requirements
  - Prioritize stories in backlog
  - Size stories
  - Add stories to sprint
2. Sprint planning
  - Rolling wave planning - Keep planning throughout the sprint
  - Progressive elaboration - Take inputs from demos and replan releases from learnings
  - Iteration 0 - Planning before first sprint
  - Iteration H - Hardening - Planning before release
  - Define sprint goal
  - Check predicted story points and commited story points
3. Daily scrum
  - Daily meetings at same place/time
  - Time-boxed to 15 mins
  - Everyone updates their status and answers questions like what did you do yesterday, what will you do today, any blockers.
  - Focus on impediments, scrum master supposed to get everyone unblocked.
4. Sprint review
  - Show what was accomplished at the last day of sprint
  - Demos should be done on production to test your changes in action
5. Sprint retrospective
  - Identifies how did the sprint go, what went well and what could have gone better
  - Suggests improvements
  - Suggestions for kaizen

#### Do's and Dont's of sprint planning -
1. Do not close incomplete stories
2. Do not create clones for stories to be pulled in next sprint
3. Do not change story points, unless the estimate was off
4. Move incomplete stories to next sprint if important, else move to backlog

#### Efficiency improvements -
- Recognize and eliminate waste after retrospective
- Most common wastes - [ Partially done work | Extra processes | Extra features | Task switching | Waiting | Motion | Defects ]
