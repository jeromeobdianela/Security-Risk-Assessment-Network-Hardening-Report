# 🛡️ Security Risk Assessment: Network Hardening

*As a cybersecurity trainee, below are the recommendations for hardening a network after a data breach.*

---

## 📋 Scenario Overview

I am a security analyst working for a social media organization. The organization recently experienced a major data breach that compromised the safety of its customers' personal information, such as names and addresses. Leadership wants to implement strong network hardening practices that can be performed consistently to prevent future attacks and breaches.

After inspecting the organization's network, I discovered four major vulnerabilities:

- Employees share passwords.
- The admin password for the database is set to the default.
- The firewalls do not have rules in place to filter traffic coming in and out of the network.
- Multifactor authentication (MFA) is not used.

If no action is taken to address these vulnerabilities, the organization remains at risk of another data breach or other attacks in the future.

---

## 🔍 Vulnerability Assessment & Tool Selection

I reviewed a reference list of network hardening tasks and selected the three methods that best address the vulnerabilities I found.

---

## 📝 Security Risk Assessment Report

### Hardening tools and methods selected

Three hardening tools the organization can use to address the vulnerabilities found include: 
1.	Implementing multi-factor authentication (MFA)
2.	Setting and enforcing strong password policies
3.	Performing firewall maintenance regularly

MFA requires users to use more than one way to identify and verify their credentials before accessing an application. Some MFA methods include fingerprint scans, ID cards, pin numbers, and passwords. 

Password policies can be refined to include rules regarding password length, a list of acceptable characters, and a disclaimer to discourage password sharing. They can also include rules surrounding unsuccessful login attempts, such as the user losing access to the network after five unsuccessful attempts. 

Firewall maintenance entails checking and updating security configurations regularly to stay ahead of potential threats.  

### Explanation of recommendations

1. Enforcing multi-factor authentication (MFA) adds an additional layer of security beyond a password. It will reduce the likelihood that a malicious actor can access a network through a brute force or related attack since additional effort is required to authenticate in more than one way. MFA may also reduce the likelihood of people sharing passwords. Since the recipient of the shared password would need to possess additional authentication besides a password, MFA makes it less useful to share passwords, thereby making passwords less likely to be shared.

2. Creating and enforcing a password policy within the company will make it increasingly challenging for malicious actors to access the network. Policies such as suspending the account after a certain number of logins can prevent successful brute force attacks. Increasing password complexity, requiring more frequent password updates, and not allowing passwords to be reused also help stall malicious actors from infiltrating the network. 

3. Firewall maintenance should happen regularly. Network administrators should ensure that firewall rules are in place that reflect the most up to date standards for allowed and denied traffic. Traffic from sources that are suspicious should be placed on a denied traffic list. Firewall rules should be updated whenever a security event occurs, especially an event that allows suspicious network traffic into the network. This measure can be used to protect against various DoS and DDoS attacks.

---

Applied together, these three measures address all four vulnerabilities and give the organization a repeatable approach to hardening its network and protecting customers' personal information.
