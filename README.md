ELAPHANTS WEATHER ADD-ON

EWA — Elaphants Weather Add-on

Project Vision, Scientific Scope, Atmospheric Simulation Architecture, Adaptive Cloud Geometry, Technical Roadmap, Development Documentation, and Creator Background

---

PROJECT INFORMATION

Field| Information
Project Name| Elaphants Weather Add-on
Abbreviation| EWA
Platform| Minecraft Bedrock Edition
Primary Target| Minecraft Bedrock, including mobile devices
Creator| Independent creator from Indonesia
AI Assistance| ChatGPT
Project Status| Planning and learning — implementation has not yet begun
Development Approach| Step-by-step, scientifically informed, mobile-aware
Main Development Focus| Atmospheric simulation, weather, clouds, environmental interaction, and sky phenomena
Special Cloud Architecture Concept| Adaptive Cloud Cell System (ACCS)
Release Date| Not confirmed

Release Date and Development Reality

Previously mentioned estimated dates:

- December 16, 2026.
- January 14, 2027.

Both dates were informal guesses, not official commitments.

There is currently no confirmed release date for EWA.

LET MI TING, LET MI TING... Uhhhh Janu-aray... Uhhhh deck-sember... 😭🙏

Jokes aside, EWA's development time depends on learning, technical research, implementation, testing, optimization, compatibility, documentation, and the actual condition of the project.

EWA will not be declared ready simply because a calendar date arrives.

The project should only be released when a suitable version is genuinely functional, tested under documented conditions, sufficiently optimized, and ready for distribution.

---

PROJECT OVERVIEW

Project Vision

Elaphants Weather Add-on is an independently envisioned Minecraft Bedrock Edition project aiming to create a scientifically informed atmospheric and environmental simulation experience.

Its long-term vision combines:

1. A realistic atmospheric and weather system.
2. A playable meteorological simulator.
3. An interconnected environmental simulation ecosystem.
4. Advanced cloud morphology and atmospheric rendering.
5. Adaptive three-dimensional cloud geometry.
6. Severe-weather and storm observation systems.
7. Climate, hydrology, and selected geological interactions.
8. Selected astronomical and atmospheric optical phenomena.

The central objective is to reproduce important real-world atmospheric processes as accurately as Minecraft Bedrock's actual technical capabilities allow.

EWA is not intended to be merely a collection of weather effects.

Its long-term design emphasizes interconnected systems in which atmospheric conditions influence cloud formation, cloud development, storms, precipitation, wind, visibility, and environmental interactions.

Core Project Identity

EWA follows five central principles.

1. Natural Development

Weather and atmospheric phenomena should emerge from interacting environmental conditions instead of relying entirely on rigid scripted sequences.

2. Atmospheric Interconnection

Global, regional, and local atmospheric systems should influence one another.

3. Adaptive Structures

Clouds and weather systems should be capable of changing their structure according to their simulated environment.

4. Environmental Interaction

Weather should have meaningful interactions with terrain, vegetation, buildings, visibility, and other environmental elements.

5. Realism Within Technical Limits

Scientific accuracy is a major objective, but Bedrock compatibility, performance, memory usage, and technical feasibility must remain part of every development decision.

---

PROJECT STATUS AND DEVELOPMENT HONESTY

EWA is currently in the planning and learning stage.

The systems described in this document are proposed designs, research objectives, and development goals. They are not evidence of completed or working features.

The following development-status categories must be used consistently:

Status| Meaning
Planned| A feature has been proposed but its implementation has not been established.
Designed| Its intended behavior, requirements, and architecture have been documented.
Experimental| A technical experiment or prototype exists but is not yet considered reliable.
Implemented| A working implementation has been created.
Tested| The implementation has been tested under documented conditions.
Completed| The feature has satisfied its defined acceptance criteria.

A valid file import does not automatically mean that a feature works.

A visual demonstration does not automatically prove that the underlying simulation is scientifically accurate.

A concept document does not count as an implementation.

A successful test on one device does not guarantee compatibility with every Bedrock platform.

---

THREE PLAYER-VISIBILITY CLASSIFICATIONS

Every player-facing feature should receive one of three visibility classifications.

These classifications describe how noticeable a feature is during gameplay. They do not describe implementation difficulty, scientific importance, or development priority.

[Noticeable]

A feature that is directly and clearly observable by the player under its intended conditions.

Examples:

- A visible tornado.
- A large cumulonimbus cloud.
- Heavy localized rainfall.
- A visible fog bank.
- A major lightning flash.

[Moderately noticeable]

A feature that can be observed under suitable conditions, lighting, distance, proximity, or player interaction.

Examples:

- Subtle cloud-layer movement.
- A developing gust front.
- A visible rain boundary.
- A gradual change in surface wetness.
- A local wind difference between terrain regions.

[Subtle]

A small environmental detail that contributes to immersion but is not necessarily obvious during ordinary gameplay.

Examples:

- Slight variations in atmospheric color.
- Small changes in vegetation movement.
- Gradual surface drying.
- Minor changes in cloud-edge structure.
- Small differences in environmental moisture.

Classification rule: Backend-only operations that cannot produce any observable player-facing consequence should not be counted as standalone player-visible features. They should instead be documented as technical requirements or internal systems.

---

PART I — PROJECT IDENTITY AND DEVELOPMENT PRINCIPLES

0. Project Identity — [Noticeable]

EWA is an independently envisioned Minecraft Bedrock Edition project focused on atmospheric realism, weather simulation, environmental interactions, and advanced sky phenomena.

1. Project Vision — [Noticeable]

The long-term vision is to develop an interconnected simulation ecosystem covering atmospheric processes, cloud morphology, severe weather, climate, environmental hazards, and selected astronomical phenomena.

2. Project Name and Abbreviation — [Noticeable]

EWA stands for Elaphants Weather Add-on. The name represents the project's identity and long-term development ambitions.

3. Project Status — [Noticeable]

EWA remains in planning and learning. No proposed feature should be described as functional until an implementation has been created and tested.

4. Target Platform — [Noticeable]

The primary target is Minecraft Bedrock Edition, including Android and other supported platforms. Each feature must be evaluated against the actual capabilities of its targeted Bedrock version.

5. Mobile-First Development — [Noticeable]

Development must consider frame rate, frame-time stability, memory consumption, particle counts, entity counts, simulation frequency, rendering complexity, block updates, and large-scale weather workloads.

6. Scientific Accuracy — [Noticeable]

Meteorological, atmospheric, geological, and astronomical systems should be based on credible scientific references. Simplified simulations must be identified as approximations.

7. Original Development — [Noticeable]

EWA should use original code, textures, models, documentation, and other assets wherever possible. Existing projects may provide inspiration, but their assets and code must not be copied without appropriate permission and licensing.

8. Honest Feature Status — [Noticeable]

Development documentation must distinguish planned, designed, experimental, implemented, tested, and completed features.

9. Practical Realism — [Noticeable]

Development should prioritize meaningful visual and environmental realism instead of spending excessive resources on effects with little observable value.

10. Scientific and Fictional Separation — [Noticeable]

Scientifically documented phenomena and fictional gameplay mechanics must be clearly distinguished. Fictional phenomena must never be presented as established meteorology.

---

PART II — ATMOSPHERIC FOUNDATIONS

11. Atmospheric State — [Moderately noticeable]

Represent atmospheric conditions using interconnected variables such as temperature, humidity, pressure, wind velocity, vertical motion, cloud water, stability, precipitation, visibility, and selected electrical properties.

12. Atmospheric Pressure — [Moderately noticeable]

Pressure differences may influence wind movement, convergence, divergence, and storm organization.

13. Temperature — [Moderately noticeable]

Temperature should influence condensation potential, atmospheric stability, cloud development, and precipitation processes.

14. Humidity — [Moderately noticeable]

Humidity should influence atmospheric moisture availability, condensation potential, fog, and cloud development.

15. Atmospheric Stability — [Moderately noticeable]

Stable and unstable conditions should produce different convective behaviors and cloud-development characteristics.

16. Vertical Air Motion — [Moderately noticeable]

Updrafts and downdrafts should represent rising and sinking air and influence convection, precipitation, and storm organization.

17. Three-Dimensional Wind Fields — [Noticeable]

Wind should be represented as a coherent three-dimensional velocity field, incorporating horizontal direction, horizontal speed, vertical motion, shear, gusts, convergence, divergence, terrain effects, and storm-generated outflow.

18. Wind Shear — [Moderately noticeable]

Wind speed and direction may change with altitude. These differences should influence storm organization and cloud morphology where supported.

