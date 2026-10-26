# Flight Highlights

Flight Highlights is an engagement-focused concept submission for a Microsoft internal hackathon. It reimagines exterior aircraft camera viewing as a narrative travel experience rather than a passive single camera feed.

## Project idea narrative

### The problem it addresses

Many passengers miss scenic moments because of seat position, timing, closed shades, or simply looking away at the wrong time. Traditional map views do not help users revisit what they missed or understand what is worth watching next.

### Proposed experience

Flight Highlights combines camera selection, route context, and replay cues:

1. Switch between multiple camera perspectives (forward, wing views, down/gear-style angles).
2. Use timeline pin drops to revisit moments from earlier in the flight.
3. See what is upcoming through route-aware highlight indicators.
4. Enable notifications for interesting moments and major landmarks.
5. Generate a post-flight summary/caption flow for sharing.

The prototype also demonstrates operational controls such as simulated crew advisories and temporary camera blackouts.

### Why it matters

For passengers, this creates a richer “window seat from any seat” experience.  
For airlines, it introduces new engagement, memory-making, and optional social amplification opportunities tied to the journey itself.

### Hackathon demo scope

This prototype focuses on interaction model and storytelling: timeline, pin-based replay, camera switching, and summary/share flows. It is a concept demonstration and not a production content-rights or fleet-camera integration implementation.

![Flight Highlights screenshot](./flight-highlights-screenshot.png)

## Rendering instructions

1. Download or clone this repo to a local folder.
2. Open PowerShell in the repo root.
3. Run `python -m http.server 8080`.
4. Open `http://localhost:8080/flight-highlights/flight-highlights-prototype.html`.
