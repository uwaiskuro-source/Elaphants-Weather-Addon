ELAPHANTS WEATHER ADD-ON

EWA — Master Project Document

Project Vision, Scientific Scope, Atmospheric Simulation, Adaptive Cloud Geometry, Environmental Systems, Vehicle Customization, Technical Architecture, Development Roadmap, and Creator Background

Document status: Reconstructed master specification
Project: EWA — Elaphants Weather Add-on
Platform: Minecraft Bedrock Edition
Primary target: Bedrock, including Android/mobile
Creator origin: Indonesia
Creator age reference: 11 years old in 2026
Project stage: Planning and learning — implementation has not yet begun
Previous master scope: Entries 0–333
New scope: Entries 334 onward
Release date: Not confirmed
GitHub repository: https://github.com/uwaiskuro-source/Elaphants-Weather-Addon

---

PART A — PROJECT IDENTITY

A1. Project Name

EWA stands for Elaphants Weather Add-on.

The project was previously known as TRAA — Truly Realistic Atmospheric Add-on. It was later renamed to EWA.

Its purpose is to develop a scientifically informed atmospheric and environmental simulation experience for Minecraft Bedrock Edition.

A2. Project History

- Mecha Weather was previously considered an earlier weather-project milestone.
- TRAA was envisioned as its successor.
- The project subsequently became EWA.
- EWA is an independent project from Indonesia.
- ChatGPT is used for planning, learning, research, and technical guidance.
- No public downloadable EWA release has been established in the documented project status.

A3. Project Philosophy

EWA should prioritize:

1. Scientific plausibility.
2. Interconnected atmospheric systems.
3. Realistic environmental reactions.
4. Adaptive cloud and storm structures.
5. Meaningful player observation.
6. Mobile-aware performance.
7. Technical feasibility.
8. Honest implementation reporting.

The project should not simply contain hundreds of disconnected effects. Its systems should influence one another.

A4. Development Status

All proposed features remain planned or designed unless their implementation is independently confirmed.

Status terminology:

- Planned: proposed feature.
- Designed: behavior and requirements documented.
- Experimental: prototype or technical experiment exists.
- Implemented: working implementation exists.
- Tested: implementation tested under documented conditions.
- Completed: acceptance criteria satisfied.

A concept, texture, model, imported file, or visual mockup does not automatically prove that a complete system works.

A5. Release Date

Previously mentioned possible dates:

- December 16, 2026.
- January 14, 2027.

Both were informal estimates, not confirmed release dates.

There is currently no official release date.

LET MI TING, LET MI TING... Uhhhh Janu-aray... Uhhhh deck-sember... 😭🙏

The project will only be considered ready when it has been implemented, tested, optimized, documented, and prepared for distribution.

---

PART B — ORIGINAL MASTER SCOPE (0–333)

The previous master README established 334 numbered entries, from 0 through 333.

These entries remain part of the historical foundation of EWA and should be retained when assembling the complete numbered edition.

Their major divisions are:

1. Project identity and development principles.
2. Atmospheric foundations.
3. Cloud classification and morphology.
4. Adaptive cloud geometry and rendering.
5. Thunderstorms and severe weather.
6. Lightning and electrical processes.
7. Precipitation and hydrometeorology.
8. Tornado systems.
9. Wind, coastal weather, and tropical systems.
10. Fog and atmospheric visibility.
11. Volcanic systems and ash.
12. Climate and large-scale atmospheric circulation.
13. Environmental interactions and hydrology.
14. Weather observation and related systems.
15. Additional atmospheric and environmental systems.
16. Cloud visibility, distance, and rendering management.
17. Atmospheric control and custom scenarios.
18. Audio and environmental feedback.
19. Atmospheric data and simulation architecture.
20. Adaptive performance presets.
21. Creator development and learning roadmap.

The previous numbered scope includes:

- Major cloud genera and cloud variations.
- Cumulus, cumulonimbus, cirrus, stratus, stratocumulus, and other cloud forms.
- Cloud growth, merging, fragmentation, and dissipation.
- Adaptive Cloud Cell System (ACCS).
- Cloud lighting and shading.
- Thunderstorm organization.
- Supercells, multicells, squall lines, and mesocyclones.
- Updrafts, downdrafts, inflow, and outflow.
- Lightning and thunder.
- Rain, drizzle, hail, and localized precipitation.
- Tornado morphology, movement, damage, and dissipation.
- Landspouts, waterspouts, and dust devils.
- Wind fields, coastal circulation, and tropical cyclones.
- Fog, mist, and visibility.
- Volcanic ash and selected geological interactions.
- Regional climate, seasonal variation, and large-scale circulation.
- Atmospheric data management.
- Rendering distance, culling, and cloud-state persistence.
- Natural simulation and custom scenario controls.
- Weather audio.
- Lite, Balanced, High, and Ultra performance presets.
- Creator learning and technical development.

