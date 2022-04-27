# Service Level Indicator

A Service Level Indicator (**SLI**) is a quantitative measure of a metric.

For example, an SLI might indicate that the current loading time of a web-page is 152 milliseconds.

# Service Level Agreement

A Service Level Agreement (**SLA**) is a contract with consumers about expected levels of service.

# Service Level Objective

A Service Level Objective (**SLO**) is a range of valid measurements for a metric.

For example, an SLO might define that a web-page loads within 200ms of the user accessing it.

# slo-sli-sla

**SLIs** (*Service Level Indicators*), **SLOs** (*Service Level Objectives*), and **SLAs** (*Service Level Agreements*) are used to tie system monitoring metrics to business goals and objectives.

| Term | Description                                |
| ---- | ------------------------------------------ |
| SLA  | A contract with consumers                  |
| SLO  | A range of valid measurements for a metric |
| SLI  | The current measurement of a metric        |

# Metrics

**Metrics** express a value relevant to the system at a specific point of time. Some key metrics:

- **Latency**: Latency is the time between the start of an event, such as serving a request, to its completion. This metric is a key indicator of performance.
- **Traffic**/**Connections**: Traffic is the amount of system usage over time. An abnormal amount of traffic can require scaling to maintain performance.
- **Errors**: An error is invalid state our system has reached. Examples include a memory limit or reading a corrupted data file. The rate of errors returned by a service can indicate deeper issues.
- **Saturation**: Saturation describes the load on our system's resources. Our system is reaching its limits can result in poor performance.
- Page load time
- **User logins**: successes, failures, time taken, daily active users, weekly active users 
- **Searches**: number performed, latency
- **Databases**: query latency, transactions per second.
- **Standard OS metrics**: CPU, memory, network, and disk usage.

# Monitoring

**Monitoring** allows teams to watch and understand the state of their system by gathering predefined metrics or logs.

### Alert

An **alert** helps teams stay informed about activities occurring in a monitored system.

### Monitoring Pitfalls

Improper monitoring can produce too many alerts which are not useful or actionable. These noisy alerts can cause staff to distrust alerts and ignore alerts that are actually useful.

### Monitoring tools

In DevOps, monitoring tools are use to provide continuous process of identifying, tracking, analyzing, and alerting on specific components of the system.

### Monitoring Metrics

When implementing monitoring, metrics should be chosen that reveal the health of the system, as well as issues with user experience.

### Monitoring and Observability Metrics

Metrics should exist to measure the quality of the monitoring and observability of systems. These metrics might include the number of improper alerts, time for issue resolution, and the time taken for an issue to be identified.

### Observability

**Observability** is the degree to which the metrics of a system can be acted upon to locate and fix a problem.

### Monitoring Quality

To improve monitoring quality:

- Define actionable alerts that are customized to the needs of our organization.
- Collect application logs and make this data available and understandable.
- Incorporate logging into the build and deployment process.
- Define custom, actionable alerts that are relevant to the organization.

Handling alerts:

- **False negatives**: Pay attention when a user-affecting issue has happened, and the system does not alert us. The lack of an alert indicates a hole in our monitoring. We should hold a retrospective meeting to find out what metrics could have alerted us to the problem. 
- **False positives**: This occurs when an alert is generated, but there is nothing wrong with the system. The threshold for an alert may need to be adjusted, or the alert might need to be deleted altogether.
- **Unactionable alerts**: This type of alert has little to do with a problem and doesn’t need anything done. Like false negatives, we should reduce or delete un-actionable alerts. 
