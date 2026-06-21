## Research questions

Voxel generation: Which physical mechanism(s) can reliably and repeatably produce visible, localized voxels in free air at luminance and lifetime compatible with human-perception-based display requirements, while minimizing safety risks and material byproducts?

Dynamic positioning and synthesis: How can individual voxels be moved or re-generated in space with sufficient spatio-temporal resolution and accuracy to synthesize continuous perceptual constructs (trajectories, 2D surfaces, and 3D volumes) within the target workspace?

Throughput and perceptual persistence: What voxel generation rate, dwell time, and motion trajectories are required to achieve temporally continuous perception (including color and brightness fidelity) for typical human visual persistence, and how do these metrics trade off against optical source constraints (pulse energy, repetition rate) and actuator bandwidth?

System-level integration and constraints: What beam-steering, focus-control, or trapping architectures (e.g., AODs, galvanometer mirrors + varifocal optics, phased ultrasound arrays, particle-delivery systems) provide the required spatial bandwidth and reliability within the 50 cm workspace, given constraints on thermal loading, power consumption, and electromagnetic/optical safety?

Environmental and operational robustness: How do ambient conditions (air currents, particulates, humidity), particle lifetime (for trapping-based methods), and medium management (for doped-mist or dye approaches) affect voxel stability and display longevity in practical indoor environments?

Scope and hypotheses

Hypothesis 1: Point-wise laser-induced ionization (laser-induced plasma) can generate sufficiently bright voxels for mid-air display at sub-millimeter localization, but achieving perceptual frame rates across a densely populated 50 cm volume will require laser sources and beam-steering subsystems operating at >10^4 addressable points per second and careful thermal and safety engineering.

Hypothesis 2: Photophoretic or acoustophoresis-based moving-scatterer approaches can reduce peak optical intensity and safety risk while enabling persistent voxels by motion-based persistence, provided a controllable micro-environment minimizes convective disturbances and supports particle provisioning.

Hypothesis 3: Two-photon excitation in a controlled, transparent doped medium permits superior spatial confinement and reduced stray illumination at voxel intersections, but the need for seeded media and high-peak-power femtosecond sources imposes logistical and safety trade-offs that limit practical deployment in general indoor environments.

Metric-driven goals

Spatial resolution: Demonstrate voxel localization uncertainty ≤ 1 mm (standard deviation) in X, Y, and Z across the workspace.

Temporal throughput: Achieve effective perceptual voxel throughput sufficient to render continuous lines and surfaces; target addressable-point rates ≥ 10^4 s^-1 for fast-moving voxels, or equivalent perceived continuity using persistence-by-motion (particle translation velocities and illumination timing).

Luminance and contrast: Produce voxels with peak luminous intensity and duration sufficient to be visible under typical indoor lighting (quantify as candela per steradian per voxel or photopic luminance), with controllable brightness modulation.

Safety: Maintain optical and environmental exposure levels within established safety standards for ocular and dermal exposure, and demonstrate negligible hazardous byproduct generation under prolonged operation.

Robustness: Operate reliably for at least N hours of cumulative duty cycle (specify target, e.g., 100 h) without significant degradation of voxel quality, particle supply exhaustion, or medium contamination.

Methodological tasks

Survey and select the voxel-generation mechanism(s) for experimental prototyping, justifying selection by trade-off analysis (brightness, localization, safety, and throughput).

Design a beam-steering and focus-control architecture capable of addressing the 50 cm workspace with targeted spatial precision and slew rate; specify candidate actuators and control loops.

Develop motion-planning and rendering algorithms that translate desired geometric primitives (points → lines → 2D planes → 3D volumes) into physically realizable voxel generation sequences, accounting for source constraints and perceptual persistence.

Build a testbed and measurement rig to quantify voxel size, brightness, localization error, generation latency, and environmental sensitivity; develop safety interlocks and monitoring.

Evaluate perceptual efficacy via psychophysical tests (motion continuity, shape recognition, brightness perception) and iterate on system parameters.

Expected contributions

A validated problem formulation and design space for reflector-free mid-air volumetric displays in compact workspaces.

Comparative quantitative assessment of candidate physical mechanisms and steering architectures for voxel generation and motion-based composition into higher-dimensional primitives.

Prototype demonstrations (or detailed experimental designs) showing lines and planar surfaces synthesized from point-wise voxels within a 50 cm workspace, with measured spatial and temporal performance metrics.



