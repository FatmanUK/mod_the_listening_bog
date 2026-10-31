## Step 3 — structural arc and motif map

The arrangement follows the title: **The Listening Bog** begins as a place with its own pulse. It notices a reed call, answers it with small clicks and rattles, then gradually reveals a faint, almost synthetic tone beneath the organic sounds. The music draws back toward the end, but the bog gives one final, shaped answer rather than fading away.

This structure is sample-independent. Motifs describe musical roles and contours; sample choices can be adjusted after audition.

### Motifs

- **A — Mud pulse:** A low, gently rocking figure with a slight rhythmic lurch. It establishes the bog’s living pulse.
- **B — Listening reed:** A short, descending woodwind phrase with a held pause, as if waiting for a reply.
- **C — Water memory:** A soft sustained tone or small chord that shifts to a neighbouring tone and recedes.
- **D — Beetle ticks:** An uneven click-and-rattle pattern, usually in small groups rather than a regular drum beat.
- **E — Nerve glint:** A clipped two-note signal that sits close to the reed’s pitch but has a more synthetic edge.

### Pattern roles

Pattern IDs are hexadecimal.

| Pattern | Motif combination | Role |
|---|---|---|
| `00` | A hint of A, sparse D | Establish the place; leave plenty of space. |
| `01` | B | First reed call, exposed and unhurried. |
| `02` | D, then E | The small sounds answer from deeper in the bog. |
| `03` | A + B | The pulse appears beneath the call. |
| `04` | A + C | First crossing; broaden the harmony without filling every channel. |
| `05` | A + D, B fragment | A lightly varied return, with more movement in the undergrowth. |
| `06` | B + E | Call and response begin to resemble one another. |
| `07` | A + B + C + D | Fullest statement: all four parts have a clear role. |
| `08` | C + E | Withdraw the pulse; let the organic and synthetic tones overlap. |
| `09` | B fragments + D | The call breaks into brief remembered pieces. |
| `0A` | A + E | Gather the pulse and signal toward the ending. |
| `0B` | B contour turned upward, D double-click, final A | Coda flourish and resolution; no fade or order-list loop. |

### Proposed order list

This uses `0C` unique patterns across `12` order entries, with deliberate reuse. At speed `06` and BPM `5A` (90 decimal), each 64-row pattern lasts about 10.7 seconds; this order list gives an estimated runtime of **192 seconds**.

| Order | Pattern | Section |
|---|---|---|
| `00` | `00` | Threshold |
| `01` | `01` | First call |
| `02` | `02` | Answer in the reeds |
| `03` | `03` | Pulse underfoot |
| `04` | `04` | First crossing |
| `05` | `03` | Return to the pulse |
| `06` | `04` | The crossing feels familiar |
| `07` | `05` | Listening chamber |
| `08` | `06` | The call doubles |
| `09` | `07` | The bog answers fully |
| `0A` | `06` | The answer thins |
| `0B` | `07` | Full current |
| `0C` | `04` | Recognition |
| `0D` | `08` | Withdrawal |
| `0E` | `09` | Fragments in the reeds |
| `0F` | `08` | Last echo |
| `10` | `0A` | Coda gathers |
| `11` | `0B` | Final flourish and resolution |

Keep the four-channel roles flexible: one carries the call, one the harmonic bed, one the pulse, and one the clicks or rattles. Let parts drop out and re-enter so the repeated patterns feel like returns to familiar ground, not a continuous wall of sound.

Step 3 is complete. The bootstrap notes that this is a good point to generate an updated Markdown bootstrap with the title, tempo, proposed sample set, and this structure.