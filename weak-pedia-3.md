# Weak Pedia 3 — OSINT Challenge (200 pts)

### 🧩 Challenge Description

> _"Who is our favourite suspect by the way?"_  
>  
> Flag format: `BitCTF{Name1_Name2_Name3}`

---

### 🧠 Thought Process

#### Step 1: Understand the D.B. Cooper Case
The **D.B. Cooper** hijacking is a famous unsolved case from **November 24, 1971**, where a man using the alias **Dan Cooper** (later dubbed **D.B. Cooper** by the media) hijacked **Northwest Orient Airlines Flight 305**. He demanded **$200,000** in ransom and parachuted out of the plane mid-flight, disappearing without a trace. Despite an exhaustive investigation, the FBI has never definitively identified Cooper.

#### Step 2: Interpreting "Our Favourite Suspect"
The phrase **"our favourite suspect"** implies that there is a widely recognized individual who stands out as a leading theory. The flag format of `BitCTF{Name1_Name2_Name3}` indicates that the answer should be a full name with three parts (e.g., first, middle, last). 

Since the challenge title is **Weak Pedia** (a likely reference to Wikipedia), the most "popular" or **favorite suspect** in the case is likely the one most frequently discussed in prominent sources or widely regarded by investigators.

#### Step 3: Notable Suspects
Over the years, several suspects have been proposed for the D.B. Cooper case. Some of the most notable include:

- **Richard Floyd McCoy**: A Vietnam veteran and skilled parachutist who hijacked a plane in 1972 in a similar manner to Cooper. McCoy's crime was almost identical, leading to speculation about his involvement, though the FBI officially ruled him out based on discrepancies in his physical description.
  
- **Kenneth Peter Christiansen**: A former paratrooper and airline employee, suggested by his brother and investigated in a 2007 book. While a plausible suspect, he's less widely regarded as the top candidate.

- **Robert Richard Rackstraw**: A veteran with parachuting skills, recently featured in documentaries. However, the evidence against him is circumstantial.

- **Duane L. Weber**: Linked to the case through a deathbed confession, but lacking substantial proof.

- **Sheridan Peterson**: Another parachutist who was later suggested as a possible suspect, but not as highly regarded as others.

#### Step 4: Narrowing Down the Favorite Suspect
The most prominent and well-known suspect among all of these is **Richard Floyd McCoy**. Here’s why:

- **Historical Prominence**: While the FBI officially dismissed McCoy as a suspect, he is one of the most widely discussed and frequently cited individuals due to the similarities between his hijacking and Cooper's. His crime mirrored Cooper’s perfectly, and McCoy was a skilled parachutist, just like Cooper.
  
- **Name Fit**: McCoy's full name—**Richard Floyd McCoy**—matches the three-part flag format exactly (First = Richard, Middle = Floyd, Last = McCoy).

- **Cultural Resonance**: Articles, books, and documentaries often revisit McCoy's case as a leading theory, cementing his place as the "favorite" suspect among many researchers and enthusiasts.

#### Step 5: Understanding the Challenge Context
The **Weak Pedia** challenge likely draws from popular, accessible knowledge—such as Wikipedia—rather than obscure or lesser-known theories. McCoy's name is widely discussed and considered by many to be the top suspect, making him the obvious choice for this challenge.

#### Step 6: Constructing the Flag
Given all of the above, the **most reasonable** choice is **Richard Floyd McCoy**. The flag format requires underscores between the names, so the final flag is:

```text
BitCTF{Richard_Floyd_McCoy}
