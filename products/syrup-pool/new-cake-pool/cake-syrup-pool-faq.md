# HOPE Syrup Pool FAQ

## FAQ

### What lock duration can we choose?

You can choose from 1-52 weeks. What do you prefer?

### What variables affect the new HOPE Syrup Pool APYs (Flexible and Fixed-Term Staking options)?

Since flexible staking and fixed-term staking options are part of the same pool, the following variables affect the APY of both:

* Total HOPE staked in flexible staking and fixed-term staking (the sum of both). The more HOPE staked, the lower the APY.
* Total locked HOPE in fixed-term staking. The more HOPE locked means more yield boosts, resulting in fewer HOPE rewards for others (especially flexible staking).
* The average lock duration of all HOPE locked in fixed-term staking. If the average lock duration increases, APY will decrease.

### Can I harvest the rewards during the locked period?

No. You can harvest the rewards only when the locked duration is ended. This is based on the yield/return we are providing as well as the technical implementations.

### Can I extend the lock duration?

Yes. Extending the lock duration adds more time to your **initial lock duration**. When choosing to extend your lock duration, note:

New extended lock duration = initial lock duration + added duration

### Can I remove my HOPE from Fixed-Term staking via contract if I change my mind?

No. Your HOPE cannot be removed or withdrawn from fixed-term staking at any point in time until your lock duration ends and your HOPE is unlocked.

### What is the "HOPE Locked" amount?

The "HOPE Locked" amount is a user's initial locked HOPE balance plus HOPE rewards to date.

HOPE Locked = Initial locked HOPE balance + HOPE rewards

When adding more HOPE to fixed-term staking, the "HOPE to be locked" amount is the user's initial locked HOPE balance, HOPE rewards to date, and the HOPE being added.

### Can the Fixed-Term Staking HOPE pool APY change after I lock my HOPE?

Yes, the fixed-term staking HOPE pool APY is variable, just like the old CAKE pools. The fixed-term staking HOPE pool APY is not fixed and is dependent on:

* Total HOPE staked in the HOPE pool (the sum of both Flexible + Fixed-Term Staking).
* The average lock duration of all HOPE locked in fixed-term staking.
* A yield boost (similar to a multiplier) calculated from a user's initial lock duration. The longer you lock your CAKE, the higher the yield boost.

For example, if you lock your CAKE for 52 weeks, your yield boost will be larger than if you lock your CAKE for 26 weeks. The yield boost increases linearly the longer you lock your CAKE.

### Can I still participate in IFOs if my CAKE is locked in the Fixed-Term Staking pool, or will I need to buy more CAKE?

TBD, more information will be provided soon.

### Can I vote if my CAKE is locked in the Fixed-Term Staking pool?

TBD, more information will be provided soon.

### Can I use both the Flexible Staking CAKE pool and the Fixed-Term Staking CAKE pool at the same time?

No. As mentioned above in the "What’s the difference" section, both options are part of the same, single pool. You currently can **never** have CAKE in both fixed-term and flexible staking.

We have multiple solutions coming in the future to allow users to use both flexible staking and fixed-term staking at the same time, but for now, you can choose only one of them.

### Is there a fee for converting Flexible Staked CAKE to Fixed-Term Staked CAKE?

No. There are no additional fees for moving CAKE from flexible staking to fixed-term staking, only network fees.

### What happens at the end of the lock duration? What is "After Burning"?

When your fixed-term staking period ends, and your CAKE unlocks, you have 7 days to complete one of two options:

* Lock your CAKE to begin a new fixed-term staking period\
  or
* Convert your staked CAKE to flexible staking (no 72-hour withdrawal fee).

![](../../../.gitbook/assets/cake-pool-lock-end.png)

During these 7 days, you will still earn CAKE at the same APY as your lock period.

After 7 days, if you have not done one of the two options, your staked CAKE will enter what is called "After Burning". In "After Burning", you will still earn CAKE, but a portion of your rewards will be sent to burn at a linearly decreasing APR over 90 days, where your APR will be 0% after 90 days.

The “After Burning” state will last for 90 days until all the CAKE rewards are burnt. So, to avoid missing out on CAKE rewards, we recommend starting a new fixed-term staking period or converting your CAKE to flexible staking at the end of your lock staking period.

![](<../../../.gitbook/assets/cake-pool-lock-burn (1).png>)
