+++

date = '2025-08-09T13:39:07-03:00'
layout = "project_detail_carousel"
draft ="false"
id ="cloud-2"
image = "images/cloud_cyber/cloud_cyber2.png"


title = "Capstone: Cloud Security Incident Response"
text = "Completed a capstone project simulating a major data breach at Cymbal Retail. The project covered the full incident response process — finding vulnerabilities, containing the breach, recovering systems, fixing compliance issues, and confirming that all security gaps were closed."

url = "projects/cloud-cybersecurity/cloud-2"
tools = ["Google Cloud Security Command Center", "Google Cloud IAM", "Cloud Logging", "Cloud Monitoring", "Firewall Rules", "Cloud Storage ACLs"]
frameworks = ["NIST CSF", "ISO 27001"]
standards = ["PCI-DSS", "GDPR", "SOC 2"]



[[steps]]
title = "Step 1"
description = "Identified malware infection and root cause."
text = "Analyzed unusual cloud activity using Google Cloud Security Command Center and confirmed a malware infection on the compromised VM. Investigated SSH and RDP logs, which revealed that the VM had open ports and a public IP, enabling attacker access."
image=["images/cloud_cyber/cloud_2/step1_part1.png","images/cloud_cyber/cloud_2/step1_part2.png"]

[[steps]]
title = "Step 2"
description = "Detected privilege escalation risks."
text = "Found that the VM used the default service account with full API access, and excessive IAM roles had been assigned to users. This misconfiguration enabled privilege escalation, allowing attackers to compromise other services including BigQuery."
image="images/cloud_cyber/cloud_2/step2.png"

[[steps]]
title = "Step 3"
description = "Confirmed data exfiltration."
text = "Discovered that attackers exfiltrated credit card data, names, and locations through a publicly accessible storage bucket with fine-grained ACLs. The bucket’s open access was abused to stage and export sensitive customer information."
image=["images/cloud_cyber/cloud_2/step3_part1.png","images/cloud_cyber/cloud_2/step1_part2.png"]

[[steps]]
title = "Step 4"
description = "Contained the incident and isolated systems."
text = "Isolated the compromised VM (cc-app-01) from the network (stopped the VM, started a new VM from its snapshot taken befor the incident and turned on SecureBootMode to address 'Compute Secure Boot disabled vulnerability', started the new VM (cc-app-02) and deleted the compromised virtual machine)."
image=["images/cloud_cyber/cloud_2/step4_part1.png","images/cloud_cyber/cloud_2/step4_part2.png"]

[[steps]]
title = "Step 5"
description = "Restricted network and storage access."
text = "Updated firewall rules to disable open SSH and RDP ports. Removed public access to the exposed storage bucket and applied uniform bucket-level access control to eliminate conflicting IAM and ACL permissions to address Public bucket ACL, Bucket policy only disabled, and Bucket logging disabled vulnerabilities. Created a new firewall rule(allow-ssh-cc-restricted) to restrict SSH access to only authorized IP addresses from the source network 35.235.240.0/20 to compute instances with the target tag cc. I also deleted other existing firewall rules to restrict access to the following protocols:rcmp, ssh and rdp whilst enabling logging for the rest of the rules."
image=["images/cloud_cyber/cloud_2/step5_part1.png","images/cloud_cyber/cloud_2/step5_part2.png","images/cloud_cyber/cloud_2/step5_part3.png","images/cloud_cyber/cloud_2/step5_part4.png","images/cloud_cyber/cloud_2/step5_part5.png"]


[[steps]]
title = "Step 6"
description = "Validated remediation and compliance."
text = "Ran post-incident vulnerability scans, verified compliance with PCI-DSS and GDPR, and generated detailed security reports confirming all risks were mitigated and systems were secure."
image="images/cloud_cyber/cloud_2/step6.png"

[[steps]]
title = "Step 7"
description = "Provided recommendations for future prevention."
text = "Documented lessons learned and recommended key measures such as multi-factor authentication (MFA), regular risk assessments, periodic penetration testing, and strict adherence to least privilege principles."


+++