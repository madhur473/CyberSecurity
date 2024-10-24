# CyberSecurity
Algorithm for the Uber Data Breach (Step-by-Step Process)
This algorithm outlines the hacker's attack process, from gaining initial access through social engineering to fully exploiting Uber’s internal systems.

Step 1: Target the employee via social engineering.

The attacker identifies a vulnerable employee.
Initiates phishing/social engineering to gain trust.
Step 2: Request VPN credentials.

The attacker convinces the employee to hand over VPN login credentials.
Step 3: Log into Uber’s internal network using VPN.

The attacker uses the obtained credentials to access Uber’s internal systems.
Step 4: Launch MFA fatigue attack.

The attacker repeatedly sends multi-factor authentication (MFA) requests until the employee approves access due to fatigue.
Step 5: Search for hardcoded credentials in PowerShell scripts.

The attacker finds PowerShell scripts that contain administrative credentials, allowing further access.
Step 6: Escalate privileges to access sensitive internal systems.

With the admin credentials, the attacker escalates privileges and gains control over Uber's internal tools like AWS, GSuite, and Slack.
Step 7: Announce the breach internally.

The attacker uses a compromised Slack account to post a message declaring the hack.
Step 8: Compromise further services (AWS, Google Cloud, etc.).

The attacker accesses Uber’s cloud infrastructure and other services, potentially exposing sensitive data.
Step 9: Leave the network and cover tracks.

The attacker exits the network, leaving minimal traces.
