# Room Summary: Intro to Cyber Threat Intelligence  
**Platform:** TryHackMe  
**Difficulty:** Easy  

---

## 1. What Did the Room Actually Teach?

The room teaches how to take a raw piece of suspicious data — such as an IP address or a file hash — and transform it into actionable intelligence.  

It walks through a structured six-step process analysts use to collect, evaluate, enrich, and share threat intelligence.  

Additionally, it introduces the core industry frameworks used to label, categorize, and communicate threats in a consistent and standardized way.

---

## 2. Key Concepts

| Concept | What It Means (Simply) | Why It Matters |
|----------|-------------------------|----------------|
| IOC (Indicator of Compromise) | A clue that something malicious may have occurred | Provides a concrete starting point for investigation |
| Enrichment | Looking up an indicator across multiple intelligence sources | Transforms raw data into contextual intelligence |
| TLP (Traffic Light Protocol) | A classification label controlling information sharing | Prevents accidental exposure of sensitive intelligence |
| CTI Lifecycle | A structured six-step loop from question to action | Ensures intelligence supports decisions instead of accumulating unused |
| Cyber Kill Chain | A 7-stage model describing how attacks unfold | Helps determine where an organization is in the attack process |
| MITRE ATT&CK | A structured framework cataloging attacker techniques | Creates a shared language across security teams |

---

## 3. What Type of Intelligence Is This?

**Primarily Tactical Intelligence**

The room focuses on handling indicators and mapping attacker techniques in a way that supports immediate defensive actions.  

While it introduces operational concepts like the Kill Chain, the main emphasis is on technical application rather than long-term campaign or strategic risk analysis.

---

## 4. If I Were a CTI Analyst in an Organization

- I would use the enrichment process to triage every incoming alert using a consistent and repeatable methodology.
- I would map alerts to Kill Chain stages to identify whether seemingly separate events are part of a coordinated attack.
- I would reference MITRE ATT&CK technique IDs to ensure findings are clearly understood by other analysts.
- I would apply TLP classifications correctly when sharing intelligence with partners to protect investigative integrity.

---

## 5. What Felt Clear?

The transition from **data → information → intelligence** felt logical and intuitive.  

A raw indicator without context has limited value, and the room clearly demonstrated how enrichment and analysis provide meaning.  

The Kill Chain framework also resonated strongly — attacks are rarely single isolated events, and mapping stages provides structural clarity.

---

## 6. What Was Less Clear?

The enrichment tools were introduced quickly, making it difficult to understand which tool should be prioritized during a live triage scenario.  

Knowing that tools such as VirusTotal, Shodan, and URLhaus exist is different from understanding when and why to use each in practice.  

This distinction likely becomes clearer with repetition and applied experience.

---

## 7. Question for Further Exploration

When triaging a live alert, is there a structured or recommended order for enrichment tools — or does the workflow depend entirely on the indicator type and contextual factors?
