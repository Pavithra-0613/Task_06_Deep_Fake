# Task 06 – Deep Fake (“Street Interview” with SU Coach)  
**Author:** Pavithra Ramasamy Pattuselvam  
**Repo:** https://github.com/Pavithra-0613/Task_06_Deep_Fake  

## What this is  
A short, **audience-facing “street interview”** where an SU student bumps into the Syracuse Women’s Lacrosse coach in NYC and asks four quick questions about last season and next steps. The answers reflect my Task 05 findings (Carney = top scorer, Ward = top playmaker, Adamson = possession engine, Goodale = defensive catalyst).  

> **Assignment fit:** Task 6 asks us to transform our narrative into an **AI-generated “deep fake” interview**, preferably “street interview” style. Audio or video is acceptable; the **process documentation** is the priority. I used free tools and focused on a clean workflow.  

---

## Files  
- `interview_script.txt` – the full Q&A (same as below)  
- `final_mix_stereo.mp3` – **final stitched stereo audio** (Student voice panned left, Coach voice panned right, intro centered)  
- `audio/` – *(optional)* folder for raw or intermediate clips  

---

## Street Interview Script (final)  
*(Scene: A Syracuse student is strolling around New York City in the summer and unexpectedly bumps into the Syracuse Women’s Lacrosse coach. They decide to do a quick street-style Q&A.)*  

**Student:** “Coach! What a surprise running into you here in New York. Mind if I ask you a couple of quick questions about last season?”  
**Coach:** “Of course, fire away.”  

**Student:** “First off, who was your go-to scorer this season?”  
**Coach:** “That would be Megan Carney. She had an incredible year and was the player we relied on when we needed goals.”  

**Student:** “And who was the best at setting up those plays?”  
**Coach:** “Emma Ward. She has amazing vision and was constantly finding her teammates in scoring positions.”  

**Student:** “Every team needs someone to do the gritty work — who was that player for you?”  
**Coach:** “Olivia Adamson. She hustled nonstop, winning draws and scooping up loose balls to keep us in control.”  

**Student:** “Looking ahead, what’s the one focus for next season?”  
**Coach:** “We want to tighten up our defense. Katie Goodale is a key part of that — she shuts opponents down and makes those clutch defensive plays that change games.”  

---

## Tools I tried (all free)  
- **Text-to-Speech (TTS):** generated two voices (Student + Coach) with a free online TTS tool.  
- **Audio editing:** used **Audacity** to arrange clips, pan left/right, normalize, and export the final stereo MP3.  
- **(Optional) Video avatar:** not required for this task.  

---

## Workflow (what I did)  
1. **Script drafting** – Wrote a 4-Q street interview in casual, audience-first language based on Task 05 findings.  
2. **Voice generation** – Generated two voices (Student + Coach) with a free TTS. Exported short MP3s line by line.  
3. **Mixing** – Imported Student/Coach clips into Audacity, arranged them in sequence, panned **Student left** and **Coach right**, normalized audio, and exported `final_mix_stereo.mp3`.  
4. **Documentation** – Captured the above steps, tool names/settings, and challenges below.  

---

## Challenges & what I learned  
- **Free limits:** Some TTS tools capped characters/exports; I had to keep lines short and export in pieces.  
- **Voice clarity:** Slight pauses between lines helped the Q&A feel natural.  
- **Street vibe:** Light intro + short, plain-language questions kept it audience-friendly.  

---

## Ethics note  
This is an **academic deep-fake style** demo using **AI voices**, not impersonating a real individual’s exact voice. No real person’s face or voice was used or claimed; this is clearly labeled research.  

---

## How to reproduce  
1. Copy `interview_script.txt`.  
2. Use any free TTS to export Student and Coach voices as MP3s.  
3. Import into **Audacity**, arrange Student → Coach → Student → Coach.  
4. Pan Student left, Coach right, normalize audio.  
5. Export to `final_mix_stereo.mp3`.  

---

## Final Output  
The final deliverable is **`final_mix_stereo.mp3`** (in the repo root).  
It is a polished stereo interview: **Student on the left channel, Coach on the right channel, and intro centered.**  
