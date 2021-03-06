# Software Engineering

## Table of Contents

-   [**Software Engineering**](#software_engineering)

    -   [**Table of Contents**](#table-of-contents)

        -   [Introduction](#introduction)
        -   [Software is Developed not Manufactured](#software-is-developed-not-Manufactured)
        -   [Software Development Life Cycle](#software-development-life-cycle)
        -   [Waterfall Model](#waterfall-model)
        -   [Iterative Model](#iterative-model)
        -   [SDLC Spiral Model](#sdlc-spiral-model)
        -   [Testing](#testing)
        -   [Concurrency](#concurrency)
        -   [Error Handling](#error-handling)
        -   [Formatting](#formatting)
        -   [Comments](#comments)

### `Introduction`

Software engineering is the application of engineering to the development of software in a systematic method.

Why Software engineering?

1. As Software development is expensive so proper measures are required so that the resources are used efficiently and effectively.

2. Cost and time considerations are another factor, which arises the need for Software Engineering.

3. Reliability factors.

Main Principal: The Vision must be clear.

**[⬆ back to top](#table-of-contents)**

### `Software is Developed not Manufactured`

Why Software is Developed or Engineered, not Manufactured?

Answer:
Saying that something is manufactured means that it is created, 'from the ground up', from nothing. And that certain chemical/physical processes are used to create it.

Software has NO physical form. It is computer code, instructions for an operating system (something else without physical form). A computer program is kind of like a story, something else without physical form. Although it is easy to memorize a short story, it is darn near impossible to memorize computer code. People who write computer programs use nothing of a physical process to create the software. They simply use words/letters to create the code. The finished code is called 'software'. Sometimes the software is an operating system, a program, a widget, or simply 'code'.

**[⬆ back to top](#table-of-contents)**

### `Software Development Life Cycle`

Software Development Life Cycle (SDLC) is a process used by the software industry to design, develop and test high quality software. The SDLC aims to produce a high-quality software that meets customer expectations, reaches completion within times and cost estimates.

![](software-lifecycle.png)

1. Planning and Requirement Analysis.
2. Defining Requirements
    - SRS
3. Designing the Product Architecture
    - meta-data and data dictionaries,
    - logical diagrams,
    - data-flow diagrams
4. Building or Developing the Product
    - Coding
5. Testing the Product
6. Deployment in the Market and Maintenance.

SDLC Models
There are various software development life cycle models defined and designed which are followed during the software development process.

    - Waterfall Model
    - Iterative Model
    - Spiral Model
    - V-Model
    - Big Bang Model

**[⬆ back to top](#table-of-contents)**

### `Waterfall Model`

![](waterfall-model.png)

Waterfall Model:

1. The Waterfall model is the earliest SDLC approach that was used for software development.

2. Waterfall model is an example of a Sequential model. So it is also referred to as a linear-sequential life cycle model.

3. It is very simple to understand and use. In a waterfall model, each phase must be completed before the next phase can begin.

4. Also called as classic life cycle model.

When Should You Use It?
Ans:

1. Requirements are clear and fixed that may not change.

2. There are no ambiguous requirements.(no confusion)

3. It is good to use this model when the technology is well understood.

4. The project is short and cost is low.

5. Risk is zero or minimum.

Advantages:

1. Simple and easy to understand and use.
2. Easy to manage.
3. Works well for smaller and low budget projects where
   requirements are very well understood.
4. Clearly defined stages and Well understood.
5. Easy to arrange tasks.
6. Process and results are well documented.

Disadvantages:

1. No working software is produced until late during the life cycle.
2. High amounts of risk and uncertainty.
3. Not a good model for complex and object-oriented projects.
4. Poor model for long and ongoing projects.
5. It is difficult to measure progress within stages.
6. Cannot accommodate changing requirements.

**[⬆ back to top](#table-of-contents)**

### `Iterative Model`

![](iterative-model.png)

Iterative Model:
In iterative model the organization start with some of the software specification and develop the first version of the software. After the first version if there is a need to change the software then a new version of the software is created with a new iteration.
It will repeat until deployment of the software.

When to use iterative model:

1. Requirements of the complete system are clearly defined and understood.
2. When the project is big.
3. Major requirements must be defined; however, some details can evolve with time.

Advantages of Iterative model:

1. Generates working software quickly and early during the software life cycle.
2. Easier to test and debug during a smaller iteration.
3. Easier to manage risk because risky pieces are identified and handled during its iteration.
4. Each iteration can be easily managed.

Disadvantages of Iterative model:

1. It is not suitable for smaller projects.
2. It is not suitable for changing requirements.
3. More management Attention is required.

**[⬆ back to top](#table-of-contents)**

### `SDLC Spiral Mode`

SDLC Spiral Model

![](spiral-model.png)

1. Spiral model is one of the most important Software Development Life Cycle models.
2. This model was first described by Barry Boehm in 1986.
3. Spiral Model can handle large amount of risk.
4. The spiral model has four phases:
    - Planning
    - Risk Analysis
    - Development & Testing
    - Evaluation.
5. In its diagrammatic representation, it looks like a spiral.

PLANNING: Requirements are gathered from the customers and the objectives are identified,
and analyzed at the start of every phase. Requirements like BSR (Business
Requirements Specifications) and SRS(System Requirements
Specifications) are gathered from this quadrant. Then alternative solutions
possible for the phase are proposed in this quadrant.

RISK ANALYSIS: During the second quadrant all the possible solutions are evaluated to select
the best possible solution. Then the risks associated with that solution is
identified and the risks are resolved using the best possible strategy. At the end
of this quadrant, Prototype is built for the best possible solution.

DEVELOPMENT and TESTING: During the third quadrant, the identified features are Developed and verified
through Testing.

EVALUATION: This phase allows the customer to evaluate the output of the project before the
project continues to the nest spiral. Customer evaluate the software and provide
their feedback and approval.
In the end, planning for the next phase is started.

When to use Spiral Model?

1. When the project is large.
2. Where the amount of risk is large.
3. Where requirements are complicated.
4. Where Software require significant changes.
5. Where enough time frame is their.
6. Where releases are required to be frequent.

Advantages of Spiral Model:

1. Best model for the risk analysis and risk handling.
2. Good for large projects.
3. Flexibility in Requirements.
4. Customer Satisfaction.
5. Software is produced Early.

Disadvantages of Spiral Model:

1. The Spiral Model is much more complex than other SDLC models.
2. Spiral Model is not suitable for small projects as it is expensive.
3. It’s Costly for smaller Projects.
4. Difficulty in time management: As the number of phases is unknown at the start of the project, so time estimation is very difficult.
