# Literature Review Notes

## General

### Enhanced Hydroplaning Prediction Tool

```tex
\cite{lee2020}
```

- Main goal was implementation of the tool, not improving models
- Good point of reference for other articles

### Tire Hydroplaning and Its Effects on Tire Traction

```tex
\cite{horne1968}
```

- Buildup of fluid pressure between tire and ground
- Three types of traction loss:
  - Dynamic hydroplaning
  - Viscous hydroplaning (thin-film lubrication)
  - Reverted rubber skid
- Affect from pavement texture, water depth, tread design, vertical load, and tire pressure
- "The Rolling Tire"
  - Dynamic pressure generated in tire groovewhen stagnation pressure generated at tire-water interface
  - Viscous pressure generated when the rubber of the tire rib cannot displace the thin film left on the smooth surface after most water is displaced
  - Hydroplaning occurs when the combined water pressure balances the tire-ground beating pressure across the tire footprint, lifting the tire off the surface
  - Research indicates the hydroplaning speed is proportional to the square root of tire pressure - not appropriate when viscous forces dominate
  - Viscous pressure builds up more rapidly with speed than dynamic pressure
  - Viscous hydroplaning more likely at lower speeds unless this pressure is reduced with pavement texture or tire tread design
- "The Skidding Tire - Dry Pavements"
  - Friction coefficient very dependent on slip ratio
  - Peak braking friction at 0.2 slip ratio due to tire elastic deformation
  - Side force friction quickly drops to 0 with high slip ratio - skidding tire makes almost no turning force
- "The Skidding Tire - Wet Pavements"
  - Friction greatly reduced by wet pavement, not yet fully understood
  - When tire is rotating, water passes easily through tread and drains. When locked, water flow is reduced and the water is trapped, just circulating in the tire footprint
  - "Reverted Rubber Skid"
    - Tire rubber heated to the point that it melts and reverts to uncured state
    - Occurs after long skid and creates low friction down to low speeds
    - Proposed that a braked tire on wet pavement gets hot enough to boil the water trapped in the tire footprint
    - Also possible that tire is carried on a cushion of steam
    - Only known to occur during aircraft landings, not cars
- "Techniques for Alleviating Tire Traction Losses From Tire Hydroplaning"
  - "Viscous Pressures Predominating - Viscous Hydroplaning"
    - Occurs when pavement is smooth, a viscous contaminant is present, or tire locks
    - Can occur during light precipitation due to thin film formed
    - Providing pavement texture alleviates the problem
    - Loss of traction due to skid can be eliminated with devices that prevent skids, like ABS
  - "Dynamic Forces Predominating - Dynamic Hydroplaning"
    - Only occurs when pavement is flooded, depends on tire tread and pavement design
    - Testing air jets in front of tires to clear water
  - "Steam Pressures Predominating - Reverted Rubber Skid"
    - Prevent tires from locking up

### Pavement and Geometric Design Criteria for Minimizing Hydroplaning

```tex
\cite{gallaway1979}
```

