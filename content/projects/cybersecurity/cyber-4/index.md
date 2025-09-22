+++
layout = "project_detail_carousel"
draft ="false"
title = "Threat Intelligence Investigation Using MISP – PupyRAT Malware Analysis"
text = "Deployed and configured MISP on Ubuntu using Docker to centralize threat intelligence. Investigated a published CIRCL event on PupyRAT malware, analyzed its behavior, and identified indicators of compromise such as command-and-control server IPs."
tools = ["MISP", "Docker", "Ubuntu"]
frameworks = ["Threat Intelligence Sharing", "Malware Analysis"]
standards = ["MITRE ATT&CK (TA0001 – Initial Access, TA0002 – Execution)", "NIST CSF (DE.CM – Security Continuous Monitoring)"]

[[steps]]
title = "Step 1"
description = "Deployed MISP on Ubuntu."
text = "Installed and configured MISP using Docker containers on an Ubuntu system to enable centralized threat intelligence sharing and analysis."
image="images/cyber/cyber-4/step1.png"

[[steps]]
title = "Step 2"
description = "Located and investigated the PupyRAT event."
text = "Searched for CIRCL event ID 1582 in MISP, confirming details of the PupyRAT malware and its behavior."
image="images/cyber/cyber-4/step2.png"

[[steps]]
title = "Step 3"
description = "Analyzed malware indicators of compromise."
text = "Identified PupyRAT's command-and-control server IP (43.32.186.33) and confirmed that the malware gained ADMIN-level access to compromised systems."
image="images/cyber/cyber-4/step3.png"

[[steps]]
title = "Step 4"
description = "Extracted actionable threat intelligence."
text = "Documented IOCs (IP, behavior patterns) and mapped them to MITRE ATT&CK techniques for incident response readiness."

key_learnings=[
"Gained practical experience in installing and configuring MISP for centralized threat intelligence sharing.",
"Learned how to investigate real-world CIRCL events and extract actionable IOCs.",
"Improved skills in malware behavior analysis and identifying command-and-control infrastructure",
"Strengthened understanding of mapping threats to MITRE ATT&CK techniques for incident response and threat hunting",
"Reinforced the importance of using open-source threat intelligence platforms for proactive defense."
]


+++