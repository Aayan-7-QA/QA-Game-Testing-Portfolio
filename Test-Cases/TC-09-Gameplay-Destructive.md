# TC-09 — Gameplay Destructive

| Field | Details |
|-------|---------|
| **ID** | QBGT-D-9 |
| **Summary** | Game should not crash when tapping jump button "100+" within 5 seconds |
| **Pre-Condition** | 1. Install JMeter 2. Set JMeter option to simulate 100 tapping per 5 sec 3. Connect JMeter to game |
| **Status** | Pass |

## Steps
1. Boot the game on the build 1.29.908B
2. Start the gameplay/mission
3. Start JMeter tapping by 100+ for 5 seconds

## Actual Result
The game did not crash and no errors were displayed and continued running smoothly

## Expected Result
The game should not crash and no errors should be displayed, it runs smoothly

## Post-Conditions
\-
