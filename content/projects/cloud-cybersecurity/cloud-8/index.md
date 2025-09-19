+++

date = '2025-08-09T13:39:07-03:00'
layout = "project_detail_carousel"
draft ="false"
title ="Application Vulnerability Scanning with Web Security Scanner"
id ="cloud-8"
url = "projects/cloud-cybersecurity/cloud-8"

text = "Identified and mitigated web application vulnerabilities, focusing on OWASP® Top 10 Cross-Site Scripting (XSS) risks, to secure a corporate banking application before production deployment."

tools = ["Google Cloud Web Security Scanner", "Google Cloud Compute Engine", "Static IP Configuration","Cloud Shell"]
frameworks = ["OWASP Top 10"]
standards = ["ISO 27001", "NIST CSF"]


[[steps]]
title = "Step 1"
description = "Created a static IP address and launched a virtual "
text = "Created a static IP address and launched a virtual machine."
image = "images/cloud_cyber/cloud_8/step1.png"


[[steps]]
title = "Step 2"
description = "Deployed the vulnerable banking application on the VM."
text = "Deployed the vulnerable banking application on the VM."
image = "images/cloud_cyber/cloud_8/step2.png"


[[steps]]
title = "Step 3"
description = "Set up and ran the application to prepare for scanning."
text = "Set up and ran the application to prepare for scanning."
image = "images/cloud_cyber/cloud_8/step3.png"

[[steps]]
title = "Step 4"
description = "Accessed and scanned the application using Web Security Scanner."
text = "Accessed and scanned the application using Web Security Scanner."
image = ["images/cloud_cyber/cloud_8/step4_part1.png","images/cloud_cyber/cloud_8/step4_part2.png"]

[[steps]]
title = "Step 5"
description = "Fixed vulnerabilities and re-scanned to verify mitigation"
text = "Fixed vulnerabilities and re-scanned to verify mitigation."
image = ["images/cloud_cyber/cloud_8/step5_part1.png","images/cloud_cyber/cloud_8/step5_part2.png"]


key_learnings = [
    "Gained hands-on experience scanning for web application vulnerabilities using Web Security Scanner.",
    "Understood the importance of proactively identifying and addressing application weaknesses to manage risks.",
    "Learned how vulnerability management contributes to compliance and strengthens overall security posture.",
    "Recognized that fixing security gaps helps prevent exploitation, minimize security incident impact, and maintain trust with users."
]




+++