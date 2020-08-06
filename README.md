# FPGA Addon Speciality IO

The **FPGA Addon Speciality IO** represents a collection of support files used by the [FPGA Addon Custom Device](https://github.com/ni/niveristand-fpga-addon-custom-device). It contains special IP for doing the following:
- PWM Generation - PWM.Generate.Digital(.vi)
- Sinewave Generation - Sine.Generate(.vi)
- Digital Static Generation - Static.Generate.Digital(.vi)
- Analog PWM Measurement - PWM.Measure.Analog(.vi)
- Digital PWM Measurement - PWM.Measure.Digital(.vi)
- Digital Static Measurement - Static.Measure.Digital(.vi)
- Digital Wheel Speed Sensor Simulation - WSS.Generate.Digital(.vi)
- Quadrature Encoder Measurement - QuadratureEncoder.Measure.Digital(.vi)

## LabVIEW Version

LabVIEW 2018

## Dependencies

### Running the add-on

- NI RIO >= 18.0

### Source

- NI RIO >= 18.0
- [LabVIEW FPGA Advanced Session Resources](https://decibel.ni.com/content/docs/DOC-35574)
- OpenG LabVIEW Data Library >= 4.2.0.21
- [VeriStand Addon Inline Async API](https://github.com/ni/niveristand-custom-device-inline-async-api)
- [VeriStand Addon Hardware Resource Discovery](https://github.com/NIVeriStandAdd-Ons/Hardware-Resource-Discovery)
- [VeriStand Addon System Definition Utilities](https://github.com/NIVeriStandAdd-Ons/VeriStand-Addon-System-Definition-Utilities)
- [HTML Help File Tools](https://github.com/NIVeriStandAdd-Ons/HTML-Help-File-Tools)
- [VeriStand Import and Export Tools](https://github.com/NIVeriStandAdd-Ons/VeriStand-Addon-CD-Import-and-Export-Tool)

## Git History & Rebasing Policy

Branch rebasing and other history modifications will be listed here, with several notable exceptions:
- Branches prefixed with `dev/` may be rebased, overwritten, or deleted at any time.
- Pull requests may be squashed on merge.

## License
The FPGA Addon Speciality IO is licensed under an MIT-style license (see LICENSE). Other incorporated projects may be licensed under different licenses. All licenses allow for non-commercial and commercial use.