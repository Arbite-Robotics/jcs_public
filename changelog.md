# JCS changelog


## 0.2.1 - 04/11/2024
dev_mc: Check AS5047p SPI for stale data before TX
dev_mc: Main controller state is now an enum and is available via the parameter interface
all: Parameter protocol robustification and added retries
dev_host: Check signals and parameters for NaN before transmission
dev_host: Decode process errors into something useful

NOTE: This release is a major network update. 0.2.x versions are NOT compatible with 0.1.x versions

---

## 0.1.2 - 18/07/2024
dev_mc: Fixed incorrect naming of input signal `i_q` when renamed for torque input


## 0.1.1 - 18/07/2024
- Initial release
