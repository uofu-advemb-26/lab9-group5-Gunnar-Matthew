
| number | arms_down | alarm_on | northbound_present | southbound_present | north_approach | south_approach | north_depart | south_depart | 10 seconds elapsed | safety_hazard |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 0 | 0 | 0 | 0 | 0 | 6 | 5 | 0 | 0 | 0 |  |
| 1 | 0 | 0 | 0 | 1 | 25 | 25 | 25 | 25 | 25 | 25 violation |
| 2 | 0 | 0 | 1 | 0 | 25 | 25 | 25 | 25 | 25 | 25 violation |
| 3 | 0 | 0 | 1 | 1 | 25 | 25 | 25 | 25 | 25 | 25 violation |
| 4 | 0 | 1 | 0 | 0 | 6 | 5 | 20 | 20 | 0 |  |
| 5 | 0 | 1 | 0 | 1 | 7 | 5 | 22 | 22 | 13 |  |
| 6 | 0 | 1 | 1 | 0 | 6 | 7 | 22 | 22 | 14 |  |
| 7 | 0 | 1 | 1 | 1 | 7 | 7 | 22 | 22 | 15 |  |
| 8 | 1 | 0 | 0 | 0 | 26 | 26 | 26 | 26 | 26 | 26 violation |
| 9 | 1 | 0 | 0 | 1 | 26 | 26 | 26 | 26 | 26 | 26 violation |
| 10 | 1 | 0 | 1 | 0 | 26 | 26 | 26 | 26 | 26 | 26 violation |
| 11 | 1 | 0 | 1 | 1 | 26 | 26 | 26 | 26 | 26 | 26 violation |
| 12 | 1 | 1 | 0 | 0 | 6 | 5 | 20 | 20 | 0 | Should never get to this state, not a safety violation, but inconvenient |
| 13 | 1 | 1 | 0 | 1 | 15 | 13 | 20 | 4 | 13 |  |
| 14 | 1 | 1 | 1 | 0 | 14 | 15 | 4 | 20 | 14 |  |
| 15 | 1 | 1 | 1 | 1 | 15 | 15 | 13 | 14 | 15 |  |


| number | invariant |
| :--- | :--- |
| 16 | Electricity will not be interrupted |
| 17 | When a train passes a sensor, it is always detected |
| 18 | Barrier motors are able to lift and lower the barrier |
| 19 | Trains on each track only run in one direction. |
| 20 | An approach signal will always precede a depart signal |
| 21 | The alarm is louder than ambient noise |
| 22 | It always takes more than 10 seconds for the train to reach the crossing after passing the approaching sensor. |
| 23 | The departing sensor must signal only the last car as the last car. |
| 24 | The sensors only send a signal when detecting trains (i.e. not animals, people, clouds) |
| 25 | If a train is present, barrier is always already lowered |
| 26 | If the barrier is down, the alarm is ringing |
