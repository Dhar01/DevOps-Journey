# Deployment

**Deployment** is the general process of making a piece of software available to its users. It encompasses a number of important tools and processes including:

- Version control systems
- Infrastructure Management
- Testing
- Deployment environments.

# Version Control Systems

A **version control** system helps keep a project’s files clean, organized, and maintainable by tracking and maintaining different versions of a file or project.

Important features of version control systems include:

- Tracking every change that is introduced into the code
- Saving all previous versions of the code.
- Identifying merge conflicts.

### Branching

In version control, **branching** is the process of creating a copy of the source code (*the 'trunk'*).

Developers can work on their branches without changing the source code that real users and other developers depend on.

### Merging

In version control, **merging** is the process of combining the changes in one branch with another.

This occurs when the differences between the two branches are ready to be reconciled.

# Type of Tests

Different types of tests exist that are used in the various stages of deployment. Four types of tests that are often used are:

- A **unit test** evaluates the smallest possible unit of testable code, such as a single function.
- An **integration test** evaluates how the units of a program work with one another.
- An **acceptance test** evaluates whether the user experience aligns with the business requirements of the software.
- An **end-to-end test** evaluates the application's behavior using production-like infrastructure that includes networking, databases, and calls to external APIs.

# Infrastructure definition

**Infrastructure** is the set of hardware and software components that are used to develop, test, deploy and host web services.

Examples of these components include servers, switches, routers, and operating systems.

# Operations Team

**Operations team** are traditionally responsible for managing an application's infrastructure.

Services provided by the Operations team include infrastructure configuration, device management, incidence and security response, and ongoing maintenance.

# Environments

An **environment** in the context of creating and deploying software, is the subset of infrastructure resources used to execute a program under specific constraints.

Common example includes:

- Local development environment
- Integration environment
- QA/Testing environment
- Staging environment
- Production environment

### Local Development environments

The **local development environment** is a developer's computer where they create features of an application.

### Integration environments

The **integration environment** is where developers attempt to merge features into a unified code-base, often using version-control software like Git.

### Testing environments

The **quality assurance**(QA)/**testing environment** is where tests are executed to ensure the functionality and usability of a project.

### Staging environments

The **staging environment** mimics the final production environment. Final performance tests can be executed before real users are involved.

### Production environments

The **production environment** refers to the infrastructure resources that support the application accessed by clients.

The infrastructure consisted of hardware and software components including databases, servers, APIs, and external services scaled for real-world usage.

# DevOps

**DevOps** is a culture that is supported by a set of practices and tools that assists the collaboration of Development and Operations teams.

DevOps aims to resolve the issues in the development process that arise due to the conflicting goals and isolation of traditional development and operations teams.

### Integration of Development & Operations teams

The integration of Development and Operations teams results in the following benefits:

1. Work is no longer passed back and forth between teams.
2. Development, staging, and production environments are consistent.
3. Development best practices are applied to infrastructure management.

### DevOps Team improvements

The central pillars of a DevOps culture include:

- **System Level thinking**: Thinking about the whole production system, rather than a single department or part.
- **Feedback loops**: allowing each part of the process to receive information and improve.
- A culture of continuous experimentation and learning.

### DevOps team Bottlenecks

DevOps teams seek to reduce the impact of system bottlenecks. **Bottlenecks** are the slowest part of the production process and they limit the overall pace of production.

### DevOps Team Communication

Companies with separated development and operations teams can have some issues:

- Developers might concentrate on the code without considering infrastructure or testing needs.
- The Operations team might only consider infrastructure needs without considering impacts on functionality.

DevOps seeks to have each member of the team consider the entire development process. All members share responsibility for the final result.

### DevOps Feedback Loops

**Feedback loops** use metrics to gain insights into application performance. Action can then be taken from these insights to continuously improve processes. Metrics that measure customer value should be prioritized.

### DevOps Failure

In DevOps, failure is seen as something to learn from and is a normal part of the improvement process. It can lead to valuable insights being discovered.

One method DevOps teams use to normalize failure is through **blameless retrospectives** (*or postmortems*).
