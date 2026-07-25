hi# NPCAI Enhanced Prompts — English Ultimate Edition

An enhanced English prompt pack for **NPCAI** (NPCI), the Gemini-powered NPC dialogue
plugin for LSPDFR by DoubleHook. This is not a translation — it's a rewrite of the stock
prompts aimed at more natural conversation, more consistent personalities, and more
realistic police, fire, and EMS roleplay.

Built by **Sxniex**, 

---

## What's in this pack

| File | Purpose |
|---|---|
| `NPCI_GeminiPrompt.txt` | Civilian NPC behavior — personality, emotion, cooperation, dialogue rules |
| `NPCI_EmergencyPrompt.txt` | Police backup, sheriff, trooper, EMS, fire, and specialty role behavior |
| `NPCI_VoiceStyles.ini` | Per-archetype voice/attitude overrides (biker, hillbilly, gang, wealthy, etc.) |
| `NPCI_TranscriptionPhrases.txt` | Voice-command trigger phrases (dismiss, sit, face player, etc.) |

All four files are plain text/INI, UTF-8 encoded, ready to drop in as-is.

---

## What's different from the stock prompts

**Character consistency.** Every conversation rolls a fixed set of traits up front —
region, personality, a hidden trait, a cooperation level, and a starting emotional
state — and holds them for the whole interaction. NPCs no longer randomly flip
personality mid-conversation.

**Gradual emotional escalation.** Civilians move through a six-stage ladder (Calm →
Concerned → Defensive → Frustrated → Angry → Resigned) one step at a time, driven by
the officer's behavior, instead of jumping straight to hostile or straight to broken.

**Conversation memory.** NPCs are instructed to lock in anything they've already said —
where they live, who they were with, whose car it is — so they stop contradicting
themselves two lines later.

**A real cooperation spectrum.** Nine levels between "fully cooperative" and "lawyered
up," independent of personality — a friendly ped can still be hiding something, an
aggressive one can still comply.

**Anti-repetition rules.** NPCs are told not to reuse the same acknowledgment, excuse,
or sentence opener twice in a row — one of the most noticeable stock-prompt tells.

**Voice stability for TTS.** Explicit rules against the text patterns that cause pitch
spikes in Gemini's voice output — multiple exclamation points, ALL CAPS, stutter
hyphens, trailing ellipses — plus grounded, non-hysterical delivery for tense scenes
like violent arrests and officer-down calls.

**Expanded procedural coverage.** DUI stops, felony/high-risk stops, domestic violence,
mental health crises, search warrants, missing persons, active shooter, and crime scene
preservation, on top of the standard traffic-stop and pursuit scenarios.

**Deeper emergency services.** Every responder role (patrol, detective, SWAT, sheriff,
trooper, EMS, fire, coroner, CSI, ranger, wildlife warden, animal control, gang unit,
arson investigator) has its own realistic vocabulary, lane restrictions, and dispatch
limits, so an EMS ped never calls a tow truck and a firefighter never plays coroner.

**Regional and cultural variety, without stereotype.** A rotating pool of American
regional backgrounds (SoCal, Deep South, Midwest, Boston, Texas, immigrant
communities, etc.) that flavors speech with two or three natural details instead of
a caricature accent.


---

## Compatibility

- Built against **NPCAI 3.1.1**.
- No plugin files, actions, or tool names were added, removed, or renamed.
- No new NPCAI capabilities are assumed — every action referenced in these prompts
  (`call_backup`, `call_ems`, `call_fire`, `call_coroner`, `call_transport`, `call_tow`,
  `call_animal_control`, `dismiss_backup`, `follow_player`, `look_at_me`/`face_player`,
  passenger checks, player self-actions, `attack_player`) exists in the base plugin.

---

## Credits

- **DoubleHook** — creator of NPCAI Plugin thank you so much for this plugin 
- **Sxniex** — English Ultimate Enhanced Edition prompt .

If you use or redistribute this pack, please keep this credit intact.
