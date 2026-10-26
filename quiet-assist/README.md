# Quiet Assist

Quiet Assist is a passenger-safety and dignity concept built as a Microsoft internal hackathon submission. It provides a discreet digital path for passengers to ask for help without drawing attention in the cabin.

## Project idea narrative

### The problem it addresses

Passengers do not always feel comfortable raising a hand or verbally describing sensitive concerns where nearby travelers can hear. That can delay assistance in situations involving anxiety, unwanted interaction, discomfort, or language barriers.

### Proposed experience

Quiet Assist gives passengers a private flow with urgency-aware choices:

1. **I Need Help Now** for immediate support.
2. **Speak Privately** for sensitive crew conversation.
3. **When Convenient** for routine comfort/service needs.

The crew side demonstrates operational triage with a request queue, lit seat map, status handling (accept/acknowledge/resolve), and translation controls so crews can read requests in a preferred language. The prototype also highlights escalation behavior reminding passengers to use physical call systems for urgent needs.

### Why it matters

For passengers, the concept increases psychological safety and lowers the barrier to asking for help.  
For crew, it improves prioritization and reduces ambiguity by standardizing request context, urgency, and handling flow.

### Hackathon demo scope

This prototype simulates private passenger submission, crew orchestration, and language-translation UX patterns. It focuses on experience and operational clarity, not production integrations such as airline identity systems, policy engines, or device fleet rollout.

![Quiet Assist screenshot](./quiet-assist-screenshot.png)

## Rendering instructions

1. Download or clone this repo to a local folder.
2. Open PowerShell in the repo root.
3. Run `python -m http.server 8080`.
4. Open `http://localhost:8080/quiet-assist/quiet-assist-prototype.html`.