19. Convergence — [Moderately noticeable]

Air flowing together may contribute to localized rising motion and cloud development.

20. Divergence — [Moderately noticeable]

Air spreading apart may represent an important component of atmospheric circulation.

21. Air Masses — [Moderately noticeable]

Different air masses should have distinguishable temperature, moisture, stability, and movement characteristics.

22. Atmospheric Fronts — [Noticeable]

Cold, warm, stationary, and occluded fronts may influence regional cloud patterns and weather transitions.

23. Boundary Layers — [Moderately noticeable]

Near-surface atmospheric conditions may differ from those at higher altitudes, influencing fog, low clouds, surface heating, and convection.

24. Terrain Effects — [Noticeable]

Mountains, valleys, plains, coastlines, forests, deserts, and urban environments may influence local atmospheric behavior.

25. Day-Night Atmospheric Changes — [Moderately noticeable]

Daytime heating and nighttime cooling should influence selected atmospheric processes, including convection, stability, fog formation, and local wind circulation.

---

PART III — CLOUD CLASSIFICATION AND MORPHOLOGY

26. Cloud Classification — [Noticeable]

EWA aims to represent the major recognized cloud genera and important cloud variations. Cloud identity should depend on atmospheric conditions rather than permanently fixed models.

27. Cirrus Clouds — [Noticeable]

High-altitude clouds should display delicate, fibrous structures. Their geometry should not be forced into rounded cloud-lobe shapes. A dedicated wispy geometry approach is proposed.

28. Cirrostratus Clouds — [Noticeable]

Broad, translucent high clouds may cover large portions of the sky and support optical effects such as halos.

29. Cirrocumulus Clouds — [Noticeable]

Small high-level cloud elements may form organized patterns.

30. Altostratus Clouds — [Noticeable]

Middle-level layered clouds should support broad and relatively uniform sky coverage.

31. Altocumulus Clouds — [Noticeable]

Middle-level cloud patches should vary in size, spacing, thickness, and arrangement.

32. Stratus Clouds — [Noticeable]

Low uniform cloud layers should have a comparatively flat and continuous appearance.

33. Stratocumulus Clouds — [Noticeable]

Low cloud fields should contain rounded masses, gaps, and broad horizontal structures.

34. Nimbostratus Clouds — [Noticeable]

Thick precipitation-bearing layers should be capable of obscuring large portions of the sky.

35. Cumulus Clouds — [Noticeable]

Convective clouds should vary in size, vertical development, and atmospheric support.

36. Cumulus Humilis — [Noticeable]

Small fair-weather cumulus clouds should have limited vertical development.

37. Cumulus Mediocris — [Noticeable]

Moderately developed cumulus clouds should display stronger vertical growth.

38. Cumulus Congestus — [Noticeable]

Towering cumulus clouds should exhibit substantial vertical development and may evolve into thunderstorms under suitable conditions.

39. Cumulonimbus Clouds — [Noticeable]

Cumulonimbus clouds should support deep vertical structures, precipitation, strong convection, and potentially severe-weather features.

40. Anvil Clouds — [Noticeable]

Mature cumulonimbus clouds should be able to spread horizontally near the upper troposphere.

41. Overshooting Tops — [Noticeable]

Strong updrafts may push cloud turrets above the surrounding anvil.

42. Mammatus Clouds — [Noticeable]

Rounded pouch-like structures may appear beneath suitable cloud bases or anvil regions.

43. Lenticular Clouds — [Noticeable]

Terrain-associated airflow may produce smooth lens-shaped clouds.

44. Banner Clouds — [Noticeable]

Localized clouds may form near mountain peaks under suitable conditions.

45. Orographic Clouds — [Noticeable]

Air forced upward by terrain may cool and condense, producing terrain-associated clouds.

46. Wave Clouds — [Noticeable]

Atmospheric gravity waves may produce repeating cloud bands and wave-related formations.

47. Roll Clouds — [Noticeable]

Long horizontal tube-shaped clouds should be represented as a distinct formation.

48. Morning Glory Clouds — [Noticeable]

Morning Glory formations should be treated as specialized atmospheric phenomena rather than ordinary daily cloud formations.

49. Fog and Mist — [Noticeable]

Near-surface suspended water droplets should reduce visibility according to their density and environmental conditions.

50. Cloud Development — [Noticeable]

Clouds should support formation, growth, maturity, weakening, fragmentation, merging, and dissipation as descriptive states. These states must not become mandatory scripted sequences.

---

PART IV — ADAPTIVE CLOUD GEOMETRY AND RENDERING

4.1 General Cloud Geometry

51. Custom Sky Appearance — [Noticeable]

EWA aims to develop a custom sky and cloud appearance that reduces dependence on Minecraft's default Fancy Clouds. Rendering feasibility must be tested on actual Bedrock versions.

52. Three-Dimensional Cloud Geometry — [Noticeable]

Clouds should possess depth and internal structure. Flat cutouts and simple stacked discs are not the intended final appearance.

53. Cloud Lobe Geometry System — [Noticeable]

The proposed cloud-formation concept uses three-dimensional cloud lobes. Lobes may be rounded, oval, elongated, irregular, flattened, bulging, or adaptively deformed.

54. Cloud Lobe Assembly — [Noticeable]

Large formations, particularly cumulonimbus clouds, may consist of multiple connected or overlapping lobes that collectively form a coherent cloud.

55. Adaptive Lobe Dimensions — [Moderately noticeable]

Each lobe may have its own width, height, length, and shape.

56. Lobe Growth — [Noticeable]

Existing lobes may gradually enlarge and change shape. Existing geometry should be reused for growth when appropriate.

57. Lobe Persistence — [Moderately noticeable]

Some lobes may remain relatively unchanged while other parts of the cloud grow or weaken.

58. New Lobe Formation — [Noticeable]

New lobes may emerge where atmospheric and geometric conditions support additional development. Their creation should not be arbitrary or excessively frequent.

59. Internal Lobe Removal — [Subtle]

Lobes that become completely internal to another structure may be reduced or removed from active geometry when they no longer contribute to visible cloud structure.

60. Cloud Geometry Optimization — [Moderately noticeable]

The system should investigate merging, hiding, or removing redundant geometry without damaging the visible cloud.

61. Cloud Morphology — [Noticeable]

Overall cloud shape should emerge from lobe arrangement, dimensions, deformation, and interaction. Cumulonimbus clouds may develop cauliflower-like bulges, turrets, overshooting tops, and anvils.

62. Adaptive Cloud Types — [Noticeable]

A common cloud-formation system should support different cloud types. Atmospheric conditions determine potential cloud identity while geometry develops according to the environment.

63. Cloud Width — [Noticeable]

Cloud width should depend on structure, cloud type, atmospheric conditions, and development.

64. Cloud Length — [Noticeable]

Horizontal cloud extent should adapt to morphology and wind conditions.

65. Cloud Height — [Noticeable]

Cloud vertical dimensions should depend on cloud type and atmospheric support.

66. Cloud Density — [Noticeable]

Cloud density should influence opacity, shading, internal appearance, and visible thickness.

67. Cloud Structure — [Noticeable]

Clouds may contain edges, cores, turrets, bulges, layers, anvils, and precipitation-bearing regions. Not every cloud should contain every component.

68. Cloud Dissipation — [Noticeable]

Clouds should gradually shrink, deform, fragment, disperse, or disappear as their supporting conditions change.

69. Cloud Identity and Persistence — [Moderately noticeable]

Clouds should preserve their identity while moving and evolving. Repeatedly deleting and replacing clouds should be avoided when it causes visible discontinuities.

70. Cloud Movement — [Noticeable]

Clouds should move coherently with their assigned wind fields, avoiding unnecessary jumps, flickering, and abrupt replacement.

4.2 Adaptive Cloud Cell System (ACCS)

71. Adaptive Cloud Cell System — [Noticeable]

EWA proposes an advanced three-dimensional geometry architecture called the Adaptive Cloud Cell System (ACCS).

ACCS is a proposed system for building cloud volume from deformable three-dimensional cells. It is intended to provide a more flexible alternative to relying entirely on fixed cloud models or ordinary two-dimensional particles.

The system is currently a design concept. Its implementation and compatibility with Minecraft Bedrock have not been established.

72. Initial Cloud Cell — [Noticeable]

A cloud structure may begin with a small three-dimensional cell. The initial cell is conceptually cube-shaped and provides a starting geometry for cloud development.

The cell is not intended to represent a Minecraft block. It is a geometric volume unit in the proposed cloud architecture.

73. Five-by-Five Surface Grid — [Noticeable]

