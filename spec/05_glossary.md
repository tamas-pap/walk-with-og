# Walk with Mungo — Glossary

*The shared vocabulary for the MVP. Concept-level definitions, independent of how anything is stored. Where two terms are easily confused, the description draws the border. Post-MVP concepts (moods, guests, multi-walk story arcs, running bits) are deliberately excluded until they're needed.*

---

### Character layer

| # | Name      | Description                                                                                                                 | Example                                                                          |
|---|-----------|-----------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| 1 | Character | A fictional companion the user walks with — a persona plus a voice. The MVP has one.                                        | Mungo.                                                                           |
| 2 | Persona   | The fixed core of a character: worldview, what it notices, what it finds funny, how it speaks. The part that never changes. | Mungo — simple-minded, accidentally wise, naive about modernity, plainly spoken. |
| 3 | Voice     | The synthesized audio identity of a character. One voice per character.                                                     | Mungo's TTS voice — warm, unhurried, grunt-soft.                                 |


---

### Content layer

| # | Name            | Description                                                                                                                                                                       | Example                                                                                                                     |
|---|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| 1 | Category        | A broad subject bucket that organizes seeds and lets coverage be read at a glance. Also used by the director to space related content apart.                                      | work · body · food · relations · waiting · home · time · things.                                                            |
| 2 | Seed            | A specific idea an atom is generated from — granular enough to produce something sharp, before it's written in Mungo's voice. Lives in one category.                              | `lift_one_floor`: "person waits for the lift to go down one floor / effort-saving removes the effort that would feel good." |
| 3 | Atom            | The semantic unit of content — one idea, of a given type, generated from a seed, that the user is never meant to hear twice.                                                      | Mungo's lines about people taking the lift down one floor.                                                                  |
| 4 | Variant         | An alternate phrasing of the same atom, each with its own rendered audio — exists so even revisitable content never sounds identical.                                             | Two tellings of the lift-atom, worded differently.                                                                          |
| 5 | Atom attributes | The labels that let the director place an atom well: **type** (its job), **category** (its subject), **depth** (emotional weight 1–4), **attention** (ambient / listen / engage). | A story atom; category *food*; depth 3; attention *listen*.                                                                 |


*Atom types in the MVP: push · open · first-beat · hey-response · close · observation · noticing · question · callback · story · quiet · challenge · tip.*

---

### Interaction layer

| # | Name     | Description                                                                                        | Example                                                                |
|---|----------|----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------|
| 1 | Choice   | An answer option offered on a question (3–4 per question), tappable or spoken.                     | "still deciding / decided but scared / not my call / let's just walk." |
| 2 | Reaction | The short, in-character acknowledgement baked into a choice, so no answer ever falls into silence. | Tap "scared" → "Good. Scared means it matters."                        |


---

### Runtime layer

| # | Name        | Description                                                                                                                                                                     | Example                                                                 |
|---|-------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|
| 1 | Session     | One run of the app from open to close — the technical record of a walk.                                                                                                         | Tonight's walk, 19:50–20:25.                                            |
| 2 | Walk        | The user-facing experience inside a session. (Session = the record; walk = the experience.)                                                                                     | "That was a good walk."                                                 |
| 3 | WalkContext | The live, in-the-moment picture of the walk that the director reads to decide what happens next — elapsed time, whether the user is moving, walk phase, whether Hey is pending. | Elapsed 14 min, moving, no Hey → phase *middle*.                        |
| 4 | Director    | The runtime brain that decides, live, when Mungo speaks and what he plays — filters, scores, then samples. Reads the WalkContext.                                               | Picks a noticing over a story because the night is sparse.              |
| 5 | Cadence     | The rhythm of speech vs. silence — when the director decides to speak at all.                                                                                                   | Roughly every 3–5 min, stretching if the user stays quiet.              |
| 6 | The Hey     | The user's one mid-walk lever: a button meaning "your turn — give me something."                                                                                                | Tap Hey → a question, a story, or "Mm. Still here."                     |
| 7 | Check-in    | The end-of-walk question reading whether the walk worked — the core promise signal.                                                                                             | "Lighter, same, or rearranged?"                                         |
| 8 | Push        | A lock-screen notification that is Mungo's first line of the evening — a gift, never a reminder.                                                                                | "Found a stick that looks exactly like your week. Come, I'll show you." |
| 9 | Walk phase  | Where in the arc a moment sits — opening, middle, closing — constraining which atoms fit. Derived inside the WalkContext.                                                       | A close atom plays only in the closing phase.                           |


---

### Memory layer

| # | Name   | Description                                                                                                      | Example                                                   |
|---|--------|------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------|
| 1 | Memory | Everything the product retains about a user across walks. In the MVP, only enumerable facts — nothing free-form. | Knows the last decision_state and which atoms were heard. |


