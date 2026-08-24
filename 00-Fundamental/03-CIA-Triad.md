# CIA Triad

## 🎯 Learning Objectives

After completing this lesson, I can:

- Explain the CIA Triad.
- Describe Confidentiality, Integrity, and Availability.
- Identify common threats against each principle.
- Understand how security controls protect the CIA Triad.

---

# 🔒 Confidentiality

Confidentiality ensures that sensitive information is only accessible to authorized users.

Examples:

- Passwords
- Customer Data
- Medical Records
- Financial Information

Security Controls:

- Strong Passwords
- Multi-Factor Authentication (MFA)
- Encryption
- Access Control
- VPN

---

# ✅ Integrity

Integrity ensures that information remains accurate, complete, and unchanged unless modified by an authorized user.

Examples:

- File Hashing
- Digital Signatures
- Audit Logs

Common Threats:

- SQL Injection
- Malware
- Unauthorized Modification

---

# 🌐 Availability

Availability ensures that systems and information remain accessible when needed.

Security Controls:

- Backup
- Redundancy
- Disaster Recovery
- Load Balancer
- Monitoring

Common Threats:

- DDoS
- Hardware Failure
- Ransomware
- Server Crash

---

# 📝 Summary

The CIA Triad is the foundation of Information Security. Every security control is designed to protect one or more of its three principles: Confidentiality, Integrity, and Availability.

# 📝 Quiz
1. What does the CIA Triad stand for?
2. Explain the differences between Confidentiality, Integrity, and Availability using real-world examples.
3. Why is hashing used to maintain Integrity?
4. What is the difference between a Data Breach and a DDoS attack in the context of the CIA Triad?
5. Name three security controls used to maintain Confidentiality.
6. Why must a SOC Analyst understand the CIA Triad before analyzing alerts?
7. Describe an example of an incident that could affect more than one CIA principle.

#  🕵️‍♂️ Mini Case
### Case
At 09:15, the SIEM system generated three alerts:
1. A user successfully logged into the VPN from Indonesia, and seven minutes later, the same account logged in from Germany.
2. The product database showed a price change from IDR 5,000,000 to IDR 50,000 without a corresponding change request ticket.
3. The company website was inaccessible for two hours due to an extremely high traffic spike.
### Task
For each incident:
1. Identify the affected CIA principle.
2. Explain your reasoning.
3. List at least two initial investigation steps to be taken as an SOC Analyst.
4. Determine the handling priority (low, medium, or high) and provide the reason.