The original README's detailed descriptions and technical qualifications should remain preserved in the historical baseline rather than being silently discarded.

---

PART C — ATMOSPHERIC FOUNDATIONS

C1. Atmospheric State

The atmospheric simulation should use interconnected variables.

Possible variables include:

- Air temperature.
- Atmospheric pressure.
- Air density.
- Relative humidity.
- Specific humidity.
- Water-vapor mixing ratio.
- Dew point.
- Wet-bulb temperature.
- Wind speed.
- Wind direction.
- Vertical velocity.
- Wind shear.
- Turbulence.
- Vorticity.
- Convergence.
- Divergence.
- Atmospheric stability.
- CAPE.
- CIN.
- LCL.
- LFC.
- Environmental lapse rate.
- Cloud water.
- Ice particles.
- Rainwater.
- Graupel.
- Hail.
- Visibility.
- Surface temperature.
- Soil moisture.
- Evaporation.
- Condensation.
- Latent heat.
- Sensible heat.
- Terrain influences.

Not every variable needs to be simulated at full numerical resolution. A hierarchy of global, regional, and local atmospheric information is preferable.

C2. Atmospheric Physics

Air should behave as a connected environmental system.

The design includes:

- Inertia.
- Momentum.
- Buoyancy.
- Pressure gradients.
- Air-mass movement.
- Warm and cold air interactions.
- Humid and dry air interactions.
- Updrafts and downdrafts.
- Turbulence and eddies.
- Entrainment.
- Surface friction.
- Terrain-induced airflow.
- Convective circulation.

The simulation should avoid treating wind as a simple animation direction independent of other atmospheric processes.

C3. Different Storm Organizations

Storm types should have distinct dynamics.

Examples:

Supercell

- Persistent rotating updraft.
- Mesocyclone.
- Inflow.
- Forward-flank downdraft.
- Rear-flank downdraft.
- Outflow.
- Possible tornado development.

Multicell

- Multiple convective cells.
- Cell regeneration.
- Gust-front interactions.
- Cold-pool development.

Squall line

- Organized linear convection.
- Gust front.
- Cold pool.
- Heavy precipitation.
- Possible bowing segments.

Tropical cyclone

- Organized low-level inflow.
- Eyewall convection.
- Spiral rainbands.
- Upper-level outflow.
- Latent-heat-driven circulation.

Extratropical cyclone

- Low-pressure circulation.
- Warm and cold fronts.
- Frontal lifting.
- Jet-stream interactions.

Cumulonimbus is a cloud genus, not a universal storm organization. EWA must preserve that distinction.

---

PART D — CLOUD VISUAL UPDATE

D1. General Objective

The cloud visual system should produce realistic three-dimensional cloud structures while remaining compatible with the intended Bedrock environment.

The latest direction emphasizes cloud entities with adaptive geometry.

D2. Autonomous Volumetric Cloud Entity System

Proposed architecture name: Autonomous Volumetric Cloud Entity System.

Each cloud is intended to use an entity-based representation with a white structural foundation.

Its intended characteristics:

- Three-dimensional structure.
- Volumetric appearance.
- Adjustable size.
- Adaptive shape.
- Atmospheric-condition-dependent growth.
- Atmospheric-condition-dependent deformation.
- Independent cloud identity.
- Controlled formation of additional cloud entities.
- Smooth transitions.
- Mobile-aware rendering.
- No dependency on Render Dragon as a design requirement.

The intended visual result is a realistic cloud rather than a flat sprite or ordinary particle effect.

The term volumetric describes the visual objective. It does not establish that Bedrock supports true volumetric ray marching in this architecture.

D3. Adaptive Cloud Size

Cloud dimensions should respond to atmospheric conditions.

Possible dimensions:

- Width.
- Length.
- Height.
- Local thickness.
- Internal density.
- Outer contour.
- Individual structural components.

Growth and shrinkage should occur gradually.

D4. Adaptive Cloud Deformation

Cloud geometry should change according to:

- Wind.
- Wind shear.
- Updraft.
- Downdraft.
- Atmospheric stability.
- Moisture availability.
- Turbulence.
- Cloud type.
- Local atmospheric conditions.

Different cloud types should have different structural behavior.

Cirrus should not be forced to resemble rounded cumulus lobes. Layered clouds should not be treated as ordinary convective towers.

D5. Autonomous Cloud Duplication

Cloud entities may generate additional cloud entities when atmospheric conditions support cloud development.

The intended process:

