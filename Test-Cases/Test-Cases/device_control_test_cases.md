# Device Control Test Cases

| # | Scenario | Steps | Expected Result | Actual Result | Status |
|---|----------|-------|-----------------|---------------|--------|
| 1 | Unauthorized USB blocked | Plug SanDisk Cruzer Blade / random USB | Device access denied, event logged as Blocked | As expected | ✅ PASS |
| 2 | Authorized USB allowed | Plug USB SanDisk 3.2Gen1 (whitelisted Device ID) | Device allowed, log shows Allowed | As expected | ✅ PASS |
| 3 | Bluetooth blocked | Turn on Bluetooth on endpoint | Bluetooth disabled / no connection possible | As expected | ✅ PASS |
| 4 | CDROM blocked | Insert CD/DVD and try to access | CD/DVD access blocked (as per policy) | As expected | ✅ PASS |
| 5 | Multiple attempts logging | Plug/unplug USB multiple times | All attempts visible under Threats Xplorer → Device Control activity | As expected | ✅ PASS |