Each of the six faces of an initial cell should contain a 5 × 5 vertex arrangement.

This means:

- Six faces per cell.
- Twenty-five grid vertices counted on each face.
- One hundred and fifty face-level vertex references if each face is counted independently.

Shared vertices along edges and corners should be reused where the mesh representation permits it.

74. Shared Vertex Structure — [Subtle]

When adjacent faces share their edge and corner vertices, a 5 × 5 grid on each of the six faces produces 98 unique surface vertices.

The 150 face-level references and 98 unique surface vertices describe two different counting methods. They must not be confused during implementation.

75. Cell Surface Deformation — [Noticeable]

The cell's surface vertices should be capable of moving from their initial positions. This allows the cell to develop rounded, irregular, elongated, flattened, or otherwise deformed shapes.

76. Adaptive Cell Expansion — [Noticeable]

Cells should be able to increase their dimensions as the cloud grows. Expansion should follow the cloud's intended morphology and atmospheric development rather than occurring as an arbitrary scale change.

77. Shape-Dependent Cell Subdivision — [Noticeable]

If an existing cell cannot represent the required cloud shape with sufficient detail, the system may create additional cells or subdivide the affected region.

New cells should be introduced only where additional geometric resolution is justified.

78. Adaptive Surface Detail — [Noticeable]

As a cell becomes larger, its original vertex spacing may become too wide to represent small curves and surface irregularities.

The system should identify areas where the geometry becomes visibly too flat or insufficiently detailed and add local subdivisions where needed.

79. Localized Refinement — [Moderately noticeable]

Subdivision should be concentrated in areas that need additional detail. A cloud should not automatically receive the same maximum geometric resolution everywhere.

80. Cell-to-Cell Connection — [Noticeable]

Adjacent cells should form a coherent cloud structure. Their geometry should connect or blend where the intended cloud shape requires a continuous surface.

81. Internal Surface Removal — [Noticeable]

When two cells meet or overlap, internal faces should not remain visible as artificial walls inside the combined cloud structure.

The system should investigate surface merging, hidden-face removal, shared boundaries, or another suitable geometry method.

82. Seamless Cloud Volume — [Noticeable]

The visual result should not resemble a collection of disconnected cubes. Cell boundaries should not create unwanted visible seams, hard walls, or obvious geometric intersections.

83. Internal Volume Representation — [Moderately noticeable]

The cloud is intended to represent a filled volume rather than automatically becoming hollow when internal faces are removed.

Removing internal visual surfaces does not mean deleting the cloud's internal volume or atmospheric data.

84. Optional Hollow Regions — [Moderately noticeable]

If a future cloud type or specialized visual effect intentionally requires a hollow region, that behavior may be supported separately. Hollow space must not occur accidentally because cell surfaces overlap.

85. Cell Collision and Contact — [Moderately noticeable]

Cell interactions may require geometric collision or contact detection. This should be treated separately from whether a cell boundary is visible.

86. Collision Without Visible Internal Walls — [Noticeable]

The system should preserve necessary collision or contact behavior without rendering internal walls between connected cells.

A collision boundary does not need to appear as a visible wall in the final cloud.

87. Cell Shape Continuity — [Noticeable]

Connected cells should transition smoothly enough to preserve the intended cloud silhouette and avoid sudden shape discontinuities.

88. Cell-Level Shading — [Noticeable]

Shading should respond to surface orientation, light direction, cloud thickness, and nearby cloud geometry. Individual cells should not appear as unrelated solid cubes.

89. Volumetric Appearance — [Noticeable]

The final cloud should create a volumetric appearance, with soft internal depth, atmospheric scattering approximations, and suitable density transitions.

The term volumetric describes the intended visual result. It does not guarantee that Bedrock will support true volumetric ray marching.

90. ACCS Performance Management — [Moderately noticeable]

The number of cells, vertex updates, subdivision operations, surface calculations, and rendering operations must be controlled.

ACCS should investigate local updates, cached geometry, update budgets, and other methods that avoid rebuilding the entire cloud every simulation step.

91. ACCS State Preservation — [Moderately noticeable]

Cloud cells should preserve relevant shape, connection, and development information when rendering is skipped or the player moves away.

92. ACCS Geometry Validation — [Moderately noticeable]

The system should detect invalid geometry, unwanted gaps, overlapping surfaces, excessive subdivision, and other structural problems where the chosen implementation permits it.

93. ACCS Cloud-Type Support — [Noticeable]

ACCS should support different cloud morphologies without forcing every cloud type to use the same geometric structure.

Rounded cells may be useful for cumulus formations, while fibrous, layered, or elongated geometry may be more appropriate for other cloud types.

94. ACCS and Cloud Growth — [Noticeable]

Cloud growth should be able to modify existing cells, create new cells, and refine geometry according to simulated atmospheric conditions.

95. ACCS Development Status — [Noticeable]

ACCS is a proposed architecture, not an implemented Minecraft feature. Its feasibility must be established through small modeling and rendering experiments before it becomes part of a working EWA build.

4.3 Cloud Lighting and Color

96. Atmospheric Lighting — [Noticeable]

Cloud lighting should respond to sunlight direction, illumination intensity, time of day, atmospheric conditions, and cloud structure.

97. Directional Sun Illumination — [Moderately noticeable]

A proposed Sun Direction Indicator should estimate the sun's direction and determine which cloud surfaces receive direct illumination.

98. Illuminated Cloud Regions — [Noticeable]

Cloud surfaces facing the light source should receive stronger illumination where appropriate.

99. Shadowed Cloud Regions — [Noticeable]

Cloud regions facing away from the light source or obscured by other structures should appear darker.

100. Cloud Self-Shadowing — [Noticeable]

Cloud structures should influence the apparent lighting of other cloud regions. Approximation may be necessary if full volumetric shadowing is unavailable.

101. Daytime Cloud Colors — [Noticeable]

Cloud colors should depend on illumination, density, atmospheric conditions, and surrounding sky color.

102. White Clouds — [Noticeable]

Well-illuminated cloud regions should remain bright while retaining structural detail.

103. Intermediate Gray Values — [Noticeable]

Subtle shading should distinguish cloud structures without artificial, excessively harsh boundaries.

104. Dark and Near-Black Clouds — [Noticeable]

Dark cloud regions should represent suitable combinations of thickness, shadowing, and illumination. Near-black colors should not be applied indiscriminately.

105. Sunrise and Sunset Colors — [Noticeable]

Cloud colors should respond to sunlight direction and color.

106. Directional Sunset Illumination — [Noticeable]

Clouds should not simply become uniformly orange. Illumination should depend on the direction of sunlight and cloud orientation.

107. Orange Cloud Palette — [Noticeable]

A proposed visual range contains seven orange-related levels, from slightly orange to very dark orange. These should remain distinguishable from ordinary storm shading.

108. Nighttime Cloud Colors — [Noticeable]

A proposed nighttime range includes dark white, gray, dark gray, black, and progressively darker shades, depending on available illumination.

109. Lightning Illumination — [Noticeable]

Lightning should briefly illuminate nearby cloud structures where technically feasible.

110. Storm Lighting Effects — [Noticeable]

Lightning should reveal cloud depth and structure without permanently glowing or excessively brightening the entire sky.

111. Environmental Color Reflection — [Moderately noticeable]

Greenish, bluish, and other atmospheric tints may be represented through suitable lighting approximations.

112. Continuous Color Variation — [Noticeable]

Cloud shading should support smooth transitions instead of relying entirely on a small set of fixed color levels.

113. Large Color Range — [Moderately noticeable]

The design goal is to support a broad range of possible cloud appearances through combinations of illumination, tint, opacity, and shading. Millions of possible combinations are an ambition, not a verified technical capability.

114. Visual Compatibility — [Moderately noticeable]

Compatibility with other lighting and visual add-ons must be evaluated through testing.

115. Cloud Sound Effects — [Subtle]

Cloud-related weather audio should be associated with suitable environmental conditions and events rather than repeated without context.

---

PART V — THUNDERSTORMS AND SEVERE WEATHER

116. Natural Thunderstorm Development — [Noticeable]

Thunderstorms should emerge from suitable atmospheric conditions rather than relying entirely on random spawning or a rigid universal sequence.

117. Independent Storm Cells — [Noticeable]

Individual storm cells should maintain their own local atmospheric and structural characteristics.

118. Storm Cell Interaction — [Noticeable]

Nearby cells may influence one another through outflow, downdrafts, updrafts, gust fronts, wind changes, convergence, and precipitation interactions.

119. Multicell Storms — [Noticeable]