1. An initial cloud entity exists.
2. Atmospheric conditions support growth.
3. Its geometry gradually changes.
4. New cloud structures may develop.
5. Additional cloud entities may form when justified by the simulated atmosphere.
6. New entities develop independently while retaining their atmospheric relationships.

Duplication must not be an unconditional cloning loop.

It should be controlled by moisture, temperature, vertical motion, stability, available geometry budget, and other relevant conditions.

D6. Seamless Cloud Integration

Adjacent cloud entities should be able to appear as one continuous formation.

The design objective is to avoid:

- Obvious seams.
- Visible gaps.
- Artificial internal walls.
- Unwanted intersections.
- Abrupt size changes.
- Visible regeneration.

Cloud merging and entity identity are separate concerns: entities may remain independently tracked while appearing visually connected.

D7. Adaptive Cloud Cell System (ACCS)

ACCS remains an earlier proposed geometry architecture.

Its original concept includes:

- Three-dimensional cells.
- A 5 × 5 vertex arrangement on each of six faces.
- 150 face-level vertex references.
- 98 unique surface vertices when shared vertices are reused.
- Surface deformation.
- Adaptive growth.
- Local subdivision.
- Connected cells.
- Removal or hiding of internal surfaces.
- Collision considerations.
- Shading.
- Volumetric appearance.
- Geometry budgets.

ACCS and the newer autonomous cloud-entity architecture are related design directions, but their final relationship has not yet been established.

They must not be treated as two already working systems.

D8. Cloud Shading and Color

Cloud appearance should respond to:

- Sun direction.
- Sun elevation.
- Light intensity.
- Cloud thickness.
- Cloud density.
- Surface orientation.
- Atmospheric scattering.
- Internal occlusion.
- Time of day.
- Lightning illumination.

Cloud color should not be restricted to a few fixed colors.

The earlier visual concept includes:

- Ten normal daylight brightness-to-darkness levels.
- Seven sunrise/sunset orange levels.
- Six nighttime levels.
- Continuous shading transitions as a longer-term goal.

These are design references, not a proven color-rendering capability.

D9. Lightning Cloud Flash

Lightning should briefly illuminate nearby cloud structures.

The illumination should:

- Reveal cloud depth.
- Affect suitable nearby structures.
- Avoid permanent cloud glow.
- Avoid uniformly brightening the entire sky.
- Respond to the lightning event.

D10. Cloud Shadow System

Clouds should cast visible shadows even when no rain is occurring.

Shadow behavior should depend on:

- Cloud altitude.
- Cloud density.
- Cloud thickness.
- Cloud geometry.
- Sun angle.
- Wind-driven cloud movement.
- Atmospheric scattering.

Higher clouds should generally produce more diffuse-looking shadows under comparable conditions because the distance between the cloud and the receiving surface increases the penumbra.

The system should avoid hard black blobs.

Cloud shadows should:

- Move with the cloud.
- Change shape with cloud geometry.
- Change darkness with cloud opacity and thickness.
- Have soft edges.
- Remain visible in suitable non-rainy weather.

Bedrock's available rendering and shadow interfaces must be tested before claiming arbitrary cloud-shaped soft shadows are possible.

---

PART E — WEATHER-BASED HOSTILE SPAWNING

E1. Regional Weather-Based Spawn Conditions

Hostile spawning should be influenced by the weather at the actual spawn location.

A player does not need to be standing in rain for hostile entities to spawn in a separate rainy region.

Example:

- Region A: raining.
- Region B: dry.
- Player: standing in Region B.
- Spawn candidate: located in Region A.

The spawn decision should evaluate Region A's weather rather than only checking the player's current weather exposure.

E2. Spawn Evaluation

The system should consider:

- Local weather state.
- Spawn location.
- Existing Minecraft spawn rules.
- Light conditions.
- Surface requirements.
- Entity caps.
- Player-distance rules.
- Mob-specific restrictions.

Rain should be an additional environmental factor, not an unconditional permission to spawn every hostile mob.

E3. Weather Data Source

The system should use EWA's own regional weather state where possible.

It should not create a second independent weather simulation solely for mob spawning.

Bedrock implementation feasibility and spawn-event limitations require testing.

---

PART F — VEGETATION AND WIND INTERACTION

F1. Vegetation Wind Response

Vegetation should react to simulated wind.

Affected vegetation includes:

- Tree leaves.
- Grass.
- Short grass.
- Tall grass.
- Sugar cane.
- Bush-like plants.
- Dead Bush.
- Other suitable leafy plants.

Wood trunks and logs should not sway as ordinary leaves do.

F2. Wind-Dependent Motion

No wind:

- Vegetation remains still or nearly still.

Weak wind:

