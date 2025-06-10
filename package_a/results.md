# some first high level results

- Rallies actually increased (overall from 8.5% to 13.6%)
- we can compare the results for open division

|  | open |  |
| --- | --- | --- |
| Double Faults | 22,7848 | significantly lower |
| Rallies | 13,9970 | significantly higher |
| Sideouts with defensive touch | 12,7923 | change not significant |
| Sideouts | 18,8823 | significantly lower |
| Aces | 21,0180 | change not significant |
| non-ace points on serve | 10,5230 | significantly higher |

![Screenshot 2025-06-06 at 14.20.35.png](Screenshot_2025-06-06_at_14.20.35.png)

# survey results for package A

- tbd

# deep dive report for package A (metrics)

## Touches per Point
    - increased from 3.2 to 3.5 (for open a significant rise) for open
## Average Change of Possession (for Rallies)
    - increased from 3.2 to 3.6 for open
## First Serve Percentage
    - no changes
## Rally Ratio
    - how many points that are actually played beyond serve, are rallies?
    - 18.6% to 30% for open
## Game Score
    - 100 = RRR target goals, above 100 exceed goals, below 100 fall short of the goals
        - Rallies count a lot, value is reduced when we have a lot of double faults
        - Aces should be lower than rallies
        - The greatest weight is given to rally % (±2.5 per % above/below 25%) with reducing double faults as the second biggest factor (+.25 per % below 20, -2 per % above 20).
        - Aces greater than 15% only hurt the quality score if the ace % is greater than the rally %
        - A bonus is given if the first serve percentage exceeds 70%
        - A bonus is given for longer rallies
    - An ideal game with score 100 would have 25% rallies, 20% double faults, 65% first serve percentage, 15% aces and 3 average changes of possession (= minimal rally)
    - The average baseline game was around 39 points, the average package A game was around 64 points
        - when we only look at open games the average game score rises from 32 to 62

# something for the website

- tbd