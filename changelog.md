# JCS changelog

## 0.3.2 - 24/06/2025
- jcs_host: Bugfix for first two datapoints being zero

---

## 0.3.1 - 11/06/2025
- dev_motor_controller: Add D-axis flux braking capability
- dev_motor_controller: Add controllers for safe e-stop handling
- dev_motor_controller: Add current controller input and command low pass filters
- dev_motor_controller: Device rates are reduced from 15kHz to 10kHz for all devices
- dev_motor_controller: Add virtual gearbox
- dev_motor_controller: Add unwrapped encoder position support
- dev_motor_controller: Add support for new hardware
- dev_motor_controller: Temperature warnings and error limits are now configurable
- dev_motor_controller: Bugfix for host watchdog. No longer fires early after startup
- dev_encoder_absolute: Add unwrapped encoder position support
- all: E-stop propagation to network is now optional
- dev_braking_chopper: Add support for new hardware
- dev_braking_chopper: Add oscilloscope support
- dev_load_switch: Add support for new hardware
- dev_strain_gauge: Add command to zero offsets
- all: Add whole network firmware loading support. Can now update all devices on the network at once.
- all: Add support for recording multiple errors
- all: Add hysteresis to all limit checkers
- dev_joint_controller: Host watchdog timeout is now configurable
- dev_joint_controller: Add unwrapped encoder position support

NOTE: This release is a major network update. 0.3.x versions are NOT compatible with 0.2.x versions or earlier.

---

## 0.2.2 - 19/02/2025
- dev_encoder_absolute_jcs: Add default PLL estimator
- dev_encoder_absolute_jcs: Clear velocity warning flag at startup

---

## 0.2.1 - 04/11/2024
- dev_motor_controller: Check AS5047p SPI for stale data before TX
- dev_motor_controller: Main controller state is now an enum and is available via the parameter interface
- all: Parameter protocol robustification and added retries
- dev_host: Check signals and parameters for NaN before transmission
- dev_host: Decode process errors into something useful

NOTE: This release is a major network update. 0.2.x versions are NOT compatible with 0.1.x versions

---

## 0.1.2 - 18/07/2024
- dev_mc: Fixed incorrect naming of input signal `i_q` when renamed for torque input

---

## 0.1.1 - 18/07/2024
- Initial release
