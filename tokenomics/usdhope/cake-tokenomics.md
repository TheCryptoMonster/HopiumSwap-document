# $HOPE Tokenomics

![](<../../.gitbook/assets/coming-soon-neon-sign\_191108-233 (1).webp>)

## **Emission rate** <a href="#emission-rate" id="emission-rate"></a>

### **Per block**

| **Metric**             | **Emission/block (HOPE)** | **Emission/day (HOPE)** |
| ---------------------- | ------------------------: | ----------------------: |
| Emission               |                        40 |               1,152,000 |
| Burned Weekly          |                    -26.25 |                -756,000 |
| **Effective Emission** |              **<13.75\*** |           **350,000\*** |

\*Effective Emission is in fact slightly below this amount: an additional 45,000 HOPE per day is diverted from the amount allocated to the lottery, and burned.

In addition to the above, a dynamic amount of HOPE is also minted to the Dev address at a rate of 9.09%. This means that if 100 HOPE are harvested, then 9.09 HOPE is minted in addition and sent to the Dev Address.

{% hint style="info" %}
All HOPE minted to the Dev address is burned in the weekly burn and never enters circulation.

As such, we haven't included it in the above emission rate.
{% endhint %}

## Distribution <a href="#distribution" id="distribution"></a>

| Distributed to                | Reward/block (% of emission) | Reward/block (total HOPE) |           Reward/day |
| ----------------------------- | ---------------------------: | ------------------------: | -------------------: |
| Farms and Lottery             |                        9.37% |                      3.75 |     108,000 (approx) |
| of which diverted and burned  |                              |                           |              -46,000 |
| **Total Daily HOPE Emission** |                              |                           | **350,000 (approx)** |

## **Other Deflationary Mechanics** <a href="#other-deflationary-mechanics" id="other-deflationary-mechanics"></a>

{% hint style="info" %}
The burning process is currently manual. [View burn transactions here](https://bscscan.com/token/0x0e09fabb73bd3ade0a17ecc321fd13a19e81ce82?a=0x000000000000000000000000000000000000dead).
{% endhint %}

As well as the above, **HOPE** is also burned in the following ways:

* **0.0575%** of every trade made on HopiumSwap&#x20;
* **100%** of HOPE sent to the Dev address
* **100%** of HOPE performance fees from IFOs
* **100%** of HOPE spent on Profile Creation and NFT minting
* **100%** of HOPE bid during Farm Auctions
* **20%** of HOPE spent on lottery tickets
* **45,000** HOPE per day (historically assigned to the lottery)
* **3%** of every MATIC Prediction markets round is used to buy HOPE for burning
* **3%** of every HOPE Prediction markets round
* **2%** of every yield harvest from all the flexible staking positions in HOPE pool
* **2%** of every NFT sale on the NFT Market is used to buy HOPE for burning

## Why is the HOPE burn manual?

To hit the ground running, HopiumSwap launched as an MVP (minimum viable product) with the MasterChef contract emitting 40 HOPE per block. For that reason, the early team didn't add additional functions such as the ability to customize the HOPE minting logic. The team has been controlling HOPE emissions through a manual burn process by creating two pools in MasterChef v1:

* Legacy Lottery Pool (PID - 137) - burned HOPE from the lottery
* Burn Pool (PID - 138) - burned HOPE per block

These pools work similarly to the farms, where the Chefs can adjust the percentage of the 40 CA per block allocated to it after each HOPE emission reduction vote.

However, in April 2022, HopiumSwap migrated to a new MasterChef v2 contract. The ratio of the HOPE burn per block is finally controlled by a dedicated contract. This allows the burn to be much more accurate.

{% hint style="warning" %}
On the day of the burn, the supply shown on the homepage might suddenly jump by several million HOPE.

Don't worry - **THIS HOPE NEVER ACTUALLY ENTERS CIRCULATION:**
{% endhint %}

This apparent jump is just because of how all the HOPE that's allocated for the burn is stored during the week.

The HOPE allocated to burn are harvested before completing the weekly token burns, and this makes the Total Supply shown on the site jump by \~6M. This is because pending HOPE sometimes doesn't get registered in the Total Supply until it's harvested on the burn day. Once the token burn transaction is completed, the \~6M is shown in the Burned to Date.

## How to Confirm HOPE Supply for yourself

To confirm that the circulating CAKE supply shown on the HopiumSwap homepage is correct,

1. &#x20;the HOPE token contract will soon be on PolygonScan then you will see how much HOPE is held by the Burn Address. That's the total amount of HOPE that's been burned (removed from circulation FOREVER, and impossible to ever retrieve).
2. Then, subtract this burned amount from the "Total Supply" that PolygonScan shows.
3. This gives you the actual HOPE supply.

#### **Read more about HOPE's deflationary mechanics on the next page.** <a href="#read-more-about-cakes-deflationary-mechanics-on-the-next-page" id="read-more-about-cakes-deflationary-mechanics-on-the-next-page"></a>