Multiple cells may coexist, develop, weaken, and interact.

120. Squall Lines — [Noticeable]

Storm cells may organize into larger linear systems when environmental conditions support such organization.

121. Supercell Architecture — [Noticeable]

Supercells should be represented as organized thunderstorms with persistent rotating updrafts under suitable conditions.

122. Mesocyclones — [Noticeable]

A rotating storm updraft may be represented as a mesocyclone. A mesocyclone must not automatically generate a tornado.

123. Wall Clouds — [Noticeable]

Wall clouds may develop beneath suitable regions of organized storms.

124. Shelf Clouds — [Noticeable]

Shelf clouds should form along suitable gust fronts and outflow boundaries.

125. Flanking Lines — [Noticeable]

Flanking-line cloud structures may develop alongside suitable organized thunderstorms.

126. Overshooting Tops — [Noticeable]

Strong updrafts may produce cloud turrets extending above the surrounding anvil.

127. Updraft Regions — [Moderately noticeable]

Rising air should transport moisture and precipitation particles and influence cloud growth.

128. Downdraft Regions — [Moderately noticeable]

Descending air should influence precipitation, cold outflow, and storm organization.

129. Storm Inflow — [Moderately noticeable]

Air entering a storm should influence its development and organization.

130. Storm Outflow — [Noticeable]

Rain-cooled air spreading away from a storm may produce gust fronts and influence new convection.

131. Forward-Flank Regions — [Noticeable]

Forward-flank precipitation regions may contain substantial rainfall or hail.

132. Rear-Flank Regions — [Moderately noticeable]

Rear-flank airflow and precipitation structures may be represented in suitable rotating storms.

133. Hail Cores — [Noticeable]

Hail-bearing regions should be distinguishable from ordinary rainfall.

134. Storm Dissipation — [Noticeable]

Storms should weaken as their simulated atmospheric support diminishes. Their internal development states must not force every storm to follow identical phases.

---

PART VI — LIGHTNING AND ELECTRICAL PROCESSES

135. Charge Separation — [Moderately noticeable]

Lightning should originate from an approximation of electrical charge separation within storm clouds.

136. Ice-Particle Interactions — [Subtle]

Interactions between ice particles, graupel, and other hydrometeors may contribute to simulated electrical charge separation.

137. Electrical Field — [Moderately noticeable]

The system may represent an approximate electrical field within suitable storm regions.

138. Intracloud Lightning — [Noticeable]

Lightning may occur within a single cloud.

139. Cloud-to-Ground Lightning — [Noticeable]

Lightning may discharge between a storm cloud and the ground.

140. Cloud-to-Cloud Lightning — [Noticeable]

Lightning may occur between separate cloud regions under suitable conditions.

141. Positive Cloud-to-Ground Lightning — [Noticeable]

Positive cloud-to-ground discharges may be represented as a distinct electrical event.

142. Lightning Distribution — [Noticeable]

Lightning location and frequency should be influenced by simulated electrical and storm conditions.

143. Thunder Timing — [Noticeable]

Thunder should follow lightning with a delay approximating the distance between the player and the discharge.

144. Lightning Illumination — [Noticeable]

Lightning should briefly illuminate nearby cloud structures and the environment where supported.

145. Electrical Simulation Limitations — [Moderately noticeable]

Electrical activity must be identified as an approximation unless the implementation supports more detailed physical modeling.

---

PART VII — PRECIPITATION AND HYDROMETEOROLOGY

146. Cloud Water — [Moderately noticeable]

Cloud moisture should influence precipitation potential.

147. Condensation — [Subtle]

The system should approximate how atmospheric moisture condenses under suitable conditions.

148. Droplet Growth — [Subtle]

Cloud droplets may grow through simplified microphysical processes.

149. Collision and Coalescence — [Subtle]

Droplet interactions may contribute to rainfall development.

150. Rainfall Intensity — [Noticeable]

Rainfall should vary according to cloud structure and simulated atmospheric conditions.

151. Drizzle — [Noticeable]

Light precipitation should be distinguishable from heavier rainfall.

152. Heavy Rain — [Noticeable]

Heavy precipitation should be associated with suitable cloud and storm structures.

153. Localized Precipitation — [Noticeable]

Rain should be distributed locally beneath precipitation-producing cloud regions rather than automatically covering the entire world.

154. Rain Shafts — [Noticeable]

Dense precipitation regions should form recognizable rain shafts.

155. Wind-Displaced Rainfall — [Noticeable]

Wind should be able to move precipitation away from the cloud's apparent horizontal position.

156. Virga — [Noticeable]

Precipitation may evaporate before reaching the ground.

157. Hail Formation — [Moderately noticeable]

Hail growth should be associated with freezing and suitable updraft conditions.

158. Hail Properties — [Noticeable]

Hailstones may vary in size, mass, density, velocity, trajectory, and impact behavior.

159. Hail Accumulation — [Noticeable]

Hail may accumulate on surfaces through a controlled approximation that avoids excessive world updates.

160. Hail Impact — [Noticeable]

Impact effects may depend on mass, velocity, and material durability. Damage must be configurable and performance-aware.

161. Other Precipitation Types — [Noticeable]

Additional precipitation types may be considered where their required environmental conditions can be represented.

---

PART VIII — TORNADO SYSTEMS

162. Tornado Formation — [Noticeable]

Tornado formation should depend on suitable storm and atmospheric conditions. A rotating cloud or mesocyclone alone must not automatically create a tornado.

163. Tornado Development — [Noticeable]

Tornado development should emerge from interacting environmental conditions rather than an identical fixed sequence.

164. Tornado Lifecycle — [Noticeable]

Formation, development, intensification, weakening, and dissipation may be tracked as descriptive states, not mandatory scripted phases.

165. Tornado Morphology — [Noticeable]

Tornado geometry should adapt to simulated circulation. Potential visual forms include rope, cone, stovepipe, wedge, bowl-shaped, elephant-trunk-like, hourglass, irregular, multivortex, and other documented appearances. Morphology must not be treated as a guaranteed intensity measurement.

166. Rope Tornadoes — [Noticeable]

Narrow, elongated tornadoes may have curved and irregular structures.

167. Cone Tornadoes — [Noticeable]

Cone tornadoes may have a tapered circulation profile.

168. Stovepipe Tornadoes — [Noticeable]

Stovepipe tornadoes may have a comparatively broad column-like appearance.

169. Wedge Tornadoes — [Noticeable]

Wedge tornadoes may occupy a broad visible area. Apparent width must not be treated as a reliable measurement of intensity.

170. Irregular Tornadoes — [Noticeable]

Tornadoes should support changing width, asymmetrical edges, and nonuniform structures.

171. Multivortex Tornadoes — [Noticeable]

A parent circulation may contain smaller subvortices.

172. Twin Tornadoes — [Noticeable]

Multiple tornadoes may occur within the same general storm environment when conditions support separate circulations.

173. Satellite Tornadoes — [Noticeable]

A smaller tornado may occur near a larger circulation in a suitable storm scenario.

174. Rain-Wrapped Tornadoes — [Noticeable]

Precipitation may obscure tornado visibility.

175. Tornado Motion — [Noticeable]

Tornado movement should be associated with its parent storm and surrounding environmental steering field.

176. Tornado Path — [Noticeable]

The path should respond to movement and environmental conditions rather than being limited to a predetermined straight line.

177. Tornado Sway — [Noticeable]

Narrow tornadoes may bend or change orientation according to their simulated airflow.

178. Tornado Wind Field — [Moderately noticeable]

The system should approximate rotational wind behavior and spatial variation.

179. Tornado Debris — [Noticeable]

Debris selection should depend on nearby environmental materials, with properties such as material, size, mass, rotation, trajectory, collision, and falling behavior. Urban and forest environments should produce different visual debris patterns where feasible.

180. Tornado Damage — [Noticeable]

Damage should depend on simulated wind, exposure, duration, distance, and material durability. Player-built structures must be protected by configurable rules.

181. Tornado Sound — [Noticeable]

Audio should reflect distance and environmental conditions.

182. Tornado Dissipation — [Noticeable]

Tornadoes should gradually weaken and disappear when their supporting circulation diminishes.

183. Tornado Intensity Categories — [Moderately noticeable]

A custom gameplay intensity system may be developed, but it must not be presented as an official meteorological rating system.

184. Fujita and Enhanced Fujita Scales — [Moderately noticeable]

The official Fujita and Enhanced Fujita scales range from F0–F5 and EF0–EF5 respectively. The Enhanced Fujita scale is based on damage indicators and estimated wind speeds, not direct wind measurements. Any custom extension must be clearly identified as fictional.

