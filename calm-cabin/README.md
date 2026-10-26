# Calm Cabin

Calm Cabin is a seatback wellness concept created for a Microsoft internal hackathon submission. The idea is to turn the in-flight entertainment screen into a supportive comfort companion for passengers who may be anxious, overstimulated, tired, or simply looking for a calmer cabin experience.

## Project idea narrative

### The problem it addresses

Traditional seatback systems are optimized for broad entertainment catalogs, but they do not always help passengers quickly manage in-flight stress, sensory overload, or rest. In real cabin conditions, people need low-friction choices they can access in seconds, not a deep browsing journey.

### Proposed experience

Calm Cabin organizes choices around intent rather than content categories:

1. **Help Me Relax** for breathing and guided calm sessions.
2. **Distract Me** for light, attention-shifting content.
3. **Somewhere Peaceful** for scenic visual escapes.
4. **Help Me Rest** for sleep-friendly ambient options.

The prototype also demonstrates practical cabin controls such as service preference alignment (for example do-not-disturb style behavior), announcement-aware playback interruptions, and compact seatback-friendly controls that prioritize glanceability and fast recovery.

### Why it matters

For passengers, this can reduce friction in moments of discomfort and improve perceived care.  
For airlines, it offers a differentiated wellbeing feature that can improve satisfaction scores and support brand positioning around thoughtful onboard experience.

### Hackathon demo scope

This prototype simulates mode-based content selection, controlled playback, and cabin-safe interactions in a constrained seatback viewport. It is intended as an experience prototype rather than a production-ready integrated IFE backend.

![Calm Cabin screenshot](./calm-cabin-screenshot.png)

## Rendering instructions

1. Download or clone this repo to a local folder.
2. Open PowerShell in the repo root.
3. Run `python -m http.server 8080`.
4. Open `http://localhost:8080/calm-cabin/calm-cabin-prototype.html`.
