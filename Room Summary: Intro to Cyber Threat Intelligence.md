
Room Summary: Intro to Cyber Threat Intelligence
TryHackMe  |  Difficulty: Easy  
*
1. What did the room actually teach?
The room teaches you how to take a raw piece of suspicious data - like an IP address or a file - and turn it into something you can act on. It walks through a structured six-step process that analysts use to collect, evaluate, and share threat intelligence. It also introduces the main frameworks the industry uses to label and communicate threats consistently.

2. Key Concepts
| Concept | What it means simply | Why it matters |
| --- | --- | --- |
| IOC | A clue that something bad happened | Gives you something concrete to investigate |
| Enrichment | Looking up an indicator across multiple sources | Turns a data point into a decision |
| TLP | A label that tells you who you can share intel with | Prevents accidental leaks to the wrong people |
| CTI Lifecycle | A six-step loop from question to action | Keeps intelligence from piling up unused |
| Kill Chain | A map of the 7 stages of an attack | Helps you figure out where in the attack you are |
| MITRE ATT&CK | A numbered catalog of attacker techniques | Gives everyone on the team the same language |

3. What type of intelligence is this?
Primarily Tactical Intelligence
The room focuses on handling indicators and mapping attacker techniques, which supports immediate defensive actions. While it touches on operational concepts like the Kill Chain, the emphasis is on technical application rather than campaign-level analysis.

4. If I were a CTI analyst in an organization -
•	I would use the enrichment process to triage every incoming alert with a consistent method instead of guessing
•	I would map alerts to Kill Chain stages to recognize when separate events are actually one connected attack
•	I would use ATT&CK IDs so the next analyst doesn't have to re-interpret what I found
•	I would use TLP correctly when sharing indicators with partner organizations to protect the investigation

5. What felt clear? 
The progression from data to information to intelligence felt natural. A raw indicator without context genuinely is useless, and the room made that logic easy to follow. The Kill Chain also clicked quickly because attacks are never a single event — mapping the stages gives the whole picture a shape.

6. What was less clear? 
The enrichment tools were introduced quickly and it was hard to get a feel for which one to reach for first in a real situation. Knowing that VirusTotal exists is one thing — knowing when to use it over Shodan or URLhaus in the middle of a live triage is something that only becomes clear with repetition.

7. One question I want to explore further: When triaging a live alert, is there a standard order for running enrichment tools — or does it depend entirely on the indicator type and context?