- Gentle movement.

Moderate wind:

- More noticeable swaying.

Strong wind:

- Faster and stronger movement.

Gusts:

- Temporary stronger movement.

Wind direction:

- Determines the direction of bending and swaying.

F3. Plant-Specific Motion

Grass-like vegetation may lean toward the wind.

Sugar cane may bend and sway.

Bushes should respond according to their geometry.

Tree leaves should sway without making the entire trunk tilt.

F4. Inertia

Vegetation should not instantly stop or reverse when wind direction changes.

Movement should settle gradually.

F5. Vegetation Damage

Strong winds may damage vegetation.

Possible outcomes:

- Leaves become damaged.
- Leaves detach.
- Leaves are carried by wind.
- Grass becomes uprooted.
- Grass disappears.
- Sugar cane is damaged or uprooted.
- Bushes are damaged.
- Dead bushes are displaced.

Damage thresholds should differ by vegetation type and environmental conditions.

F6. Soil and Grass Surface Changes

Grass-covered soil may lose its vegetation layer.

A Grass Block may become Dirt when its grass layer is removed under suitable conditions.

The system should distinguish vegetation loss from ordinary random block replacement.

---

PART G — WIND EROSION AND DESERT SAND

G1. Surface Sand Drift

Desert sand should respond to strong wind.

The visual target is a low cream-colored cloud-like layer moving close to the ground.

The effect should not look like ordinary high-altitude clouds.

G2. Sand Movement

The system should approximate:

- Saltation: sand grains hopping along the surface.
- Suspension: fine particles remaining airborne.
- Surface creep: larger grains rolling or sliding.

G3. Wind Intensity

Weak wind:

- Occasional small sand movement.

Moderate wind:

- Visible surface drift.

Strong wind:

- Broad low-level blowing-sand clouds.

Very strong wind:

- Sandstorm conditions may develop.

G4. Sandstorm Visuals

Sandstorm effects should include:

- Cream or beige coloration.
- Low-level movement.
- Directional transport.
- Changing density.
- Reduced visibility.
- Gradual settling when wind weakens.

G5. Soil Erosion

Wind erosion should depend on:

- Wind speed.
- Surface exposure.
- Soil moisture.
- Particle size.
- Vegetation coverage.
- Surface material.

Pressure alone should not be treated as a magical upward suction force.

Airflow, aerodynamic lift, turbulence, and particle properties are more appropriate factors.

---

PART H — VEHICLE SURFACE SCULPTING

H1. Purpose

Vehicle bodies should be customizable beyond ordinary full-block construction.

The objective is to create more aerodynamic and visually refined vehicle shapes.

H2. Pixel Grinding

The existing grinding concept allows the player to remove one pixel-sized portion at a time.

The player aims at the surface and uses the grinding tool.

Each successful action removes or reshapes one small surface unit.

H3. Smooth Grinding

A second mode uses the same grinding tool.

Intended interaction:

- Player crouches.
- Player aims at a previously modified block.
- Player uses the alternate interaction.
- The target is modified through a larger smoothing operation.

The result should not necessarily retain a stepped pixel appearance.

H4. Two Surface Modes

Pixel mode

- Small stepped details.
- One-pixel modifications.
- Suitable for fine surface shaping.

Smooth mode

- Rounded, sloped, or shortened surfaces.
- No visible pixel stepping in the intended final shape.
- Suitable for aerodynamic transitions.

H5. References

The project uses existing Bedrock add-ons as conceptual references:

- Real Miniblocks by Vatonage: reference for small pixel-scale block geometry.
- Blockz+ by JayCubTruth: reference for custom non-cubic and smoother block shapes.

These references demonstrate relevant visual possibilities, but do not establish that EWA can edit arbitrary block geometry dynamically.

Any external code or assets require appropriate permission and licensing.

---

PART I — DYNAMIC PSEUDO-BLOCK GEOMETRY SYSTEM

I1. System Concept

Proposed name: Dynamic Pseudo-Block Geometry System (DPGS).

DPGS is intended to convert selected modified block surfaces into entity-like objects that visually and behaviorally resemble blocks.

The conversion may occur when:

- A block has been pixel-ground.
- A block has a sloped surface.
- A block has an irregular surface.
- A block has been smooth-ground.
- A block contains a modified geometry profile.

The system is not limited to blocks that have already undergone smooth grinding.

I2. Geometry Scanner

The proposed scanner reads:

- Block endpoints.
- Geometric corners.
- Surface inclination.
- Surface depth.
- Modified areas.
- Remaining original geometry.
- Position relative to the original block space.

It should distinguish geometric corners from individual pixel corners.

I3. Pseudo-Block Entity

The resulting object should:

