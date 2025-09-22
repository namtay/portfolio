+++
date = '2025-08-09T13:39:07-03:00'
layout = "project_detail_carousel"
draft ="false"
description ="Created and managed Identity and Access Management (IAM) custom roles."
id="cyber-1"
image = "images/cloud_cyber/cloud_cyber1.png"
title = "OT Endpoint Detection and Monitoring system"
text = "Designed and implemented an OT-focused endpoint detection and monitoring system using Machine Learning to detect and classify malicious activity targeting ICS/SCADA networks."

url= "projects/cybersecurity/cyber-1"
tools = ["Google Colab", "Python", "Scikit-learn", "TensorFlow", "NumPy"]
frameworks = ["OT/ICS Security Framework", "Machine Learning-based Threat Detection"]
standards = ["NIST CSF (DE.CM – Continuous Monitoring, PR.IP – Information Protection Processes)",
             "MITRE ATT&CK for ICS",
             "Best Practices for OT Cybersecurity Monitoring"]


[[steps]]
title = "Step 1"
description="Data Preparation and Feature Engineering"
text = "Used endpoint datasets from different sources(IOT_Sentinnel dataset,TON_IoT dataset, UNSW_NB15 dataset) and performed preprocessing and feature engineering for machine learning model training."
image=["images/cyber/cyber-1/step1_part1.png","images/cyber/cyber-1/step1_part2.png"]

[[steps]]
title = "Step 2 "
description = "Model Development and Training"
text = "Developed and trained Random Forest, SVM, LSTM, and CNN models in Google Colab to detect and classify malicious activity."
image=["images/cyber/cyber-1/step2_part1.png","images/cyber/cyber-1/step2_part2.png","images/cyber/cyber-1/step2_part3.png","images/cyber/cyber-1/step2_part4.png"]

[[steps]]
title = "Step 3"
description="Model Evaluation and Comparison"
text = "Compared model performance based on precision, and recall to determine the most effective detection algorithm."
image=["images/cyber/cyber-1/step3_part1.png","images/cyber/cyber-1/step3_part2.png"]

[[steps]]
title = "Step 4"
description="Deployment Planning"
text = "Suggested the best-performing model for deployment as Random Forest in the OT monitoring system to enhance ICS/SCADA network visibility.Also suggested deployment platforms like Cloud or Hybrid over on-site deployment."


key_learnings = [
    "Gained hands-on experience developing ML models for OT/ICS threat detection.",
    "Learned to compare and optimize models based on precision, recall, and real-time feasibility.",
    "Understood the integration of ML-based detection within ICS/SCADA monitoring systems.",
    "Enhanced knowledge of OT/ICS security frameworks and best practices for endpoint protection."
]


+++