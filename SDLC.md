# 我是啥来着？这啥文件来着？我写这个干嘛来着？嗯？
## Software Development Life Cycle Note

### Code and Fix problems

❖ No process steps – no specs, docs, tests…
❖ No separation of concerns – no teamwork
❖ No way to deal with complexity

### Process Models
❖ bring order to the chaos of software development
❖ bring structure to software engineering
❖ provide a road map for software teams
❖ define the flow of all activities, actions and tasks, the degree
of iteration, the work products, and the organization of the
work.
❖ however, software engineering work and the products
that are produced remain on “the edge of chaos.”

### Waterfall (1968)
communication : project initiation, requirements gathering
planning : estimating scheduling, tracking
modeling : analysis design
construction : code test
development : delivery support feedback
啊啊啊啊我喜欢花卷我的花卷我的我的我的我的
❖ useful when:
❖ requirements for a problem are well understood
❖ work flows from communication through
deployment in a reasonably linear fashion.
❖ e.g., an adaptation to accounting software that has been
mandated because of changes to government regulations
### Waterfall: Problems
❖ Real projects rarely follow a sequential flow
❖ Hard to state all requirements explicitly
❖ No maintenance or evolution involved
❖ Customer must have patience
❖ Any blunder can be disastrous
### Boehm’s First Law
Errors are most frequent during requirements and design activities 
the more expensive the later they are removed.
### Incremental Model
❖ Each linear sequence produces a particular “increment”
to the software
❖ First increment typically core product; more features
added by later increments
❖ Allows flexible allocation of resources
### Incremental Model: When to Use?
❖ initial software requirements are reasonably well
defined, but the overall scope of the development effort
is not purely linear.
❖ may need to provide a limited set of software
functionality to users quickly and then refine and
expand in later software releases.
❖ => choose a process model that is designed to produce
the software in increments
### Evolutionary Model: Prototyping
❖ business and product requirements often change as
development proceeds
❖ tight market deadlines => impossible to complete the
software BUT must introduce a limited version to meet
competitive or business pressure
❖ core product requirements: well understood
❖ but not the details of product or system extensions
❖ need a process model that accommodates a product that
grows and changes.
### Spiral Model
❖ evolutionary software process model that couples the iterative
nature of prototyping with the controlled and systematic aspects
of the waterfall model
❖ System is developed in series of evolutionary releases
❖ early releases: model/prototype
❖ later releases: increasingly more complete versions
❖ Milestones for each iteration of the spiral
❖ Process does not end with delivery
❖ Reflects iterative nature of development
### Unified Process (1999)
❖ a “use case driven, architecture-centric, iterative and
incremental” software process
❖ draws best features of traditional models
❖ recognizes the importance of customer communication
❖ focus on architecture
- ❖ goals: understandability, reliance to future changes,
and reuse
- Encompasses communication with user + planning
- Results in a set of use cases
- Architecture is just a tentative outline
- Refines and expands preliminary use cases
- Provides architecture and initial design model
- Builds (or acquires)
software components
according to architecture
- Completes design model
- Includes implementation,
unit tests, acceptance tests
- Software given to end users for beta testing
- Feedback reports defects and changes
- Creates support information (user
manuals, troubleshooting guides, etc)
47
- Software is deployed
- Problems are monitored
- Feedback results in new iteration
❖ It is likely that at the same time the construction,
transition, and production phases are being conducted,
work may have already begun on the next software
increment. This means that the five UP phases do not
occur in a sequence, but rather with staggered
concurrency.
❖ Draws on best features of conventional process models
❖ Emphasizes software architecture and design
❖ Integrates with UML modeling techniques (more on this
later)
### Agile Model
❖ Individuals and activities over processes and tools.
❖ Working software over comprehensive documentation.
❖ Customer collaboration over contract negotiation.
❖ Responding to change over following a plan.
❖ Fast development? Hacking? Prototyping? Uncontrolled
fun? Programmer heaven?
❖ Agility = ability to react to changing situations quickly,
appropriately, and effectively.
❖ notice changes early
❖ initiate action promptly
❖ create a feasible and effective alternative plan quickly
❖ reorient work and resources quickly and effectively
### Agile Process: When to Use
❖ Difficult to predict which requirements will persist or
change in the future.
❖ For many types of software, design and development
are interleaved.
❖ Analysis, design, construction, and testing are not as
predictable.

So, how to tackle unpredictability?
Make the process adaptable
In agile, cost of changes is low compare to other SD processes!
Agility and the Cost of Change

### Extreme Programming (XP) (1999—)
❖ the most widely used approach to agile software
development
❖ uses an object-oriented approach as its preferred
development paradigm
❖ four framework activities: planning, design, coding, and
testing.
- Each story becomes a unit test that serves as
specification
- The program is continuously refactored to
have the design match
- pair programming:
to ensure continuous review
- Unit tests
-- detect errors
-- find missing functionality
-- measure progress
-- the resulting prototypes result in new stories
### Scrum
❖ Work in small teams to maximize communication,
minimize overhead and maximize knowledge sharing.
❖ Adaptable to technical and business changes.
❖ Yields frequent software increments that can be inspected.
❖ Development work and the people who perform it are
partitioned into clean, low coupling partitions.
❖ Constant testing and documentation is performed.
❖ Ability to declare project “done” whenever required.
### Scrum Process Flow
❖ backlog : A prioritized list project requirements or
features that provide business value
❖ sprints : Consists of work units that are required to
achieve a defined backlog into a predefined
time-box (usually 30 days).
❖ scrum meetings : Short 15 mins. meetings held daily by the scrum
team. The Scrum master leads the meeting.
❖ demos : Demonstrate software increment to the
customer for evaluation.
