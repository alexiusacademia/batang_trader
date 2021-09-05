---
title: "Basics of Technical Analysis"
date: 2021-09-04T18:45:47+08:00
draft: false
categories:
    - Trading
tags:
    - technical analysis
---

In this entry, we'll be talking about the fundamentals of reading the trend of a given market. By understanding the trend of a market, we gain knowledge of its behaviour. This may help us predict what the possible next direction of the market prices will be. Is it going up, or down?

In this article, I will present some useful tools and indicators available to us in the Binance platform. Note that this may be available to other major exchanges as well.

## Chart Views

There are two useful chart types that I usually use, the *Line Chart* and the *Candlestick Chart*.

The line chart looks something as shown below,

<img src="/static/line-chart.png" loading="lazy" />

while the candlestick chart is something like this.

<img src="/static/candlestick-chart.png" loading="lazy" />

The example above shows the chart for Bitcoin at the time of this writing.

If you just want the summarized overview of the market trend, you may want to go with the line chart, however, if you want a more detailed presentation, maybe the candlestick chart is best for you, and this is where I am looking for most of the time. 

To get the line chart on Binance chart, just tap or click on the `Time` button at the top left of the chart and if you want the candlestick chart, just select the intervals at the right of the `Time` button (in the case above, the selected one is `15m`).

## Candlestick

Candlesticks can be seen in charts as replacement for the plain line charts. A candlestick gives us more detailed information about a particular time frame.

<img src="/static/basic-ta/candlestick.png" loading="lazy" />

If you selected a 15m time frame, the above is a representation of that time frame. What happens is that at the start of 15 minutes, the candlestick starts at the `Open (O)` marker. Then within the 15 minutes time, the price goes as high as the `High (H)` marker and goes down to `Low (L)` marker. After that, before going to the next time frame, the price ends at the `Close (C)` marker.

The color of the stick is dictated by the open and close markers. If the closing price is higher than the opening price, the color is <span style="color: green;"><strong>green</strong></span> and <span style="color: red;"><strong>red</strong></span> for the opposite.

The `change` is the difference between `close` and `open` prices.

## What to look for?

In general, if you are a day trader and just riding the trend as I normally do, what you want to look for is a **Sign of Reversal (SOR)**.

An SOR is an indication that the direction of a trend in focus is about to change. Now this is the best time to either buy or sell.

If the previous trend that is about to end is downward, you may want to buy at the SOR and when the previous trend is upward, you want to sell at this point as the price may go down.

Here is an example:

<img src="/static/basic-ta/sample-sor.png" loading="lazy" />

Two SORs have been marked in the image above. Both are two-candlestick SORs. Basically, what you want is to find something like in `S1` and treat as buying signal and `S2` as selling signals. This is a definite profit for us right? Well, if we get them correctly, and we will, in time.

As everything in trading, it's all about buying at lower expense and selling at higher returns. Buy spotting signs of reversals correctly, we maximize the use of our profit in trading. We would like to minimize the stagnant state of our money so the profit flow continues.

## Support and Resistance

Support and resistance are invisible boundaries that are effective on a certain amount of time on a trend. An example of a horizontal support and resistance is shown below.

<figure>
    <img src="/static/basic-ta/support-resistance.png" loading="lazy" />
    <figcaption style="font-size: 0.75em;"><strong>BTC/USDT</strong> - 30m Timeframe - July 28-30, 2021</figcaption>
</figure>

The upper horizontal line is the `resistance` and the lower horizontal line is the `support`.

A resistance is an indication that there are strong sellings at that level while the support is an indication of strong buys. Sometimes this two lines forms a rectangle if you close them at the end for horizontal levels and sometimes they form triangular enclosures to the trend.

## Drawing Tools

One of the many drawing tools available in the trading view of binance, the simplest one that I use and recommend for you to start with is the line tool. 

We can use this to project a trendline and maybe spot a sign of reversal.

