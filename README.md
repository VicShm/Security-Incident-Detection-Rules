# Security Incident Detection Rules for Infrastructure Software

This repository provides a prioritized set of detection rules designed to detect information security incidents in infrastructure software environments. It includes pre-built queries for Splunk and Elasticsearch, allowing you to quickly create alerts for effective monitoring and response to security events.


## Overview

Detecting security incidents swiftly and accurately in infrastructure components is critical for maintaining a secure operational environment. This collection focuses on actionable detection logic that can be integrated into common SIEM platforms such as Splunk and Elastic Stack.
- Infrastructure software encompasses operating systems, network devices, virtualization platforms, and other critical components underpinning IT services.
- The rules help identify suspicious activities, potential breaches, and other anomalies indicating information security incidents (e.g., unauthorized access attempts, malware indicators, abnormal network activities).
- By leveraging these predefined queries, security teams can automate monitoring and alerting, enabling rapid response and mitigation.


## What’s Included

- Splunk Search Processing Language (SPL) Queries: Curated searches designed to detect typical infrastructure security incidents. These can be deployed as alert conditions in Splunk to notify teams of unusual or malicious activity.
- Elasticsearch Query DSL Samples: Equivalent queries formatted for Elastic’s Query DSL, ready to be used in Kibana alerts or Elastic Security detection rules.
- Guidance on tuning and adapting rules to your specific environment and threat landscape.


## Why Use This Collection?

- Accelerate🚀 Detection: Implement tested detection logic without needing to start from scratch.
- Improve Coverage: Rules address a broad range of infrastructure-related incident vectors📈 and behaviors.
- Consistency🛠️ and Standardization: Use a unified approach to incident detection across different monitoring platforms.
- Scalable Alerting🏗️ : Designed to integrate seamlessly with SIEM alerting pipelines.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Learn More

- [Wazuh. Free and open source Host-based Intrusion Detection System](https://wazuh.com/)
- [The shareable detection format for security professionals.](https://sigmahq.io/)
