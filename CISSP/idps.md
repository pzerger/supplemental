# Intrusion Detection and Intrusion Prevention Systems (IDS/IPS)

## What is the goal of intrusion detection and prevention (IDS/IPS)?

The primary goal of IDS/IPS is to identify and possibly prevent unauthorized intrusions into computer systems or networks. They monitor traffic, identify suspicious activities, and take appropriate actions based on predefined rules or algorithms.

## Intrusion Detection System (IDS)

**Function**: Monitors network or system activities for malicious or policy-violating behaviors. When detected, it sends alerts to administrators.

**Advantages**:
- Provides visibility into malicious activities.

- Can cover a large network segment.

**Disadvantages**:
- Can generate false positives.

- Does not take direct action to block attacks; it only alerts.

## Intrusion Prevention System (IPS)
**Function**: Proactively denies network traffic based on a security policy, blocking malicious activities in real-time.

**Advantages**:

- Takes direct action against threats.

- Can stop attacks before they reach the target.

**Disadvantages**:

- Can generate false positives that block legitimate traffic.

- Requires careful tuning to prevent disrupting network operations.

## Behavior-based IDS/IPS

**Function**: Monitors network behavior, learns what's normal, and alerts or blocks traffic that deviates from the baseline.

**Advantages**:

- Can detect previously unknown threats based on behavior.

- Adapts to changing network behaviors.

**Disadvantages**:
- Potential for false positives, especially in the learning phase.
- Requires continuous tuning as network behaviors evolve.

## Knowledge-based IDS

**Function**: Uses a database of known vulnerabilities and attack patterns to detect intrusions.

**Advantages**:
- Can quickly detect known attack patterns.
- Lower false positives when well-tuned.

**Disadvantages**:

- Cannot detect zero-day or previously unknown threats.

- Requires regular updates to its database.

## Host-based IDS/IPS

**Function**: Installed on individual systems to monitor and protect them from malicious activities.

**Advantages**:

- Provides detailed insight into host activities.

- Can identify attacks targeting specific OS or applications.

**Disadvantages**:

- Requires deployment on each host, making scalability challenging.

- Might not capture broader network-level activities.

## Types of Network-based IDS/IPS

### Network-based IDS/IPS

**Function**: Monitors traffic across the network and identifies suspicious activities.

**Advantages**:

- Covers a broad network segment.

- Can detect and potentially block malicious traffic.

**Disadvantages**:

- Can be resource-intensive.

- Potential for false positives.

### Inline Network-based IDS/IPS

**Function**: Positioned directly in the traffic flow and can actively block or modify malicious packets.

**Advantages**:

- Immediate response to detected threats.

- Can modify or drop malicious traffic in real-time.

**Disadvantages**:

- Can introduce latency.

- A failure could impact network availability.

### Passive Network-based IDS/IPS

**Function**: Monitors a copy of network traffic without interacting with the actual traffic flow.

**Advantages**:
- Does not introduce latency.

- Failure does not disrupt the actual traffic.

**Disadvantages**:

- Cannot take active prevention measures.

- Might miss some traffic if not all traffic is mirrored.

### Sensors and Collectors
**Function**:
- **Sensors**: Devices or applications that collect data about traffic or activities.

- **Collectors**: Devices or applications that receive and store data from sensors, often processing and analyzing the data.

**Advantages**:
- Provides a distributed approach to detection and analysis.

- Allows for centralized storage and analysis of data.

**Disadvantages**:
- Requires management and coordination between sensors and collectors.

- Can be resource-intensive for large-scale deployments.

## Wireless IDS/IPS
**Function**: Monitors wireless network traffic and behaviors to detect and possibly prevent unauthorized activities or attacks.

**Advantages**:
- Protects against rogue access points, unauthorized connections, and other wireless threats.

- Can adapt to the dynamic nature of wireless networks.

**Disadvantages**:
- Requires specialized knowledge of wireless protocols and threats.

- Potential for false positives due to overlapping wireless signals or misconfigurations.