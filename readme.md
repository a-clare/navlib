# NAVLib - CPP

### dev roadmap

- GNSS
- GNSS + INS
- GNSS + INS with different state estimators
- VO
- VO + GNSS
- VO + GNSS + INS

#### GNSS Roadmap

- rinex file reading
  - observations
  - nav ephemeris
- ephemeris calculations
- post process
  - static:
    - single point positioning GPS
    - single point positioning BeiDou
    - single point positioning multi frequency
    - single point positioning Galileo
    - single point positioning GLONASS
  - dynamic
    - repeat static
- code smoothing
- post process 
  - code only differential
- offline measurement analysis
  - single and double differences
  - code minus carrier
- atmospheric models
  - troposphere
  - ionosphere  
- post process
  - carrier phase float
  - carrier phase float linear combinations
- LAMBDA ambiguity resolution
- SP3 file reading of precise orbits
- post process
  - precise point positioning
- ublox file reading
- post processd ublox 
  - single point positioning
  - differential
  - precise point positioning
  
  

