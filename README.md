
## Known Issues

- **Dawn/dusk lighting**: During in-game sunrise and sunset, the warm yellow ambient lighting significantly interferes with HSV-based cursor detection, causing tracking failures and drastically reduced fishing success rates. This is an inherent limitation of the current color-based detection approach. If you encounter this, consider adjusting the cursor HSV thresholds in Settings to compensate for the shifted lighting conditions.

This repository attempts to fix these lighting issues.
