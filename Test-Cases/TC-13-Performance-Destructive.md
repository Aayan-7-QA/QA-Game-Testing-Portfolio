# TC-11 — Performance Destructive

| Field | Details |
|-------|---------|
| **ID** | QBGT-D-13 |
| **Summary** | The game should not crash after spawning over 1000 enemies/characters |
| **Pre-Condition** | 1. Install jmeter |
                    |  2. Set jmeter option to simulate 1000+ |
                    |  3. Connect jmeter to game  |
| **Status** | Fail |

## Steps
1. Boot the game on the build 1.60.21
2. Start the gameplay/mission
3. Start jmeter by putting a load of 1000+ on the game 

## Actual Result
The game crashed after spawning over 1000 loads

## Expected Result
The game crashed after spawning 1000+ enemies no error message was displayed and the game force closed

## Post-Conditions
       -    
