# Weak Pedia 4 — OSINT Challenge (300 pts)

### 🧩 Challenge Description

> _"Cooper's flight was a Boeing 727-100. How old was she when Cooper asked for a bourbon from seat 18-E?"_  
>  
> Flag format: `BitCTF{Count}`

---

### 🧠 Thought Process

#### Step 1: Identify the Aircraft and the Event
The **D.B. Cooper** hijacking took place on **November 24, 1971**, aboard **Northwest Orient Airlines Flight 305**. The aircraft was a **Boeing 727-51** with the FAA registration **N467US** and construction number **18803**. Cooper boarded the flight, took seat **18-E**, and ordered a **bourbon and 7-Up** before takeoff. The focus here is on the **age of the aircraft** at the time Cooper asked for the bourbon, which is shortly before takeoff on that day.

#### Step 2: Determine the Aircraft's "Birth" Date
To determine the age of the aircraft, we need its **first flight date**, as aircraft age is typically calculated from this point. The **first flight** of the Boeing 727-51 **N467US** took place on **April 9, 1965**. This marks the start of its operational life and serves as the reference point for calculating its age.

#### Step 3: Calculate the Aircraft's Age on November 24, 1971
We now need to calculate the aircraft's age on **November 24, 1971**, which is the date of the hijacking. Here's the breakdown:

- From **April 9, 1965**, to **April 9, 1971**, the aircraft is **6 full years** old.
- Now, we calculate the additional time between **April 9, 1971**, and **November 24, 1971**:
  - **April 9 to May 9**: 1 month
  - **May 9 to June 9**: 2 months
  - **June 9 to July 9**: 3 months
  - **July 9 to August 9**: 4 months
  - **August 9 to September 9**: 5 months
  - **September 9 to October 9**: 6 months
  - **October 9 to November 9**: 7 months
  - **November 9 to November 24**: 15 days

This gives us a total of **7 months and 15 days**. Therefore, the aircraft’s age on **November 24, 1971**, is **6 years, 7 months, and 15 days**.

#### Step 4: Interpret "Age" for the Flag
The flag format requires a **single number**. While the precise age is **6 years, 7 months, and 15 days**, aircraft age is generally expressed in whole years, especially in historical contexts. Since the aircraft had completed **6 full years** by November 24, 1971, and had not yet reached its 7th anniversary (April 9, 1972), it is common to refer to it as **6 years old**.

Thus, the aircraft, referred to as "she" in the question, was **6 years old** on the date of the hijacking.

#### Step 5: Verify the Context
The question asks for the aircraft's age when **Cooper** asked for a bourbon from seat 18-E, which was shortly before takeoff on **November 24, 1971**. There’s no need for a more precise measure (e.g., in months or days), as the flag format suggests a whole number. Therefore, the **age of the aircraft** at that moment is best expressed as **6 years**.

#### Final Answer
The Boeing 727-100 (N467US) was **6 years old** when D.B. Cooper asked for a bourbon from seat 18-E. The flag is:

```text
BitCTF{6}
