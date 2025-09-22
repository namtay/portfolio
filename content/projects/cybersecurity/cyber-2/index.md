+++
date = '2025-08-09T13:39:07-03:00'
layout = "project_detail_carousel"
draft ="false"
id="cyber-2"

title = "Security Monitoring and Log Analysis with Splunk"
text = "Configured Splunk on Linux Ubuntu to ingest logs, analyze access patterns, and monitor system logs in real time for security events."
tools = ["Splunk Enterprise", "Linux Ubuntu", "Syslog"]
frameworks = ["Security Information and Event Management (SIEM)", "Log Analysis"]
standards = ["NIST CSF (DE.CM – Security Continuous Monitoring)", "ISO 27001 (A.12.4 – Logging and Monitoring)"]

[[steps]]
title = "Step 1"
description = "Analyzed web access patterns using Splunk."
text = "Ingested access.log into Splunk and wrote search queries to identify the top 10 operating systems accessing the system."
image=["images/cyber/cyber-2/step1_part1.png","images/cyber/cyber-2/step1_part2.png"]

[[steps]]
title = "Step 2"
description = "Performed traffic analysis."
text = "Calculated the average byte transfer per date and hour using Splunk search queries to identify usage trends."
image=["images/cyber/cyber-2/step2_part1.png","images/cyber/cyber-2/step2_part2.png"]

[[steps]]
title = "Step 3"
description = "Implemented real-time security monitoring."
text = "Configured Splunk to monitor local syslog continuously and alert on suspicious security events.Also displayed results that show authentication failure."
image=["images/cyber/cyber-2/step3_part1.png","images/cyber/cyber-2/step3_part2.png"]

key_learnings = [
    "Gained experience using Splunk to ingest and analyze logs for actionable security insights.",
    "Learned to write search queries for identifying trends such as top operating systems and traffic patterns.",
    "Configured real-time syslog monitoring to detect and respond to security events quickly.",
    "Understood the importance of continuous log monitoring for incident detection and compliance requirements."
]

+++