185. Extreme Tornado Settings — [Noticeable]

Exaggerated sandbox settings may be included for experimentation. For example, a proposed 1,500 mph setting is fictional gameplay, not a realistic ordinary tornado measurement.

186. Landspouts — [Noticeable]

Landspouts should be distinguished from typical supercell tornadoes because their formation mechanisms differ.

187. Waterspouts — [Noticeable]

Waterspouts may occur over suitable bodies of water.

188. Dust Devils — [Noticeable]

Dust devils should be treated as a separate surface-vortex phenomenon, not as tornadoes.

189. Tornado Visibility — [Noticeable]

Visibility should depend on condensation, debris, precipitation, lighting, and viewing conditions.

---

PART IX — WIND, COASTAL WEATHER, AND TROPICAL SYSTEMS

190. Global Wind Movement — [Noticeable]

Clouds and weather systems should move according to a coherent wind model.

191. Regional and Local Wind — [Noticeable]

Local wind may differ from regional and global wind because of terrain, convection, storm outflow, and other influences.

192. Wind Effects — [Noticeable]

Wind may influence clouds, debris, precipitation, vegetation, particles, and selected environmental interactions.

193. Wind Gusts — [Noticeable]

Wind speed and direction should be capable of changing over time.

194. Coastal Weather — [Noticeable]

Coastal environments may exhibit simplified sea-breeze and land-breeze circulation.

195. Ocean Currents — [Moderately noticeable]

A future system may approximate ocean currents and their environmental interactions.

196. Tropical Cyclones — [Noticeable]

Tropical cyclones may contain organized circulation, spiral rainbands, a central region, and other recognizable structures.

197. Tropical Cyclone Development — [Noticeable]

Cyclone development should depend on suitable environmental conditions rather than arbitrary spawning alone.

198. Tropical Cyclone Lifecycle — [Noticeable]

Development, intensification, maturity, weakening, and dissipation may be represented as descriptive states.

199. Cyclone Classification — [Moderately noticeable]

The official Saffir–Simpson Hurricane Wind Scale ranges from Category 1 to Category 5. It classifies hurricanes using sustained wind speed, not every possible cyclone impact. Additional EWA categories must be identified as custom gameplay classifications.

200. Storm Surge — [Noticeable]

A simplified storm-surge effect may be explored for coastal environments.

---

PART X — FOG AND ATMOSPHERIC VISIBILITY

201. Fog Formation — [Noticeable]

Fog should depend on suitable temperature, moisture, and atmospheric conditions.

202. Radiation Fog — [Noticeable]

Fog may form through surface cooling under suitable conditions.

203. Advection Fog — [Noticeable]

Fog may develop when moist air moves over a cooler surface.

204. Upslope Fog — [Noticeable]

Air forced upward along terrain may cool and produce fog.

205. Evaporation Fog — [Noticeable]

Fog may form when moisture enters relatively cooler air.

206. Fog Density — [Noticeable]

Fog thickness should vary dynamically.

207. Fog Visibility — [Noticeable]

Visibility should decrease according to fog density and atmospheric conditions.

208. Fog Movement — [Noticeable]

Wind and terrain should influence fog movement where appropriate.

209. Fog and Ground Visibility — [Moderately noticeable]

Ground-level fog should be managed separately from distant cloud visibility.

210. Exposure Effects — [Moderately noticeable]

Optional gameplay effects may be associated with prolonged exposure to selected environmental hazards. Ordinary short exposure to normal fog should not automatically trigger arbitrary penalties.

---

PART XI — VOLCANIC SYSTEMS AND ASH

211. Volcanic Systems — [Noticeable]

A future expansion may simulate volcanic activity as a geological system interacting with the atmosphere.

212. Volcanic Eruptions — [Noticeable]

Different eruption styles may be represented using configurable visual and environmental effects.

213. Volcanic Ash Plumes — [Noticeable]

Ash clouds should have recognizable vertical development, opacity, and movement. They must not behave exactly like ordinary water clouds.

214. Ash Particle Properties — [Moderately noticeable]

Ash particles may vary in size, concentration, and transport behavior.

215. Ash Transport — [Noticeable]

Ash should move according to global, regional, and local wind fields.

216. Ash Visibility — [Noticeable]

Visibility should decrease according to ash concentration, distance, and lighting.

217. Ash Deposition — [Noticeable]

Ash may accumulate on selected surfaces through an efficient approximation.

218. Ash and Rain Interaction — [Moderately noticeable]

Rain may interact with airborne and deposited ash.

219. Ash Exposure — [Moderately noticeable]

Optional gameplay effects may represent environmental exposure to volcanic ash. These effects must not be presented as real-world medical guidance.

220. Volcanic Lightning — [Noticeable]

Lightning-like flashes may be represented in suitable eruption scenarios as an approximation of electrical activity associated with ash and particle interactions.

221. Fictional Environmental Hazards — [Noticeable]

Fictional hazards must be clearly separated from scientifically documented phenomena.

---

PART XII — CLIMATE AND LARGE-SCALE ATMOSPHERIC CIRCULATION

222. Regional Climate — [Moderately noticeable]

Different regions may have different temperature, humidity, wind, cloud, and precipitation characteristics.

223. Seasonal Variation — [Noticeable]

Seasonal changes may influence atmospheric conditions and weather patterns.

224. Latitude Effects — [Moderately noticeable]

Latitude may influence simulated temperature, sunlight, and atmospheric circulation.

225. Global Atmospheric Circulation — [Moderately noticeable]

A future system may approximate major global circulation patterns.

226. Hadley Cells — [Moderately noticeable]

The Hadley circulation may be represented through a simplified large-scale atmospheric model.

227. Ferrel Cells — [Moderately noticeable]

The Ferrel circulation may be included as part of an approximate global circulation system.

228. Polar Cells — [Moderately noticeable]

Polar circulation may be represented through simplified high-latitude atmospheric behavior.

229. Monsoon Systems — [Noticeable]

Monsoon patterns may influence seasonal wind and precipitation distribution.

230. ENSO — [Moderately noticeable]

El Niño and La Niña may be represented as large-scale climate variability scenarios, not ordinary local weather events.

231. Climate Timescales — [Moderately noticeable]

Climate behavior and short-term weather behavior must be treated as different timescales.

232. Regional Weather Frequency — [Moderately noticeable]

Regional climate may influence the frequency and characteristics of selected weather phenomena.

233. Climate and Storm Interaction — [Moderately noticeable]

Climate conditions may influence the environmental background in which storms develop.

---

PART XIII — ENVIRONMENTAL INTERACTIONS AND HYDROLOGY

234. Terrain Interaction — [Noticeable]

Elevation, slope, terrain shape, and surrounding geography may influence atmospheric and environmental systems.

235. Forest Environments — [Noticeable]

Forests may influence selected local environmental conditions and provide material for debris systems.

236. Desert Environments — [Noticeable]

Desert regions may exhibit different surface and atmospheric characteristics.

237. Urban Environments — [Noticeable]

Buildings and urban terrain may influence selected local wind and environmental interactions.

238. Player-Built Structures — [Noticeable]

Player-built structures may influence local environmental behavior where simulation scale and technical capabilities allow.

239. Rainfall Accumulation — [Noticeable]

Rainfall should contribute to a simplified environmental water-accumulation model.

240. Surface Runoff — [Noticeable]

Water movement should consider terrain slope and elevation.

241. Drainage — [Moderately noticeable]

A simplified drainage model may determine how accumulated water moves through the environment.

242. Ponding — [Noticeable]

Water may accumulate in low-lying areas.

243. River Overflow — [Noticeable]

Heavy rainfall may contribute to river overflow in suitable simulated environments.

244. Flooding — [Noticeable]

Flood behavior should consider rainfall, elevation, slope, surface properties, drainage, and nearby water systems.

245. Building Interactions — [Noticeable]

Flooding may interact with selected buildings and environmental structures.

246. Environmental Damage — [Noticeable]

Damage should depend on phenomenon intensity, exposure, material properties, and duration.

247. Environmental Recovery — [Moderately noticeable]

Selected environmental effects may recover over time. Player-built structures must not be automatically reset or restored without explicit system design.

---

PART XIV — SKY EVENTS AND ASTRONOMICAL VISUALS

248. Solar Eclipses — [Noticeable]

A future sky-event system may approximate solar eclipse appearances.

249. Lunar Eclipses — [Noticeable]

Lunar eclipses should be represented separately from ordinary lunar phases.

250. Blood Moon Appearance — [Noticeable]

