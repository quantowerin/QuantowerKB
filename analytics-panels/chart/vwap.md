---
description: >-
  Volume Weighted Average Price shows a fair price of an asset and based on a
  trading volume.
---

# VWAP

**Volume Weighted Average Price** knows as **VWAP** is a “benchmark” price of an asset for any period of the trading day or session. Average price is weighted by volume for evaluating the overpaying or underpaying of current price relative to the VWAP price.

![](../../.gitbook/assets/vwap.png)

The indicator is calculated for any period of time according to the following algorithm:

* the average price \(AP\) is calculated for each bar or candle. The calculation is made for each price change for the current candle.  AP = \(H+L+C\)/3
* the average price is multiplied by the volume that has passed in the current candlestick or bar. For example, in real time new trade will increase the volume and thus weigh the price. Thus, for each price or volume change we will get value AP \* V.
* the above values are summed up and divided by the total volume for the specified period.

  ```text
                        **VWAP = \(Sum of Average Price \* Traded Volume\) / Cumulative Volume**
  ```

## **How to add VWAP to the chart?**

The VWAP indicator is located on the Volume Analysis toolbar. When you click on it, a menu with basic settings and an indicator activation / deactivation switch will appear.

![VWAP Indicator is placed on Volume Analysis toolbar](../../.gitbook/assets/vwap-tool.png)

The quick settings menu contains three parameters:

* **Base period and Value** — defines the number of bars \(duration\) on which VWAP will be calculated
* **Show Standard Deviations** — when the parameter is active, the standard deviation lines up and down from VWAP will be additionally calculated on the chart. In the advanced settings you can set the number of standard deviations.
* **Enabled** switch shows or hides the VWAP indicator on the chart

### Advanced indicator settings

By clicking on the "**Gear"** icon, additional settings will open. When choosing a Day period VWAP in the advanced settings, you can set the start and end of the trading session.

![Additional setiings for VWAP Indicator](../../.gitbook/assets/vwap-advanced-settings.png)

You can also set the value and colors for the standard deviation, which will be used in the quick settings.

## How to use VWAP in trading?

VWAP has numerous application in the trading world. It is helpful for both institutional investors and retail intraday traders. Below are some well known applications of VWAP:

* It helps in Buying low and Selling High. If the price is below VWAP, it is considered as undervalued, while price above VWAP is considered as overvalued.
* Crossing of prices above/below VWAP line in chart indicates momentum shift or change of trend.
* VWAP is also used as a trading benchmark by institutional investors who are not worried about the timing of the trade, but who are concerned about the adverse impact of their trades on the price of the security.
* VWAP serves as a reference point for prices for one day. As such, it is best suited for intraday analysis**.** Chartists can compare current prices with the VWAP values to determine the intraday trend.
* VWAP indicator can be used as a dynamic support/resistance line during sideways market.

For intraday trading we have found that it is possible to trade the return of the price to VWAP on small timeframes. For example, let's consider ES \(e-mini S&P500\) futures on 5-minute chart with an hourly VWAP.

![Trading with VWAP in Quantower platform](../../.gitbook/assets/vwap-trading.png)

An important point in this tactic is that the distance between the VWAP value and the closing price should be significant.

![The distance between the VWAP value and the closing price should be significant ](../../.gitbook/assets/vwap-trading1.png)

