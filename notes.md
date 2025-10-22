# Notes

My notes and thought process as I start planning out my thesis.

## The Concept

"Development of an advanced hydroplaning prediction tool"

- Building on previous hydroplaning tool
- Use existing models for predicting hydroplaning based on water film thickness (WFT)
- Improve models for estimating WFT based on
  - Rainfall rate
  - Cross-slope and grade
  - Texture/profile depth
  - Rutting
  - Pavement type

### How to improve these models?

- Use small pavement samples and vary angles to test actual WFT
- ~~CFD model~~ run on 3D models of samples
  - CFD may be outside the scope of the project
  - Tile solver based on equations developed from theory & real world data
- Develop empirical equations to predict WFT on one "tile"
- Final model combines effect from multiple tiles

### Final Tool

- Input continuous data from MPSV/other sources
  - Cross-slope
  - Grade
  - Texture
  - Design speed
- Report continuous hydroplaning risk for a roadway

## Implementation Details

### Sample Construction

- Need samples of pavement to collect actual WFT data from
  - Dense grade
  - Open grade (FC-5, FC-7, ...?)
  - Concrete (longitudinal ground, transverse ground, ...?)
- ~~For dense grade and concrete, 3D scan real roads and 3D print~~
- After discussing with concrete and asphalt labs, may be able to get real samples
  - Asphalt lab frequently makes 16x20 samples of dense and open
  - Need to do some calculations to know what sizes needed due to boundary layer effects
  - For concrete, easy to make small slabs with grout
  - Still can't grind, maybe include macrotexture in mould bottom

### How to measure WFT?

- Conductive height probe from above
- Add reference points ~~in 3D models~~