A reddish lunar appearance may be represented as a visual event where appropriate.

251. Meteors — [Noticeable]

Meteors may appear as separate astronomical events.

252. Meteor Showers — [Noticeable]

Meteor showers may produce multiple visible meteor events.

253. Comets — [Noticeable]

Comet-like objects may be included as sky events.

254. Solar Halos — [Noticeable]

Halos may be represented as optical effects associated with sunlight and atmospheric ice crystals.

255. Lunar Halos — [Noticeable]

Lunar halos may be represented as corresponding optical phenomena.

256. Sun Dogs and Moon Dogs — [Noticeable]

Parhelia and corresponding lunar optical effects may be explored as specialized atmospheric lighting phenomena.

257. Night Sky — [Noticeable]

The nighttime sky may include richer star fields and atmospheric darkness.

258. Milky Way — [Noticeable]

A future visual expansion may represent the Milky Way.

259. Andromeda Galaxy — [Noticeable]

The Andromeda Galaxy may be included as a distant sky-rendering feature. These visuals do not prove that EWA has a complete orbital or astronomical simulation.

---

PART XV — WEATHER OBSERVATION AND INSTRUMENTS

260. Weather Stations — [Noticeable]

Weather stations may measure simulated temperature, humidity, pressure, wind, and rainfall.

261. Anemometers — [Noticeable]

Anemometers should display wind measurements derived from the same simulated atmosphere.

262. Barometers — [Noticeable]

Barometers may display atmospheric pressure.

263. Rain Gauges — [Noticeable]

Rain gauges may measure simulated precipitation accumulation.

264. Radiosondes — [Noticeable]

A radiosonde system may provide vertical atmospheric measurements.

265. Weather Radar — [Noticeable]

Radar should display an approximation of precipitation reflectivity and storm structure.

266. Doppler Velocity — [Noticeable]

A Doppler mode may represent radial motion toward or away from the radar.

267. Storm Tracking — [Noticeable]

Radar may track storm movement using successive observations.

268. Mesocyclone Indicators — [Noticeable]

Radar may display rotational signatures associated with suitable storm structures.

269. Hook Echo — [Noticeable]

A hook-like reflectivity structure may be represented where the simulated storm produces a suitable pattern.

270. Hail Indicators — [Noticeable]

Radar may display regions associated with possible hail. Radar signatures are indicators, not definitive proof of tornadoes or hail.

271. Satellite Observation — [Noticeable]

A future satellite system may display cloud coverage and selected atmospheric patterns.

272. Lightning Detection — [Noticeable]

Lightning detectors may display detected electrical events.

273. Shared Atmospheric Data — [Moderately noticeable]

Observation tools should use the same underlying simulated atmospheric data as the weather systems, rather than generating unrelated measurements.

---

PART XVI — CLOUD VISIBILITY, DISTANCE, AND RENDERING MANAGEMENT

274. Cloud Visibility Range — [Noticeable]

Cloud visibility should be managed separately from Minecraft's land render distance. The sky may show distant clouds even when terrain is no longer visible.

275. Atmospheric Cloud Fog — [Noticeable]

Distant clouds should gradually blend into the atmosphere through an appropriate cloud-visibility fog model, distinguishable from ground-level fog.

276. Full Structural Detail — [Noticeable]

The design goal is to preserve the same underlying cloud structural model regardless of distance. Actual rendering detail may still be constrained by Bedrock performance and rendering capabilities.

277. Visibility-Based Rendering — [Moderately noticeable]

Cloud components that cannot be seen by the player may be excluded from rendering. This is rendering culling, not permanent deletion of atmospheric data.

278. Cloud Data Preservation — [Moderately noticeable]

Cloud identity, geometry state, and relevant simulation information should remain available while rendering is skipped. Visible clouds should be restored from preserved state when they re-enter the viewing area.

279. Cloud Occlusion — [Noticeable]

Cloud structures should visually obscure other cloud structures where appropriate.

280. Horizon Integration — [Noticeable]

Distant clouds should blend naturally into the horizon.

281. Cloud Perspective — [Noticeable]

Cloud appearance should respond to viewing perspective without sudden visual popping.

282. Cloud Boundary System — [Noticeable]

Cloud boundaries should change gradually as the cloud develops or interacts with surrounding atmospheric conditions.

283. Cloud Edge Turbulence — [Moderately noticeable]

Cloud edges may display subtle structural changes representing turbulent mixing.

284. Cloud Fragmentation — [Noticeable]

Clouds should be capable of separating into smaller formations when their structure weakens or environmental conditions support fragmentation.

285. Cloud Merging — [Noticeable]

Nearby clouds may merge when their geometry and atmospheric conditions make the interaction appropriate.

286. Cloud Layer Interaction — [Noticeable]

Different cloud layers should overlap at different apparent heights.

287. Cloud Shadow Approximation — [Noticeable]

Cloud shadows should help communicate thickness and illumination direction where Bedrock supports the required effects.

288. Anvil Evolution — [Noticeable]

Anvils should evolve with the parent storm, including changes in horizontal spread, shape, and apparent thickness.

289. Anvil Overspread — [Noticeable]

Large anvils may gradually spread across the sky.

290. Anvil Dissipation — [Noticeable]

Anvils should gradually weaken and disperse as their supporting storm structure changes.

291. Shelf Cloud Evolution — [Noticeable]

Shelf clouds should evolve with their associated gust fronts and outflow boundaries.

292. Roll Cloud Motion — [Noticeable]

Roll clouds should move as coherent horizontal formations.

293. Mountain Wave Interaction — [Noticeable]

Airflow over mountains may produce wave clouds and related formations.

294. Orographic Cloud Changes — [Noticeable]

Clouds near mountains should form and evolve according to simplified terrain and airflow conditions.

---

PART XVII — ATMOSPHERIC CONTROL AND CUSTOM SCENARIOS

295. Atmospheric Control — [Noticeable]

Players may eventually be able to configure selected atmospheric variables and weather scenarios.

296. Natural Simulation Mode — [Noticeable]

Natural mode should allow weather phenomena to develop according to the simulated atmospheric environment.

297. Immediate Scenario Mode — [Noticeable]

Immediate mode may create selected scenarios quickly for testing and sandbox play. It must be identified as bypassing some or all natural development processes.

298. Phenomenon Controls — [Noticeable]

Players may enable or disable selected phenomena. Disabling one phenomenon should not automatically force another to occur.

299. Natural Occurrence — [Moderately noticeable]

Phenomenon occurrence should depend on environmental conditions, regional climate, season, and other relevant simulated variables.

300. Custom Scenario Parameters — [Noticeable]

Custom parameters may be available for testing and experimentation. Fictional values must be identified as gameplay settings.

---

PART XVIII — AUDIO AND ENVIRONMENTAL FEEDBACK

301. Dynamic Weather Audio — [Noticeable]

Audio should respond to phenomenon type, distance, intensity, and environmental conditions.

302. Spatial Thunder — [Noticeable]

Thunder should have directional and distance-related behavior where technically feasible.

303. Rain Audio — [Noticeable]

Rain audio should vary according to precipitation intensity and environmental context.

304. Wind Audio — [Noticeable]

Wind sound should respond to simulated wind strength and selected surroundings.

305. Tornado Audio — [Noticeable]

Tornado audio should reflect distance and the surrounding storm environment.

306. Environmental Acoustics — [Moderately noticeable]

Buildings and terrain may influence audio through simplified environmental approximations.

307. Audio Performance — [Subtle]

Sound effects should avoid excessive repetition and unnecessary simultaneous playback.

---

PART XIX — ATMOSPHERIC DATA AND SIMULATION ARCHITECTURE

308. Global Atmospheric Data — [Moderately noticeable]

Global state should represent broad atmospheric conditions.

309. Regional Atmospheric Data — [Moderately noticeable]

Regional state should represent conditions across larger local areas.

310. Local Atmospheric Data — [Moderately noticeable]

Local state should represent smaller-scale environmental and weather conditions.

311. Interconnected Data — [Moderately noticeable]

Global, regional, and local atmospheric states should influence one another where the model supports those relationships.

312. Dynamic Properties — [Subtle]

Minecraft Dynamic Properties may be investigated for storing selected persistent simulation information. They are a storage mechanism, not a complete atmospheric simulation engine.

313. Spatial Management — [Subtle]

The system should investigate organizing atmospheric information into manageable spatial regions.

314. Staggered Updates — [Subtle]

Simulation tasks should be distributed over time instead of updating every system simultaneously.

315. Update Budgets — [Subtle]

Each simulation subsystem should have a defined computational budget.

