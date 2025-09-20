+++

date = '2025-08-09T13:39:07-03:00'
layout = "project_detail_carousel"
draft ="false"

id ="cloud-10"
url = "projects/cloud-cybersecurity/cloud-10"

title = "Investigating and Remediating IAM Threat Findings"
text = "Recreated malicious IAM activity, analyzed Security Command Center findings, and remediated improper IAM configurations to distinguish benign activity from true security incidents."
tools = ["Google Cloud Security Command Center", "Cloud Logging", "IAM", "Event Threat Detection"]
frameworks = ["Zero Trust Architecture", "Cloud Threat Detection & Response"]
standards = ["ISO 27001", "NIST CSF"]

[[steps]]
title = "Step 1"
description = "Granted permission to an external account"
text = "Granted permissions to an external account-bad.actor.demo to intentionally trigger an IAM Event Threat Detection finding."
image = "images/cloud_cyber/cloud_10/step1.png"

[[steps]]
title = "Step 2"
description = "Reviewed Findings"
text = "Used Security Command Center to access and review the two IAM findings."
image = "images/cloud_cyber/cloud_10/step2.png"

[[steps]]
title = "Step 3"
description = "Analyzed logs"
text = "Analyzed logs in Security Command Center and Cloud Logging to find out the principal that granted access."
image = "images/cloud_cyber/cloud_10/step3.png"

[[steps]]
title = "Step 4"
description = "Remediated Findings"
text = "Remediated the malicious finding by adjusting IAM settings and removing unauthorized permissions."
image = ["images/cloud_cyber/cloud_10/step4_part1.png","images/cloud_cyber/cloud_10/step4_part2.png"]

key_learnings = [
    "Gained practical experience analyzing security alerts to determine whether activity is malicious or benign.",
    "Learned how to intentionally trigger IAM Event Threat Detection findings for investigation purposes.",
    "Used Security Command Center and Cloud Logging to review and correlate findings.",
    "Remediated malicious activity by removing excessive permissions (project owner role) from an external user."
]


+++