- Look like the modified block.
- Occupy a suitable position.
- Stand on or attach to the vehicle.
- Follow vehicle movement.
- Follow vehicle rotation.
- Follow relevant vehicle physics.
- Retain the original block's durability rules.
- Avoid unnecessary interaction.
- Avoid unwanted shadows when the design specifies no shadow.

I4. Hitbox

The desired hitbox should follow the modified geometry as closely as Bedrock allows.

The intended design is more precise than a generic full-block collision box.

The system should distinguish:

- Visual geometry.
- Selection geometry.
- Collision geometry.
- Damage geometry.

These structures must remain coordinated.

I5. Damage Geometry

Damage should follow the object's current geometry.

Possible cases:

Smooth surface

- Damage follows smooth geometry.

Pixel surface

- Damage follows the stepped pixel geometry.

Angled pixel surface

- Damage follows the pixel geometry and its orientation.

Original block with a sloped shape

- Damage should follow the sloped shape.

The system should not force every damaged object into the same square pixel pattern.

I6. Selection Outline

When the crosshair targets the pseudo-block, an outline should appear.

The selection outline should communicate the selectable area.

The player should be able to destroy the pseudo-block through the intended block-breaking interaction.

I7. Durability

The pseudo-block should preserve the durability of its original block type.

Conversion into an entity-like representation should not automatically reset durability.

I8. Vehicle Physics

Pseudo-block entities should follow the vehicle's movement and physics.

They should not become loose independent objects during normal vehicle motion.

I9. Shadow

The intended shadow should depend on:

- Object geometry.
- Position.
- Orientation.
- Depth.
- Light direction.
- Distance from the receiving surface.

If an object occupies more of one side of a block region, its shadow should reflect that spatial relationship.

I10. Technical Limitations

Bedrock entity collision does not automatically provide arbitrary per-pixel collision matching.

Dynamic geometry editing, exact block-like placement, selection outlines, and custom shadow behavior require independent technical research.

DPGS is a design proposal, not a confirmed native Bedrock capability.

---

PART J — CUSTOM VEHICLE PAINTING AND DRAWING

J1. Paint System

Vehicle surfaces should support custom colors.

Two painting methods are planned:

1. Full-block painting using a paint bucket.
2. Canvas-based painting for detailed designs.

J2. Paint Bucket

The player aims at a target block and uses the paint-bucket interaction.

The whole block receives the selected color.

J3. Canvas GUI

The player interacts with a target block and opens a custom drawing interface.

The interface should provide:

- A canvas.
- A color palette.
- Brush selection.
- Adjustable brush size.
- Pixel-level drawing.
- Writing.
- Patterns.
- Custom illustrations.
- Erasing tools.

J4. Dye-Based Colors

Dyes provide the initial pigment source.

The system should support more than the original dye colors through color blending.

J5. Pixel Color Blending

Example:

1. A pixel is painted red.
2. The same pixel receives blue paint.
3. The system blends the two pigment values.
4. The result becomes a purple-like color.

The blending method should be documented.

A physically realistic pigment-mixing model may differ from simple RGB addition or averaging.

J6. Brush Size

The player should be able to increase or decrease brush size.

The canvas should support fine details and larger painted regions.

J7. Tissue Eraser

Item name: Tissue.

The Tissue item is intended to remove paint.

Full-block cleaning:

- Aim at a painted block.
- Use Tissue.
- Restore the block's original color.

Canvas cleaning:

- Use the Tissue icon inside the drawing GUI.
- Erase selected painted regions.

J8. Tissue Durability

Tissue should have durability.

Repeated use reduces its remaining cleaning capacity.

When its durability is exhausted, it becomes a dirty Tissue.

J9. Dirty Tissue as Pigment Storage

Dirty Tissue should no longer clean surfaces.

It may instead act as a limited-use brush.

It can release the color stored in it.

Example:

- Tissue cleans blue paint.
- It later contacts red pigment.
- Its stored pigment becomes a red-blue mixture.
- It can release the resulting mixed color as a brush.

J10. Mixing Restrictions

Once a mixed color is stored in dirty Tissue, the proposed design does not allow additional mixing into that stored mixture.

This preserves the distinction between clean pigment storage and exhausted cleaning material.

J11. Vehicle Lamps

The paint and sculpting systems should also apply to vehicle lamps or lamp-sized blocks.

Lamp housings should support:

- Sculpting.
- Smooth shaping.
- Pixel shaping.
- Painting.
- Drawing.
- Custom surface patterns.

The light-emitting behavior itself must remain compatible with the lamp's actual implementation.

J12. Technical Limitations

A canvas GUI can be designed, but dynamically generating unique textures for every modified block is not automatically supported by ordinary Bedrock resource-pack systems.

