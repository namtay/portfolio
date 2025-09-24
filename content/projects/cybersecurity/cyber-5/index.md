+++
layout = "project_detail_carousel"
draft ="false"
id="cyber-5"
image = "images/cloud_cyber/cloud_cyber1.png"
title = "Penetration Testing with Nmap and Metasploit"
text = "Performed a penetration testing capstone project for a new trading company to identify vulnerabilities in target systems. The project used Nmap for port scanning and Metasploit for exploit testing, demonstrating how attackers could gain access and how security teams can prevent such attacks."
tools = ["Nmap", "Metasploit Framework", "Kali Linux", "ipconfig"]
frameworks = ["PTES", "OWASP Testing Guide"]
standards = ["ISO 27001", "NIST CSF"]

[[steps]]
title = "Step 1"
description = "Identify target system."
text = "Checked the IP address of the target computer using the ipconfig command to ensure proper network identification."
image = "images/cyber/cyber-5/step1.png"

[[steps]]
title = "Step 2"
description = "Set up testing environment."
text = "Logged into Kali Linux on the virtual machine to prepare the penetration testing environment."
image = "images/cyber/cyber-5/step2.png"

[[steps]]
title = "Step 3"
description = "Scanned network for open ports."
text = "Used Nmap to scan the target IP address, identified open ports, and traced possible attack vectors."
image = "images/cyber/cyber-5/step3.png"

[[steps]]
title = "Step 4"
description = "Started Metasploit Framework."
text = "Ran Metasploit using 'sudo msfconsole' to begin searching for exploits and payloads relevant to the discovered ports."
image = "images/cyber/cyber-5/step4.png"

[[steps]]
title = "Step 5"
description = "Searched for exploit modules."
text = "Used the Metasploit 'search' command to find exploit, payload, and auxiliary modules that could be used against the target system."
image = "images/cyber/cyber-5/step5.png"

[[steps]]
title = "Step 6"
description = "Refined search with grep."
text = "Filtered search results using the 'grep' command to narrow down the most relevant exploit module for the target system."
image = "images/cyber/cyber-5/step6.png"

[[steps]]
title = "Step 7"
description = "Loaded and configured exploit."
text = "Selected a module from the search results using the 'use <module_name>' command, then ran 'show options' to view configurable parameters."
image = "images/cyber/cyber-5/step7-9.png"

[[steps]]
title = "Step 8"
description = "Set module options."
text = "Configured required parameters, including setting the RHOST option to the target IP address, ensuring the exploit targeted the correct system."
image = "images/cyber/cyber-5/step7-9.png"

[[steps]]
title = "Step 9"
description = "Executed exploit and analyze results."
text = "Ran the exploit and observed the system's response to determine if it was vulnerable and exploitable."
image = "images/cyber/cyber-5/step7-9.png"

[findings_and_recommendations]
findings = [
    "Two IP addresses were tested for vulnerabilities; one was exploitable, the other was secure.",
    "The vulnerable system showed how attackers can gain unauthorized access through open ports and misconfigured services."
]

recommendations = [
    "Implement regular patch management.",
    "Close unnecessary open ports.",
    "Enforce least privilege on user accounts.",
    "Conduct periodic penetration tests to identify new vulnerabilities."
]

+++