316. Simulation Scheduling — [Subtle]

Different systems may require different update frequencies. Cloud appearance, wind state, storm structure, and precipitation do not necessarily need identical update intervals.

317. Data Persistence — [Subtle]

Important atmospheric state should be preserved when practical.

318. Chunk and Region Management — [Subtle]

Simulation management should account for loaded areas, unloaded areas, and the limitations of Bedrock's world access.

319. Avoiding Unnecessary Entities — [Subtle]

The system should avoid creating excessive entities when a more efficient supported representation is available.

320. Avoiding Excessive Block Updates — [Subtle]

Damage, flooding, accumulation, and environmental interactions must use controlled update budgets.

---

PART XX — ADAPTIVE PERFORMANCE PRESETS

321. Performance Presets — [Noticeable]

EWA proposes four primary simulation presets: Lite, Balanced, High, and Ultra. They should retain the same general atmospheric model and core simulation concepts while adjusting simulation detail, update frequency, and resource-related parameters.

322. Lite — [Noticeable]

Designed to reduce computational and rendering demands, especially on less powerful devices.

323. Balanced — [Noticeable]

Designed as a general-purpose configuration balancing visual quality, simulation behavior, and performance.

324. High — [Noticeable]

Designed to allow greater simulation and visual detail on capable devices.

325. Ultra — [Noticeable]

Designed for devices that can handle the highest available simulation and visual workload. Ultra must not be assumed to work well on every mobile device.

326. User-Controlled Settings — [Noticeable]

Players should be able to select their preferred preset where the implementation supports it.

327. Performance Monitoring — [Moderately noticeable]

The development process should measure frame rate, frame time, memory consumption, and simulation cost.

328. Performance Target — [Moderately noticeable]

A previous design discussion proposed keeping additional performance cost around 5–10 FPS or less. This is an optimization target, not a guarantee. Actual performance must be measured on supported devices and Minecraft versions.

329. Performance and Structural Consistency — [Noticeable]

Cloud structural identity should remain consistent across performance presets wherever technically possible.

Lower presets may reduce update frequency, particle density, rendering distance, secondary effects, and other expensive visual operations. However, performance optimization should avoid making a cloud suddenly change identity, jump to a different shape, lose its atmospheric state, or visibly regenerate when the player changes settings.

The underlying simulation model should remain conceptually consistent. Lower settings may use cheaper approximations, but those approximations must be documented honestly.

330. ACCS Performance Scaling — [Moderately noticeable]

ACCS should be able to reduce expensive geometric operations under lower performance presets.

Possible adjustments include:

- Reducing the frequency of vertex updates.
- Limiting the number of new cells created in a given interval.
- Reducing subdivision in distant or visually unimportant regions.
- Reusing cached geometry where appropriate.
- Prioritizing visible cloud regions.
- Deferring nonessential geometry calculations.

These adjustments should preserve the cloud's underlying identity and atmospheric state. A lower preset should not automatically turn a detailed cloud into an unrelated shape.

331. Adaptive Geometry Budget — [Subtle]

A future geometry budget may control the maximum number of active cells, vertices, subdivisions, and geometry operations allowed within a defined update period.

The budget should be adjustable according to device capability and measured performance.

332. Structural Detail Consistency — [Noticeable]

When geometry detail is reduced, transitions should be gradual and visually controlled. The system should avoid sudden flat surfaces, obvious cube boundaries, visible internal walls, or abrupt cloud-shape changes.

---

PART XXI — CREATOR DEVELOPMENT AND LEARNING ROADMAP

333. Creator Learning, Development Preparation, and Toolchain — [Noticeable]

EWA is being developed as a long-term independent learning and creative project by a young creator from Indonesia.

In 2026, the creator is 11 years old and currently in Grade 6 of elementary school. The creator is still learning and planning the project. This is an important part of EWA's development history and must be represented honestly.

Before attempting to implement the full atmospheric simulation architecture, the creator needs to study and practice the foundational technologies required for Minecraft Bedrock add-on development.

A. Required Programming and Data Skills

JSON

JSON is essential for many Minecraft Bedrock resource-pack and behavior-pack definitions.

Learning objectives:

- Understanding JSON objects and arrays.
- Understanding strings, numbers, booleans, and null values.
- Learning correct syntax and structure.
- Understanding identifiers and namespaces.
- Reading and editing manifest files.
- Understanding resource and behavior definitions.
- Learning how to diagnose malformed JSON.
- Understanding version fields and dependency declarations.
- Organizing complex JSON files clearly.

Molang

Molang is a Minecraft expression language used in supported resource-pack systems.

Learning objectives:

- Understanding basic expressions.
- Learning variables and queries.
- Understanding mathematical operations.
- Learning conditional expressions.
- Understanding animation and rendering-related expressions.
- Learning how supported Molang queries differ between contexts.
- Testing expressions in small, controlled examples.
- Avoiding assumptions that every Molang feature is available in every Bedrock context.

JavaScript

JavaScript is important for supported Bedrock scripting systems.

Learning objectives:

- Understanding variables and data types.
- Learning functions.
- Understanding conditions and loops.
- Learning arrays and objects.
- Understanding events and callbacks.
- Learning basic error handling.
- Understanding supported Minecraft Script API modules.
- Learning entity, world, and block interactions.
- Understanding scheduling and performance.
- Learning how to organize code into manageable modules.

JavaScript implementation must use APIs supported by the actual target Minecraft version. Ordinary browser JavaScript capabilities must not be assumed to exist inside the Minecraft scripting environment.

B. Current Development Applications

The creator currently uses the following applications:

Purpose| Application
Coding and editing source files| VS Code Droid
File management| MiXplorer
Block textures and other image assets| Pixel Studio
Additional texture editing and artwork| ibis Paint

File manager update: MiXplorer is the current file-management application. FS File Manager is no longer listed as the current tool.

These applications are the creator's currently identified tools, not a guarantee that every application provides every feature needed by EWA.

C. Three-Dimensional Modeling Preparation

EWA's proposed cloud architecture requires more than ordinary image editing.

The creator may need to learn:

- Three-dimensional mesh modeling.
- Vertex, edge, and face structures.
- Mesh topology.
- Surface deformation.
- Three-dimensional coordinates.
- Mesh subdivision.
- Mesh merging.
- Surface normals.
- Materials and shading.
- Rigging and skeletal animation where useful.
- Animation keyframes.
- Geometry export and format conversion.
- Basic optimization of 3D assets.

A 3D modeling application should be selected according to Android compatibility, actual device performance, export support, and the availability of necessary modeling features.

Bone animation may be useful for animating parts of a model, but it is not automatically a replacement for ACCS. Adaptive cell subdivision, surface merging, and dynamic volume generation require additional technical systems.

D. Recommended Learning Order

1. Learn basic JSON syntax and structure.
2. Practice editing simple Bedrock manifests.
3. Learn the organization of resource packs and behavior packs.
4. Study Molang fundamentals.
5. Practice simple texture and visual-asset workflows.
6. Learn basic 3D modeling and mesh topology.
7. Practice vertex editing and mesh deformation.
8. Learn basic rigging and bone animation.
9. Learn JavaScript fundamentals.
10. Study the supported Minecraft Bedrock Script API.
11. Build small independent experiments.
12. Test each experiment in a controlled world.
13. Document errors, compatibility, and performance.
14. Combine only systems that have been independently tested.
15. Gradually develop EWA's larger architecture.

E. Small Experiments Before Large Systems

The creator should not attempt to implement every EWA feature at once.

A sensible learning progression is:

- A valid resource pack.
- A valid behavior pack.
- A simple custom texture.
- A basic custom entity or supported visual representation.
- A small script responding to an event.
- A controlled environmental variable.
- A simple weather-related visual experiment.
- A basic 3D mesh model.
- A mesh deformation experiment.
- A small skeletal animation experiment.
- A simple cloud geometry prototype.
- A controlled experiment with connected geometry.
- A documented performance test.
- A more complex integrated prototype.

Each experiment should have a clear objective and acceptance criteria.

F. Bedrock Compatibility

Every experiment must be checked against the actual Minecraft Bedrock version being targeted.

The existence of an experimental toggle does not guarantee that a particular API or feature is supported.

The creator has identified several available experimental options, but new experimental features should be investigated and discussed before being introduced into the project.

Version compatibility, minimum engine requirements, manifest formatting, Script API availability, rendering behavior, and device performance must be verified rather than assumed.

G. Mobile Development Constraints

The creator's intended development environment includes Android.

The long-term target includes mobile-friendly performance, with particular attention to devices around the 8 GB RAM class.

