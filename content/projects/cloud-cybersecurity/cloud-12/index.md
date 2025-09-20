+++

date = '2025-08-09T13:39:07-03:00'
layout = "project_detail_carousel"
draft ="false"
id ="cloud-12"
url = "projects/cloud-cybersecurity/cloud-12"

title = "Incident Response Simulation and Log Analysis with BigQuery"
text = "Recreated a high-severity security incident in a controlled test environment, generated and exported logs, and used BigQuery to analyze malicious activity and understand incident response workflows."
tools = ["Google Cloud Logging", "BigQuery", "IAM"]
frameworks = ["NIST Incident Response Lifecycle", "Cloud Threat Detection & Response"]
standards = ["ISO 27001", "NIST CSF"]

[[steps]]
title = "Step 1"
description="Recreated a security incident"
text = "Recreated the security incident by generating malicious activity from a test user account."
image="images/cloud_cyber/cloud_12/step1.png"


[[steps]]
title = "Step 2"
description="Exported logs via sink"
text = "Exported logs via sink associated with the incident for offline analysis."
image="images/cloud_cyber/cloud_12/step2.png"


[[steps]]
title = "Step 3"
description= "Generated additional user activity"
text = "Generated additional user activity to further simulate the incident scenario."
image="images/cloud_cyber/cloud_12/step3.png"


[[steps]]
title = "Step 4"
description=""
text = "Used BigQuery to analyze the logs, identify indicators of compromise, and understand attacker behavior."
image="images/cloud_cyber/cloud_12/step4.png"


key_learnings = [
    "Gained first-hand experience with the process of incident response by recreating a real-world security incident.",
    "Learned how to export and analyze logs to trace malicious activity across cloud resources.",
    "Developed skills using BigQuery to query and investigate large volumes of log data efficiently.",
    "Understood the importance of recreating incidents in a test environment to safely learn response and investigation techniques."
]


+++