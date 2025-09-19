+++


date = '2025-08-09T13:39:07-03:00'
layout = "project_detail_carousel"
draft ="false"
title ="Role-Based Access for Third-Party Audit"
id ="cloud-6"
image = "images/cloud_cyber/cloud_cyber2.png"

description = "Configured IAM roles and permissions to provide controlled audit access to a sensitive database in Google Cloud"

text = " Ensured secure third-party audit access to a database containing sensitive customer billing and invoice data. Using Google Cloud IAM, I created a custom role with restricted permissions for viewing and listing the database contents. I then assigned this role to the audit team members and verified that the access had been correctly granted."

applicable_scenario= "This demonstrates practical experience in cloud access management, specifically creating and assigning roles with the principle of least privilege. It is relevant for organizations that need to provide external parties with limited access to sensitive data while maintaining strict security controls."

url= "projects/cloud-cybersecurity/cloud-6"
tools = ["Google Cloud IAM", "Cloud Console"]
frameworks = ["Zero Trust Architecture", "Role-Based Access Control (RBAC)"]
standards = ["NIST CSF (PR.AC – Access Control, PR.DS – Data Security)",
             "ISO 27001 (Annex A.9 – Access Control, A.8 – Asset Management)",
             "Cloud Security Best Practices"]


[[steps]]  
title = "Step 1"  
description = "Created Custom Role"
text = "Created a custom IAM role with permissions limited to viewing and listing the database contents."  
image = "images/cloud_cyber/cloud_6/step1.png"  


[[steps]]  
title = "Step 2"
description ="Assigned Role to User"  
text = "Assigned the custom role to audit team members using IAM to grant controlled access."  
image = "images/cloud_cyber/cloud_6/step2.png"  

[[steps]]  
title = "Step 3"  
description = "Verified Role Assignment"
text = "Verified that the custom role had been correctly assigned and the audit team could access the database as intended."  
image = "images/cloud_cyber/cloud_6/step2.png"  


key_learnings = [
    "Custom IAM roles can be used to provide controlled, least-privilege access to sensitive cloud resources.",
    "Assigning and verifying roles ensures that external teams, like auditors, can perform their work securely.",
    "IAM is critical for managing digital identities and access permissions in a cloud environment.",
    "Using IAM effectively helps prevent unauthorized access and supports secure cloud operations."]


+++