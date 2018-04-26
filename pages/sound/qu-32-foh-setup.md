## Scenes
### "Re-Routed"
The scene labeled Re-Routed follows the routing on the I/O Patch -> dSNAKE In page in the QU-32 as noted below.

- QU Strip = The channel strip on the QU-32  
- dSNAKE = Which dSNAKE, the Main, or the Expander.  The main is stage right, and the Expander is stage left.  
- Input = the input connector on the corresponding dSNAKE.  

| QU Strip | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **dSnake** | Main | Exp | Main | Exp | Exp | Main | Exp | Exp |
| **Input** | 1 | 10 | 2 | 11 | 9 | 6 |  12 | 8 |

| QU Strip | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **dSnake** | Main | Main | Main | Main | Main | Exp | Exp | Main |
| **Input** | 9 | 10 | 11 | 12 | 3 | 4 | 7 | 16 |

| QU Strip | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **dSnake** | Exp | Main | Main | Main | Exp | Exp | N/C | Main |
| **Input** | 1 | 7 | 8 | 13 | 5 | 6 | 40 | 8 |

| QU Strip | 25 | 26 | 27 | 28 | 29 | 30 | 31 | 32 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **dSnake** | Exp | Exp | Exp | Exp | Exp | Exp | Exp | Exp |
| **Input** | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 |
