# 🌍 GeoAR.it — A Human-Centred Spatial Platform

GeoAR.it is a deeply personal, human-first platform built to help people navigate the real world with clarity, context, and emotional support. It blends **geospatial awareness**, **augmented reality**, and **AI companionship** into a gentle, meaningful digital layer designed to sit alongside everyday life — not replace it.

At its heart, GeoAR.it is about **people**:  
what they feel, where they are, and how technology can quietly help rather than overwhelm.

---

## 💠 What GeoAR.it Is

GeoAR.it is the foundation layer of the **MetARverse** — a world where:

- places have meaning,  
- memories attach to locations,  
- AI understands context rather than guessing,  
- and the digital world complements real life.

It provides:

- A **real-time digital twin** of the UK  
- **Hyperlocal awareness** (what’s around you right now)  
- **Anchors** for venues, hotspots, objects, memories, and interactions  
- A structured, meaningful data layer for AI agents to understand human experience  

Everything begins with the platform’s simple building blocks:

**Venue → Hotspot → Hotspot Properties → Prefab**  
Each one is an anchor point in the real world that the AI and AR layers can attach meaning to.

---

## 🧞 Geordie Genie — Your Companion in the MetARverse

Geordie Genie represents the human side of the platform:  
a warm, local, emotionally intelligent character who helps guide the user through their surroundings with humour, empathy, and awareness.

He is the bridge between:

- the real world,  
- the digital twin, and  
- the user’s emotional state.

He can remember things for you, keep you safe, point you towards meaningful places, and help encode your experiences using the **MetARverse Semantic Event Protocol**.

---

## 🧬 The MetARverse (Semantic Life Layer)

The **MetARverse** is not a game world.  
It’s a **semantic layer of human experience** — a structure where:

- feelings  
- events  
- memories  
- preferences  
- interactions  
- and locations  

are encoded in a standardised, machine-readable way so an AI agent can develop *real* understanding rather than hallucinations.

The MetARverse lets a user say:

- “This place makes me feel calm.”  
- “I’m scared of deep water.”  
- “My happy memory happened right here.”  

And the system remembers — respectfully, privately, meaningfully.

This is **not another Uncanny Valley platform**.  
This is technology built around *human truth*.

---

## 🗺️ Core Spatial Entities

Below is a simple high-level relationship diagram showing the four key pillars of the GeoAR.it spatial layer:

- **Venue** — A real-world location (pub, park, shop, station).  
- **Hotspot** — A point or object placed within or near a venue.  
- **Hotspot Properties** — Metadata that describes a hotspot’s behaviour, type, or attributes.  
- **Prefab** — A 3D/AR asset associated with a hotspot (e.g., line navigation arrow, portal, sign, object).

---

## 🧩 Venue / Hotspot / Properties / Prefab relationship

```mermaid
flowchart TD

    %% Nodes
    VENUE["VENUE"]
    HOTSPOT["HOTSPOT"]
    HOTSPOTPROPERTY["HOTSPOT PROPERTIES"]
    PREFAB["PREFAB"]

    %% Vertical Layout
    VENUE --> HOTSPOT
    HOTSPOT --> HOTSPOTPROPERTY
    HOTSPOT --> PREFAB

    %% Clickable Links
    click VENUE "https://geoar.it/help#category-Venue-Properties" "View Venue Properties"
    click HOTSPOTPROPERTY "https://geoar.it/help#category-Hotspot-Properties" "View Hotspot Properties"
    click PREFAB "https://geoar.it/help#category-Prefab-Properties" "View Prefab Properties"

```
