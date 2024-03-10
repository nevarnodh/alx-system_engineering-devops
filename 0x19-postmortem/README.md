**Issue Summary:**
- **Duration:** March 8th, 2024, 15:30 UTC to March 9th, 2024, 09:00 UTC
- **Impact:** The primary web service experienced intermittent outages, resulting in a 20% decrease in user accessibility.
- **Root Cause:** A misconfiguration in the load balancer led to excessive traffic redirection, causing service degradation.

**Timeline:**
- **March 8th, 2024, 15:30 UTC:** Issue detected through monitoring alerts indicating increased latency.
- **March 8th, 2024, 15:35 UTC:** Engineering team initiated investigation, suspecting potential server overload.
- **March 8th, 2024, 16:00 UTC:** Load balancer settings reviewed and suspected as the culprit.
- **March 8th, 2024, 16:30 UTC:** Load balancer configurations adjusted to mitigate traffic redirection.
- **March 8th, 2024, 17:00 UTC:** Issue seemed resolved; incident considered closed.
- **March 9th, 2024, 08:45 UTC:** Reports of service degradation resurfaced.
- **March 9th, 2024, 08:50 UTC:** Investigation resumed, focusing on load balancer logs.
- **March 9th, 2024, 09:00 UTC:** Root cause identified as a misconfigured routing algorithm.
- **March 9th, 2024, 09:30 UTC:** Load balancer settings reverted to default; service stability restored.

**Root Cause and Resolution:**
- **Root Cause:** Misconfiguration in the load balancer's routing algorithm caused excessive redirection of traffic, leading to service degradation.
- **Resolution:** Load balancer configurations were reverted to default settings, ensuring proper traffic distribution and service stability.

**Corrective and Preventative Measures:**
- **Improvements/Fixes:**
  1. Enhance load balancer configuration validation processes to catch misconfigurations earlier.
  2. Implement automated monitoring for load balancer performance metrics to promptly detect anomalies.
  3. Conduct regular load testing to validate load balancer behavior under different traffic conditions.
- **Tasks:**
  1. Develop a checklist for load balancer configuration validation.
  2. Implement automated alerts for load balancer performance deviations.
  3. Schedule periodic load testing exercises to assess system scalability and resilience.

By implementing these measures, we aim to mitigate the risk of similar incidents in the future and ensure uninterrupted service delivery to our users.

https://docs.google.com/document/d/12VHmjxlTLlAlVI45OuZ-WB1ZfCyjnaFNu_gs8jrHKpo/edit?usp=sharing

https://docs.google.com/document/d/1j05aGcwU63CgeWZu7jzObzGOV2GRxg3AGVttuMlBGCQ/edit?usp=sharing

