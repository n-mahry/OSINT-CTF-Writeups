# Weak Pedia 1 — OSINT Challenge (50 pts)

### 🧩 Challenge Description

> _"Those days nobody thought the kind of Cooper that had boarded. He was not who he looked like or perhaps he was, nobody really knows, not even the feds. 9 years later a small portion of his 'ransom' was found._  
>  
> **When was this?**  
>  
> Flag format: `BitCTF{M_D_Y}`

---

### 🧠 Thought Process

#### Step 1: Analyze the Clue
The challenge refers to someone named **"Cooper"** who:
- Boarded something (likely a plane),
- Had a mysterious identity (“not who he looked like”),
- Was involved in a **ransom** situation,
- And had a **portion of the ransom found 9 years later**.

These keywords point directly to the famous unsolved case of **D.B. Cooper**.

#### Step 2: Research the Case
Using OSINT (Wikipedia, Google), we find:

- **D.B. Cooper** (alias Dan Cooper) hijacked **Northwest Orient Flight 305** on **November 24, 1971**, demanding **$200,000 in ransom**.
- After receiving the money, he **parachuted out of the plane mid-flight**, never to be seen again.
- The FBI never conclusively identified him.

#### Step 3: Confirm the "Ransom Found" Detail
The challenge mentions that **9 years later**, part of the ransom was discovered.

From Wikipedia and FBI records:
- In **February 1980**, **$5,800** in deteriorating $20 bills was found by an 8-year-old boy named Brian Ingram along the Columbia River in Washington State.
- The serial numbers matched the ransom money given to D.B. Cooper in 1971.

Even though the exact time span is 8 years and a few months, it’s commonly referred to as **9 years later** in casual recounting — aligning with the challenge’s narrative.

#### Step 4: Determine "When was this?"
While the ransom was found in **1980**, the question "When was this?" refers to the **original event** of Cooper **boarding the plane and hijacking it** — not when the money was found.

This is supported by:
- The wording "Those days nobody thought..." clearly referencing **the hijacking date**.
- The identity mystery and "boarding" all happened on **November 24, 1971**.

---

### ✅ Final Flag

```text
BitCTF{November_24_1971}