The implementation may require a custom data representation, texture atlas strategy, pre-authored variants, or another supported rendering architecture.

The final approach must be tested.

---

PART K — WEATHER OBSERVATION SYSTEMS

K1. Weather Radar

The radar system should provide several observation modes.

Satellite mode

- Overhead cloud appearance.
- Cloud coverage.
- Large-scale cloud structures.

Reflectivity mode

- Approximation of precipitation-related radar reflectivity.
- Distinguishable precipitation regions.

Velocity mode

- Radial movement toward or away from the radar.
- Potential rotational signatures.

Wind mode

- Wind direction.
- Wind speed where supported by the simulated data.

Satellite imagery and radar measurements must remain conceptually distinct.

K2. Radar Map

The radar interface should display a land map beneath the weather overlays.

Possible map elements:

- Roads.
- Rivers.
- Lakes.
- Coastlines.
- Settlements.
- Terrain.
- Radar location.
- Storm location.

K3. Tornado Track

The Tornado Track system should preserve the path of a tornado after it has completely dissipated.

Its visual design includes:

- Filled circular markers.
- Nested filled circles.
- A trail behind the tornado.
- Optional rotation of the marker.
- Persistent event history.

Separate tornado identities must remain separate.

This includes:

- Main tornado.
- Satellite tornadoes.
- Twin tornadoes.
- Multiple vortices.

Overlapping tracks should not automatically merge into one identity.

K4. Historical Tornado Records

After an event ends, its path should remain accessible through an archive or historical view.

K5. Weather Balloon

A balloon may be released and tracked.

The interface should display:

- Altitude.
- Direction.
- Movement.
- Position.
- Balloon trail.
- Available atmospheric measurements.

Its trail should remain separate from Tornado Track.

K6. Atmospheric Prediction

Predictions should use the simulated atmospheric data.

Forecasts should not be purely random.

Uncertainty must be represented rather than claiming perfect prediction.

K7. Tornado Siren

The siren system should support:

- Detection radius.
- Triggering storm types.
- Trigger thresholds.
- Automatic mode.
- Manual mode.
- Warning audio.
- Status display.

It should use EWA's existing atmospheric and storm data instead of creating a second independent detection system.

K8. Drone Observation

A drone should be deployable on the ground in a suitable open area.

The player may use a Drone Control remote to enter the drone's camera view.

The interface should provide appropriate controls.

Crouching is the proposed method for leaving drone view.

Battery, range, and entity-management constraints should be considered.

K9. Anemometer

The proposed anemometer contains:

- A static pole or support.
- A rotating cup or head component.

The support should not require an unnecessarily active entity.

The rotating component should respond to wind speed.

Calm wind should produce little or no rotation.

The device should be protected from unwanted interaction.

If its supporting ground block is lifted or destroyed, the device should be removed rather than floating independently.

If the support is destroyed, its rotating component must also be cleaned up.

---

PART L — VEHICLES AND STORM OBSERVATION

L1. Vehicle Customization

Vehicles may support:

- Custom body shaping.
- Custom painting.
- Custom drawings.
- Roof customization.
- Lighting customization.
- Anemometer installation.
- Observation equipment.
- Aerodynamic surface modifications.

Not every vehicle must be aerodynamic.

L2. Aerodynamic Shapes

The surface sculpting system should allow vehicle body shapes to become smoother and more streamlined.

L3. Vehicle Equipment

Proposed components include:

- Lights.
- Roof equipment.
- Anemometer.
- Radar.
- Observation camera.
- Probe-related fictional gameplay equipment.
- Adjustable vehicle suspension.
- Other compatible customization components.

All equipment should be treated as game simulation and observation features.

L4. Vehicle Physics

Vehicle components should follow the vehicle's transform and physics.

They should not detach, float, or become misaligned during ordinary movement.

L5. External Add-on Compatibility

EWA may investigate compatibility with Create Aeronautics Bedrock.

Official collaboration requires agreement from the original developer.

Unofficial compatibility must respect the add-on's licensing and intellectual-property restrictions.

Credit alone does not grant permission to redistribute another creator's assets or code.

---

PART M — SETTINGS INTEGRATION

M1. Official Minecraft Settings

EWA's intended user experience includes settings integrated into Minecraft's official settings environment, using a model comparable to settings provided by some visual add-ons.

This is a target design, not a confirmed Bedrock API capability.

M2. Proposed Settings Categories

Atmosphere

- Atmospheric detail.
- Fog.
- Lighting.

Weather

- Rain.
- Wind.
- Storm behavior.
- Weather effects.

Clouds

- Cloud quality.
- Cloud detail.
- Cloud distance.
- Cloud geometry settings.

