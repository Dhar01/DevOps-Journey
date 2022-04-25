# Scalability

**Scalability** is a system's ability to add resources to keep up with growing demand. A system with great scalability will be able to do this without interrupting services.

### Vertical Scaling

**Vertical scaling** means adding computing resources to existing systems. This can be achieved in a variety of ways such as increasing network speeds or the available storage or RAM of servers.

Vertical scaling is relatively simple and affordable, however, the application could experience downtime as a result of performing upgrades.

### Horizontal Scaling

**Horizontal Scaling** means increasing system resources by adding nodes (*i.e. servers*) to the system. Each node is able to server the same application and a <ins>load balancer</ins> distributes requests across the nodes.

Horizontal scaling is complex to setup but can be achieved without any downtime for existing servers.

# Elasticity

**Elasticity** is the ability of a system to add or subtract resources automatically in response to fluctuating demand.

An elastic system reduces resources when demand slows, helping to avoid unnecessary costs with pay-per-use infrastructure services.

# Dependencies

In software development, **dependencies** are external files and programs that are not part of an application but are used by it.

# Orchestration

According to RedHat, **Orchestration** is the automated configuration, management, and coordination of infrastructure.

Orchestration software, such as <mark>Kubernetes</mark> controls many components working together in harmony. This software can:

- Deploy containers across many servers.
- Restart failed containers
- Roll out updates without any downtime.
- Horizontally scale containerized applications.

# Immutable Infrastructure

**Immutable infrastructure** means that servers are not changed once they are created. Instead, when infrastructure configurations change, new servers are created and old ones are destroyed.

Immutable infrastructure and the use of configuration files guarantees that all servers are created in the same manner and eliminates the risk of configuration drift.

# Manual Infrastructure configuration

Historically, infrastructure configuration has been performed manually by people. This has led to high costs, inconsistency across configurations and difficulty in pinpointing sources of errors.

# Virtualization

**Virtualization** is the process of running a simulated virtual computer on a host machine. These virtual computers, usually called virtual machines (VMs), are distinct environments each with their own operating system (OS), dependencies such as binaries/libraries, and users. Virtualization allows multiple virtual computers to be run on a single host machine.

# Containerization

**Containerization** is a form of virtualization in which multiple virtual environments called <ins>containers</ins> can share the operating system of the host physical machine.

Containers differ from virtual machines in that they share the underlying operating system. Containers are fast, lightweight and portable.

# Cloud-based infrastructure

Cloud-based infrastructure refers to infrastructure and computing resources that are made available to users over the internet. Cloud resources are generally managed and housed by a dedicated third-party provider.

### Infrastructure as Code

**Infrastructure as Code** (<mark>IaC</mark>) is the act of defining infrastructure configuration in version controlled configuration files.

### IaC Benefits

Infrastructure as Code (IaC) has the following benefits over manual infrastructure configuration:

- <ins>Speed</ins>: Configuration can be faster since it is automated.
- <ins>Consistency</ins>: Infrastructure state consistently matches what is specified in configuration files.
- <ins>Visibility</ins>: Version control make it easy to tell exactly when and where changes are made.
- <ins>Cost</ins>: Fewer staff hours are spent configuring and troubleshooting infrastructure.