<figure>
    <img src="/static/basic-ta/trendline-sor.png" loading="lazy" />
    <figcaption style="font-size: 0.75em;"><strong>CHR/USDT</strong> - 15m Timeframe - August 26-27, 2021</figcaption>
</figure>

What I did here is I drew a line (orange line) representing resistance of the downtrend. When the trend or candlesticks escapes the line going up and did not go back down, I treat is as a sign of reversal.

There are a lot of drawing tools available in the binance chart view but we will stick to the line tool in this article because of it's basic characteristics and it's easy to understand.

## Indicators

There are lots of indicators also in the chart view of binance but we will only look at the few of them. These indicators are what I often used in making analysis of trends.

### Trading Volume

Trading volume may be shown at the bottom of the chart in binance and it look like this.

![trading-volume](/static/basic-ta/trading-volume.png)

Every bar or column in that graph represents the total volume of transactions per time frame as selected in the trading chart. 

So how is this useful? Well it tells us about how much buying or selling is happening. This is not easily visible in the candlesticks.


### Bollinger Band

Bollinger bands are more popular and more useful in stock markets, however, you can still use them in cryptocurrency trading. 

![bolling-bands](/static/basic-ta/boll.png)

The above-chart has bollinger bands enabled.

Two interesting parts that are sometimes useful for me is the upper and lower bound.

You may see that when the candlesticks reaches the lower bound, it's a possible good time for buying and when it reaches the upper bound, that is a good time for selling. However, there are times when the chart does not goes up all the way to the upper bound, sometimes it goes back down after reaching the middle bound. The same happens when the chart came from the upper bound, it sometimes doesn't go all the way down to the lower bound. In these situations, we combine the use of bollinger bands with the sign of reversals given to us by candlesticks. This way, we get a bigger chance of predicting if the chart will go all the way up or down or is it going to come back after reaching the middle bound.


### Stochastic RSI

Another one is the Stochastic RSI. There are plain RSI or *Relative Strength Index*, but the Stochastic RSI is more sensitive and this is the one I would normally use when using an RSI indicator.

So what does an RSI tells us? 

If the graph of an RSI reaches 20% and below, it is an indication that the market is over-sell and when the graph reaches 80% and above, it is an indication that the market is over-bought.

An RSI or Stochastic RSI can be displayed at the bottom of the graph as shown below.

![stochastic rsi](/static/basic-ta/stoch-rsi.png)

The direction of the graph of Stochastic RSI or plain RSI can be noted to be opposite of that of the candlestick charts.

RSIs are not directly an indication of sign of reversals but it may sometimes be used. RSIs are just indication of over-sell and over-buy.


### Gold and Death Cross

Out of the indicators mentioned previously, this one is what I used in majority especially when making quick buys or selling limits. Here is an example of this indicator.

<figure>
    <img src="/static/basic-ta/cross.png" loading="lazy" />
    <figcaption style="font-size: 0.75em;"><strong>Golden and Death Cross</strong> - 15m Timeframe - August 28-September 1, 2021</figcaption>
</figure>

Death cross and Golden cross can be used as buy and sell indicators. I use this most of the time for buying entry points. What I set in the above is that the red line is the short term and the blue line is for the long term average.

Usage of this is very simple. I set the buy entry when the blue line crosses the red line and going under it. If you notice in the graph above, everytime the blue goes under the red line, the candlestick chart goes up and when the blue line crosses the red line and goes over it, the candlestick chart usually goes down.

Now this is not the most efficient entry for buy and sell points as you may notice but they give you the most chance of having the correct entry points giving you the most of your profit.


## Closing Remarks

Now this is not a lot but I would like to think that this is a start. A start of understanding about the technical analysis of a market. Introducing beginners with few trading jargons that they may encounter along the way.

I hope you like this article. We'll be talking in more detail about some of the tools here in the future entries for a clearer understanding and real life examples.

Thank you for reading.