Cloud Shadows

- Shadow quality.
- Shadow softness.
- Shadow intensity.

Storm Simulation

- Storm detail.
- Storm dynamics.
- Selected simulation options.

Vegetation

- Wind response.
- Vegetation damage.
- Surface interaction.

Environmental Effects

- Sand movement.
- Dust.
- Soil erosion.

Mob Behavior

- Weather-based spawn behavior.

Observation Systems

- Radar.
- Drone.
- Weather balloon.
- Tornado Track.

Vehicle Customization

- Sculpting options.
- Paint options.
- Canvas behavior.

Performance

- Lite.
- Balanced.
- High.
- Ultra.

The final categories depend on actual Bedrock settings integration capabilities.

---

PART N — PERFORMANCE AND MOBILE COMPATIBILITY

N1. Mobile Target

EWA should consider devices around the 8 GB physical RAM class.

Memory extension or virtual RAM must not be treated as equivalent to physical RAM.

N2. Rendering Target

The cloud visual design specifically seeks compatibility without depending on Render Dragon.

This is an important design requirement, but it remains unverified until tested on the intended Minecraft version and rendering environment.

N3. Performance Presets

The original proposed presets remain:

- Lite.
- Balanced.
- High.
- Ultra.

The presets should adjust computational and rendering costs while preserving the underlying atmospheric identity wherever possible.

N4. Performance Priorities

- Stable frame time.
- Controlled memory usage.
- Limited entity counts.
- Controlled particle counts.
- Staggered updates.
- Regional simulation.
- Rendering culling.
- Geometry budgets.
- Efficient cloud updates.
- Controlled block changes.
- Limited unnecessary entity creation.

N5. Performance Claims

No performance target should be described as achieved without actual testing.

A previous proposal mentioned approximately 5–10 FPS of additional cost as a target, not a guarantee.

---

PART O — TECHNICAL DEVELOPMENT

O1. Required Skills

The creator needs to study:

JSON

- Objects.
- Arrays.
- Data types.
- Manifests.
- Identifiers.
- Dependencies.
- Resource and behavior definitions.

Molang

- Expressions.
- Variables.
- Queries.
- Conditions.
- Mathematical operations.
- Animation-related behavior.

JavaScript

- Variables.
- Functions.
- Arrays.
- Objects.
- Conditions.
- Loops.
- Events.
- Error handling.
- Minecraft Script API.

3D Modeling

- Vertices.
- Edges.
- Faces.
- Mesh topology.
- Surface deformation.
- Mesh subdivision.
- Mesh merging.
- Normals.
- Materials.
- Shading.
- Rigging.
- Animation.

O2. Current Applications

Purpose| Application
Coding and editing| VS Code Droid
File management| MiXplorer
Texture creation| Pixel Studio
Additional artwork| ibis Paint

These are the currently identified tools, not proof that every required workflow is supported by them.

O3. Experimental Features

The creator has identified the following Minecraft experimental options:

- Villager Trade Rebalancing.
- Upcoming Creator Features.
- Beta APIs.
- Experimental Creator Camera Features.
- Render Dragon Features.
- Voxel Shape Features.
- POI.
- Creator World Clocks.

Any additional experimental feature should be discussed before being introduced into the project.

O4. Bedrock Version Compatibility

Every implementation must be checked against the actual target Bedrock version.

Previous project discussions referenced Bedrock 1.26.20.27 and a target of 1.26.60.

Manifest engine requirements, Script API availability, and renderer compatibility must be verified rather than assumed.

---

PART P — TECHNICAL LIMITATIONS

EWA is ambitious, but Minecraft Bedrock is not a general-purpose scientific atmospheric simulation engine.

Important research challenges include:

- True volumetric ray marching.
- Arbitrary dynamic mesh generation.
- Runtime mesh subdivision.
- Seamless mesh merging.
- Dynamic per-pixel block collision.
- Exact geometry-derived entity hitboxes.
- Arbitrary cloud-shaped soft shadows.
- Dynamic texture generation from canvas drawing.
- Official Settings integration.
- Large-scale atmospheric simulation.
- High-resolution radar simulation.
- Large numbers of autonomous cloud entities.

A visual approximation must not be confused with a physically complete simulation.

A custom model is not automatically a dynamic mesh.

An entity is not automatically a block.

A collision box is not automatically an exact surface hitbox.

A visually volumetric cloud is not automatically a physically volumetric cloud.

Every major technical system needs a small controlled prototype before integration.

---

PART Q — DEVELOPMENT ROADMAP

Stage 1 — Programming Foundations

- JSON.
- Molang.
- JavaScript.
- Resource packs.
- Behavior packs.
- Manifests.
- Basic debugging.

