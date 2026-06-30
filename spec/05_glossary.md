# Walk with Og - Glossary

*The shared vocabulary for the MVP. These are concept-level definitions, independent of storage or implementation. The glossary should make the product immediately understandable to a human or an LLM.*

---

## Foundation layer

| # | Name | Description | Example |
|---|------|-------------|---------|
| 1 | Modern pressure | Abstract demands that create real mental and bodily load. | Emails, deadlines, comparison, unfinished tasks, phone pull. |
| 2 | Ancient signal | The older human need or alarm underneath modern pressure. | Safety, rest, tribe, shelter, hunger, shame, danger, courage. |
| 3 | Walkable | Small enough to move through, even if not solved. | An avoided email becomes "open it, read it, answer one line." |
| 4 | Grounded company | Og's role: present beside the user without managing, diagnosing, or optimizing them. | Fewer words on a heavy day; a simple noticing on a tired evening. |
| 5 | Care boundary | The line that keeps Og from acting like clinical care, crisis support, or a replacement relationship. | "This sounds too heavy to carry alone. Find a real person for this one." |

---

## Character layer

| # | Name | Description | Example |
|---|------|-------------|---------|
| 1 | Character | A fictional companion the user walks with: persona plus voice. The MVP has one. | Og. |
| 2 | Persona | The fixed core of a character: worldview, values, humor, boundaries, and speech rules. | Og is ancient-minded, modern-aware, warm, blunt, and deliberately simple. |
| 3 | Voice | The synthesized audio identity of a character. One voice per character. | Og's TTS voice: warm, grounded, unhurried, never gimmicky. |
| 4 | Ancient frame | Og's way of translating modern pressure into older human realities. | A phone becomes a small fire with the whole tribe inside it. |

---

## Content layer

| # | Name | Description | Example |
|---|------|-------------|---------|
| 1 | Use case | A repeatable situation where Og has a clear job on the walk. | The Doorstep Moment, The Heavy Day, The Avoided Thing. |
| 2 | Category | A broad subject bucket that organizes seeds and helps the director space related content apart. | work, body, phone, food, rest, tribe, loneliness, weather. |
| 3 | Seed | A specific idea an atom is generated from, before it is written in Og's voice. Lives in one category. | `email_teeth`: "body treats an email like danger, but it is only words in a box." |
| 4 | Atom | One semantic unit of content, generated from a seed, that the user is not meant to hear twice. | Og's line about answering one email with one rough sentence. |
| 5 | Variant | An alternate phrasing of the same atom, rendered separately so revisitable content stays fresh. | Two different versions of the same "phone as tribe fire" idea. |
| 6 | Atom attributes | Labels that let the director place an atom well: type, category, depth, attention. | A quiet atom; category *body*; depth 2; attention *ambient*. |

*MVP atom types: push, open, first-beat, hey-response, close, observation, noticing, question, callback, story, quiet, challenge, tip.*

---

## Interaction layer

| # | Name | Description | Example |
|---|------|-------------|---------|
| 1 | Choice | An answer option offered on a question, tappable or spoken. | "too tired / still angry / thinking in circles / just walk." |
| 2 | Reaction | The short, in-character acknowledgement attached to a choice so no answer falls into silence. | Tap "still angry" -> "Good. Anger has legs. Let it walk." |

---

## Runtime layer

| # | Name | Description | Example |
|---|------|-------------|---------|
| 1 | Session | One run of the app from open to close: the technical record of a walk. | Tonight's session, 19:50-20:25. |
| 2 | Walk | The user-facing experience inside a session. Session is the record; walk is what it felt like. | "That was a good walk." |
| 3 | WalkContext | The live picture the director reads: elapsed time, movement, walk phase, location context if available, weather if available, and whether Hey is pending. | Elapsed 14 min, moving, light rain, no Hey, phase *middle*. |
| 4 | Director | The runtime brain that decides when Og speaks and what plays: filter, score, then sample. | Picks quiet over a story because the Heavy Day use case is active. |
| 5 | Cadence | The rhythm of speech and silence. Cadence decides whether Og should speak at all. | Roughly every 3-5 min, stretching longer if the user stays quiet. |
| 6 | The Hey | The user's one mid-walk lever meaning "your turn, give me something." | Tap Hey -> a question, a story, or "Still here. Keep walking." |
| 7 | Check-in | The end-of-walk question that reads whether the walk delivered the promise. | "Lighter, clearer, softer, less stuck, or same?" |
| 8 | Push | A lock-screen line from Og that makes starting feel possible. A gift, never a reminder. | "Come outside. The phone can guard the cave for ten minutes." |
| 9 | Walk phase | Where a moment sits in the walk arc: opening, middle, closing. Constrains which atoms fit. | A close atom plays only near the end. |

---

## Memory layer

| # | Name | Description | Example |
|---|------|-------------|---------|
| 1 | Memory | What the product retains across walks. In the MVP, prefer enumerable facts over free-form psychological profiles. | Which atoms were heard, last check-in result, recurring chosen use case. |
