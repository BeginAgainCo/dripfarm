Everything above the base is a stack of layers with a fixed front-to-back order. Swapping any one layer leaves the others untouched — that independence is what makes infinite outfits cheap.

**Settled**{.badge .settled} · The compositing order, back to front:

| Order | Layer | Notes |
|---|---|---|
| 1 | **Back hair** | The part of the hairstyle that falls *behind* the body and clothes. |
| 2 | **Base (the person)** | The showroom-grade canvas. Always exactly one. |
| 3 | **Garment stack** | One or more garments, each rendered in a chosen wear variant, ordered base-to-outer (tee under jacket under coat). |
| 4 | **Front hair** | The part of the hairstyle that falls *in front* — bangs, hair over the shoulder. |
| 5 | **Face / makeup** | The switchable look applied to the face region. |

**Settled**{.badge .settled} · Hair is two layers, not one — front and back bracket the garment stack.

Long hair down the back sits *behind* a top; hair swept over the shoulder sits *in front* of it. A hairstyle is therefore a pair — a back piece and a front piece — and the garment stack lives between them. This is the detail that makes hung-on outfits read as real instead of pasted-on.

**Leaning**{.badge .leaning} · The garment stack is an ordered list, and depth is unbounded.

Tee, then shirt, then jacket, then coat — many layers, ordered inner-to-outer. We don't cap the count. Each garment carries its chosen wear variant, so the same piece can read differently depending on how it's worn within the stack.

**Leaning**{.badge .leaning} · A garment owns its wear variants; the stack just picks one per garment.

Each garment is "an array of possible ways it is worn." Styling = choose garments, order them, and pick a variant for each. The variant is part of the garment's model, not a separate edit step.

**Open**{.badge .open} · Face is one layer now; it may need to split like hair did.

Makeup sits cleanly on the face region today. Glasses, earrings, and other face-adjacent accessories may not — some belong in front of hair, some behind. We're modeling face as a single layer until something forces the split, the same way hair forced front/back.
