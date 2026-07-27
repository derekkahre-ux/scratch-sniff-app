# 🧪 Project Synaesthesia
> **Crossmodal Digital Scent & Olfactory Memory Simulation Engine**

[![Status](https://img.shields.io/badge/Status-Concept%2FPrototype-indigo.svg)](#)
[![Stack](https://img.shields.io/badge/Stack-WebGL%20%7C%20Web%20Audio%20%7C%20Haptics-blue.svg)](#)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](#)

While mobile hardware cannot emit volatile organic compounds or aromas, **Project Synaesthesia** uses **crossmodal perception**—the neurological phenomenon where aligned inputs from vision, touch, and sound trick the human brain into experiencing an olfactory memory response (*the Proustian effect*).

---

## 📐 Core Architecture & Sensory Pillars

Synaesthesia relies on four synchronized sensory triggers operating at the exact moment of user contact:

Here is a brief, warm, and transparent disclaimer you can use directly on your onboarding screen or inside the app's settings.

Onboarding Screen Copy
Welcome to Synaesthesia 🌿
How an illusion comes to life.

A Quick Note Before We Begin

Synaesthesia is an interactive sensory experiment. Since mobile screens can’t emit physical scents, this app uses a carefully timed mix of haptic textures, 3D spatial audio, and visual physics to trigger your brain’s natural scent memories (crossmodal perception).

You’re in full control: If the vibrations or audio feel too intense at any point, you can adjust or pause sensory feedback anytime in Settings.

Sensory Safety: This app guides gentle breathing rhythms for immersion, but it is not intended as medical or relaxation therapy.

Tap below when you’re ready to test your sensory perception!

Key Design Tips for the Onboarding UI
Acknowledge the Illusion Front and Center: Using phrases like "interactive sensory experiment" or "sensory illusion" builds trust immediately. Users love feeling like they are part of a cool tech experiment rather than being tricked.

Include an Opt-Out / Quick Mute Toggle: Place a small gear or sound/haptic icon directly on the onboarding screen so users sensitive to strong vibrations or binaural audio know they can scale it back right away.

No Medical Claims: Keep the language focused on "curiosity," "memory," and "perception" rather than "wellness," "healing," or "anxiety relief."

Designing accessibility options for a multisensory illusion requires shifting from **sensory convergence** (where sight, sound, and touch all must align to trick the brain) to **sensory translation**—where missing channels are intelligently mapped to the senses the user *does* rely on.

Here is how you can adapt the experience for different accessibility needs while keeping the core magic of sensory exploration intact.

---

## 1. Adaptations for Deaf or Hard-of-Hearing Users

For deaf users, spatial ASMR audio (such as the microscopic *snap* of citrus zest or the dry *crinkle* of pine) is unavailable. The experience must map those acoustic cues into rich visual and haptic feedback.

* **Sub-Bass Haptic Layering:** Standard haptics handle texture (surface friction). For deaf users, enable a secondary "acoustic haptic" track using low-frequency impulses that translate sound waves (like the sizzle of an oil sac popping) directly into tactile beats.
* **Visual Sound-Wave Oscillations:** Render micro-ripples or subtle light pulses at the exact point of touch that expand in synch with the haptic friction, mimicking acoustic frequency waves.
* **Closed-Captioning for Sensory Cues:** Include subtle, poetic visual descriptors during the inhale prompt (e.g., *[Soft sizzle of fresh zest]*, *[Dry, earthy crinkle]*).

---

## 2. Adaptations for Blind or Low-Vision Users

When visual cues (like particle mists and surface shaders) are unavailable, the spatial audio and tactile feedback must bear the full weight of the experience.

* **Enhanced Spatial Audio Panning:** Use dynamic binaural 3D audio that tracks the user’s finger in real time across a 360-degree virtual stage, giving precise spatial feedback about where the "texture" is being scratched.
* **VoiceOver & TalkBack Tactile Mapping:** Provide screen-reader-friendly audio descriptions that prime the user's mind *before* touch (e.g., "Bergamot card loaded. Focus zone is located in the upper center of the screen.").
* **Tactile Boundaries (Haptic Walls):** Use sharp, distinct haptic pulses to define the edges of the interactive "scratch zone" so low-vision users know exactly where the active canvas starts and ends without needing visual borders.

---

## 3. Adaptations for Low Haptic Sensitivity

Some users have reduced nerve sensitivity in their fingertips due to neuropathy, age, or medical conditions, or they may be using devices with weaker vibration motors.

* **Haptic Gain & Frequency Boost:** Offer a "High-Contrast Haptics" toggle in Settings that amplifies the motor’s amplitude and lowers the vibration frequency to create heavier, more distinct physical thumps rather than delicate micro-pulses.
* **Thermal Visual Reinforcement:** Compensate for muted touch by exaggerating visual temperature cues. Expanding warm orange/amber glow fields (for spices/coffee) or frosty blue light trails (for mint) help the visual cortex compensate for lower tactile feedback.
* **Audio-Assisted Friction:** Scale up the volume and bass resonance of the ASMR audio track dynamically as finger pressure/speed increases, substituting auditory depth for missing tactile depth.

---

## 4. The "Sensory Matrix" Settings UI

Rather than hiding these in standard menus, present accessibility as a **Sensory Profile Customizer** during onboarding:

```
┌────────────────────────────────────────────────────────┐
│               SENSORY PROFILE CUSTOMIZER               │
├────────────────────────────────────────────────────────┤
│ Vision Boost   [ Off ]  ──►  Amplifies Audio & Haptics │
│ Audio Sync     [ On  ]  ──►  Visual Soundwaves Active  │
│ Haptic Force   [ ===|===== ] 150% Amplified            │
│ Inhale Assist  [ On  ]  ──►  Visual & Haptic Pacing    │
└────────────────────────────────────────────────────────┘

```

This allows users to dial in whichever combination of senses works best for their body, making the app an inclusive playground for crossmodal perception.

---
