SLTC Core integration/staging repository
=======================================

SLTC Coin Features
- Anonymized transactions using our "Stealth Mode"
- Time Based Masternode Rewards - people who hold MN for a longer time can be rewarded more than others.
- Fast transactions or Flash Send.
- Masternode technology used to secure the network and provide the above features, each Masternode is secured
  with collateral of 6K SLTC

### Coin Specs
<table>
<tr><td>Algo</td><td>Lyra2z</td></tr>
<tr><td>Block Time</td><td>150 Seconds</td></tr>
<tr><td>Difficulty Retargeting</td><td>Every Block</td></tr>
<tr><td>Max Coin Supply (PoW Phase)</td><td>48,000,000 SLTC</td></tr>

<tr><td>Premine</td><td>2,500,000 (minus swap) SLTC</td></tr>
</table>

### Reward Distribution

<table>
<th colspan=4>PoW Phase</th>
<tr><th>Block Height</th><th>Reward Amount</th><th>Notes</th><th>Duration (Days)</th></tr>
<tr><td>0-2</td><td>2,500,000 SLTC</td><td>Initial Premine</td><td>0 Days</td></tr>
<tr><td>2-100</td><td>1 SLTC</td><td>Initial Premine</td><td>0 Days</td></tr>
<tr><td>200-500</td><td>3 SLTC</td><td rowspan=2>Instamine Protection</td><td rowspan=2> Approx 60 Days</td></tr>
<tr><td>501-800</td><td>5 SLTC</td><td rowspan=2>Instamine Protection</td><td rowspan=2> Approx 60 Days</td></tr>
<tr><td>801-2000</td><td>7 SLTC</td><td rowspan=2>Instamine Protection</td><td rowspan=2> Approx 60 Days</td></tr>
<tr><td>2001-25,000</td><td>20 SLTC</td><td rowspan=2>Open Mining</td><td rowspan=2> Approx 60 Days</td></tr>
<tr><th colspan=4>PoS Phase</th></tr>
<tr><th>Block Height</th><th colspan=3>Reward Amount</th></tr>

### PoW Rewards Breakdown

<table>
<th>Block Height</th><th>Miner</th><th>Masternodes</th>
<tr><td>2001-25,000</td><td>50% (10 SLTC)</td><td>50% (10 SLTC)</td></tr>
</table>

### PoS Rewards Breakdown

<table>
<th>Phase</th><th>Block Height</th><th>Reward</th><th>Stakers</th><th>Masternodes</th>
<tr><td>Phase 1</td><td>25,000-190,000</td><td>24 SLTC</td><td>50% (12 SLTC)</td><td>50% (12 SLTC)</td></tr>
<tr><td>Phase 2</td><td>190,000-380,000</td><td>20 SLTC</td><td>50% (10 SLTC)</td><td>50% (10 SLTC)</td></tr>
<tr><td>Phase 3</td><td>380,000-570,000</td><td>30 SLTC</td><td>50% (15 SLTC)</td><td>70% (15 SLTC)</td></tr>
<tr><td>Phase 4</td><td>570,000-950,000</td><td>24 SLTC</td><td>50% (12 SLTC)</td><td>50% (12 SLTC)</td></tr>
<tr><td>Phase 5</td><td>950,000-1.14M</td><td>20 SLTC</td><td>50% (10 SLTC)</td><td>70% (10 SLTC)</td></tr>
<tr><td>Phase 6</td><td>1.14M-1.33M</td><td>16 SLTC</td><td>50% (8 SLTC)</td><td>70% (8 SLTC)</td></tr>
Halves Every 190k blocks after block 1.33M
</table>

### MN Payments

- Masternode payments start from block 2001.
