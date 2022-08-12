---
description: Fixed-Term CAKE Staking and IFO Allocations
---

# iHOPE

### **What is iHOPE?**

iHOPE  is similar to “IFO credits” from the previous IFO HOPE  staking pool, which was retired during the MasterChef v2 migration. After this update, iHOPE  will determine the maximum HOPE  commit limit in the HopiumSwap IFO public sales. For example, if you have 200 iHOPE , you will be able to commit 200 HOPE  in any upcoming IFO public sales.

**iHOPE is NOT a new token, it is a numerical metric being used by the HopiumSwap IFO system.**

### How is iHOPE  calculated?

The number of iHOPE you have is based on the number of HOPE  staked in the fixed-term HOPE staking pool and the total staking duration of your current fixed-term staking position.

iHOPE  works based on a staking duration threshold for all iHOPE  users.

If your staking duration is above the threshold, the number of iHOPE  you have is equal to the number of the HOPE  in your staking position.

If your staking duration is below the threshold, the number of iHOPE  you have will be linear decreased and adjusted.

If your staking position is ended, the number of iHOPE  you have is 0.

For example, if the threshold is 20 weeks:

* Your current fixed-term staking position has a duration of 25 weeks and 200 staked HOPE . Then the number of iHOPE  you have is 200.
* Your current fixed-term staking position has a duration of 10 weeks and 200 staked CAKE. Then the number of iHOPE  you have equals 200 × (10 ÷ 20) = 100.
* Your current fixed-term staking position has a duration of 2 weeks and 200 staked CAKE. Then the number of iHOPE  you have equals 200 × (2 ÷ 20) = 20.
* Your current fixed-term staking position has a duration of 2 weeks and 200 staked CAKE. But the position is ended. Then the number of iHOPE  you have is 0.

|                      | Your staking duration is equal to or longer than the threshold | Your staking duration is shorter than the threshold                   |
| -------------------- | -------------------------------------------------------------- | --------------------------------------------------------------------- |
| **iHOPE** **Amount** | Equals your Locked CAKE Amount                                 | Equals your Locked HOPE  Amount x (Your Staking Duration / Threshold) |

### How to check the number of iHOPE  I have?

![](../../.gitbook/assets/image3.png)

You can check the number of iHOPE  you have in the IFO page [here](https://pancakeswap.finance/ifo).

### **How to increase the number of i**HOPE **I have?**

You can increase the number of iHOPE you have by:

* Adding more HOPE  to your fixed-term staking position in the HOPE  syrup pool.
* Extend your fixed-term staking durations if your current durations is shorter than the threshold.

![](../../.gitbook/assets/image2.png)

You can preview the number of iHOPE  generated from your staking position when adjusting or initializing the fixed-staking.

### What is the threshold for iHOPE  calculations?

Between each IFOs, the kitchen will optimize the threshold based on the average staking duration of the fixed-term staking HOPE  pool. The adjustment will be published on all social channels.

![](<../../.gitbook/assets/image (134).png>)

You can check the current threshold for iHOPE  calculations by hovering or tapping the underlined iHOPE  text in the CAKE syrup pool window.