Memory extension or virtual RAM must not be treated as equivalent to physical RAM.

A successful experiment on a single device does not establish universal mobile compatibility.

The modeling application and the final Minecraft add-on also have different performance requirements. A model that can be edited on an Android device may still be too expensive to render or animate efficiently inside Minecraft.

H. Independent Development and AI Assistance

ChatGPT is used as an AI-assisted planning, explanation, research, and technical guidance tool.

AI assistance does not replace the creator's responsibility to understand, test, and verify the implementation.

The creator remains responsible for project decisions, original assets, testing, and the final development direction.

Important: Being 11 years old and still learning does not mean the entire project must be completed immediately. EWA is a long-term learning project. The creator can progress gradually, and the documentation should reflect actual progress instead of pretending that advanced systems are already operational.

---

DEVELOPMENT ROADMAP

The following roadmap is a proposed order of work, not a confirmed schedule.

Stage 1 — Foundations

- Learn JSON.
- Learn Molang.
- Learn JavaScript.
- Understand Bedrock resource packs and behavior packs.
- Understand manifests, identifiers, and dependencies.
- Practice basic debugging.

Stage 2 — 3D Modeling Foundations

- Learn mesh modeling.
- Understand vertices, edges, and faces.
- Practice 3D object deformation.
- Learn mesh subdivision.
- Explore mesh merging and surface topology.
- Learn basic rigging and bone animation.
- Test 3D export formats.

Stage 3 — Small Technical Experiments

- Test a simple resource pack.
- Test a simple behavior pack.
- Create and import original textures.
- Test supported entities and particles.
- Test basic scripting.
- Record compatibility and performance.

Stage 4 — Basic Cloud Geometry

- Create a basic three-dimensional cloud model.
- Test rounded cloud geometry.
- Test wispy geometry for Cirrus.
- Experiment with layered cloud geometry.
- Test shading and surface smoothness.
- Investigate geometry export and Bedrock compatibility.

Stage 5 — ACCS Research and Prototyping

- Create a small initial Cloud Cell.
- Test a 5 × 5 vertex grid on each face.
- Verify shared vertex handling.
- Test surface deformation.
- Test cell expansion.
- Investigate adaptive subdivision.
- Test connected cells.
- Investigate removal of internal surfaces.
- Test collision independently from visual surface rendering.
- Measure the cost of geometry updates.

ACCS should not be integrated into the complete weather system until its basic geometric behavior and technical feasibility have been established.

Stage 6 — Basic Atmospheric Model

- Define atmospheric variables.
- Establish a manageable spatial representation.
- Test temperature and humidity values.
- Test wind direction and speed.
- Establish simple regional and local data.

Stage 7 — Basic Weather Systems

- Develop simple cloud behavior.
- Test localized precipitation.
- Investigate fog and visibility.
- Test wind and environmental responses.
- Establish event continuity.

Stage 8 — Advanced Weather Systems

- Investigate organized thunderstorms.
- Develop storm observation.
- Explore advanced cloud morphology.
- Investigate lightning and severe weather.
- Test environmental interactions.

Stage 9 — Optimization and Integration

- Measure frame time.
- Measure memory consumption.
- Test different simulation workloads.
- Investigate culling and scheduling.
- Test mobile performance.
- Integrate only compatible and reliable systems.

Stage 10 — Documentation and Distribution

- Document implemented features.
- Record supported Minecraft versions.
- Provide known limitations.
- Prepare installation instructions.
- Test the final package.
- Prepare distribution only when the project is genuinely ready.

---

TECHNICAL LIMITATIONS AND SCIENTIFIC HONESTY

EWA's vision is ambitious, but Minecraft Bedrock is not a general-purpose scientific atmospheric modeling platform.

Several real-world processes may require substantial simplification.

Examples include:

- Full three-dimensional atmospheric fluid dynamics.
- High-resolution cloud microphysics.
- True volumetric ray marching.
- Physically accurate cloud self-shadowing.
- Full electromagnetic storm simulation.
- Realistic terrain-driven hydrological modeling.
- Complete global climate simulation.
- High-resolution radar signal processing.
- Fully physical debris dynamics.
- Dynamic adaptive mesh generation at runtime.
- Arbitrary mesh merging and deformation during gameplay.
- Large-scale volumetric collision calculations.

A visual approximation may resemble a real phenomenon without reproducing the complete underlying physics.

For example, a cloud may visually resemble a cumulonimbus while its internal growth is controlled by a simplified model.

Similarly, a cloud may use three-dimensional geometry without having a fully physical volumetric simulation.

ACCS is an ambitious proposed geometry architecture. Its intended behavior must be tested against the actual capabilities of Bedrock's resource-pack, entity, rendering, and scripting systems.

A visual prototype made in a standalone 3D modeling application does not prove that the same geometry can be dynamically generated, merged, deformed, and rendered inside Minecraft.

That distinction must remain explicit.

---

PERFORMANCE AND COMPATIBILITY POLICY

EWA should prioritize:

1. Stable frame time.
2. Controlled memory use.
3. Limited unnecessary entities.
4. Efficient particle usage.
5. Staggered simulation updates.
6. Controlled block updates.
7. Regional data management.
8. Rendering culling where supported.
9. Persistent atmospheric state.
10. Compatibility with the targeted Bedrock version.
11. Controlled cloud geometry complexity.
12. Efficient mesh and vertex updates.
13. Localized adaptive subdivision.
14. Separation of visual geometry and collision data where appropriate.

No performance target should be advertised as achieved until it has been measured.

The Lite, Balanced, High, and Ultra presets are design proposals. Their final behavior must be determined through implementation and testing.

An 8 GB RAM target is a development consideration, not a guarantee that every feature or combination will run smoothly.

---

DOCUMENTATION RULES

Every major feature should eventually have:

- A feature identifier.
- A clear description.
- Its scientific basis.
- Its intended player-visible behavior.
- Its visibility classification.
- Its technical dependencies.
- Its compatibility requirements.
- Its performance considerations.
- Its implementation status.
- Its testing conditions.
- Its known limitations.

A planned feature must not be described as implemented.

An experimental feature must not be described as completed.

A working prototype must not be described as a fully validated scientific simulation.

For major geometry systems such as ACCS, documentation should additionally record:

- Geometry structure.
- Vertex and face counts.
- Subdivision rules.
- Cell connection behavior.
- Surface-merging behavior.
- Collision behavior.
- Geometry update frequency.
- Memory usage.
- Rendering cost.
- Supported export formats.
- Bedrock compatibility results.

---

PROJECT SCALE AND FUTURE EXPANSION

The numbered entries in this document establish the current foundational project scope.

They do not represent the complete EWA vision.

There are still many additional features, subsystems, interactions, environmental processes, rendering ideas, simulation methods, observation tools, and technical systems that may be documented in future expansions.

The broader project concept contains potentially thousands of individual feature ideas and system components.

Those future ideas should be organized, reviewed, checked for scientific plausibility, evaluated for Bedrock feasibility, and prioritized according to development resources.

A large feature count does not automatically mean a better add-on. Each feature must have a clear purpose, a realistic implementation path, and a justified place in the overall architecture.

---

FINAL PROJECT STATEMENT

Elaphants Weather Add-on is a long-term independent Minecraft Bedrock project created with the ambition of bringing a more interconnected, scientifically informed, and visually immersive atmospheric experience into the game.

The creator is currently 11 years old in 2026, in Grade 6, and still learning the foundational technologies needed to begin implementation.

The immediate priority is not to rush into building thousands of features.

The immediate priority is to learn JSON, Molang, JavaScript, and three-dimensional modeling; understand Minecraft Bedrock's technical systems; practice with the available applications; and gradually turn the documented ideas into small working experiments.

EWA's development should remain honest, gradual, technically informed, and realistic about its limitations.

The project may become large, but it should be built one reliable step at a time.

Current numbered scope: 0–333.

Current implementation status: Planning and learning.

Current cloud geometry proposal: Adaptive Cloud Cell System (ACCS).

Release date: Not confirmed.

Future scope: Many additional features and systems remain to be documented.

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

One of the major ideas currently being explored is ACCS: a system that could build three-dimensional cloud structures from deformable cells, adaptive geometry, connected surfaces, and volumetric visual effects.

I know the project is ambitious. I also know that I still have a lot to learn. That is part of the journey.

Thank you for following the development of EWA.

And don't forget this project! 🌩️🌪️☁️

See you again later.

Goodbye, and see you next time! 👋😭

EWA — Elaphants Weather Add-on

An independent project from Indonesia.