Summary report for a pretty big project. [Phase 1: Tentative Pavement and Geometric Design Criteria for Minimizing Hydroplaning](<https://rosap.ntl.bts.gov/view/dot/41846>). Can't find Phase 2.

Also from Gallaway (not exhaustive):

- [The Effects of Rainfall Intensity, Pavement Cross Slope, Surface Texture, and Drainage Length on Pavement Water Depths](<https://rosap.ntl.bts.gov/view/dot/84801>)
- [Influence of Water Depths on Friction Properties of Various Pavement Types](<https://rosap.ntl.bts.gov/view/dot/84802>)
- [Effects of Pavement Surface Characteristics and Textures on Skid Resistance](<https://rosap.ntl.bts.gov/view/dot/84800>)
- [Highway Friction Measurements with MU-Meter and Locked Wheel Trailer](<https://rosap.ntl.bts.gov/view/dot/84798>)

I will only look at the parts relavent to my project here.

- Chapter outline
  1. The phenomenon of hydroplaning
  2. Hydroplaning and traction tests under controlled conditions
  3. Minimizing hydroplaning conditions on PCC surfaces
  4. Determining the probability of selected rainfall intensities
  5. Pavement drainage
  6. Tire-pavement interactions on OGFC in simulated and natural rainfall
  7. Pavement cross-slope criteria as related to vehicle control
  8. Design criteria for drainage of sag vertical curves
  9. Criteria to reduce hydroplaning
  10. Summary and conclusions
- Chapter 1
  - Browne (2): Wet friction hydroplaning only happens with low pavement microtexture. High microtexture can break the water film
  - Several previous equations for predicted V<sub>h</sub> presented
  - Gengenbach (4): For treaded tires, no hydroplaning observed at water depth under 0.08 in
  - Force analysis of tire in hydroplaning
- Chapter 5
  - Looked at puddle depth due to cross-slope/rutting
  - Empirical and theoretical equations for water depth compared, see ref (11)
- Chapter 6
  - Internal drainage in OGFC greatly reduced after surface layer stabilizes

### Tentative Pavement and Geometric Design Criteria for Minimizing Hydroplaning

```tex
\cite{gallaway1975}
```

- Chapter outline
  1. The phenomenon of hydroplaning
  2. Empirical indications of hydroplaning
  3. Pavement drainage
  4. Surface texture, skid resistance, and accident frequency
  5. Pavement cross slope criteria as related to vehicle control
  6. A determination of deficiencies in existing surface drainage design methodology for sag vertical curves
  7. Summary of tentative criteria to reduce hydroplaning
  8. Tentative recommendations for construction
- Chapter 2
  - See ref (147)
  - Spin down trailer
    - Indicates change in magnitude/orientation of force on tire interface
    - Given as % change in rotational speed
    - Resultant force in spindown moves further forward on tire, line of action moves reducing torque on the wheel
    - Full dynamic hydroplaning can occur at spindown such as 10%, 50%, or even 101%
  - Drag link skid number trailer
    - Locks trailer and measures drag force
    - Includes hydrodynamic drag, so tire-pavement friction is overpredicted
  - Torque skid number trailer
    - Uses a torque transducer. Gives a better estimate of tire-pavement friction
  - Interpretation of hydroplaning data
    - Small speed difference between 10% and 50% SD, so 10% used as hydroplaning indicator
    - Fit equation for hydroplaning speed based on spindown, pressure, tread depth, texture depth, and water thickness
    - Not sensitive to texture depth below ~0.03in
    - Deterioration of control during hydroplaning occurrs gradually over about 20 mph. It seems abrupt beause on a straight road very little friction is required to maintain direction about 0.1. The drop from 0.1 to 0 takes place in 1 or 2 mph or with slight change in water or texture depth
    - Transverse texture provides better drainage than longitudinal
    - Transverse texture is better at draining the tire-pavement contact patch
    - Transverse texture resists forward water movement that creates the tire water wedge
    - Longitudinal texture is better for cornering friction
- Chapter 3
  - Thin film of water increases in thickness as it flows to edge of pavement
  - While flow is below the top of pavement microasperities (texture), flow can be considered like porous media with free surface. -> Negative water depth
  - Turns to open channel flow once water surface covers texture
  - For porous flow, Darcy's law (look into this)
  - Ackers (ref 8) gives an equation for open channel flow
  - (Refs 9 and 10) looking at critical Froude number for open channels
  - Real rainfall water depth tests from (ref 11)
  - Effects of rainfall impact neglected. This would cause turbulence at lower critical Froude number values
  - Depression storage is the amount of water required to fill the surface before runoff
  - Surface detention is the sheet of water on the surface at constant runoff
  - Surface detention also causes splash, and depression storage causes spray after rainfall is over
  - (Refs 2 and 12) give more limited equations for water depth
  - Equations for equivalent slope and drainage length
- Chapter 4
  - (Ref 24) high dependence of water depth on wind speed and direction
  - Microtexture very important for wet friction in viscous hydroplaning but also increases tire wear
  - Macrotexture important for dynamic hydroplaning, but aggregate above ~15mm causes road noise concerns
  - (Ref 31) used a drainage meter to evaluate hydraulic radius of flow between tire and pavement
  - (Ref 32) used outflow device to evaluate wet weather performance
  - Equations given to predict SN from various factors
