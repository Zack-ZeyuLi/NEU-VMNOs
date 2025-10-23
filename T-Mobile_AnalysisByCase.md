# T-Mobile (M) & Mint (V1) & Metro (V2) at Boston
## Location 1 - Malden Center
### T-Mobile + Mint Round 5 - T-Mobile throughput dropped
PCI, NR-ARFCN, RSRP, RSRQ, SINR, Bandwidth almostly stay same  
RB utilization ratio, slot utilization ratio, Transport Block Size dropped  
Mint throughput no significant increase  
**Qci 6 -> 9 (Mint is also 9)**  
--> More UEs of T-Mobile connected to gNB (May subject to some UE with Qci = 7)  

### T-Mobile + Metro Round 2 - T-Mobile throught slightly dropped
1. PCell throughput increased: 203 -> 288
   - NR-ARFCN 520110 -> 502110; Bandwidth 100 -> 90
   - RB utilization ratio increased: 23% -> 35%  (more active slot)
3. SCell[1], SCell[2], SCell[3] were inactive
   - RSRP are bad, no throughput (no RB utilization ratio, no slot utilization ratio)

### T-Mobile + Metro Round 5 - T-Mobile dropped, Metro increased
TMobile PRB, RB utilization, slot utilization dropped   
Metro PRB, RB utilization, slot utilization increased  
**T-Mobile Qci 6 -> 9, Metro Qci stay 7**
![Qci](images/L1_T-Mobile_vs_Metro_Round5.png)

### Mint + Metro - Round 5 - Mint dropped, Metro increased
Mint PRB, RB utilization, slot utilization dropped  
Metro PRB, RB utilization, slot utilization increased  
**Mint Qci 7 -> 9, Metro Qci stay 7**
![Qci](images/L1_Mint_vs_Metro_Round5.png)

### M + V1 + V2, Round 3 Mint dropped
PCell perform regularly  
SCell[1], SCell[2], SCell[3] were inactive, RSRP very bad

### M + V1 + v2, Round 4 TMobile dropped
**TMobile Qci 6 -> 9, Mint & Metro stay 7**
TMobile PRB, RB utilization, slot utilization dropped   
![Qci](images/L1_M_vs_V1_vs_V2_Round4.png)

### M + V1 + V2, Round 5, 3 operators perform closely
**TMobile & Mint Qci 9, Metro half 7 half 9**
![Qci](images/L1_M_vs_V1_vs_V2_Round5.png)
TMobile & Mint PRB, RB utilization, slot utilization dropped   
Metro PRB, RB utilization, slot utilization increased in the first half and decreased in the second half
![PRB](images/L1_Metro_Round5.png)
