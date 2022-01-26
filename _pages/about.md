---
title: "Sea-Pol Specification"
layout: single
excerpt: "Sea-Pol is a dual-polarization ship-deployable C-band radar
featuring dynamic platform stabilization"
permalink: /about/  
---

The CSU Sea-Pol ship- and land-deployable radar measures dual-polarization data over a range in excess of 200 km. The radar operates at C-band (5.65 GHz) and has a 4.3m stabilized antenna system. An inertial navigation unit (INU) measures ship motion and sends compensation commands to the antenna positioner. Doppler velocity data is also corrected for ship velocity. This permits high quality data to be collected at sea, correcting for ship roll and pitch up to 7 degrees. The radar operates in simultaneous transmit and receive mode, as well as horizontal-only mode, with a sensitivity of -7 dBZ at 100 km. A variety of pulse widths and PRFs are supported, within a 0.12% duty cycle limit.

<center><div>
<img src="/assets/seapol_piston2018.jpg" width="90%" alt="Sea-Pol in 2018"></div>
<p><small><italic> Sea-Pol radar deployed on R/V Thompson in 2018 </italic></small></p>
</center>

## Technical Data


| System Specifications     |    |
| ------------------------- | ---------------------------------------------- |
| Input power              | Single phase 240V/100A or 480V/50A, 60 Hz    |
| Power connection         | Meltric DS100 series 240V or 480V connectors |
| Typical radar power      | 4500 W                                       |
| Typical HVAC power       | 8000 W                                       |
| External data connection | Ethernet (CAT5e/fiber-optic)                 |
| Data rate required       | 10 Mb/s (min), 100 Mb/s (optimal)            |


| Antenna Platform and Radome     |    |
|--------------------------|----------------------------------------------|
| Radome type             | 5.4 m, fiberglass panels                      |
| Platform height         | 10ft/3m from decks |
| Total height      | 27ft/8.4m from deck   |
| Environmental Specifications    | 115 mph/185 km/h windspeed       |
| Radar shelter | 20’ ISO 1C container, with HVAC, insulation       |


| Pedestal    |    |
|---------------------|-------------------------------------------------------------|
| Type              | Elevation over azimuth        |
| Elevation limits       | -5° — 80° |
| Maximum scan rate      | 30 °/s<sup>2</sup> |
| Acceleration       | 12 °/s   |
| Position accuracy | < 0.1°                |
| Weight       |  800 kg         |


| Transmitter     |    |
|---------------------|-------------------------------------------------------------|
|   Type                   |   Coaxial magnetron SFD-373A   |
|   Modulator type         |   Solid state                  |
|   Frequency range        |   5.5 – 5.7 GHz                |
|   Peak power             |   250 kW                       |
|   Pulse widths           |   0.36, 0.67, 1.24 or 2.0 μs   |
|   Duty Cycle             |   0.12% maximum                |
|   Pulse Rep. Frequency   |   50 – 2400 Hz                 |
|   Average Power          |   300 W                        |
|   Polarization Modes     |   HV, H                        |


| Antenna     |    |
|---------------------|-------------------------------------------------------------|
|   Reflector diameter           |   4.3 m                      |
|   Gain (typical)               |   45 dBi                     |
|   Beam width                   |   < 1.0°                     |
|   Peak side lobes              |   < -27 dB (typ. < -30 dB)   |
|   Integrated X-pol isolation   |   < -29 dB                   |
|   X-pol isol. at boresight     |   < -40 dB                   |
|   H/V alignment                |   < 0.1 °                    |
|   Weight                       |   170                        |


| Signal Processing     |    |
|---------------------|-------------------------------------------------------------|
|   Signal processor                |   Vaisala RVP900                                 |
|   Azimuth averaging               |   2 – 1024 pulses                                |
|   Clutter filter                  |   Adaptive (GMAP), > 50 dB clutter suppression   |
|   Data outputs                    |   All dual-polarization moment data              |
|   Dual PRF velocity de-aliasing   |   2:3, 3:4 or 4:5                                |
|   IF digitization                 |   16 bit, 100 MHz                                |
|   Number of range bins            |   Up to 8168                                     |
|   Optional data output            |   Raw I/Q time-series                            |
|   Processing modes                |   Pulse pair, FFT                                |
|   Range resolution                |   54, 100, 180 or 300m                           |


| Radar Receiver     |    |
|---------------------|-------------------------------------------------------------|
|   Type              |   Dual-stage, dual-channel IF downconverter and digitizer   |
|   Noise figure      |   < 3.5 dB                                                  |
|   Dynamic Range     |   > 99 dB                                                   |
|   Image rejection   |   > 100 dB (including waveguide filters)                    |
|   Tuning range      |   5.5 – 5.7 GHz                                             |
|   First IF          |   442 MHz                                                   |
|   Second IF         |   60 MHz                                                    |
