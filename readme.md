# Notes

My notes and thought process as I start planning out my thesis.

## The Concept

Improve water film thickness (WFT) model in some way

- Known issues with current tool regarding pooling
- Potential places to improve WFT model:
  - Puddling due to positive puddle depth in ruts
  - Transition effects on adjacent planes
  - Possibly generalize to a provided transverse profile

## Implementation Details

### Sample Construction

- Need samples of pavement to collect actual WFT data from
  - Dense grade
  - Open grade (FC-5, FC-7, ...?)
  - ~~Concrete (longitudinal ground, transverse ground, ...?)~~ There are too many options of concrete and sample construction is difficult, limit scope to asphalt pavement
- Or figure out a way to test on real roads
- After discussing with asphalt lab, may be able to get real samples
  - Asphalt lab frequently makes 16x20 samples of dense and open
  - Need to do some calculations to know what sizes needed due to boundary layer effects
  - Some reading indicated that drainage (due to voids) on OGFC lessens significantly as the pavement settles to its final shape

### How to measure WFT?

- Conductive height probe from above
