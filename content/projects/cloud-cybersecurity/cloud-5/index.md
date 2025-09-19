+++
date = '2025-08-09T13:39:07-03:00'
layout = "project_detail_carousel"
draft ="false"
description ="Created and managed Identity and Access Management (IAM) custom roles."
id ="cloud-5"
image = "images/cloud_cyber/cloud_cyber5.png"
title = "VPC Network"
text = "Set up a test VPC and subnets in Google Cloud to replicate a new hybrid cloud network for security assessment."

url = "projects/cloud-cybersecurity/cloud-5"

applicable_scenario = "Useful for demonstrating hands-on experience with Google Cloud networking, building test environments, and supporting security assessments in a hybrid cloud migration project"
tools = ["Google Cloud Shell", "gcloud CLI", "Google Cloud VPC Networking"]
frameworks = ["Google Cloud VPC Architecture", "Zero Trust Architecture"]
standards = ["NIST CSF (PR.AC – Access Control, PR.DS – Data Security)", 
             "ISO 27001 (Annex A.9 – Access Control, A.13 – Communications Security)", 
             "Network Segmentation Best Practices", 
             "Cloud Security Posture Assessment"]

[[steps]] 
title = "Step 1"
description = "Created a VPC network "
text = "Created a new VPC network using Google Cloud Shell and gcloud CLI."
image = "images/cloud_cyber/cloud_5/vpc_network.png"



[[steps]] 
title = "Step 2"
description = "Configured a subnet using gcloud CLI"
text = "Configured a subnet within the VPC using gcloud CLI to enable proper network segmentation."
image= "images/cloud_cyber/cloud_5/step_2.png"


[[steps]] 
title = "Step 3"
description = "Verified created networks"
text = "Verified the created networks by running gcloud network listing commands in Cloud Shell."
image= "images/cloud_cyber/cloud_5/step_3.png"



[[steps]] 
title = "Step 4"
description = "Confirmed configuration"
text = "Listed and reviewed all subnets within the network to confirm correct configuration."
image="images/cloud_cyber/cloud_5/step_4.png"


key_learnings = [
    "Gained hands-on experience creating and verifying a test VPC network and subnet in Google Cloud.",
    "Learned how to replicate a production-like environment for security testing.",
    "Collected insights from the test network and subnets to inform and improve security plans for the production environment."
]

+++