Stage 2 — Modeling Foundations

- Three-dimensional coordinates.
- Mesh topology.
- Vertex editing.
- Surface deformation.
- Subdivision.
- Mesh merging.
- Basic animation.

Stage 3 — Small Bedrock Experiments

- Basic resource pack.
- Basic behavior pack.
- Custom texture.
- Simple entity.
- Simple script.
- Controlled event.
- Performance measurement.

Stage 4 — Cloud Geometry Research

- Basic cloud model.
- Rounded cloud structures.
- Wispy cloud structures.
- Layered clouds.
- Shading.
- Geometry export.

Stage 5 — ACCS and Cloud Entity Research

- Initial cell.
- 5 × 5 surface grid.
- Shared vertices.
- Deformation.
- Expansion.
- Subdivision.
- Connected cells.
- Internal surface handling.
- Cloud entity behavior.
- Growth and duplication.
- Performance testing.

Stage 6 — Atmospheric Model

- Atmospheric variables.
- Spatial representation.
- Temperature.
- Humidity.
- Pressure.
- Wind.
- Regional data.

Stage 7 — Weather Simulation

- Cloud behavior.
- Local precipitation.
- Fog.
- Wind.
- Storm dynamics.
- Environmental response.

Stage 8 — Advanced Systems

- Tornadoes.
- Severe thunderstorms.
- Radar.
- Observation tools.
- Cloud shadows.
- Vegetation response.
- Desert sand movement.

Stage 9 — Vehicle and Geometry Systems

- Pixel grinding.
- Smooth grinding.
- Geometry scanning.
- DPGS.
- Hitbox research.
- Vehicle physics.
- Custom painting.
- Canvas GUI.
- Tissue and pigment storage.

Stage 10 — Optimization and Integration

- Frame-time measurement.
- Memory measurement.
- Entity budgets.
- Geometry budgets.
- Update scheduling.
- Mobile testing.
- Compatibility testing.

Stage 11 — Documentation and Distribution

- Feature status.
- Supported versions.
- Known limitations.
- Installation instructions.
- Testing records.
- Final package validation.
- Distribution only when genuinely ready.

---

PART R — PROJECT SCALE AND FUTURE EXPANSION

The numbered feature list is not the entire EWA vision.

Thousands of additional ideas and possible systems may be explored over time.

However, every new idea should be:

1. Described clearly.
2. Checked for scientific plausibility.
3. Evaluated for Bedrock feasibility.
4. Evaluated for performance.
5. Assigned a development priority.
6. Connected to the appropriate subsystem.
7. Given a clear implementation status.

A large feature count is not automatically a measure of quality.

The guiding principle remains: fewer disconnected effects, more deeply interconnected simulation.

---

PART S — FINAL PROJECT STATEMENT

Elaphants Weather Add-on is an independent Minecraft Bedrock project from Indonesia.

Its long-term ambition is to bring a more interconnected, scientifically informed, and visually immersive atmospheric experience into Minecraft.

The creator is 11 years old in 2026 and is still learning the foundational technologies required for implementation.

The project remains in planning and learning.

Its major design directions include atmospheric simulation, severe weather, adaptive cloud geometry, environmental interactions, storm observation, vehicle customization, and advanced visual systems.

The immediate priority is learning, research, small experiments, and technical validation.

EWA should grow gradually, without claiming that proposed systems are already functional.

Current historical numbered scope: 0–333.
Newly documented additions: 334 onward.
Implementation status: Planning and learning.
Cloud geometry concept: ACCS and autonomous volumetric cloud entities; final architecture relationship pending.
Vehicle geometry concept: DPGS.
Release date: Not confirmed.
Project origin: Indonesia.

---

CREATOR'S NOTE

This project is still a work in progress at the planning and learning level.

I am an 11-year-old Grade 6 student in 2026, and I still need to learn JSON, Molang, JavaScript, and 3D modeling before I can properly begin developing the systems described in this document.

My current applications are:

- VS Code Droid — coding and editing.
- MiXplorer — file management.
- Pixel Studio — block textures and other image assets.
- ibis Paint — additional texture editing and artwork.

There are still thousands of potential features and system ideas that may eventually become part of EWA. They will be documented and developed gradually as my knowledge and technical capabilities improve.

One of the major ideas currently being explored is ACCS, alongside the newer autonomous cloud entity concept.

I know the project is ambitious. I also know that I still have a lot to learn. That is part of the journey.

Thank you for following the development of EWA.

And don't forget this project! 🌩️🌪️☁️

See you again later.

Goodbye, and see you next time! 👋😭

EWA — Elaphants Weather Add-on

An independent project from Indonesia.