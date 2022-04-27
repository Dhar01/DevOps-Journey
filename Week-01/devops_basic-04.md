# System Threats

Common problems that occur to a system are internal failures, external failures, as well as malicious attacks. These problems are all inevitable, but DevOps practices can minimize their frequency and severity.

# Resiliency

In DevOps, **resiliency** is a system's ability to continue to provide an acceptable level of performance even when problems are occurring within the system.

### Resiliency methods

Resiliency can be achieved through methods such as:

- **Caching**: storing frequently or recently retrieved responses in a fast, accessible location.
- **Input Validation**: running checks for malicious requests and throwing them away if found.
- **Load balancing**: distributing requests evenly across different servers to avoid networking any individual server.

### Measuring Resiliency

Resiliency can be measured by determining how quickly a critical failing service can recover, and the degree to which critical services are available during a failure (*number of failed requests, latency*).

### Resiliency Measurements

Resiliency is measured to gain an understanding of how our system has performed under adverse conditions.

These measurements can be compared to targets to identify areas for improvement.

### Resiliency Testing

A system’s resiliency can be tested through practices such as:

- Simulating internal and external failures (**Chaos engineering**).
- Pushing the system to its limits through tests (**Load Testing**).
- Attempting to locate security vulnerabilities (**Penetration Testing**).

> The term '*Chaos engineering*' came from the Netflix engineers, they introduced the idea of a '*Chaos monkey*'.

Oh, [here](https://github.com/Netflix/SimianArmy/wiki/The-Chaos-Monkey-Army) is the whole army!

# Internal System Problems

Internal system problems include system changes and hardware failures.

These internal problems can be addressed through practices such as <ins>change-management processes</ins> and <ins>redundancy</ins>.

# External System Problems

External system problems include loss of dependency availability or support.

These can be addressed through practices such as <ins>fallback strategies</ins> and a proactive approach to dependency management.

# Cyber Attacks

Cyber attacks include DDoS and SQL injection attacks and can be mitigated through practices such as input validation.

# Recovery Point Objective

Recovery Point Objective (**RPO**) is the acceptable amount of data loss after a system outage.
