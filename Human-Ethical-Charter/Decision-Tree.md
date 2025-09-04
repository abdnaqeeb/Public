# Illustrative Decision Tree for Applying the Charter

This decision tree provides a **practical tool** for interpreting the *Human Ethical Charter*.  
It translates the ten articles into a series of questions that help evaluate whether a behavior or attribute is to be considered a **Virtue, Vice, Exception, or Subject to Review**.  

It is not a replacement for the Charter’s principles, but an illustrative guide to support decision-making in real contexts.  

```mermaid
flowchart TB
A[Behavior/Attribute] --> B{"Does it violate a fundamental right? (Art.1)"}
B -- Yes --> Bx{"Existential catastrophe + least-infringing, temporary, under oversight? (Art.9)"}
Bx -- Yes --> R3[Exceptionally permissible with safeguards]
Bx -- No --> R1[Vice]
B -- No --> C{"Does it push anyone below sufficiency? (Art.2)"}
C -- Yes --> R1
C -- No --> D{"Does it harm well-being, esp. the disadvantaged? (Art.3)"}
D -- Yes --> R1
D -- No --> E{"Is it unjust in distribution across groups/generations? (Art.4)"}
E -- Yes --> R1
E -- No --> F{"Does it harm relationships or duties of care? (Art.5)"}
F -- Yes --> R1
F -- No --> G{"Is the condemnation/support based only on local/temporal tradition? (Art.7)"}
G -- Yes --> H["Re-evaluate using dignity, justice, well-being (Arts.1–4)"]
H --> S
G -- No --> S{"Sustainable, transparent, and trust-building across generations? (Art.8)"}
S -- No --> R1
S -- Yes --> V{"Does it cultivate core virtues (courage, honesty, compassion, justice, self-control)? (Art.6)"}
V -- Yes --> R2[Virtue]
V -- No --> R4["Needs participatory review & periodic update (Art.10)"]
