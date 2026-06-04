The base layer is the one thing we refuse to ship at "good enough." It is the canvas every other layer registers against, so its quality caps the quality of every outfit ever rendered on it.

**Settled**{.badge .settled} · The goal is "person in a showroom" — clean background, even lighting, consistent pose and framing.

Not a generative fantasy of the person — *the actual person*, cleaned up to studio conditions. Removed background, corrected lighting, a neutral backdrop, predictable framing. The result should read like a lookbook plate, not a selfie.

**Leaning**{.badge .leaning} · Several systems chain to produce one trusted base, not a single model call.

We treat base creation as a small pipeline — background removal, then cleanup and relighting, then pose/framing normalization, then a quality gate — rather than one magic step. Each stage is swappable, and a base only graduates if it passes the gate. Where the stages run and which engines fill them is an [open question](#open).

**Leaning**{.badge .leaning} · A base that fails the gate is rejected, not patched downstream.

Bad canvas in, bad outfit out — forever, across every combination. Cheaper to re-shoot or re-process the base than to fight artifacts in every overlay. The gate is the contract: nothing composites onto an un-graduated base.

**Open**{.badge .open} · How much of the base must be the literal person vs. an idealized stand-in.

Showroom lighting is clearly in scope. Reshaping the body, smoothing skin, "improving" the person — that's a line we haven't drawn yet. It touches trust, identity, and how the result feels. Flagged, not decided.
