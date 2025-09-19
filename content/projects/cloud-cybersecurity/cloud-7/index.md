+++

date = '2025-08-09T13:39:07-03:00'
layout = "project_detail_carousel"
draft ="false"
title ="Firewall Rule Analysis and Configuration"
id ="cloud-7"
url = "projects/cloud-cybersecurity/cloud-7"

text = "Analyzed inbound network traffic to a demo web server, created and tested firewall rules to allow and deny traffic, and verified the results through network logs to improve security posture."

tools = ["Google Cloud Firewall Rules", "VPC Networking", "Cloud Logging"]
frameworks = ["Zero Trust Architecture", "Network Security Monitoring"]
standards = ["NIST CSF (PR.AC – Access Control, DE.CM – Continuous Monitoring)",
             "ISO 27001 (Annex A.13 – Communications Security)",
             "Cloud Security Best Practices for Firewall Configuration"]

[[steps]]
title = "Step 1"
description="Allowed Traffic"
text = "Created a firewall rule to allow network traffic to the demo web server within the VPC network."
image = "images/cloud_cyber/cloud_7/step1.png"


[[steps]]
title = "Step 2"
description=" Generated Traffic and Analyzed Logs"
text = "Generated HTTP network traffic to the server and used Cloud Logging to analyze inbound connection logs."
image = ["images/cloud_cyber/cloud_7/step2_part1.png","images/cloud_cyber/cloud_7/step2_part2.png"]



[[steps]]
title = "Step 3"
description=" Denied Traffic"
text = "Created a new firewall rule to deny HTTP traffic to the server and tested connectivity to confirm the block."
image = ["images/cloud_cyber/cloud_7/step3_part1.png","images/cloud_cyber/cloud_7/step3_part2.png"]



[[steps]]
title = "Step 4"
description="Verified Firewall Rule Effectiveness"
text = "Analyzed firewall logs again to verify that HTTP traffic was successfully blocked as per the new rule."
image = ["images/cloud_cyber/cloud_7/step4_part1.png","images/cloud_cyber/cloud_7/step4_part2.png"]




key_learnings = [
    "Gained hands-on experience in creating and testing firewall rules for a cloud-hosted web server.",
    "Learned how to analyze log entries to monitor and validate firewall rule effectiveness.",
    "Developed familiarity with perimeter protection techniques for cloud environments.",
    "Understood how firewall rule modifications can be used to enhance network security and reduce risk of incidents."
]

+++