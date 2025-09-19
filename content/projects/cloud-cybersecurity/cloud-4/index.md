+++

layout = "project_detail_carousel"
draft ="false"
id ="cloud-4"
image = "images/cloud_cyber/cloud_cyber4.png"
title = "Cloud Storage Security Remediation"
text = "Remediated misconfigured Cloud Storage buckets and verified security compliance using Google Cloud Security tools"
url = "projects/cloud-cybersecurity/cloud-4"
description = " Addressing a misconfigured Cloud Storage bucket containing sensitive documents.  Used Google Cloud Security Command Center to identify and verify the security threats. I then remediated high- and medium-risk issues and ran a compliance report to confirm that the vulnerabilities were resolved"

applicable_scenario = "This demonstrates hands-on experience in cloud security monitoring and remediation, particularly for misconfigured storage resources. It is relevant for organizations that need to protect sensitive data in Google Cloud and ensure compliance with security standards."

tools = ["Google Cloud Security Command Center", "Cloud Storage", "Cloud Compliance Reports"]
frameworks = ["Zero Trust Architecture", "Google Cloud Security Posture Management"] 
standards = ["NIST CSF (DE.CM – Security Continuous Monitoring, PR.DS – Data Security)",
             "ISO 27001 (Annex A.8 – Asset Management, A.12 – Operations Security)",
             "Cloud Security Best Practices"] 

[[steps]] 
title = "Step 1" 
description ="Identified Security Threats" 
text = "Used Security Command Center to detect and verify vulnerabilities in Cloud Storage buckets."  
image = ["images/cloud_cyber/cloud_4/step1_public_bucket.png","images/cloud_cyber/cloud_4/step1_bucket_policy.png"]


[[steps]]  
title = "Step 2"
description = "Remediated Issues"  
text = "Remediated high- and medium-risk misconfigurations in the Cloud Storage bucket to secure sensitive data."  
image = ["images/cloud_cyber/cloud_4/step2_part1.png","images/cloud_cyber/cloud_4/step2_part2.png"]


[[steps]]  
title = "Step 3 "  
description = "Verified Compliance"
text = "Ran a compliance report in Security Command Center to confirm that the bucket vulnerabilities were resolved."  
image = ["images/cloud_cyber/cloud_4/step3_part1.png","images/cloud_cyber/cloud_4/step3_part2.png"]


key_learnings = [
    "Gained hands-on experience identifying and prioritizing cloud security threats using Security Command Center.",
    "Remediated vulnerabilities in Cloud Storage buckets to secure sensitive data.",
    "Generated CIS Google Cloud Platform Foundation 2.0 compliance reports to validate remediation.",
    "Learned how vulnerability remediation and compliance verification help prevent data breaches, unauthorized access, and data loss."
]


+++