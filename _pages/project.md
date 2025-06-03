---
layout: archive
title: "Computational Projects"
permalink: /project/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Real-Time Black Hole Ray Tracing Simulation (OpenGL)

*Duration: Oct 2023 – Present*

Developed a real-time ray tracer that visualizes photon dynamics in Schwarzschild spacetime. The program integrates null geodesics with a fourth-order Runge–Kutta scheme and renders gravitational lensing, photon rings, and event horizons at interactive frame rates.

### Contributions
- Designed and implemented the C++/GLSL rendering pipeline.
- Stabilized the integrator with adaptive step sizing and error control, eliminating artefacts near the photon sphere.
- Added handling of radial turning points and conserved quantities (e.g., signed angular momentum) to classify photon orbits (capture vs. escape).
- Planned extensions to Kerr metrics and accretion-disk radiative transfer.

![Black hole rendering](/images/blackhole.jpg)

---

## Ray-Tracing Model Extension

*Duration: Apr 2022 – Jul 2022*

Extended the learning project "Ray Tracing in One Weekend" with physically based shading and acceleration structures.

### Contributions
- Integrated microfacet BRDFs (GGX, Cook–Torrance) for realistic light–material interaction.
- Implemented a bounding-volume hierarchy (BVH) to reduce render time while preserving image quality.

![Ray tracing sample](/images/2.png)

