# TC-06 — Save & Load Negative

| Field | Details |
|-------|---------|
| **ID** | QBGT-N-6 |
| **Summary** | Game progress is not saved in the game server after playing 5 to 10 minutes |
| **Pre-Condition** | The user is playing the game after it has been installed on the device |
| **Status** | Fail |

## Steps
1. Boot the game on the build 8.92.2
2. Start the gameplay/mission
3. Play for 5 to 10 minutes to make progress
4. Open the game menu
5. Click the Save button
6. Restart the game and check if the progress was saved

## Actual Result
After making some progress, after clicking the Save button then current game progress is not saved on the game server and resets to the previous state

## Expected Result
After making some progress and then clicks the save button the game progress not saved in the server and the error message should appear save unsuccessful

## Post-Conditions
Player progress is reset to the previous state
