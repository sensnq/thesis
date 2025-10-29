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

Summary report for a pretty big project. [Phase 1: Tentative Pavement and Geometric Design Criteria for Minimizing Hydroplaning](<https://rosap.ntl.bts.gov/view/dot/41846}>). Can't find Phase 2.

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

## Hydroplaning Models

## Water Film Thickness Models
