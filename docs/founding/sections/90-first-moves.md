Phase 1 is exploration, not construction. We're proving the layer model is real and finding the engines that can serve it — by hand, on real photos, before any of it is automated.

1. **Collect photos by hand.** Gather real base shots and OOTD pictures — varied people, lighting, poses, and garment types. The goal is a corpus honest enough to break naive approaches, not a polished demo set.

2. **Cut the layers manually.** Separate a handful of looks into the real parts by hand — base, garments with their wear variants, front/back hair, face. Re-stack them into outfits that weren't originally photographed. If hand-composited layers don't read as a believable worn outfit, the whole model is wrong and we want to know now.

3. **Audition engines for each role.** Try different tools against the base-pipeline roles — background removal, cleanup and relighting, pose/framing normalization — and against the overlay registration. Judge them on the corpus, not on cherry-picked inputs. Output is a ranked read on what each role needs, not a committed stack.

4. **Find where the model bends.** Note every place a real photo resists the back-hair · base · garments · front-hair · face order — accessories, layering depth, registration drift. These become the next round's [open questions](#open).

What Phase 1 deliberately leaves out: app, automation, scale. We learn whether the layered closet holds up before we build anything to produce it.
