+++
date = '2025-08-09T13:39:07-03:00'
layout = "project_detail_carousel"
draft ="false"
id ="cloud-11"
url = "projects/cloud-cybersecurity/cloud-11"

title = "Remediating a False Positive Security Alert"
text = "Recreated a service account activity that triggered a low severity security alert, analyzed the finding using Security Command Center, and remediated the issue to understand false positives and improve security policies."
tools = ["Google Cloud Security Command Center", "IAM", "Cloud Logging"]
frameworks = ["Cloud Threat Detection & Response", "Least Privilege Principle"]
standards = ["ISO 27001", "NIST CSF"]


[[steps]]
title = "Step 1"
description = "Created a service account and activated it."
text = "Recreated the false positive by creating a service account(test-account), assigning a role, providing a key, and activating the service account."
image= ["images/cloud_cyber/cloud_11/step1_part1.png","images/cloud_cyber/cloud_11/step1_part2.png"]

[[steps]]
title = "Step 2"
description = "Account triggered a false positive finding"
text = " Triggered a false positive finding and accessed the vulnerability finding related to the triggered activity in Security Command Center."


[[steps]]
title = "Step 3"
description = "Analyzed the finding and took remediation action"
text = "Analyzed the finding and took remediation action to close the alert(deleting a service account key) and prevent future false positives."
image="images/cloud_cyber/cloud_11/step3.png"

key_learnings = [
    "Gained experience reproducing a real-world false positive alert for better understanding of alert triggers and how to take action to remediate them.",
    "Learned how to use Security Command Center to investigate and analyze vulnerability findings.",
    "Understood the importance of secure key management practices for service accounts.",]

+++