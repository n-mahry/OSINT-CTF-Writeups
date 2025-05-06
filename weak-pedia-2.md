# Weak Pedia 2 — OSINT Challenge (100 pts)

### 🧩 Challenge Description

> _"What bills were found and what was the total?"_  
>  
> Flag format: `BitCTF{bill_total}`

---

### 🧠 Thought Process

#### Step 1: Understand the Context
The challenge continues from **Weak Pedia 1**, referencing the infamous **D.B. Cooper hijacking case**. We’re asked to identify:
- The **denomination** of the bills that were found.
- The **total amount** of the recovered money.

This leads us to focus on the portion of Cooper’s ransom that was discovered years after the hijacking.

#### Step 2: Research the Case Details
From reliable historical sources (FBI reports, Wikipedia):
- **D.B. Cooper** hijacked a plane on **November 24, 1971**, demanding **$200,000** in **$20 bills**.
- In **February 1980**, a young boy named **Brian Ingram** found **three decaying bundles** of cash along the **Columbia River** near **Vancouver, Washington**.
- The **serial numbers** of the bills matched those from the Cooper ransom.

#### Step 3: Verify the Amount and Denomination
Digging into the specifics:
- **Denomination**: $20 bills — consistent throughout Cooper’s ransom.
- **Total Found**: $5,800.  
  - This is the **verified amount** cited in multiple sources, including FBI records.
  - Some general references may round this to $6,000, but **$5,800** is the precise and correct figure.

---

### ✅ Final Flag

```text
BitCTF{20_5800}
