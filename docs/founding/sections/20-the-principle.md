Guarantee the canvas, then composite cheap layers on top of it.

**Settled**{.badge .settled} · A great base layer is non-negotiable; everything else is a layer stacked on it.

We spend our quality budget on one thing: a base image that looks like the person is standing in a clean showroom with proper lighting and a removed background. Get that right and the rest of the system is just ordered overlays.

**Leaning**{.badge .leaning} · Overlays start dumb on purpose — a simple pixel overlay per layer.

The first version of "putting a garment on the body" is a registered pixel overlay on its own layer, not a physics sim and not a generative re-render. Dumb-but-consistent beats clever-but-flickery. We earn the right to get fancy later, per layer, where it visibly pays off.

**Settled**{.badge .settled} · Layers have a fixed compositing order, and that order is the product.

Back hair, then the body, then the garment stack, then front hair, then the face look. Knowing what goes in front of what — and letting any layer be swapped without touching the others — is the whole trick.
