# TC-03 — Settings Positive

| Field | Details |
|-------|---------|
| **ID** | QBGT-P-3 |
| **Summary** | Apply button becomes active if game inputted setting was changed example "Brightness and Volume"  setting etc |
| **Pre-Condition** | Game is installed on the device |
| **Status** | Fail |

## Steps
1. Boot the game on the build 1.40.52908
2. Click the game setting button
3. Change the brightness setting
4. Change the volume setting
5. Click the apply button

## Actual Result
Apply button stay inactive after changing the game settings and no error message shows

## Expected Result
Apply button become active and the game setting was changed to preferred set value

## Post-Conditions
Settings menu is closed after clicked cross button
