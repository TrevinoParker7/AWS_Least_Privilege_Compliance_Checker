# 🕶️ LAB: AWS Least-Privilege Compliance Checker 

<img width="1135" height="1127" alt="image" src="https://github.com/user-attachments/assets/4de4e1d9-6db4-43fd-95e7-fc6c74fba506" />

<img width="500" height="925" alt="image" src="https://github.com/user-attachments/assets/4063524c-1b25-44ff-8314-d7919c28b9c6" />

<img width="1325" height="540" alt="image" src="https://github.com/user-attachments/assets/92fa998d-f38c-471c-9a60-129871090ef8" />

> “You take the blue pill — keep giving everyone `*:*` and hope for the best.  
> You take the red pill — and I’ll show you how privilege actually works.”  
> — Morpheus, Chief Least-Privilege Officer

---

## 🧠 The Premise (or: Why Your Cloud Isn’t a Casino)

Malware is scary. Misconfigured IAM is terrifying.  
One of the biggest attack surfaces in the cloud isn’t a zero-day — it’s **overbroad permissions**: wildcard policies, unchecked admin roles, and privilege escalation routes so obvious even an Agent would say, “that’s sloppy.”

This lab is your **red pill** for permissions. You’ll automate least-privilege validation across your AWS estate, score risk per identity, and generate audit-ready evidence mapped to **SOC 2 CC6.3** and **NIST 800-53 AC-6** (including AC-6(1) and AC-6(2)).  
In short: become the Neo of IAM.

---

## 🎯 Why This Matters (Auditors & Managers Whisper These Words)

Every auditor, security leader, and hiring manager will eventually ask:

> “How can you prove your users and roles *only* have what they need?”

If your answer involves 17 spreadsheets, a whiteboard, and prayer — you’re doing it wrong. This lab produces automated JSON + CSV evidence that shows:

- Users/roles only have necessary permissions  
- Administrative access is rare, justified, and traceable  
- Wildcards and dangerous actions are identified and labeled CRITICAL  
- Privilege escalation paths are minimized and documented

You’ll go from “maybe” to “here’s the evidence” — and Morpheus will finally stop sighing.

---

## 🧩 What You’ll Deliver (Outputs That Impress People)

- ✅ **Python-based Least-Privilege Checker** (`privilege_analyzer.py`)  
- ✅ **JSON report** (detailed findings per entity, policy extracts, control mapping)  
- ✅ **CSV summary** (audit-ready table: entity, risk score, critical findings)  
- ✅ **Executive summary** (percent compliant, critical violation counts, remediation list)  
- ✅ **Per-entity remediation steps** (exact policy changes or suggested actions)

---

## 🔗 Controls & Mapping (Cite These in Audits)

- **SOC 2 CC6.3** — Logical access controls restrict unauthorized access  
- **NIST 800-53 AC-6** — Least Privilege  
- **NIST 800-53 AC-6(1)** — Authorize access to security functions  
- **NIST 800-53 AC-6(2)** — Non-privileged access for non-security functions

You can confidently reference the above in your audit artifacts. Stamp them with a tiny Neo-approved seal if you like.

---

## 🛠️ How This Lab Helps You

### For Your Portfolio
Add a polished least-privilege project with machine-verified evidence. Recruiters love clear data: JSON details for engineers, CSV summaries for auditors, and an executive one-pager for managers.

### For Interviews
When asked “how would you detect overprivilege?” you’ll calmly say:
> “I enumerated identities, parsed policies (attached + inline), flagged admin/wildcards/high-risk actions, scored each entity, and generated audit-ready evidence mapped to SOC 2 and NIST.”

Drop the mic. They’ll want to know more.

### For LinkedIn
Flex with this:

> “Finished a GRC lab automating least-privilege checks in AWS. I now produce JSON/CSV evidence with entity risk scores, admin/wildcard detection, and remediation guidance mapped to SOC 2 & NIST. Compliance is engineered, not manual.”

Expect likes, at least one recruiter DM, and one confused manager asking “what is `sts:AssumeRole` again?”

