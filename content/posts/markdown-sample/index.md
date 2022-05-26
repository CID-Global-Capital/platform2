---
title: "Assessing Value"
date: 2022-05-08T08:06:25+06:00
description: Understanding that growth and returns matter.
menu:
  sidebar:
    name: Assessing Value
    identifier: markdown
    weight: 30
author:
  name: Mike Mattimoe Jr.
  image: /images/author/mike.png
math: true
tags: ["Enterprise Value","Growth","Returns","NOPAT"]
---
# Surprising Result Due to Small Market Size

The vast majority of investment firms in East Africa focus on earnings multiples. A more sophisticated and appropriate method is to forecast future performance focused on key value drivers.

We analyzed two firms with the following observations:

| Company | <abbr title="Earnings before Interest and Tax">EBIT</abbr> | Growth | Returns |
| :----------: | :----: | :---: | :---: |
| Consumer staples | $450,000 | 5%     | 12%     |
| Industrials      | $550,000 | 20%    | 80%     |



And obtained strange results:

{{< img src="/posts/markdown-sample/images/ev-nopat.png" align="center" title="EV/NOPAT">}}

{{< vs >}}




The industrial company earns 20% more than the consumer stapes business, which should mean that it is valued by 20% more. However, that is only the case if all else is equal. In this case, as in nearly all uses of comparables in markets with few sales, multiples alone are not sufficient to truly assess value. Even using the key value driver formula;

[insert math equation]

which is a more robust version of an earnings multiples, the numbers do not seem to add up.

## Conclusion

In this case, the reasons for the anomalous results were identified with a full <abbr title="Discount Cash Flow Analysis">DCF</abbr> analysis and deep dive into each business.

1. Physical assets: the consumer staples business operates a physical plant, with a large plot of land and thus has a floor on the value of it's business, the liquidation value of it's physical assets. The industrial business is growing its fleet but still has 1/6th the physical assets as the consumer staples firm. This leads to a much lower downside scenario.
2. <abbr title="Operating Profit / Revenue">Operating Margins</abbr>. The consumer stapes firm operates a business with much higher operating margins and thus has a lower level of risk associated with meeting the cash flow requirements of its core business.

## Method of analysis

We took the average ROIC for the previous three years as proxy for expected future returns, and used our analysts' consensus estimate of their three-year growth outlook as a proxy for long-term expected growth.

### Data

The data can be found here:

[insert data link]

## Appendix

Typically, companies with higher ratios of enterprise value to earnings also have higher growth and/or higher ROIC driven by better sales margins and capital turnover. On the flipside, companies are generally valued at low enterprise value to earnings multiples because of their low returns on capital and low expected growth.
