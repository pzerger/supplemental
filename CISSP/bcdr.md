# Business Continuity and Disaster Recovery

- [Goals of BCDR](#goals-of-bcdr)
- [Processes and Plans](#processes-and-plans) 
- [Metrics](#metrics)
- [Types of Impacts](#types-of-impacts)
- [Testing](#testing)
- [Types of Sites](#types-of-sites)
- [Teams](#teams)
- [HA vs DR](#ha-vs-dr)

### Goals of BCDR
The primary goals of BCDR include:
- **Protection**: Safeguard critical business functions and assets from disruptions.
- **Recovery**: Restore critical functions and processes after a disruption.
- **Continuity**: Ensure continuous business operations, even during disruptions.

See [Disaster Recovery on Wikipedia](https://en.wikipedia.org/wiki/Disaster_recovery)

[Back to ToC](#business-continuity-and-disaster-recovery)

### Processes and Plans
1. **Business Impact Analysis (BIA)**: This identifies the impact of disruptions on business operations and establishes priorities for recovery.
2. **Business Continuity Plan (BCP)**: Provides a strategy to continue operations in the event of a disruption. It derives its details from the BIA.
3. **Disaster Recovery Plan (DRP)**: Focuses on restoring IT systems and data after a disaster. It's a subset of the BCP.
4. **Business Resumption Plan (BRP)**: A subset of the DRP, it details how to quickly resume business after a disruption.
5. **Continuity of Operations Plan (COOP)**: The plan for continuing to do business until the IT infrastructure can be restored. See [Continuity of Operations on Wikipedia](https://en.wikipedia.org/wiki/Continuity_of_operations)
5. **Service Level Agreement (SLA)**: A documented agreement between a service provider and a client about the level of service expected during and after a disruption.
6. **Mutual Assistance Agreements (MAAs)**: Agreements between entities to provide mutual aid in the event of a disaster. 

Relationship: BIA → BCP → DRP → BRP. SLAs and MAAs serve as supportive documents to ensure the effectiveness and cooperative nature of the plans.

[Back to ToC](#business-continuity-and-disaster-recovery)

### Metrics
- **Mean Time Between Failures (MTBF)**: Average time between system failures.
- **Mean Time To Detect (MTTD)**: Average time to detect a failure.
- **Mean Time to Failure (MTTF)**: Average time until a system or component fails.
- **Mean Time to Repair (MTTR)**: Average time to repair a system or component.
- **Recovery Point Objective (RPO)**: Maximum acceptable amount of data loss measured in time.
- **Recovery Time Objective (RTO)**: Maximum acceptable time to restore a function after a disruption.
- **Max Tolerable Downtime (MTD)**: Maximum period a service can be down without causing unacceptable damage.

### Types of Impacts
1. **Catastrophe (categories of disruption)**: Severe events causing significant disruption like nuclear incidents.
2. **Disaster (categories of disruption)**: Serious disruption events but not as severe as catastrophes like fires or floods.
3. **Man-made Disasters**: Events caused by human actions like terrorism or sabotage.
4. **Natural Disasters**: Events caused by natural phenomena like earthquakes or hurricanes.
5. **Non-Disaster (categories of disruption)**: Minor disruptions that don't significantly affect business like a short-term power outage.

[Back to ToC](#business-continuity-and-disaster-recovery)

### Testing
Tests and exercises for validating business continuity and disaster recovery plans:

- **Full Interruption Test**: Live testing, fully interrupting and replacing the primary system.
- **Read-through Test**: Verbal exercise, reviewing the plan for accuracy and comprehension.
- **Parallel Test**: Live testing, running systems in parallel (backup and primary).
- **Simulation Test**: Live scenario without real interruption.
- **Structured Walk-through**: Verbal exercise, team members discuss and walk through scenarios.

[Back to ToC](#business-continuity-and-disaster-recovery)

### Types of Sites
- **Cold Site**: Minimal infrastructure, no immediate availability. Cost: Low, Recovery Effort: High.
- **Warm Site**: Partially equipped, moderate recovery time. Cost: Medium, Recovery Effort: Medium.
- **Hot Site**: Fully equipped, immediate availability. Cost: High, Recovery Effort: Low.
- **Mobile Site**: Portable, can be set up at or near a disaster site.
- **Service Bureau**: Outsourced site, often provided by a third-party vendor.

[Back to ToC](#business-continuity-and-disaster-recovery)

### Teams
- **Recovery Team**: Focuses on recovering operations after a disruption.
- **Salvage Team**: Focuses on saving and recovering assets from the disrupted site.

[Back to ToC](#business-continuity-and-disaster-recovery)

### HA vs DR
**High availability** refers to ensuring systems and applications have minimal downtime and are accessible to users. It focuses on maintaining operations through predictable failures like hardware crashes or minor software bugs. Methods for high availability include redundancy, failover clustering, and load balancing. 

High availability is often the first line of defense, but disaster recovery deals with worst-case scenarios when high availability measures are overwhelmed. They work together to deliver both day-to-day accessibility and the ability to recover from a catastrophe.

[Back to ToC](#business-continuity-and-disaster-recovery)