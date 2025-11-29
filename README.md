# SUNOAI META TAGS GUIDE

by Shawn McAllister [@stonedoubt](https://suno.com/@stonedoubt)

Meta tags are keywords that guide SunoAI in creating your music. They function as creative instructions that define genre, mood, instruments, effects, and song structure.

This guide is organized so you can either skim and use it in 60 seconds, or dive deep as a power user.

## Table of Contents

1. [Quick Start (60 Seconds)](#1-quick-start-60-seconds)
2. [Syntax & Best Practices](#2-syntax--best-practices)
   - [Where Tags Go](#21-where-tags-go)
   - [Brackets vs Plain Text](#22-brackets-vs-plain-text)
   - [How Many Tags?](#23-how-many-tags)
   - [Priority](#24-priority)
3. [Core Meta Tag Categories](#3-core-meta-tag-categories)
   - [Song Structure](#31-song-structure-core)
   - [Mood & Atmosphere](#32-mood--atmosphere-core)
   - [Energy & Intensity](#33-energy--intensity-core)
   - [Instruments](#34-instruments-core)
   - [Genre](#35-genre-core)
   - [Vocal & Voice](#36-vocal--voice-core)
4. [Intermediate Categories](#4-intermediate-categories)
   - [Production & Effects](#41-production--effects-intermediate)
   - [Rhythm & Tempo](#42-rhythm--tempo-intermediate)
   - [Sound Effects](#43-sound-effects-intermediate)
   - [Musical Keys & Scales](#44-musical-keys--scales-intermediate)
5. [Advanced Categories](#5-advanced-categories)
   - [Chord Progressions & Harmony](#51-chord-progressions--harmony-advanced)
   - [Advanced Techniques](#52-advanced-techniques-advanced)
   - [SunoAI Advanced Parameters](#53-sunoai-advanced-parameters-advanced)
6. [Combining Tags](#6-combining-tags)
   - [Layering Approach](#61-layering-approach)
   - [Dynamic Progression](#62-dynamic-progression)
   - [Creative Contrasts](#63-creative-contrasts)
7. [Genre Templates](#7-genre-templates)
   - [Pop Ballad](#71-pop-ballad)
   - [EDM Anthem](#72-edm-anthem)
   - [Indie Folk](#73-indie-folk)
   - [Dark Electronic](#74-dark-electronic)
8. [Practical Examples](#8-practical-examples)
   - [Cosmic Echoes (Psychedelic Rock)](#81-cosmic-echoes-psychedelic-rock)
   - [Digital Pulse (EDM)](#82-digital-pulse-edm)
   - [Cyber Sushi (Futuristic EDM)](#83-cyber-sushi-futuristic-edm)
9. [Workflow, Tag Placement, and Troubleshooting](#9-workflow-tag-placement-and-troubleshooting)
   - [Recommended Workflow](#91-recommended-workflow)
   - [Tag Placement Strategy](#92-tag-placement-strategy)
   - [Troubleshooting Cheat Sheet](#93-troubleshooting-cheat-sheet)
   - [Common Mistakes to Avoid](#94-common-mistakes-to-avoid)
10. [Ultimate Success Formula and Pro Tips](#10-ultimate-success-formula-and-pro-tips)
    - [Success Formula](#101-success-formula)
    - [Professional Formula](#102-professional-formula-parameters--tags)
    - [Pro Tips](#103-pro-tips)

---

## 1. Quick Start (60 Seconds)

Use this when you just want to get a solid result quickly.

**Choose a genre and mood**

Example:
```
Rock, Dark, Aggressive
```

**Add 3–5 core style tags**

Example:
```
Distorted Electric Guitar, Male Vocal, High Energy, Dark Atmosphere
```

**Define structure in the lyrics field:**

```
[Intro]
[Verse]
[Chorus]
[Verse]
[Chorus]
[Bridge]
[Chorus]
```

**Set advanced options:**

- Weirdness: 40–60%
- Style Influence: 60–80%
- Exclude: e.g. `Acoustic, Slow Tempo` (if you want it energetic and electric)

**Generate, listen, then:**

- Adjust tags (mood, instruments, production)
- Tweak Weirdness / Style Influence
- Regenerate as needed

---

## 2. Syntax & Best Practices

This is the "rules of the road" for how to write and place tags.

### 2.1 Where Tags Go

**Lyrics field**

- Use structural and section tags in square brackets:
  - `[Intro]`, `[Verse]`, `[Chorus]`, `[Bridge]`, `[Solo Section]`, etc.
- You can also add mood/feel tags inside the lyrics if desired:
  - `[Chorus | High Energy | Anthemic]`

**Style / prompt field**

- Use comma-separated descriptive phrases **without brackets**:
  - `Progressive metal, 7/8 time, Distorted guitars, Male vocal, Dark, Atmospheric`

### 2.2 Brackets vs Plain Text

- Use **square brackets** `[...]` for:
  - Section markers in lyrics: `[Verse]`, `[Chorus]`, `[Intro]`
  - Structural and musical tags when embedded in lyrics
- Use **plain text** (no brackets) in style/prompt for:
  - Genre, instrumentation, mood, production, and additional descriptions

### 2.3 How Many Tags?

**Style/prompt:**

- Simple songs: 3–5 core tags
- Detailed control: 8–15 tags
- Avoid going beyond ~20 tags; too many can confuse the model.

**Per section (if tagging inside lyrics):**

- Aim for 3–8 tags per section

### 2.4 Priority

Put the most important information **first**:

1. Genre
2. Dominant mood
3. Lead instrument(s)
4. Vocal style / gender (if applicable)
5. Production / atmosphere

---

## 3. Core Meta Tag Categories

These are the fundamentals that most users will use for every song.

### 3.1 Song Structure (Core)

Define the architectural structure of your track.

**Essential Structure Tags**

- `[Verse]` – Main narrative section
- `[Chorus]` – Memorable hook section
- `[Bridge]` – Contrasting section
- `[Intro]` – Opening section
- `[Outro]` – Closing section
- `[Pre-Chorus]` – Build-up before chorus
- `[Post-Chorus]` – After-chorus section

**Advanced Structures**

- `[Verse 1]`, `[Verse 2]` – Numbered verses
- `[Chorus x2]` – Repeat indicators
- `[Instrumental Break]` – No vocals section
- `[Solo Section]` – Featured instrument spotlight

---

### 3.2 Mood & Atmosphere (Core)

Set the emotional tone and feeling of your track.

**Mood Cheatsheet**

| Tag             | Feel              | Good For                      |
| --------------- | ----------------- | ----------------------------- |
| `[Melancholic]` | Sad, reflective   | Ballads, breakup songs        |
| `[Euphoric]`    | Extremely happy   | EDM anthems, festival drops   |
| `[Nostalgic]`   | Wistful, retro    | 80s, lo-fi, synthwave         |
| `[Dreamy]`      | Soft, floating    | Ambient, shoegaze, chill      |
| `[Aggressive]`  | Intense, forceful | Metal, hardcore, heavy trap   |
| `[Peaceful]`    | Calm, serene      | Ambient, meditation, acoustic |
| `[Mysterious]`  | Enigmatic         | Cinematic, dark electronic    |

**Atmospheric Tags**

- `[Dark Atmosphere]` – Brooding, ominous
- `[Bright Atmosphere]` – Light, cheerful
- `[Ambient Atmosphere]` – Spacious, atmospheric
- `[Intimate Atmosphere]` – Close, personal

---

### 3.3 Energy & Intensity (Core)

Control the power and drive of your music.

**Energy Levels**

- `[High Energy]` – Pumping, driving
- `[Medium Energy]` – Steady, moderate
- `[Low Energy]` – Calm, relaxed
- `[Building Energy]` – Gradually increasing
- `[Explosive Energy]` – Sudden bursts

**Intensity Modifiers**

- `[Intense]` – Maximum power
- `[Gentle]` – Soft approach
- `[Powerful]` – Strong presence
- `[Subtle]` – Understated
- `[Dynamic]` – Varying levels

---

### 3.4 Instruments (Core)

Specify the instruments that drive your track.

**String Instruments**

- `[Electric Guitar]` – Modern, amplified
- `[Acoustic Guitar]` – Natural, organic
- `[Bass Guitar]` – Low-end foundation
- `[Violin]` – Classical elegance
- `[Cello]` – Deep, rich tones

**Percussion**

- `[Drums]` – Full drum kit
- `[Electronic Drums]` – Digital percussion
- `[Hand Percussion]` – Organic rhythms
- `[Timpani]` – Orchestral drums

**Keyboards & Synths**

- `[Piano]` – Classic acoustic
- `[Electric Piano]` – Vintage electric
- `[Synthesizer]` – Electronic sounds
- `[Organ]` – Church or Hammond
- `[Strings Section]` – Orchestral strings

**Wind Instruments**

- `[Saxophone]` – Jazz sophistication
- `[Trumpet]` – Bright, bold
- `[Flute]` – Light, airy
- `[Clarinet]` – Smooth, woody

---

### 3.5 Genre (Core)

Define the musical style and tradition.

**Popular Genres**

- `[Pop]` – Mainstream appeal
- `[Rock]` – Guitar-driven
- `[Hip-Hop]` – Urban, rhythmic
- `[Electronic]` – Digital soundscapes
- `[Jazz]` – Improvisation, swing
- `[Classical]` – Orchestral tradition
- `[Folk]` – Traditional, acoustic
- `[R&B]` – Rhythm and blues
- `[Country]` – American roots
- `[Reggae]` – Jamaican rhythm

**Electronic Subgenres**

- `[House]` – Four-on-the-floor
- `[Techno]` – Repetitive, mechanical
- `[Ambient]` – Atmospheric, textural
- `[Dubstep]` – Heavy bass drops
- `[Trance]` – Hypnotic, building

**Rock Subgenres**

- `[Alternative Rock]` – Non-mainstream rock
- `[Hard Rock]` – Heavy, distorted
- `[Indie Rock]` – Independent sound
- `[Progressive Rock]` – Complex structures

---

### 3.6 Vocal & Voice (Core)

Shape the vocal character and delivery.

**Vocal Styles**

- `[Male Vocals]` – Masculine voice
- `[Female Vocals]` – Feminine voice
- `[Harmonies]` – Multiple vocal parts
- `[Choir]` – Group vocals
- `[Whispered Vocals]` – Intimate delivery
- `[Powerful Vocals]` – Strong, belted
- `[Smooth Vocals]` – Silky delivery

**Vocal Techniques**

- `[Falsetto]` – High, breathy
- `[Vibrato]` – Voice tremolo
- `[Melismatic]` – Multi-note syllables
- `[Staccato Vocals]` – Short, detached
- `[Legato Vocals]` – Smooth, connected

**Voice Characters**

- `[Raspy Voice]` – Rough texture
- `[Clear Voice]` – Clean, pure
- `[Deep Voice]` – Low register
- `[High Voice]` – Upper register
- `[Soulful Voice]` – Emotional depth

---

## 4. Intermediate Categories

These add polish and control but are not required to start.

### 4.1 Production & Effects (Intermediate)

Professional audio processing and effects.

**Reverb & Space**

- `[Hall Reverb]` – Large space echo
- `[Room Reverb]` – Intimate space
- `[Plate Reverb]` – Vintage metallic
- `[Spring Reverb]` – Surf guitar classic
- `[No Reverb]` – Dry, close sound

**Delay & Echo**

- `[Echo]` – Distinct repetitions
- `[Delay]` – Time-based repetition
- `[Slapback Delay]` – Short, snappy
- `[Ping Pong Delay]` – Stereo bouncing

**Distortion & Saturation**

- `[Distortion]` – Heavy clipping
- `[Overdrive]` – Warm saturation
- `[Fuzz]` – Vintage distortion
- `[Clean]` – No distortion

**Modulation**

- `[Chorus]` – Pitch modulation
- `[Flanger]` – Sweeping effect
- `[Phaser]` – Phase shifting
- `[Tremolo]` – Amplitude modulation

---

### 4.2 Rhythm & Tempo (Intermediate)

Control timing, groove, and rhythmic feel.

**Tempo Markings**

- `[Slow Tempo]` – 60–80 BPM
- `[Medium Tempo]` – 90–120 BPM
- `[Fast Tempo]` – 130–180 BPM
- `[Very Fast]` – 180+ BPM

**Rhythmic Feels**

- `[Straight Feel]` – Even eighth notes
- `[Swing Feel]` – Uneven eighths
- `[Shuffle Feel]` – Triplet-based
- `[Latin Feel]` – Syncopated patterns

**Groove Types**

- `[Backbeat]` – Emphasis on 2 and 4
- `[Off-beat]` – Syncopated emphasis
- `[Polyrhythm]` – Multiple rhythms
- `[Cross-rhythm]` – Conflicting patterns

**Time Signatures**

- `[4/4 Time]` – Standard four beats
- `[3/4 Time]` – Waltz time
- `[6/8 Time]` – Compound duple
- `[5/4 Time]` – Odd meter

---

### 4.3 Sound Effects (Intermediate)

Add texture and atmosphere.

**Natural Sounds**

- `[Rain]` – Weather atmosphere
- `[Thunder]` – Dramatic impact
- `[Wind]` – Atmospheric movement
- `[Ocean Waves]` – Peaceful nature
- `[Fire Crackling]` – Warm ambiance

**Urban Sounds**

- `[Traffic]` – City atmosphere
- `[Footsteps]` – Human presence
- `[Doors]` – Transitional sounds
- `[Machinery]` – Industrial texture

**Musical Effects**

- `[Vinyl Crackle]` – Vintage texture
- `[Tape Hiss]` – Analog warmth
- `[Record Scratch]` – Hip-hop classic
- `[Reverse Reverb]` – Ethereal buildup
- `[Risers]` – Building tension
- `[Impacts]` – Dramatic punctuation

---

### 4.4 Musical Keys & Scales (Intermediate)

Specify tonality and scale systems.

**Major Keys**

- `[C Major]` – No sharps/flats
- `[G Major]` – One sharp
- `[D Major]` – Two sharps
- `[A Major]` – Three sharps
- `[E Major]` – Four sharps

**Minor Keys**

- `[A Minor]` – Natural minor
- `[E Minor]` – One sharp
- `[B Minor]` – Two sharps
- `[F# Minor]` – Three sharps

**Modes**

- `[Dorian Mode]` – Minor with raised 6th
- `[Mixolydian Mode]` – Major with lowered 7th
- `[Lydian Mode]` – Major with raised 4th
- `[Phrygian Mode]` – Minor with lowered 2nd

**Exotic Scales**

- `[Pentatonic Scale]` – Five-note scale
- `[Blues Scale]` – Pentatonic with blue note
- `[Chromatic Scale]` – All 12 notes
- `[Whole Tone Scale]` – Only whole steps

---

## 5. Advanced Categories

Use these when you want deeper musical control or professional-level nuance.

### 5.1 Chord Progressions & Harmony (Advanced)

Define harmonic movement and chord relationships.

**Classic Progressions**

- `[I-V-vi-IV]` – Pop progression (C–G–Am–F)
- `[vi-IV-I-V]` – Alternative pop (Am–F–C–G)
- `[I-vi-IV-V]` – 50s progression
- `[ii-V-I]` – Jazz standard
- `[I-VII-♭VI-♭VII]` – Rock progression

**Harmonic Qualities**

- `[Major Harmony]` – Bright, happy
- `[Minor Harmony]` – Dark, sad
- `[Modal Harmony]` – Ancient scales
- `[Jazz Harmony]` – Extended chords
- `[Dissonant Harmony]` – Tension, clash

**Advanced Harmony**

- `[Suspended Chords]` – Unresolved tension
- `[Extended Chords]` – 7ths, 9ths, 11ths
- `[Altered Chords]` – ♭5, #5, ♭9, #9
- `[Quartal Harmony]` – Built on fourths

---

### 5.2 Advanced Techniques (Advanced)

Professional production and writing techniques.

**Arrangement Techniques**

- `[Call and Response]` – Musical conversation
- `[Counterpoint]` – Independent melodies
- `[Layering]` – Multiple parts
- `[Unison]` – Same melody, multiple instruments
- `[Canon]` – Overlapping repetitions

**Dynamic Control**

- `[Crescendo]` – Gradually louder
- `[Diminuendo]` – Gradually softer
- `[Forte]` – Loud dynamic
- `[Piano]` – Soft dynamic
- `[Sforzando]` – Sudden accent

**Textural Techniques**

- `[Minimalist]` – Sparse, repetitive
- `[Maximalist]` – Dense, complex
- `[Monophonic]` – Single melody line
- `[Homophonic]` – Melody with accompaniment
- `[Polyphonic]` – Multiple independent melodies

**Creative Effects**

- `[Glitch]` – Digital artifacts
- `[Granular]` – Microscopic sampling
- `[Morphing]` – Gradual transformation
- `[Sidechaining]` – Rhythmic pumping

---

### 5.3 SunoAI Advanced Parameters (Advanced)

Fine-grained control beyond tags.

#### 5.3.1 Exclude Styles

**What it does:** Exclude specific elements you do not want in the track.

**Available for:** Pro and Premier users.

**Usage**

- In Style: `Pop, Female Vocal, Piano, Uplifting`
- In Exclude: `Male Vocal, Electric Guitar, Dark`

**Practical Uses**

Vocal control:
- Only female: Exclude `Male Vocal`
- Only male: Exclude `Female Vocal`
- Only rap: Exclude `Singing, Melodic Vocals`

Instrument control:
- Acoustic only: Exclude `Electronic, Synthesizer, Drum Machine`
- No piano: Exclude `Piano, Keyboard`
- Electronic only: Exclude `Acoustic Guitar, Acoustic Drums`

Genre control:
- Pure rock: Exclude `Electronic, Hip Hop, Pop`
- Only classical: Exclude `Modern, Electronic, Pop`

---

#### 5.3.2 Vocal Gender

**What it does:** Direct control of the main voice gender.

- Options: `Male` | `Female`

Example:
- Vocal Gender: `Female`
- Style tags: `Powerful Vocals, Soulful Vocals, R&B`

Result: Powerful female voice in R&B style.

---

#### 5.3.3 Weirdness Control

Controls how creative or strange the result can be.

- Range: `0% (Safe)` to `100% (Chaos)`
- 50% ≈ "normal"

**Weirdness vs Result**

| Goal                          | Weirdness Range | Effect                             |
| ----------------------------- | --------------: | ---------------------------------- |
| Safe, commercial, predictable |          10–30% | Follows tags closely, conventional |
| Balanced creativity (default) |          40–60% | Mix of control and surprise        |
| Experimental / avant-garde    |         70–100% | Unusual, unpredictable, abstract   |

Guidelines:
- Classic genres (Pop, Rock): `30–50%`
- Experimental (Ambient, IDM): `60–80%`
- Unusual fusions: `70–90%`
- Covers/tributes: `10–30%`

---

#### 5.3.4 Style Influence

Controls how strictly SunoAI should obey your style tags.

- Range: `0% (Loose)` to `100% (Strict)`

**Style Influence vs Result**

| Goal              | Style Influence | Effect                                 |
| ----------------- | --------------: | -------------------------------------- |
| Loose inspiration |          10–30% | Tags are suggestions; more freedom     |
| Balanced control  |          40–60% | Good mix of fidelity and variation     |
| Strict adherence  |         70–100% | Very close to tags and specified style |

Guidelines:
- Vague tags (Pop, Rock): `70–90%` for more control
- Very specific tags (e.g. Progressive djent metal): `40–60%`
- For experimentation: `20–40%`

---

#### 5.3.5 Advanced Parameter Quick Reference

| Goal                            | Weirdness | Style Influence | Typical Exclude                   |
| ------------------------------- | --------: | --------------: | --------------------------------- |
| Safe pop ballad                 |    20–40% |          70–90% | Aggressive, Screaming, Distortion |
| Faithful genre emulation        |    30–50% |         80–100% | Opposite genres                   |
| Experimental fusion             |    60–80% |          40–60% | Minimal or none                   |
| Glitchy futuristic EDM          |    70–90% |          50–70% | Acoustic, Organic                 |
| Clean acoustic songwriting demo |    10–30% |          60–80% | Electronic, Synth, Drum Machine   |

---

## 6. Combining Tags

How to combine tags for professional, controllable results.

### 6.1 Layering Approach

Think in layers.

**Base layer:**
Genre + main instrument + vocal type

```
Rock, Electric Guitar, Male Vocal
```

**Emotional layer:**
Mood + atmosphere + energy

```
Dark, Aggressive, High Energy
```

**Technical layer:**
Production + effects + arrangement

```
Raw Production, Reverb Heavy, Distortion
```

**Structural layer:**
`[Intro]`, `[Verse]`, `[Chorus]`, etc. in the lyrics

**Example combined prompt:**

Style:
```
Alternative rock, Dark, Aggressive, High Energy, Distorted Electric Guitar, Male Vocal, Raw Production, Reverb Heavy
```

Lyrics structure:
```
[Intro]
[Verse]
[Chorus]
[Verse]
[Chorus]
[Bridge]
[Chorus]
```

---

### 6.2 Dynamic Progression

Change tags by section to tell a story.

Example:
- `[Intro]`: Atmospheric, Mysterious, Clean Electric Guitar
- `[Verse]`: Introspective, Gentle, Acoustic Guitar
- `[Chorus]`: Energetic, Powerful, Distorted Electric Guitar
- `[Bridge]`: Dramatic, Cinematic, String Section
- `[Outro]`: Peaceful, Fade Out

Progressions:
- Ballad: Gentle → Building → Powerful → Emotional
- EDM: Ambient → Rising → Drop → Explosive
- Rock: Clean → Driven → Heavy → Epic

---

### 6.3 Creative Contrasts

Use opposites to create interest.

Examples:
- Gentle + Distorted Electric Guitar = Soft/hard contrast
- Electronic + Acoustic Drum Kit = Organic/digital fusion
- Dark + Uplifting = Bittersweet emotion
- Classical + Modern = Timeless vs current

Typical combinations:
- Soft/Hard: Whispered Vocals + Heavy Guitar
- Old/New: Vintage Production + Modern Sound Design
- Organic/Digital: Acoustic Guitar + Electronic Drums
- Simple/Complex: Minimalist verses + Orchestral choruses

---

## 7. Genre Templates

Copy, tweak, and use.

### 7.1 Pop Ballad

Style:
```
Pop, Emotional, Gentle, Building, Piano, String Section,
Female Vocal, Vulnerable Vocals, Reverb Heavy,
Hall Reverb, I-V-vi-IV, Major 7th, Clean Production
```

---

### 7.2 EDM Anthem

Style:
```
EDM, Progressive House, Energetic, Explosive, Anthemic,
Synth Lead, Synth Bass, TR-808, Electronic Drums,
Vocoder, Vocal Chops, Sidechain Compression,
Wall of Sound, Crowd Noise, Cheering
```

---

### 7.3 Indie Folk

Style:
```
Indie Folk, Peaceful, Contemplative, Organic,
Acoustic Guitar, Fingerpicking, Harmonica,
Male Vocal, Gentle Vocals, Natural Reverb,
Field Recording, Dorian Mode, Folk Progressions
```

---

### 7.4 Dark Electronic

Style:
```
Dark Electronic, Mysterious, Atmospheric, Synthesizer,
Minor Key, Reverb Heavy, Delay, Ambient Pads,
No Vocals, Cinematic, Tension, Building
```

---

## 8. Practical Examples

Concrete, fully specified prompts.

### 8.1 "Cosmic Echoes" (Psychedelic Rock)

Style:
```
Psychedelic Rock, Progressive Rock, Art Rock, Cinematic,
Mysterious, Atmospheric, Dreamy, Hypnotic, Epic, Dark,
Introspective, Electric Guitar, Lead Guitar, Synthesizer,
Hammond Organ, Male Vocal, Ethereal Vocals, Haunting Vocals,
Reverb Heavy, Delay, Echo, Phaser Effect, ii-V-I,
Modal Interchange, Dorian Harmony, Thunder, Wind,
Raw Production, Wall of Sound
```

Structure (lyrics):
```
[Intro - Ethereal, Hypnotic]
[Verse - Dark, Introspective]
[Chorus - Epic, Layered]
[Guitar Solo - Psychedelic, Intense]
[Chorus - Epic, Layered]
[Outro - Atmospheric, Fading]
```

**Why it works:**
- Clear psychedelic rock identity
- Deep mood layering
- Specific vintage instruments and effects
- Modal and advanced harmony for sophistication

---

### 8.2 "Digital Pulse" (EDM)

Style:
```
EDM, Progressive House, Trance, Electro House, Energetic,
Intense, Driving, Explosive, Synthesizer, Synth Lead,
TR-808, Electronic Drums, Vocoder, Autotuned Vocals,
Sidechain Compression, Low-Pass Filter Sweep, Wall of Sound,
Wide Stereo Image, Crowd Noise, Cheering, I-V-vi-IV
```

Structure (lyrics):
```
[Build-up] High-Pass Filter Sweep, Tension, Rising
[Drop] Explosive, Synth Lead, Heavy Compression, Maximum Impact
[Breakdown] Low-Pass Filter Sweep, Silence
[Second Drop] Full Wall of Sound, Crowd Cheering
```

**Advanced parameters:**
- Vocal Gender: Female (for vocal chops)
- Weirdness: 40%
- Style Influence: 80%
- Exclude: `Acoustic, Slow Tempo, Sad`

---

### 8.3 "Cyber Sushi" (Futuristic EDM)

Style:
```
EDM, Futuristic, Glitchy, Electronic, Robotic Voice,
Vocoder, Vocal Chops, Bitcrushing, Glitch Effects,
Stutter Edits, Synthesizer, Electronic Drums,
Euphoric, Anthemic, Modern Production, Creative Panning
```

Structure (lyrics):
```
[Intro] Robotic Voice, Glitch, Futuristic
[Verse] Minimal, Glitchy, Building Tension
[Pre-Drop] Stutter Edits, Rising, Anticipation
[Drop] Euphoric, Vocal Chops, Maximum Glitch
[Outro] Futuristic, Dissolving, Digital Decay
```

**Advanced parameters:**
- Weirdness: 65%
- Style Influence: 60%
- Exclude: `Acoustic, Traditional, Organic`

---

## 9. Workflow, Tag Placement, and Troubleshooting

### 9.1 Recommended Workflow

1. Start with genre and mood
2. Add key instruments and vocal style
3. Define structure in the lyrics using `[Intro]`, `[Verse]`, `[Chorus]` tags
4. Add production and effects (reverb, delay, distortion, etc.)
5. Set advanced parameters (Weirdness, Style Influence, Exclude, Vocal Gender)
6. Generate, listen, adjust, and iterate

---

### 9.2 Tag Placement Strategy

**Lyrics field:**
- Structural tags: `[Intro]`, `[Verse]`, `[Chorus]`, `[Bridge]`
- Optional mood/energy tags per section (e.g. `[Chorus | High Energy | Anthemic]`)

**Style field:**
- Descriptive tags without brackets
- Priority: Genre → Mood → Lead instrument → Vocal style → Production → Atmosphere

**Target:**
- 3–5 core tags for simple songs
- 5–10 for detailed control
- 5–8 tags per section if tagging inside lyrics

---

### 9.3 Troubleshooting Cheat Sheet

**Problem: Too melodic or too soft**

- Add: `[Aggressive]`, `[Intense]`, `[High Energy]`, `[Distortion]`, `[Powerful Vocals]`
- Increase: Style Influence (closer to 70–90%)
- Decrease: Weirdness slightly if it keeps getting pretty instead of heavy
- Exclude: `Soft, Gentle, Acoustic, Ballad` if needed

---

**Problem: Too chaotic or unfocused**

- Reduce Weirdness to 20–40%
- Remove conflicting tags (e.g. `[Calm]` and `[Aggressive]` together)
- Simplify:
  - One main genre
  - One dominant mood
  - 1–2 lead instruments

---

**Problem: Vocals not what you want**

- Set Vocal Gender: `Male` or `Female`
- Use Exclude:
  - To avoid female: `Female Vocal, Female Vocals`
  - To avoid male: `Male Vocal, Male Vocals`
- Be explicit in style:
  - `Spoken word, Rap, Screamed Vocals, Whispered Vocals`

---

**Problem: Too electronic**

- Exclude: `Electronic, Synth, Drum Machine, Electronic Drums`
- Add: `Acoustic Guitar, Acoustic Drums, Natural Reverb, Organic`

**Problem: Too acoustic**

- Exclude: `Acoustic Guitar, Acoustic Drums`
- Add: `Synthesizer, Electronic Drums, Drum Machine, Modern Production`

---

### 9.4 Common Mistakes to Avoid

- **Too many tags:** Overloading confuses the model; keep it focused.
- **Contradictory tags:** Avoid simultaneous `[Calm]` and `[Aggressive]` unless you truly want complex contrast and you know how to control it.
- **Vague descriptions:** Prefer specific instruments and qualities:
  - `Distorted Electric Guitar` > `Guitar`
  - `Smooth Soulful Female Vocals` > `Vocals`
- **Ignoring structure:** Always define at least `[Intro]`, `[Verse]`, `[Chorus]` in the lyrics.

---

## 10. Ultimate Success Formula and Pro Tips

### 10.1 Success Formula

Base pattern:
```
BASE GENRE + DOMINANT MOOD + LEAD INSTRUMENT + VOCAL STYLE +
ATMOSPHERE + PRODUCTION + STRUCTURE + PERSONAL TOUCH
= TARGET TRACK
```

Example:
```
Alternative Rock + Melancholic + Distorted Electric Guitar + Male Vocals +
Dark Atmosphere + Raw Production + Verse/Chorus/Bridge Structure +
Personal lyrical concept = Emotional rock anthem
```

---

### 10.2 Professional Formula (Parameters + Tags)

1. Define precise meta tags (aim for 15–20 if you want high control).
2. Set Style Influence high (70–80%) when you want fidelity.
3. Add Weirdness (40–60%) for creativity without losing structure.
4. Use Exclude Styles to remove unwanted genres, instruments, or vocal types.
5. Test: run 2–3 variations changing only Weirdness and Style Influence.

---

### 10.3 Pro Tips

- **Less is more:** 3–5 tags per section is often better than 20.
- **Be specific:** `Electric Guitar Distortion` is more useful than `Guitar`.
- **Test variations:** Change one thing at a time (Weirdness, Style Influence, or a small tag group).
- **Study successes:** When a song comes out great, save its tags and parameters as a template.
- **Balance energy:** Use calmer tags in verses and more intense tags in choruses for a clear arc.
- **Contrast:** Intelligent contrast (soft vs heavy, electronic vs acoustic) makes tracks memorable.

---

Remember: clear vision plus precise tagging and parameter control is what turns SunoAI from a random generator into a professional production tool.
