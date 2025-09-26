
+++

layout = "project_detail_carousel"
draft ="false"
id="cyber-6"
image = "images/cloud_cyber/cloud_cyber1.png"

title = "Active MITM Attack Simulation Using XAMPP and Burp Suite"
text = "Simulated an active MITM attack between a Windows server and an Ubuntu client to intercept and modify web traffic using XAMPP and Burp Suite, demonstrating risks to confidentiality and integrity of communication. The project highlighted practical techniques for detecting and preventing such attacks."
tools = ["XAMPP", "Burp Suite Community Edition", "Windows Firewall", "Ubuntu Browser"]
frameworks = ["OWASP Testing Guide", "PTES"]
standards = ["ISO 27001", "NIST CSF"]

[[steps]]
title = "Step 1"
description = "Set up web server and victim environment."
text = "Disabled Windows Firewall on the Windows VM, installed XAMPP with Apache, and started the web server. Accessed the server from the Ubuntu VM via http://192.168.1.2 to confirm proper setup."
image="images/cyber/cyber-6/step1.png"

[[steps]]
title = "Step 2"
description = "Installed and configured Burp Suite for MITM."
text = "Downloaded and installed Burp Suite Community Edition on the Windows VM. Launched a temporary project, added a proxy listener on IP 192.168.1.2, Port 8080, and ensured 'Intercept' was off to allow traffic flow."

[[steps]]
title = "Step 3"
description = "Configured client to route traffic through proxy."
text = "Set the Ubuntu browser to use 192.168.1.2:8080 as HTTP proxy, enabling web traffic to pass through Burp Suite for interception and analysis."

[[steps]]
title = "Step 4"
description = "Intercepted and modified web traffic."
text = "Enabled interception in Burp Suite, captured HTTP requests and responses, modified content in real-time, and forwarded it to the browser to demonstrate that the MITM attack successfully altered communication."
image=["images/cyber/cyber-6/step4_part1.png","images/cyber/cyber-6/step4_part2.png"]


[[steps]]
title = "Step 5"
description = "Analyzed results and applied security recommendations."
text = "Observed how attackers could intercept and manipulate sensitive data. Implemented recommendations to mitigate MITM attacks, including enforcing HTTPS, HSTS, monitoring traffic, and avoiding untrusted networks."
image="images/cyber/cyber-6/step5.png"

[findings_and_recommendations]
findings = [
    "MITM attacks allowed interception, monitoring, and modification of communication between systems.",
    "Sensitive data such as passwords or personal information could have been compromised if traffic was unencrypted."
]

recommendations = [
    "Using HTTPS with valid SSL/TLS certificates to encrypt communication.",
    "Implement HTTP Strict Transport Security (HSTS) to prevent protocol downgrade attacks.",
    "Employ network monitoring tools to detect unusual traffic patterns.",
    "Avoid using untrusted networks for sensitive communications."
]


+++