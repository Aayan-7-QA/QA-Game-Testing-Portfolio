# TC-08 — Gameplay Negative

| Field | Details |
|-------|---------|
| **ID** | QBGT-N-8 |
| **Summary** | After tapping the character jump button, the character doesn't jump |
| **Pre-Condition** | The user is playing the game after it has been installed on the device |
| **Status** | Pass |

## Steps
1. Boot the game on the build 1.FKJ.215
2. Start the gameplay/mission
3. Tap the jump button

## Actual Result
When tapping the character jump button, the character does not jump, it stays in the same position, and no animation is displayed. The error message appears: "Something went wrong."

## Expected Result
After tapping the jump button, the character does not jump and not respond to invalid/broken input, and an error message appears, "Something went wrong."

## Post-Conditions
Character stays in the same position on the ground
