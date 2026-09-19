# CH-017 — Same Count, Same Time — Detailed Scene Architecture v2

**POV:** MAX ONLY  
**Opening:** K2 / R1 / narrow P1 capability / local geometry unstable / C0 / X0  
**Gate 8:** PASS — QA-LOCKED

# Function
Build and test a stabilization protocol using only previously learned timing/state rules.

# Stabilization Principle
Do not strengthen the connection.

Instead:
- return furniture/reference objects to known baseline positions;
- keep Lily's key and Max's compass out of the active alignment except as passive references;
- use the writing patch/taps to measure current lag;
- act only during the lowest observed delay window;
- make the same simple state change on the same count.

# Test
Question:
Can coordinated timing reduce the geometry mismatch without increasing coherence?

Prediction:
If the rooms are misaligned partly because their local state changes are arriving at different times, synchronized baseline actions should reduce the offset.

Observation:
- severe lag varies;
- they wait for a shorter stable interval;
- on matched count, both return mirror/receiver orientation toward neutral and stop all active manipulation;
- false doorway shifts closer to physical frame;
- duplicate message arrivals decrease;
- geometry improves but does not fully reset.

Result:
Coordinated timing helps.

It is not enough by itself.

# Scenes
1. Max reviews old timing notes and rejects stronger correction.
2. Lily/Max establish baseline positions and measure current lag.
3. They execute one synchronized neutral-state correction.
4. Wrong doorway contracts toward normal; they design final CH-018 shutdown: release active anchors on the same count.

# Limits
No new power.
No P2/P3.
No C1/X1.
No Hollow.
No pre-echo.
No new F-ID.
No MT reveal.

# End
They now know what to do:
**let go on the same count.**
