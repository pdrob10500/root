

<!-- bnd_page-01.md -->

Bond Markets: Structures and Yield Calculations by Patrick Regan

Bond Markets

Structures and Yield Calculations

This book brings you in a single reference tool the standard conventions and market practices for the bond markets of Europe and also those of Australia, Canada, Japan and the United States.

Liberal use of worked examples illustrates the derivation and correct use of the relevant formulae, allowing you to program your own applications.

'ISMA set the standard for yield calculations for international bonds a number of years ago. In response to popular demand Pat Brown has extended his earlier work to produce this meticulously researched book covering no fewer than 30 bond markets around the world. I have no doubt that financial analysts will find it indispensable!'

John L Langton, Chief Executive and Secretary General of ISMA.

GDP

£37.50

![Figure](figures/bnd_page-01_figure_008.png)

GDP

An ISMA Publication in association with GDP

Bond Markets

Structures and Yield Calculations

![Figure](figures/bnd_page-01_figure_012.png)

by Patrick J Brown



<!-- bnd_page-02.md -->

BOND MARKETS

Structures and Yield Calculations



<!-- bnd_page-03.md -->

BOND MARKETS

Structures and Yield Calculations

Patrick J. Brown

ISMA

An ISMA publication in association with GDP

Gilmour Drummond Publishing

Cambridge • Edinburgh



<!-- bnd_page-04.md -->

First published in 1998 by GDP, PO Box 187, Cambridge, CB1 4TL, England in association with International Securities Market Association Limited Seven Limeharbour, London E14 9NQ Telephone: (44–171) 538 5656 Fax: (44–171) 538 9183 e-mail: sales@isma.co.uk

© 1998 International Securities Market Association

ALL RIGHTS RESERVED. No part of this publication may be reproduced, stored in a retrieval system, or transmitted in any form or by any means, electronic, photocopying, recording or otherwise, without the prior permission of the publisher and the copyright holder.

Whilst every effort has been made to ensure the accuracy of information provided in this book, no responsibility can be accepted by the publisher or the author for any inaccuracy.

ISBN 1 901912 02 7

Cover design by Jenny Stewart

Printed in the United Kingdom

All books from GDP are available at quantity discounts when purchased for business, educational, or sales promotional use.

For more information, call the Managing Director on

(44) (0) 1223 508059 or e-mail: ram21@dial.pipex.com or write to

GDP PO Box 187 Cambridge, CB1 4TL England

## CONTENTS

![Figure](figures/bnd_page-04_figure_010.png)

Preface v

Acknowledgements      vi

Chapter 1 Introduction      1

Chapter 2 Trade, Value and Settlement Dates      2

Chapter 3 Accrued Interest      5 3.1  .  Counting days accrued      5 3.2  Days in the year      9 3.3.  Accrued interest computation      12

Chapter 4 Measures of Life and Associated Calculations      13 4.1  Life to maturity      14 4.2  Life to next call      14 4.3  Life to put      15 4.4  Average life      15 4.5  Equivalent life      16 4.6  Duration      17 4.7  Modified duration or volatility      20 4.8  Convexity      21

Chapter 5 Yields      23 5.1  Current yield      23 5.2  Simple yield to maturity      24 5.3  Redemption yields      25 5.3.1  Fixed coupon bonds      27 5.3.2  Money market yields (bonds in their last coupon period)      30 5.3.3  Zero coupon bonds      33 5.3.4  Undated securities      34

v



<!-- bnd_page-05.md -->

CONTENTS

5.3.5  Bonds with sinking funds (yields to average/equivalent life)      35 5.3.6  Other bond types      37 5.3.7  Other redemption yields      38

Chapter 6  Floating Rate Note Calculations      40 6.1  Simple margin      40 6.2  Discounted margin      42 6.3  Yields 44

Chapter 7  Convertible Calculations      47 7.1  Conversion premium/discount - ratio      47 7.2  Income differential and break-even period      49

Chapter 8  Warrants      51 8.1  Bond warrants      51 8.2  Equity warrants      53 8.3  Commodity/currency warrants      54

Chapter 9  Money Market Instruments      56 9.1  Discounts      56 9.2  Yields      58 9.2.1  With one coupon payment      58 9.2.2  With more than one coupon payment      59 9.3  Floating rate certificates of deposit      60

Chapter 10 Miscellaneous      61 10.1  Bonds in default      61 10.2  Tax      61 10.3  Prices from yields      62

Chapter 11  Bonds Market Comparisons      65 11.1  Table headings      72 11.2  Footnotes      76

Appendix I The General Redemption Yield Formula      89

Appendix II Compounding Frequency Adjustments      92

Appendix III Index-Linked Stocks and Real Returns      94

ⅵ

## PREFACE

The increase in cross market bond trading, makes it very important that participants understand the differences between market practices and as a result can compare returns on a consistent basis.

Due, at least in part, to the G30 recommendations, the advent of the Euro and increased cross-border investment, bond market practices and yield conventions are tending to converge. However, it can be seen that there is still a long way to go.

The purpose of this book is to define and compare the standard methods and conventions used in the International and many domestic bond markets for calculating prices, accrued interest, yields, durations etc. The comparison concentrates on the European bond markets, but it does include some of the other major markets.

The book incorporates, updates and extends the information contained in the ISMA Formulae for Yield and Other Calculations book (now out of print) and that in the Bond Markets Mechanics chapter of the 6th Edition of the European Bond Markets book.

Patrick Brown London

ⅶ



<!-- bnd_page-06.md -->

## ACKNOWLEDGEMENTS

I would like to thank the members of the EFFAS European Bond Commission, their national bond societies and numerous other people, without whom the chapter on bond market comparisons would not have been possible.

David Self of the International Securities Market Association has given me invaluable help in the compilation of the book for which I am most grateful. I would also like to thank my secretary, Diane Dowie, who has handled a most difficult task with great skill and patience.

ⅷ

## CHAPTER 1三三INTRODUCTION

The bond markets in Europe and elsewhere have developed independently with inevitably different conventions for calculating prices, yields and interest rates and settling the various instruments. With the ever increasing amount of cross-border trading it is desirable that people should be able to compare accurately the markets in one country with another and agree the cost of the transactions. The purpose of this book is to help in the process.

The practices of the individual markets are constantly changing and these changes are tending to make the markets more homogeneous - partly due to the influence of the G30 recommendations, but more significantly, due to the greatly increased amount of cross-border trading and the advent of the euro.

Examples of this are the wide acceptance of the ISMA yield methodology, which is included in the Maastricht treaty, and the standard money market yield calculation. Similarly, there has been a move to settling bond transactions internationally, in many European domestic markets and in the U.S. corporate market on a T+3 basis (i.e. 3 business days after trade date).

However, the different bond and money markets still continue to accrue interest on a variety of bases, to trade ex-coupon for different periods etc. For example, currently in France, the money markets accrue interest on a 360-day year basis, whereas the bond markets accrue on a 365/366-day year. The situation is reversed in Italy, with the money markets accruing interest on a 365-day year and the bond markets on a 360-day year.

It should be noted that, whilst every effort has been made to establish the validity of the data, the constantly changing nature of the markets inevitably creates a potential for errors and omissions, for which neither the author or publisher can accept liability.

1



<!-- bnd_page-07.md -->

## CHAPTER 2  TRADE, VALUE AND SETTLEMENT DATES

Most markets have rules for determining the value date of a transaction. For example, the value date for a transaction in an applicable international security is governed by ISMA Rules 221–225. The rules as at January 1997 are given below:

### Rule 221 Value date new issues

The value date for a transaction effected prior to the closing date shall be the closing date or the third business day following the trade date, whichever is the later.

A business day for the purpose of this rule shall be a day when Cedel, Euroclear and the cash market of the currency in which the relevant transaction is to be settled are open for business.

In case either Cedel, Euroclear or the cash market of the currency in which the relevant transaction is to be settled, are closed for business between the trade date and the value date, accrued interest shall be adjusted.

### Rule 222 Normal value date

The value date for a transaction effected on or after the closing date shall be the third business day (as defined in rule 221) following the trade date.

In case either Cedel, Euroclear or the cash market of the currency in which the relevant transaction is to be settled, are closed for business between the trade date and the value date, accrued interest shall be adjusted.

2

TRADE, VALUE AND SETTLEMENT DATES

## Rule 223 Special value date

A special value date may be mutually agreed between the buyer and the seller at the time of dealing.

## Rule 224 Value date on non-settlement day

Deleted effective June 1, 1995.

## Rule 225 Value date and coupon due date

Where the due date of an interest coupon coincides with the value date of a transaction, the buyer shall not acquire such coupon and no accrued interest shall be calculated on such a contract. With the exception of floating rate notes, in the case of a transaction with a value date on the thirtieth calendar day and a coupon due date on the thirty-first calendar day of the same month, accrued interest shall correspond to the full value of the coupon.

The value date and the settlement date are normally identical. It is conventional and recommended that all calculations on securities are performed to the value date and not the settlement date if there is a discrepancy.

Similarly if a coupon or redemption falls on a non-settlement date then all calculations are performed as if the payment were to be made on that date.

The worst problem that can arise is when a bond is expected to be redeemed on a nonsettlement date e.g. Taylor Woodrow 8 ¾% 1 December 1990 which was redeemed on a Saturday. The terms of most new international issues are now chosen so that this does not occur, however in some domestic markets, e.g. the Netherlands and Germany, it is a common occurrence, because of their coupon payment conventions.

## Example ▶

If the cost of overnight money is 10% then the cost of a two day delay on the redemption payment is $10 \times 2/365 = 0.0548\%$ .

Coupons on fixed rate bonds will frequently occur at weekends and on bank holidays. However, this should not happen with floating rate notes as the issuing houses normally follow the convention below.

The interest payment date is the date falling six calendar months after the closing date and each date thereafter which falls six calendar months after the preceding interest payment date. If any interest payment date would otherwise fall on a day which is not a business day, it shall be postponed to the next business day unless it would thereby fall in the next calendar month. In the latter event, the interest payment date shall be the immediately preceding business day, and each subsequent interest payment date

3



<!-- bnd_page-08.md -->

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

shall be the last business day of the sixth calendar month after the month in which the preceding interest payment date shall have fallen.

Example ▶

Consider a floating rate note which pays a monthly coupon on Tuesday, 28 January 1996. The subsequent coupon payment dates will be:

<table><tr><td>28 February</td><td>Friday</td></tr><tr><td>30 March</td><td>Monday</td></tr><tr><td>30 April</td><td>Thursday</td></tr><tr><td>29 May</td><td>Friday</td></tr><tr><td>30 June</td><td>Tuesday</td></tr><tr><td>31 July</td><td>Friday</td></tr><tr><td>28 August</td><td>Friday (assuming 31 August is not a business day)</td></tr><tr><td>30 September</td><td>Wednesday</td></tr></table>


4

## CHAPTER 3

## ACCRUED INTEREST

The prices of bonds in most markets are normally quoted `Clean', i.e. without any accrued interest, which has to be paid by the purchaser. However, there are occasions when the trade is agreed on a `Flat' or Gross' price, i.e. without any accrued adjustment. This sometimes occurs because the payment of interest is uncertain, e.g. the issuer is in default and it is not clear if the accrued interest will ever be received. It also occurs with repo transactions where the convention in the market is to agree a `Flat' price for the collateral. On the other hand buy/sell back transactions tend to follow the normal bond market conventions.

### Accrual basis

Securities accrue interest in a variety of ways, according to the number of days since issue or the last coupon date. In the majority of cases the accrued interest which has to be added to the price is equal to:

$$assumed rate of interest  \times  number of days accrued / number of days in the year,$$

There are several methods of counting the number of days accrued and in the year. They are described below.

### 3.1. Counting Days Accrued

There are basically three methods of counting the number of days accrued interest, although they are subject to variation:

- • Actual calendar days, including 29 February if it occurs in the period.
• 30-day month European Method
• 30-day month U.S. Method
For international securities, ISMA rule 251 specifies how accrued interest should be calculated for fixed and floating rate securities. Fixed rate securities currently follow the 30-day month European method, whereas floating rate notes use actual days.

5



<!-- bnd_page-09.md -->

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

However, it is expected that all international securities issued after 31 December 1998 will use actual calendar days for the calculation of accrued interest. ISMA rule 251 (January 1997) specifies:

Rule 251 Accrued interest calculation

251.1 With the exception of floating rate notes, accrued interest on a contract shall be calculated on a 360-days per year basis (each calendar month to be considered one-twelfth of 360-days, or thirty days, and each period from a date in one month to the same date in the following month to be considered thirty days) from and including the date of the last paid interest coupon or the day from which interest is to accrue for a new issue, up to but excluding the value date of the transaction.

Examples of calculations in conformity with Rules 225 (see chapter 2) and 251:

<table><tr><td rowspan="2">Interest accrues from coupon dates</td><td rowspan="2">Value dates</td><td colspan="3">Number of days of accrued interest for straight and convertible bonds</td></tr><tr><td>normal</td><td>leap year</td><td></td></tr><tr><td>30.11.</td><td>28.2.</td><td>88</td><td>90</td><td>90</td></tr><tr><td>30.11.</td><td>29.2.</td><td>89</td><td></td><td>91</td></tr><tr><td>30.11.</td><td>1.3.</td><td>91</td><td>91</td><td>92</td></tr><tr><td>30.11.</td><td>3.3.</td><td>93</td><td>93</td><td>94</td></tr><tr><td>30.11.</td><td>30.3.</td><td>120</td><td>120</td><td>121</td></tr><tr><td>30.11.</td><td>31.3.</td><td>120</td><td>121</td><td>122</td></tr><tr><td>31.12.</td><td>28.2.</td><td>58</td><td>59</td><td>59</td></tr><tr><td>31.12.</td><td>29.2.</td><td>59</td><td>-</td><td>60</td></tr><tr><td>31.12.</td><td>1.3.</td><td>61</td><td>60</td><td>61</td></tr><tr><td>31.12.</td><td>3.3.</td><td>63</td><td>62</td><td>63</td></tr><tr><td>31.12.</td><td>30.3.</td><td>90</td><td>89</td><td>90</td></tr><tr><td>31.12.</td><td>31.3.</td><td>90</td><td>90</td><td>91</td></tr><tr><td>1.1.</td><td>28.2.</td><td>57</td><td>58</td><td>58</td></tr><tr><td>1.1.</td><td>29.2.</td><td>58</td><td></td><td>59</td></tr><tr><td>1.1.</td><td>1.3.</td><td>60</td><td>59</td><td>60</td></tr><tr><td>1.1.</td><td>3.3.</td><td>62</td><td>61</td><td>62</td></tr><tr><td>1.1.</td><td>30.3.</td><td>89</td><td>88</td><td>89</td></tr><tr><td>1.1.</td><td>31.3.</td><td>89</td><td>89</td><td>90</td></tr><tr><td>15.1.</td><td>28.2.</td><td>43</td><td>44</td><td>44</td></tr><tr><td>15.1.</td><td>29.2.</td><td>44</td><td></td><td>45</td></tr><tr><td>15.1.</td><td>1.3.</td><td>46</td><td>45</td><td>46</td></tr><tr><td>15.1.</td><td>3.3.</td><td>48</td><td>47</td><td>48</td></tr><tr><td>1.2.</td><td>28.2.</td><td>27</td><td>27</td><td>27</td></tr><tr><td>1.2.</td><td>29.2.</td><td>28</td><td></td><td>28</td></tr><tr><td>1.2.</td><td>1.3.</td><td>30</td><td>28</td><td>29</td></tr><tr><td>1.2.</td><td>3.3.</td><td>32</td><td>30</td><td>31</td></tr></table>


6

$$ Accrued INTERest $$

<table><tr><td>Interest accrues from coupon dates</td><td>Value dates</td><td colspan="3">Number of days of accrued interest for straight and convertible bonds</td></tr></table>


* seller collects full interest coupon, no accrued interest calculation to the buyer.

251.2 With the exception of floating rate notes, accrued interest to a value date on the thirty-first calendar day of a month shall be the same as to the thirtieth calendar day of the same month.

251.3 Accrued interest on a contract for floating rate notes shall be calculated on actual days, divided by 360 (or by 365 in the case of a Euro-sterling issue) from and including the date of the last paid interest coupon or the day from which interest is to accrue for a new issue, up to but excluding the value date of the transaction.

251.4    No accrued interest shall be calculated where rule 225 (see chapter 2) applies or where the value date coincides with the date of issue or where a transaction has been concluded at a 'flat' price.

Rule 251.3 above states that the accrued interest on Euro-sterling floating rate notes is calculated by dividing the actual days accrued by 365 and multiplying by the coupon rate. This is always true for bonds where the next coupon payment is in a non-leap year, but for coupon payments in a leap year the actual number of days is normally divided by 366. However, there are a few Euro-sterling issues where the issue documentation, which should be followed, specifies that the number of days accrued has to be divided by 365 even in a leap year.

As can be seen, in the European 30-day method (30E) the 31st of a month is always counted as if it were the 30th, and there are three days from 28 February to 1 March, even in a leap year .

In other words, if the interest accrues from date $D_1/M_1/Y_1$ to a value date of $D_2/M_2/Y_2$ , then the number of days accrued can be calculated as follows:

7



<!-- bnd_page-10.md -->

BOND Markets: Structures and Yield Calculations

If $D_{J}=31$, set it to 30

If $D_{2}=31$, set it to 30

$$ Number of days accrued =\left(D_{2}-D_{1}\right)+30 \times\left(M_{2}-M_{1}\right)+360 \times\left(Y_{2}-Y_{1}\right)$$

In the U.S. method (30U), the 31st of a month is counted - unless the period being measured is from the 30th or 31st of a previous month, when the period is counted as a whole number of months (i.e. it is a multiple of 30).

In this case, if the interest accrues from date $D_1/M_1/Y_1$ to a value date of $D_2/M_2/Y_2$ , then the number of days accrued can be calculated as follows:

If $D_{l}=31$, set it to 30

If $D_{2}=31$ and $D_{1}$ is 30 or 31 set $D_{2}$ to 30, otherwise leave as 31.

$$ Number of days accrued =\left(D_{2}-D_{1}\right)+30 \times\left(M_{2}-M_{1}\right)+360 \times\left(Y_{2}-Y_{1}\right)$$

In the U.S. method if a bond has a coupon date on the last day of February it is treated as if it were on the 30th February.

Example ▶

Consider a bond which follows the U.S. method with semi-annual coupon payments maturing on 31 August 2005. The other coupon payment is normally the last day of February. The number of days accrued interest is on the following dates.

<table><tr><td></td><td>Days accrued</td><td></td><td>Days accrued</td></tr><tr><td>27 February 1996</td><td>177</td><td>27 February 1997</td><td>177</td></tr><tr><td>28 February 1996</td><td>178</td><td>28 February 1997</td><td>0</td></tr><tr><td>29 February 1996</td><td>0</td><td></td><td></td></tr><tr><td>1 March 1996</td><td>1</td><td>1 March 1997</td><td>1</td></tr><tr><td>30 August 1996</td><td>180</td><td>30 August 1997</td><td>180</td></tr><tr><td>31 August 1996</td><td>0</td><td>31 August 1997</td><td>0</td></tr></table>


The following figure shows a comparison of some of the differences between the ISMA/European, the U.S. and the actual methods of calculating the number of days accrued.

<table><tr><td rowspan="2">Date 1</td><td rowspan="2">Date 2</td><td colspan="3">No. of days between Date 1 &amp; Date 2</td></tr><tr><td>ISMA Method</td><td>U.S. Method</td><td>Actual</td></tr><tr><td>29 July</td><td>31 August</td><td>31</td><td>32</td><td>33</td></tr><tr><td>30 July</td><td>31 August</td><td>30</td><td>30</td><td>32</td></tr><tr><td>31 July</td><td>31 August</td><td>30</td><td>30</td><td>31</td></tr></table>


8

$$ Accrued Interest $$

<table><tr><td>1 August</td><td>31 August</td><td>29</td><td>30</td><td>30</td></tr><tr><td>29 July</td><td>1 September</td><td>32</td><td>32</td><td>34</td></tr><tr><td>30 July</td><td>1 September</td><td>31</td><td>31</td><td>33</td></tr><tr><td>31 July</td><td>1 September</td><td>31</td><td>31</td><td>32</td></tr><tr><td>1 August</td><td>1 September</td><td>30</td><td>30</td><td>31</td></tr></table>


### 3.2 Days in the Year

There are four main ways of determining the number of days in the year. They are: 360, 365, actual days in the year (i.e. 365 unless it is a leap year when it is 366), and actual days in the coupon period multiplied by the number of coupon periods in a year.

The number of days in the year is not dependent on the method of calculating the number of days accrued. (For example, in the floating rate note Euromarket, for all currencies other than sterling and the Irish pound, the accrued is based on actual days since the issue or last coupon date divided by 360. In other words a floating rate note held for one year will produce an income greater than the average quoted coupon. Floating rate sterling and Irish pound notes use a 365-day year).

If the year is deemed to be actual days and allows for leap years (365/366), the convention in the Eurobond market is to divide by 366 for all coupon payments which occur in a leap year, unless there is only one payment per year. In this latter case, the payment period which includes 29 February is divided by 366. On the other hand, in the French market, the convention is to divide by 366 if a leap day occurs in the calendar year before the coupon date.

Example ▶

If a bond which accrues on a 365/366-day year has normal coupon dates of 15 January and 15 July, then the number of days in the year for each coupon period will be:




On the other hand, if the bond only had one payment on 15 January, the calculation would be:

Coupon Period

<table><tr><td>15 January 1995 - 15 January 1996 - 15 January 1996 - 15 January 1996 - 15 January 1996 -</td></tr></table>


9



<!-- bnd_page-11.md -->

![Figure](figures/bnd_page-11_figure_000.png)

![Figure](figures/bnd_page-11_figure_001.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

The position with leap years is further complicated by the 1991 International Swaps and Derivatives Association (ISDA) definitions for “day count fraction”. This is specified as the method to follow in some medium-term note programmes.

The 1991 ISDA definition states:

"Day count fraction" means, in respect of a swap transaction and the calculation of a fixed amount, a floating amount, a compounding period amount or an FRA amount,

- a) if “ actual/365" or “ actual/actual" is specified, the actual number of days in the
calculation period or compounding period in respect of which payment is being made
divided by 365 (or, if any portion of that calculation period or compounding period
falls in a leap year, the sum of (A) the actual number of days in that portion of the
calculation period or compounding period falling in a leap year divided by 366 and
(B) the actual number of days in that portion of the calculation period or
compounding period falling in a non-leap year divided by 365);
b) if “ actual/365 (fixed)" is specified, the actual number of days in the calculation
period or compounding period in respect of which payment is being made divided by
365;
ISDA are in the process of reviewing their definitions.

For the purpose of accruing interest some markets define the number of days in a year to be the actual days in the coupon period times the number of periods per annum. Markets which use this method include the U.S. Treasury market, and the proposed U.K. gilt-edged and international fixed-rate bond markets.

Example ▶

A U.S. Treasury bond with an 8% coupon in a 184 day 6-month period accrues interest at a daily rate of:

$$8/(2 \times 184)=0.021739 \%$$

Similarly in a 181 day 6-month period it accrues interest at a daily rate of:

$$8 /(2 \times 181)=0.022099 \%$$

Some bonds are issued with 'short' or 'long' first coupon periods. For these, a theoretical number of days in the period(s) has to be calculated.

The first coupon period is deemed to start on what would have been the normal coupon date on or before the date interest starts accruing on the bond.

10

$$ Accrued INTERest $$

If the date interest starts accruing is before what would have been the coupon date prior to the first coupon date, then the period has to be split into two quasi interest periods for the calculation.

Example ▶

For bonds with an 8% coupon issued on 1 February 1999 (with interest accruing from this date).

<table><tr><td>Coupon Payment Date(s)</td><td>First Coupon Payment Date</td><td>First Coupon Period Days in Year Calculation</td><td>Daily Accrual Rate</td><td>First Coupon Payment</td></tr><tr><td>1 Feb</td><td>1 Feb 2000</td><td>1 Feb 1999-1 Feb 2000 (365 days)</td><td>8/365</td><td>8%</td></tr><tr><td>1 July</td><td>1 July 1999</td><td>1 July 1998-1 July 1999 (365 days)</td><td>8/365</td><td>8 × 150/365% (1 Feb-1 July = 150 days)</td></tr><tr><td rowspan="2">1 July</td><td>1 July 2000</td><td rowspan="2">1 July 1998-1 July 2000 (731 days split into 2 periods) 1 July 1998-1 July 1999 (365 days) 1 July 1999-1 July 2000 (366 days)</td><td>8/365</td><td>Note 1</td></tr><tr><td>Period 1 Period 2</td><td>8/366</td><td>4%</td></tr><tr><td>1 Feb, Aug</td><td>1 Aug 1999</td><td>1 Feb 1999-1 Aug 1999 (181 days)</td><td>8/(2 x 181)</td><td>8 × 150/362% (1 Feb-1 July = 150 days)</td></tr><tr><td>1 Jan, July</td><td>1 July 1999</td><td>1 Jan 1999-1 July 1999 (181 days)</td><td>8/(2 x 181)</td><td>8 × 150/362% (1 Feb-1 July = 150 days)</td></tr><tr><td rowspan="2">1 Jan, July</td><td>1 Jan 2000</td><td rowspan="2">1 Jan 1999-1 Jan 2000 (365 days split into 2 periods) 1 Jan 1999-1 July 1999 (181 days) 1 July 1999-1 Jan 2000 (184 days)</td><td>8/(2 × 181)</td><td>Note 2</td></tr><tr><td>Period 1 Period 2</td><td>8/(2 × 184)</td><td>Note 2</td></tr></table>


Note 1  The first coupon payment is: $8\times150/365 + 8\times366/366\%$ as there are 150 days from 1 February 1999 to 1 July 1999 Note 2  The first coupon payment is: $8\times150/(2\times181) + 8\times184/(2\times184)\%$ as there are 150 days from 1 February 1999 to 1 July 1999.

11



<!-- bnd_page-12.md -->

![Figure](figures/bnd_page-12_figure_000.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

It can be seen that for a bond which pays an annual coupon, this method is equivalent to the actual days in the year method.

In most markets interest accrues from the issue date or last coupon date (inclusive) to the settlement date (exclusive), however this is not universally true. For example, in Italy, both the coupon and settlement dates are counted.

### 3.3. Accrued interest computation

For international bonds, ISMA Rule 252 below specifies the method of rounding U.S. dollar accrued interest.

### Rule 252 Accrued interest computation - fractions

In all transactions involving the payment of interest, fractions of a cent equalling or exceeding 5 mills shall be regarded as one cent and fractions of a cent less than 5 mills shall be disregarded. Examples:

$137,625 accrued interest has to be increased to $137,63.

$137.624 accrued interest has to be decreased to $ 137.62.

For other currencies accrued interest should be rounded to the nearest convenient currency unit in a similar way.

12

## CHAPTER 4  MEASURES OF LIFE AND ASSOCIATED CALCULATIONS

It has been seen that currently international straight bonds accrue interest on the basis of twelve 30 day months (i.e. 360-days in a year), whereas international floating-rate notes accrue interest on every calendar day. When calculating the life or other time measure of a security, the various conventions are continued, although they result in slightly different results.

For any international non-floating rate security including warrants, the period between two dates $D_1/M_1/Y_1$ and $D_2/M_2/Y_2$ is given in days by:

$$\text{If }D_{t}=31\text{, set }D_{t}=30.$$

$$ If  D_{2}=31 , set  D_{2}=30 .$$

$$ Number of days =\left(D_{2}-D_{1}\right)+30 \times\left(M_{2}-M_{1}\right)+360 \times\left(Y_{2}-Y_{1}\right)$$

For floating-rate notes the period between two dates in years is the number of complete years moving forward from the first date plus the actual number of days for the fractional period at the end divided by 365 or 366 if the fractional period includes 29 February.

Example ›

The period from 1 February 1998 to 1 August 2000 is considered to be a two year period from 1 February 1998 to 1 February 2000 plus a part period from 1 February 2000 to 1 August 2000. The part period being 182 days = 182/366 years = 0.497 years. Thus the total period is 2.497 years.

13



<!-- bnd_page-13.md -->

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

If the whole years are calculated back from the last date, a different answer is obtained, as the part period is now from 1 February 1998 to 1 August 1998 which is only 181 days.

Examples of the calculations using international bonds are given below:

<table><tr><td>Date 1</td><td>Date 2</td><td>Type of security</td><td>Period in years and days</td><td>Period in years</td></tr><tr><td>1 August 1993</td><td>1 February 1994</td><td>straight</td><td>0 years</td><td>180 days</td></tr><tr><td>1 August 1993</td><td>1 February 1994</td><td>FRN</td><td>0 years</td><td>184 days</td></tr><tr><td>1 February 1994</td><td>1 August 1995</td><td>straight</td><td>1 year</td><td>180 days</td></tr><tr><td>1 February 1994</td><td>1 August 1995</td><td>FRN</td><td>1 year</td><td>181 days</td></tr><tr><td>1 February 1994</td><td>1 August 1996</td><td>straight</td><td>2 years</td><td>180 days</td></tr><tr><td>1 February 1994</td><td>1 August 1996</td><td>FRN</td><td>2 years</td><td>182 days</td></tr><tr><td>1 January 1994</td><td>31 December 1994</td><td>straight</td><td>0 years</td><td>359 days</td></tr><tr><td>1 January 1994</td><td>31 December 1994</td><td>FRN</td><td>0 years</td><td>364 days</td></tr><tr><td>1 January 1996</td><td>31 December 1996</td><td>Straight</td><td>0 years</td><td>359 days</td></tr><tr><td>1 January 1996</td><td>31 December 1996</td><td>FRN</td><td>0 years</td><td>365 days</td></tr></table>


* The fractional periods are part of 366-day years.

Various measures of life are applied to securities. They include life to maturity, next call, put, extension period, average life, equivalent life and duration. Lives are always measured from the value date to the assumed redemption date(s) using the appropriate calendar convention.

### 4.1    Life to maturity

The maturity date of a bond is assumed to be the final normal maturity date. Any extendible or retractable dates are ignored.

### 4.2    Life to next call

Bonds are often callable by the issuer prior to maturity upon a set notice period, e.g. they may be callable only on coupon dates, at annual intervals, or at any time during the call period.

Example ▶

Consider the following variations of a bond which has an 8% coupon payable semiannually on 1 January and 1 July, and a final redemption date on 1 July 1998 provided it has not been previously called. It may be called on 30 days notice between 1 January 1993 and 30 June 1996 at:

either a) or b) or c)

any time on a coupon date annually on 1 July

14

MEASURES OF LIFE AND ASSOCIATED CALCULATIONS

<table><tr><td rowspan="2">Trade date</td><td colspan="3">Earliest next call dates</td></tr><tr><td>Option (a)</td><td>Option (b)</td><td>Option (c)</td></tr><tr><td>1 January 1990</td><td>1 January 1993</td><td>1 January 1993</td><td>1 July 1993</td></tr><tr><td>1 December 1992</td><td>1 January 1993</td><td>1 January 1993</td><td>1 July 1993</td></tr><tr><td>2 December 1992</td><td>2 January 1993</td><td>1 July 1993</td><td>1 July 1993</td></tr><tr><td>1 June 1993</td><td>1 July 1993</td><td>1 July 1993</td><td>1 July 1993</td></tr><tr><td>2 June 1993</td><td>2 July 1993</td><td>1 January 1994</td><td>1 July 1994</td></tr><tr><td>2 June 1995</td><td>2 July 1995</td><td>1 January 1996</td><td>Not callable</td></tr><tr><td>2 December 1995</td><td>2 January 1996</td><td>Not callable</td><td>Not callable</td></tr><tr><td>1 June 1996</td><td>Not callable</td><td>Not callable</td><td>Not callable</td></tr></table>


### 4.3   Life to put

It is conventional to calculate the life to put to the next put opportunity.

### 4.4. Average life

The average life of a bond is the period from the value date to the average of the future sinking fund dates weighted by the non-discounted repayments.

Some bonds have purchase funds, which enable stock to be purchased in the market within specified price ranges. Purchase funds are not mandatory and hence do not affect the long term return of an investor and so are ignored in the calculation of average life.

The average life is given by:

$$A L=\frac{\sum_{i=1}^{n} A_{i} \cdot  L_{i}}{\sum_{i=1}^{n} A_{i}}(4.1)$$

where: $\begin{array}{rcl} AL &=& \text{average life} \\ n &=& \text{number of future capital repayments} \\ A_i &=& i\text{th future repayment amount} \\ L_i &=& \text{time in years to the }i\text{th repayment} \end{array}$

Example ▶

If a bond has a sinking fund of;

20% to be redeemed on 1 June 1999

10% to be redeemed on 1 June 2000

70% to be redeemed on 1 June 2001

15



<!-- bnd_page-14.md -->

![Figure](figures/bnd_page-14_figure_000.png)

![Figure](figures/bnd_page-14_figure_001.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

then the average life on 1 June 1994 can be calculated as follows:

$$Average\ life=\frac{20\times 5+10\times 6+70\times 7}{20+10+70}=6.5\ years$$

i.e. the average redemption date is 1 December 2000.

It can be seen that the average life of a security continuously decreases over time between repayments, but jumps on a repayment date.

### 4.5 Equivalent life

The concept of equivalent life is very similar to that of average life for bonds with sinking funds, except that now the capital repayments are discounted at the redemption yield rate.

The equivalent life of a bond is the period from the value date to the average of the future sinking fund dates weighted by the discounted capital repayments. This means that the equivalent life is slightly shorter than the average life.

The equivalent life is given by:

$$E L=\frac{\sum_{i=1}^{n} A_{i} \cdot  I_{i} \cdot  v^{L i}}{\sum_{i=1}^{n} A_{i} \cdot  v^{L i}}(4.2)$$

where: $\begin{array}{rcl} & E L & = & \text{equivalent life } \\ & n & = & \text{number of future capital repayments } \\ & A_{i} & = & \text{ith future repayment amount } \\ & L_{i} & = & \text{time in years to the ith repayment } \\ & \nu & = & \text{annualized discounting factor } \end{array}$

i.e. if the annualized yield is y then $v=1/(1+y)$ ( $y=0.08$ for a yield of 8 % )

Example ▶

Using the same example as in average life of a bond which is redeemed at par in three instalments, such that 20% is redeemed on 1 June 1999, 10% on 1 June 2000 and 70% on 1 June 2001. Assuming the bond has an annualized redemption yield allowing for this schedule of 10% then the equivalent life on 1 June 1994 is given by:

$$v=1/(1+0.1)=0.90909$$

$$EL=\frac{20\times5v^{5}+10\times6v^{6}+70\times7v^{7}}{20\times v^{5}+10\times v^{6}+70\times v^{7}}$$

16

MEASURES OF LIFE AND ASSOCIATED CALCULATIONS

$$\begin{aligned}
& =\frac{62.092+33.868+251.447}{12.418+5.645+35.921} \\
& =6.435  years 
\end{aligned}$$

### 4.6. Duration

The concept of life to maturity, average or equivalent life does not give the investor a true indication of the life of a bond, since it does not take into account any coupon payments. There is, for example, a lot of difference from an investment point of view between a zero coupon 10 year bond and an 11 % 10 year bond, since the former only makes one payment after 10 years while the latter pays coupons during its life of more than its redemption value.

The concept of duration is a better measure of the life of the investment, as it takes into account both the coupon and the redemption payments. Duration is defined to be the average life of the present values of all future cash flows from the bond. In calculating the present value of the future cash flows a discount rate equal to the redemption yield of the bond is used.

Mathematically duration is given by:

$$D=\frac{\sum_{i=1}^{n} C F_{i} \cdot  L_{i} \cdot  v^{L i}}{\sum_{i=1}^{n} C F_{i} \cdot  v^{L i}}(4.3)$$

where: $\begin{array}{rcl} D &=& \text{duration} \\ n &=& \text{number of future coupon and capital cash flows} \\ CF_i &=& \text{ith future cash flow} \\ L_i &=& \text{time in years to the ith cash flow} \\ v &=& \text{annualized discounting factor} \end{array}$ i.e. if the annualized yield is y then $v = 1/(1+y)$ ( $y=0.08$ for a yield of 8 % )

Since the gross price of a bond is just the present value of all future cash flows equation (4.3) can be re-written:

$$D=\frac{1}{P}\cdot \sum_{i=1}^{n}CF_{i}\cdot  L_{i}\cdot \nu^{Li}(4.4)$$

where: $P = $  gross price (i.e. clean price plus accrued interest).

The above calculations are also known as the Macaulay Duration.

$${S}_{四边形AOCE}={S}_{\triangle AOD}=\frac {1}{2}{S}_{四边形AOE}=\frac {1}{2}{S}_{四边形AOD}$$



<!-- bnd_page-15.md -->

116 BOND MARKETS: STRUCTURES AND Y

For a zero coupon bond the duration is the same as the life to maturity.

For a bond with a fixed coupon $g$ payable $h$ times per annum, with a normal first coupon payment, which is redeemable on one coupon date, it can be shown that the duration can be given by:

$$D=\frac{f1}{h}+\frac{g\cdot  v^{f1}}{P\cdot  h^{2}}\cdot \left\{v+2v^{2}+\cdot s+(n-1)v^{n-1}\right\}+\frac{C}{P\cdot  h}\cdot (n-1)v^{n+f1-1}(4.5)$$

where: $\begin{array}{rcl} D &=& \text{duration} \\ g &=& \text{annual coupon rate } \% \\ h &=& \text{number of coupon payments per year} \\ n &=& \text{number of coupon payments to redemption} \\ P &=& \text{gross price (i.e. clean price plus accrued interest)} \\ C &=& \text{redemption value} \\ f1 &=& \text{fraction of a period from value date to the first interest} \\ & & \text{payment date. A period is defined as the normal time} \\ & & \text{between two consecutive coupon payments} \\ v &=& \text{discounting factor i.e. if the yield compounded } h \text{ times} \\ & & \text{per annum is y then } v = 1/(1 + y/h) \\ & & (y = 0.08 \text{ for a yield of } 8\%) \end{array}$

Example ▶

Consider the following bond which pays an annual 9 % coupon, is trading at par and is redeemed at par in four years time. The duration (D) of the bond is calculated as follows:

The redemption yield for this bond is 9% and so the discounting factor $v = 1/1.09 = 0.91743.$

From equation (4.4):

$$\begin{aligned}
D&=\frac{1}{100}\times\left(9\times v+9\times 2v^{2}+9\times 3v^{3}+9\times 4v^{4}+100\times 4v^{4}\right)\\
&=3.531\text{ years}
\end{aligned}$$

or from equation (4.5):

$$\begin{aligned}
D&=1+\frac{9v}{100}\times\left(v+2v^{2}+3v^{3}\right)+\frac{100}{100}\times3v^{4}\\
&=3.531\text{ years}
\end{aligned}$$

18

MEASURES OF LIFE AND ASSOCIATED CALCULATIONS

It can be seen that for non zero coupon bonds duration does not decrease smoothly for a fixed discount rate when it approaches redemption, as it jumps at every coupon payment.

The graph below shows how the duration of a bond which pays a 10% annual coupon changes over its 6-year life, assuming the price remains at par.

![Figure](figures/bnd_page-15_figure_016.png)

Another feature of duration is that if you increase the maturity date of a bond, assuming that it has the same coupon and redemption yield, then it is possible in certain circumstances for the duration to decrease as opposed to progressively increase. This can occur for long dated bonds with coupons below the assumed redemption yield. It does not occur if the bond is trading above par.

Example ›

Consider a bond which pays a 5% annual coupon and has a 10% redemption yield. For various lives to maturity it has the durations shown below:

<table><tr><td>Life to Maturity</td><td>Duration</td></tr><tr><td>10 years</td><td>7.661</td></tr><tr><td>20 years</td><td>10.741</td></tr><tr><td>30 years</td><td>11.433</td></tr><tr><td>40 years</td><td>11.389</td></tr><tr><td>50 years</td><td>11.236</td></tr><tr><td>100 years</td><td>11.006</td></tr></table>


For an undated security, equation (4.5) can be further reduced to:

$$D=\frac{f1}{h}+\frac{g}{P\cdot  h^{2}}\cdot \frac{\nu^{f+1}}{(1-\nu)^{2}}$$

19



<!-- bnd_page-16.md -->

![Figure](figures/bnd_page-16_figure_000.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

$$\begin{split}
D&=\frac{f1}{h}+\frac{v}{h\cdot (1-v)}\\
D&=\frac{f1}{h}+\frac{1}{y}\tag{4.6}
\end{split}$$

This formula for the duration is independent of the coupon.

Example ▶

An undated 8% bond pays interest semi-annually on 15 January and 15 July. On 15 April it has a redemption yield of 10.25% compounded annually. What is its duration?

A yield of 10.25% compounded annually is equivalent to a yield of 10.0% compounded semi-annually (see Appendix II). On 15 April, $f1 = 0.5$ and the duration (D) is given by:

$$\begin{aligned}
D&=\frac{0.5}{2}+\frac{1}{0.1}\\
&=10.25\text{ years}
\end{aligned}$$

### 4.7 Modified duration or volatility

The modified duration or volatility of a bond gives the percentage change in price of a bond for a unit change in yield. Hence the larger the modified duration, the greater the price volatility for a specific yield movement.

The modified duration is given by:

$$MD=-\frac{dP}{dy}\cdot \frac{1}{P}(4.7)$$

where: $$ $MD$ = modified duration $P$ = gross price (i.e. clean price plus accrued interest) $dP$ = small change in price $dy$ = corresponding small change in yield compounded with the frequency of the coupon payment

It can be easily proved (see Appendix I) that modified duration and duration are related by:

$$MD=D\cdot  v(4.8)$$

where: $\begin{matrix} MD &= & \text{modified duration} \\ D &= & \text{duration} \end{matrix}$

20

MEASURES OF LIFE AND ASSOCIATED CALCULATIONS

$v$ = discounting factor i.e. if the yield compounded $h$ times per annum is $y$ then $v = 1/(1 + y/h)$ ($y = 0.08$ for a yield of 8%) $h$ = number of coupon payments per year

Example ▶

A bond paying a 9 % annual coupon with four years to go to redemption at par, has been shown to have a duration of 3.531 years if trading at par. The modified duration (MD) is then given by:

$$MD=\frac{3.53I}{(I+0.\ 09)}=3.\ 239$$

and so applying equation (4.7) if the yield drops by 0.1% to 8.9% the price should increase by 0.324 to 100.324%.

### 4.8 Convexity

Modified duration of a bond indicates how the price will change for a small change in yield. Unfortunately, although this works very well for small yield changes it does not for larger changes. This is because the relationship between the price and the yield is not linear, but curvilinear. The degree of curvature, which varies from bond to bond is called the convexity.

Example ▶

Consider a 10 year bond with a 10 % annual coupon. Below is a table of prices, actual redemption yields, modified durations and expected yields. The expected yields are calculated using equation (4.7) and are based on the redemption yield and the modified duration when priced at par.

<table><tr><td>Price</td><td>Redemption yield</td><td>Modified duration</td><td>Expected yield</td><td>Difference between yields</td></tr><tr><td>90</td><td>11.752</td><td>5.885</td><td>11.627</td><td>0.125</td></tr><tr><td>95</td><td>10.843</td><td>6.019</td><td>10.814</td><td>0.029</td></tr><tr><td>99</td><td>10.164</td><td>6.120</td><td>10.163</td><td>0.001</td></tr><tr><td>99.9</td><td>10.016</td><td>6.142</td><td>10.016</td><td>0.000</td></tr><tr><td>100</td><td>10.000</td><td>6.145</td><td></td><td></td></tr><tr><td>100.1</td><td>9.984</td><td>6.147</td><td>9.984</td><td>0.000</td></tr><tr><td>101</td><td>9.838</td><td>6.169</td><td>9.837</td><td>0.001</td></tr><tr><td>105</td><td>9.214</td><td>6.264</td><td>9.186</td><td>0.028</td></tr><tr><td>110</td><td>8.477</td><td>6.376</td><td>8.373</td><td>0.104</td></tr></table>


21



<!-- bnd_page-17.md -->

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

It can be seen that the actual redemption yield for all prices is greater than or equal to the expected yield based on the modified duration.

Mathematically convexity is given by:

$$C X=\frac{1}{P} \cdot  \frac{d^{2} P}{d y^{2}}(4.9)$$

where: $CX = $ convexity $P = $ gross price $y = $ yield ( $y=0.08$ for a yield of 8 % ) and the second derivative of $P$ with respect to $y$ is derived from equation (5.3) which is discussed in the next chapter.

This formula is expanded in Appendix Ⅰ.

In practice instead of solving equation (4.9) it is usually sufficient to solve the approximation below:

$$C X=10^{6} \cdot \left(P_{1}+P_{2}-2 P\right) / P(4.10)$$

where: $$ $CX = $ = convexity $P = $ gross price at the current yield $P_I = $ gross price of the security if the yield were to increase by 10 basis points (0.1 % ) $P_2 = $ gross price of the security if the yield were to decrease by 10 basis points

Example ▶

Using the above example of a 10 year bond priced at par with a 10% annual coupon we have:

$$P_{I} =99.388174 (yield of  10.1 \%$$

$$P_{2} = 100.617105 (yield of 9.9\%)$$

$$\begin{aligned}
 therefore  C X & =& 10^{6} \times(99.388174+100.617105-200) / 100 \\
& = & 0.005279 \times 10^{4} \\
& = & 53
\end{aligned}$$

22

## CHAPTER 5  $$  Yields  $$

Bonds display a variety of anticipated cash flow patterns. For straights and convertibles the cash flow pattern is frequently predictable, with a fixed coupon at regular intervals and redemption on a specific date or dates. However, this is not true for floating rate notes (FRNs) where future cash flows are re-fixed on specified dates relative to a market rate or index (e.g. the London Interbank Offered Rate (LIBOR) for three month U.S. dollars), which varies over time. The methods of evaluating FRNs are discussed in chapter 6.

The wide variation of cash flow patterns for bonds means that prices cannot be used for comparing their relative attractiveness. One of the most common calculations for comparing bonds is that of yield. Three types of yield are commonly used:

- • Current yield
• Simple yield to maturity
• Redemption yield
### 5.1    Current yield

The current yield of a bond is also known as a flat, running or interest yield . It measures the income an investor would receive on a bond, if it continues to pay interest at the current rate, as a percentage of the price of the bond. It does not allow for any appreciation or depreciation that an investor would receive on disposal.

The current yield of a bond is given by the formula:

$$C Y=\frac{g \cdot  100}{C P} .(5.1)$$

where: $\begin{array}{rcl} CY &=& \text{current yield } \% \\ g &=& \text{annual coupon rate } \% \\ CP &=& \text{clean price (i.e. not including any accrued interest)} \end{array}$

23



<!-- bnd_page-18.md -->

![Figure](figures/bnd_page-18_figure_000.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

Example ▶

A bond has a clean price of 98% and a coupon of 9%, then the current yield is:

$$C Y = { \frac { 9 \times 1 0 0 } { 9 8 } } = 9 . 1 8 4 \%$$

The current yield calculation can be applied to straights, convertibles and FRNs. In the latter case, this is usually based on the last coupon fixing.

### 5.2    Simple yield to maturity

The simple yield to maturity is also known as a Japanese yield. It takes into account the effect of the capital gain or loss on maturity of the bond as well as the current yield. Unlike the redemption yield calculations any capital appreciation/depreciation is deemed to occur uniformly over the bond's life.

The simple yield to maturity of a bond is given by:

$$SY=\frac{g+(C-CP)/L}{CP}(5.2)$$

where:

Example ›

Consider a 6 % bond with 3 years 151 days (not counting any potential 29 February) to go to maturity at 100 % , which has a clean price of 96 % , then the simple yield to maturity is given by:

$$\begin{aligned}
S Y & =\frac{6+(100-96) /(3+151 / 365)}{96} \\
& =0.7471 \\
& =7.471 \%
\end{aligned}$$

24

$$ Yields $$

The simple yield to maturity formula (5.2) , gives a different value to the simple interest or money market yield formula for a bond, even in the last coupon period (see section 5.3.2 ).

### 5.3 Redemption yields

The redemption yield calculation removes the limitations of the current and simple yield to maturity calculations. It allows for all the expected future cash flows from the bond. The cash flows are usually from coupon payments and repayments of capital.

The redemption yield of a bond is that discount rate that would make the sum of the present values of all assumed future cash flows equal to the gross price of the bond. The gross price is the quoted clean price plus any associated accrued interest.

In other words the redemption yield $y$ is given by solving an equation of the form below:

$$P = \sum _ { i = 1 } ^ { n } C F _ { i } \cdot  v ^ { L i } ( 5 . 3 )$$

where: $$ $P = $ = gross price (i.e. clean price plus accrued interest) $n$ = number of future cash flows $CF_i$ = ith cash flow $L_i$ = time in periods to the ith cash flow, taking into account the market conventions for calculating the fraction of a period, (e.g. does the year have 360 or 365 days). $v$ = discounting factor i.e. $v = 1/(1 + y/h)$ $h$ = number of periods in the year $y$ = required redemption yield compounded h times per annum ( $y = 0.08$ for a yield of 8 % ).

N.B. in the case of partly-paid issues, future price calls are regarded as negative cash flows.

The period refers to the normal compounding period of the market. In the International bond and most European domestic markets this is one year, whereas in the U.K. and U.S. it is 6 months.

This general redemption yield formula, which assumes that all cash flows irrespective of their timing are discounted at the same rate, works for all securities. In addition the ISMA recommend some general principles in its application. These principles can be applied to International and other Domestic bonds.

### ISMA Redemption Yield Principles

i) Unless otherwise specified redemption yields are quoted with an annual compounding period, irrespective of how many coupon periods per annum the bond may have.

25



<!-- bnd_page-19.md -->

## BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

- ii) Compound interest is always used for the entire life, even when there is less
than one period to redemption.
iii) If the bond accrues interest on a 360-day year then the calendar for all yield
calculations consists of a 360-day year.*
iv) Unless otherwise specified, yields are calculated from the assumed value date,
not the settlement date (if different) or trade date.
* This rule may be relaxed when applying the ISMA yield calculations to non ISMA securities e.g. one might want to compare the yield on a French Government ECU OAT, which accrues interest on a 365-day year basis, with the yield on a Euro ECU issue. In both cases a 360-day year calendar will normally be assumed for the yield calculations.

Principle (i) above is compatible with the ISMA Rule 803 on a coupon date which states:

Rule 803 Standard maturity yield definition

803.1 The Association's standard method of calculating maturity yields shall be based on the definition of annual interest compounding. i.e. a bond with a 7% coupon, payable annually, priced at 100%, yields 7% per annum and the same bond paying interest semi-annually yields more.

803.2 A member of the Association calculating maturity yields by a method other than the one described above shall state exactly what method has been used for the calculation.

How to solve the general redemption yield formula (5.3) together with the derivation of modified duration and convexity is described in Appendix I .

The general redemption yield formula can be converted into a more manageable form when being applied to specific bonds. For many bonds different redemption yields can be calculated for the same bond with the same price on the same date, according to different assumptions about future cash flows, e.g. whether the bond will be called or not.

Example ▶

Consider the following bond issued by the XYZ Manufacturing Company:

- • it pays an 8 % coupon once a year on 1 December;
• any outstanding amount will be redeemed at par in four equal amounts on the
1 December 2003, 2004, 2005 and 2006 unless redeemed earlier. Individual
bonds are drawn by lot;
26

$$ Yields $$

- • it may be called between 1 December 2000 and 1 December 2002 at 102 % on
30 days notice;
• there is a `put' option at 100 % on 1 December 2001.
At any date prior to November 2000, the following types of redemption yield calculations could be considered.

- i)      Yield to maturity
This invariably means final redemption, which in this case is 1 December
2006.
ii)      Yield to average life
The weighted average of the normal redemption dates (i.e. 1 June 2005). See
discussion on average/equivalent life (section 5.3.5)
iii)      Yield to equivalent life
(see section 5.3.5)
iv)      Yield to next call
i.e. 1 December 2000 at 102%
v)      Yield to last call
vi)      Yield to put
The above options give rise to the concept of an `Expected Yield', where it is assumed that the issuer will attempt to minimize his costs and the investor will attempt to maximize his return.

Example ▶

In the U.K. Gilt-edged market some of the issues (e.g. Treasury 8% 2002/2006) may be redeemed at any time between two dates at the government's option. It is conventional to quote yields to the earliest date if the clean price of the stock is above par and to the last date if it is below par.

In the above XYZ Manufacturing Company example, the issuer will frequently call the bond if he can raise money at a lower cost after allowing for his expenses and the early call premium. Conversely the holder will exercise his put option on 1 December 2001, if the market price is below par and he can re-invest his capital at a higher return.

### 5.3.1 Fully paid fixed coupon bond with an assumed single redemption date

For a fully paid fixed coupon bond paying $h$ times per year with an assumed single redemption date, the redemption yield formula (5.3) may be rewritten as:

27



<!-- bnd_page-20.md -->

![Figure](figures/bnd_page-20_figure_000.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

$$P=v^{f1}\cdot \left(k+\sum_{i=1}^{n-1}\frac{g}{h}\cdot  v^{i}\right)+\left(C+\frac{g}{h}\cdot  f2\right)\cdot  v^{n+f1+f2-1}(5.4)$$

where: $\begin{array}{rcl} P &=& \text{gross price (i.e. clean price plus accrued interest)} \\ g &=& \text{annual coupon rate } \% \\ k &=& \text{first/next coupon payment } \% \\ h &=& \text{number of periods in the year.} \\ & & \text{So each normal coupon payment is } g/h \\ n &=& \text{number of coupon payments to assumed redemption,} \\ & & \text{excluding any fractional payment on redemption} \\ f1 &=& \text{fraction of a period from value date to the first/next} \\ & & \text{interest payment. A period is defined as the normal time} \\ & & \text{between two consecutive coupon payments} \\ f2 &=& \text{fraction of a period from the last normal coupon date to} \\ & & \text{the assumed redemption} \\ C &=& \text{redemption value} \\ v &=& \text{discounting factor i.e. } v = 1/(1 + y/h) \\ y &=& \text{required redemption yield compounded } h \text{ times per} \\ & & \text{annum } (y = 0.08 \text{ for a yield of } 8\%) \end{array}$

It should be noted that solving this equation produces an annualized redemption yield for bonds with annual coupon payments, a semi-annualized yield for bonds with semiannual coupon payments etc. It is very easy to convert a yield from one compounding frequency to another (see Appendix II ).

The above formula calculates the same redemption yield for a semi-annual bond as for an annual bond with half the annual coupon rate, and twice the life. However the yield for the former is per six months and for the latter per year.

This formula can be re-written as:

$$P=v^{f1}\cdot \left\{k+\frac{g}{h}\cdot \frac{v\left(1-v^{n-1}\right)}{(1-v)}+\left(C+\frac{g}{h}\cdot  f2\right)\cdot  v^{n+f2-1}\right\}(5.5)$$

It can be restated as:

$$P=v^{f+1}\cdot \left\{\left[(C+G\cdot  f\cdot 2)\cdot  v^{1+f\cdot 2-1}+k+\frac{G}{v}\right]\cdot \left(1\cdot  v^{n-1}\right)\right\}.$$

where: $Y = y/h$ and $G = g/h$

If we define:

$$\begin{array}{rll}
q & = &  'adjusted price'  \\
& = & P / v^{f 1}-k \\
R & = &  'adjusted redemption value'  \\
& = & (C+G \cdot  f 2) \cdot  v^{f 2}
\end{array}$$

and $n$ does not equal 1 this formula can be transformed into:

28

Yields

$$Y=\frac{G}{q}+\frac{(R\cdot  q)}{q\cdot  x}(5.6)$$

$$x=\frac{\left(I-v^{n-1}\right)}{Y\cdot  v^{n-1}}$$

This formula states that the redemption yield is equal to the current yield plus an income stream which, if re-invested at the yield rate, would at maturity amount to the proportionate capital gain or loss. Since the second factor is relatively insensitive to changes in $y$ when $n$ is greater than 2, the equation is in a form which is suitable for rapid solution by iteration. However, when $n=2$ , the equation sometimes converges very slowly or even diverges. In these circumstances a more appropriate rearrangement of equation (5.5) which converges quickly is:

$$Y=\left\{\frac{(G+R) \cdot  v}{P}+\frac{k}{P}\right\}^{1 / f 1}-1(5.7)$$

If $n=1$ the yield equation (5.5) can be re-written:

$$Y=\left\{\frac{R+k}{P}\right\}^{1/f 1}-1(5.8)$$

Yields on bonds in their last coupon period (i.e. where $n=1$ ) are described further in section 5.3.2 .

There are many other ways of solving the redemption yield equation. For example, the Newton-Raphson iterative method could be used, (see Appendix I).

The number of iterations required to solve the yield equation (5.6) , (5.7) or (5.8) is dependent on the accuracy of the initial approximation which is substituted in the right hand side of the equation.

An initial approximation which gives reasonable results is:

$$Y_{o}=\frac{G}{C P}+\left\{\frac{C}{C P}\right\}^{1 / L}-1(5.9)$$

where: $Y_o =$ initial approximation $G =$ normal coupon payment % for the compounding period $C =$ redemption value $CP =$ clean price $L =$ life = $n + f1 + f2$ -1

The above formula can be applied to calculate yields to maturity, call, extension and put, and for bonds with sinking funds, yields to average life.

第35卷 《史记》·卷一百三十五 列传第三十一 高祖五上 章帝本紀五下



<!-- bnd_page-21.md -->

![Figure](figures/bnd_page-21_figure_000.png)

![Figure](figures/bnd_page-21_figure_001.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

Example ›

Consider the above XYZ Manufacturing Company 8% bond where:

- • the interest is paid annually on 1 December;
• the issue will be redeemed at par in four equal instalments on 1 December
2003, 2004, 2005 & 2006;
• the first call opportunity is on 1 December 2000 at 102%;
• the bond holder has a put option at 100% on 1 December 2001.
If, for value date 1 September 1997, it has a price of 92%, the following redemption yields could be calculated:

<table><tr><td>To maturity</td><td>(1 December 2006)</td><td>9.3179%</td></tr><tr><td>To average life</td><td>(1 June 2005)</td><td>9.5000%</td></tr><tr><td>To next call</td><td>(1 December 2000 at 102%)</td><td>11.6033%</td></tr><tr><td>To put</td><td>(1 December 2001)</td><td>10.4018%</td></tr></table>


The redemption yield formula (5.4) above, implies that the yield of a bond varies throughout its life between coupon payments, even if the clean price is always par. This is illustrated in the following graph, which shows the yields for a bond with a 7% annual coupon, with a price throughout its 4-year life of par.

![Figure](figures/bnd_page-21_figure_009.png)

### 5.3.2 Money Market yields (Bonds in their last coupon period)

In some markets bond yields are calculated in the last coupon period on a simple interest, rather than on a compound interest basis.

The normal compound redemption yield formula (5.4) reduces in the last coupon period to:

30

$$ Yields $$

$$\begin{array} { r } { \rho = \left[ \frac { g } { h } + C \right] \cdot  v ^ { f 1 } ( 5 . 1 0 ) } \end{array}$$

where: P = gross price (i.e. clean price plus accrued interest) g = annual coupon rate h = number of coupon payments per year. In this case it has been assumed that a normal coupon g/h is paid at redemption. f1 = fraction of a period from value date to the redemption date. A period is defined as the normal time between two consecutive coupon payments C = redemption value v = discounting factor i.e. $v = 1/(1 + \gamma h)$ y = required redemption yield compounded h times per annum ($y = 0.08$ for a yield of 8%)

The formula (5.10) may be re-written as:

$$P \cdot  \left\{ \begin{array} { l } { \left( 1 + { \frac { y } { h } } \right) ^ { f l } } \\ { { = } { \frac { g } { h } } + C } \end{array} \right. ( 5 . 1 1 )$$

This formula can be expanded to:

$$p \cdot  \left[ 1 + { \frac { f \cdot  1 \cdot  y } { h } } + { \frac { f \cdot  ( f \cdot  1 \cdot  y ) \cdot  y ^ { 2 } } { 2 h ^ { 2 } } } + \cdot s \right] = { \frac { g } { h } } h + C$$

For markets which use simple interest in the last period, formula (5.11) is replaced by:

$$P \cdot  \left( 1 + { \frac { f \cdot  M M Y } { h } } \right) = { \frac { g } { h } } + C$$

In this revised formula $MMY$ is known as the 'money market yield'.

This formula may be re-stated as:

$$P=\frac{\frac{g}{h}+C}{1+MMY\cdot \frac{d}{a}}.$$

$$M M Y=\frac{\left(\frac{g}{h}+C-P\right)}{P} \cdot  \frac{a}{d}(5.12)$$

31



<!-- bnd_page-22.md -->

二零零四年四月十二日(星期六)四时十五分(下午二时零五分)在香港理工大学医学院临床医学和医学工程学院"人类文明的探索与思考"报告。

![Figure](figures/bnd_page-22_figure_002.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

where: $d = \text{number of days according to the relevant calendar until redemption}$ $a = \text{number of days in an relevant calendar year, (This could be 360, 365 or 365/366, however there are other variants)}$

as $f_{1}$

From the formulae above, it can be seen that it is easy to convert from a redemption yield (using compounding) to a money market yield and vice versa.

The relationship is:

$$(1+y/h)^{f1}=(1+MMY\cdot  f1/h)$$

If $fl=1$ then $y=MMY$ , so there is no discontinuity in moving from a compound redemption yield to a simple interest money market yield at the beginning of the last period.

Example ▶

If a security with 6 months to redemption has an annually compounded redemption yield (y) of 8%, then it will have a money market yield (MYY) given by:

$$(1+0.08/I)^{0.5}=(1+MMY\times 0.5)$$

$$\begin{array} { r l } { M M Y } & { = \left( \left[ 0 . 0 8 ^ { 0 . 5 } , - 1 \right] \times 2 \right) } \\ & { = 0 . 0 7 8 4 6 } \\ & { = 7 . 8 4 6 \% } \end{array}$$

This is exactly the same relationship as that between a semi-annually compounded yield of 7.846% and an annually compounded yield of 8%, (see Appendix II).

Money market calculations are discussed further in chapter 9. The money market yield calculation is different to the simple yield to maturity given in equation (5.2), which uses a clean as opposed to a gross price.

Example ›

Consider a bond which pays an annual coupon of 8% on 30 September each year, and is redeemed at par on 30 September 1998. The bond is quoted with a clean price of 99%.

32

$$ Yields $$

A comparison of compound interest and money market simple interest yields, based on a 360 day year, is given below for various dates.

<table><tr><td>Value Date</td><td>Life (Years)</td><td>Gross Price %</td><td>Bond Yield</td><td>Money Market Yield</td></tr><tr><td>30 September 1997</td><td>1.00</td><td>99</td><td>9.091%</td><td>9.091%</td></tr><tr><td>30 December 1997</td><td>0.75</td><td>101</td><td>9.346%</td><td>9.241%</td></tr><tr><td>30 March 1998</td><td>0.50</td><td>103</td><td>9.944%</td><td>9.709%</td></tr><tr><td>30 June 1998</td><td>0.25</td><td>105</td><td>11.928%</td><td>11.429%</td></tr></table>


N.B. the money market yield, based on a 360-day year calendar, is equivalent to an ISMA bond yield that has been compounded with the frequency of its life. Thus, in the above table, for a life to maturity of six months, the annualized bond yield of 9.944% is equivalent to a semi-annual yield of 9.709% (see section 5.3.7), which is the money market yield equivalent.

### 5.3.3    Zero coupon bonds

For zero coupon bonds the redemption yield formula (5.3) reduces to:

$$P=C\cdot  v^{n+f1-1}(5.13)$$

if one treats ii, for the purpose of calculating $fl$ and $n$, as a bond which pays zero coupons once a year on an anniversary of the redemption date. This automatically implies that $f2=0$ and the clean price $CP$ is the same as the gross price $P$.

$n + I \tau - 1$ is just the life $L$ of the bond in years, hence equation (5.13) may be rewritten as:

$$y = \left( \frac { C } { C } \right) ^ { L / L } \cdot  1$$

which is the same as the initial approximation (5.9) for fixed coupon bonds. Hence iterations are not necessary to establish the redemption yields of zero coupon bonds.

Example ▶

The XYZ Manufacturing Company has issued a zero coupon bond which will be redeemed at par on 1 November 2008. On the 28 April 1998 it is trading in the secondary market at a price of 30%, with a value date of 1 May 1998.

The life (L) of the bond from the value date to redemption is 10.5 years hence the redemption yield (y) is given by:

$$y = (100/30)^{1/10.5} - 1 = 0.12150 = 12.150\%$$

33



<!-- bnd_page-23.md -->

![Figure](figures/bnd_page-23_figure_000.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

### 5.3.4  Undated securities

The formula for undedited securities (perpetuals) assumes that the capital will never be repaid and the issuer will never default on coupon payments.

Based on these assumptions the redemption yield formula (5.3) reduces to:

$$\begin{array} { r l } { P = v ^ { f 1 } \cdot  \left\{ k + \frac { g } { h } \cdot  \left( v + v ^ { 2 } + v ^ { 3 } + \cdot s \right) \right\} } & {  } \\ { P = v ^ { f 1 } \cdot  \left\{ k + \frac { g \cdot  v } { h \cdot  ( f - v ) } \right\} } & {  } \\ { P = v ^ { f 1 } \cdot  \left\{ k + \frac { g } { y } \right\} } & {  ( 5 . 1 4 ) } \end{array}$$

where: $P = \text{gross price (i.e. clean price plus accrued interest)}$ $g = \text{annual coupon rate }$ $k = \text{first/next coupon payment }$ $h = \text{number of periods in the year. So each normal coupon payment is } g/n$ $f1 = \text{fraction of a period from value date to the first/next interest payment. A period is defined as the normal time between two consecutive coupon payments}$ $v = \text{discounting factor i.e. } v = f1/(1+y/h)$ $y = \text{required redemption yield compounded } h \text{ times per annum }(y = 0.08 \text{ for a yield of } 8\%)$

The equation (5.14) can be solved as described in the Appendix I or as:

$$y = \frac { g } { \left( \frac { P } { v ^ { f 1 } } - k \right) } ( 5 . 1 5 )$$

which can be solved by iteration with an initial approximation $y_n$ in the right hand side of:

$$y_{o}=\frac{g}{C P}$$

It should be noted that equation (5.14) on a normal coupon date, when there is no accrued interest and $f1=1$, reduces to:

$$y = \frac { g } { P } = \frac { g } { C P }$$

34

$$ Yields $$

Example ›

Consider an undated bond which pays an annual coupon of 7% on 1 December each year. If on 25 May the bond is trading at a price of 90% for a value date of 1 June 1998 then, assuming a standard coupon payment of 7% on 1 December 1998, the redemption yield (y) is given by solving:

$$\left( ) / \rho ^ { d , s } - 7 \right)$$

where: $v=1/(1+y)$

This gives: $y=7.772\%$

### 5.3.5 Bonds with sinking funds (yields to average/equivalent life)

For bonds with sinking funds, the ISMA convention used to be to calculate redemption yields to the average life of the bond. In doing so, the formula assumes that the bond is completely redeemed on one date, which is the average date of the non-discounted capital repayments and that the bond pays a full coupon up to that date. This distorts the actual cash flows of the bond, and hence does not calculate a true redemption yield. However, it does mean that the single date redemption yield formula can be applied.

Example ▶

Consider an 8% bond which pays annual coupons on 1 December each year and is redeemed at par in four equal instalments on 1 December 1999 to 2002. The assumed average life and the true cash flows from 1 December 1994 are as follows:

<table><tr><td>Date</td><td colspan="3">&#x27;Average Life&#x27; Payments</td><td colspan="3">Actual Payments</td></tr><tr><td></td><td>Coupon %</td><td>Capital %</td><td>Total %</td><td>Coupon %</td><td>Capital %</td><td>Total %</td></tr><tr><td>1 December 1994</td><td>8</td><td>-</td><td>8</td><td>8</td><td>-</td><td>8</td></tr><tr><td>Repeated each year until</td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>1 December 1998</td><td>8</td><td>-</td><td>8</td><td>8</td><td>-</td><td>8</td></tr><tr><td>1 December 1999</td><td>8</td><td>-</td><td>8</td><td>8</td><td>25</td><td>33</td></tr><tr><td>1 December 2000</td><td>8</td><td>-</td><td>8</td><td>6</td><td>25</td><td>31</td></tr><tr><td>1 June 2001</td><td>4</td><td>100</td><td>104</td><td>-</td><td>-</td><td>-</td></tr><tr><td>1 December 2001</td><td>-</td><td>-</td><td>-</td><td>4</td><td>25</td><td>29</td></tr><tr><td>1 December 2002</td><td>-</td><td>-</td><td>-</td><td>2</td><td>25</td><td>27</td></tr></table>


35



<!-- bnd_page-24.md -->

## BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

In the above table, the average redemption date is 1 June 2001 as the bond is redeemed in four equal instalments. On this date there is assumed to be a fractional coupon payment of 4%, being six months accrued interest.

N.B. the actual coupon payments decrease after part of the bond has been redeemed.

It can be seen in the above example and generally that the average life and the actual coupon and capital repayments total to the same amount in both cases, although the timings are obviously different.

It is not the convention to calculate redemption yields for bonds with purchase funds, as opposed to sinking funds in this way, since the existence of the purchase fund does not affect the expected cash flows of a long term holder of the bond.

The redemption yield calculation which discounts all the actual coupon and capital payments in the same way is often referred to as the redemption yield to equivalent life. It should be noted that this yield is not the same as that of a similar bullet bond which is redeemed on the equivalent life date (see section 4.5).

The formula for calculating the redemption yield to equivalent life of a bond with a fixed coupon, where all capital repayments are made on a coupon date, can be written as:

$$P=v^{f1}\cdot \left\{R_{l}+R_{2}\cdot  v+R_{3}\cdot  v^{2}+\cdot s+R_{n}\cdot  v^{n-1}\right\}(5.16)$$

where: p = gross price (i.e. clean price plus accrued interest) g = annual coupon rate % k = first/next coupon payment % h = number of periods in the year. So each normal coupon payment is g/h n = number of coupon payments to final redemption f1 = fraction of a period from value date to the first/next coupon payment. A period is defined as the normal time between two consecutive coupon payments Ci = percentage of the issue redeemed with the nth coupon payment R1 = k + C1 Ri = Ci + (1 - F1) · g / h for i = 2 to n F1 = fraction of the issue redeemed prior to the coupon date.

For an issue redeemed at par $F_{i}$ is given by:

$$F _ { i } = \sum _ { j = 1 } ^ { i - 1 } \sum _ { j = 1 } ^ { n } C _ { j }$$

36

$$ Yields $$

$$ v= discounting factor i.e.  v=1 /(1+y / h) $$

$y = \frac{\text{required redemption yield compounded } h \text{ times per annum } (y = 0.08 \text{ for a yield of } 8\%)}$

In practice, it is probably easier to solve the general redemption yield formula (see Appendix I), than this one.

Example ▶

Consider the following 9% U.S. dollar bond which pays annual coupons on 30 September each year and is redeemed in two equal instalments at par on 30 September 1999 and 30 September 2000.

On the 27 March 1998 it is trading at a price of 98 1/8% for a value date of 30 March 1998.

It can be shown that the yield to equivalent life of the bond is 10.024% since as the accrued interest is 4.5%, equation (5.16) becomes:

$$(08.125+4.5)=\frac{1}{1.0002^{0.5}} \times\left(9+\frac{(50+9)}{1.00024}+\frac{(50+4.5)}{1.10024^{2}}\right)$$

On the other hand the yield to average life is 10.070% as the equation to solve is now (5.5) which gives:

$$(98.125+4.5)=\frac{1}{1.10070^{0.5}}\times \left(9+\frac{9}{1.10070}+\frac{(100+4.5)}{1.10070.5}\right).$$

In the above equation the average life redemption date is 30 March 2000.

### 5.3.6 Other bond types

The general redemption yield formula (5.3) can be used for securities that have features that are not described in the previous sections.

For example it can be used for partly paid securities and graduated rate bonds.

The formula for a partly paid security redeemed on a single redemption date may be written as:

$$P + \sum _ { i = 1 } ^ { n } R _ { i } \cdot  v ^ { i } = v ^ { f } \left[ \begin{array} { l } { k + \frac { n } { 2 } \sum _ { i = 1 } ^ { n } R _ { i } } \\ { \frac { n } { 4 } \sum _ { i = 1 } ^ { n } R _ { i } } \end{array} v ^ { t } \right] + \left( C + \frac { g } { h } \int f 2 \right) \cdot  v ^ { n + f + 1 / 2 - 1 } ( 5 . 1 7 )$$

where: P = gross partly paid price (i.e. market price plus accrued interest)

$$R_{i} =future calls for  i=1  to  j$$

1997年



<!-- bnd_page-25.md -->

![Figure](figures/bnd_page-25_figure_000.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

j = number of future calls ct = the time in periods from the value date to the ith call g = annual coupon rate % k = first/next coupon payment % h = number of coupon payments per year. So each normal coupon payment is g/h n = number of coupon payments to final redemption f1 = fraction of a period from value date to the first/next payment. A period is defined as the normal time between two consecutive coupon payments f2 = fraction of a period from the last normal coupon date to the assumed redemption C = redemption value v = discounting factor i.e. $v = 1/(1 + y/h)$ y = required redemption yield compounded h times per annum ($y = 0.08$ for a yield of 5%)

Using similar notation the redemption yield formula for a graduated rate bond which pays a coupon rate of $g_1$ for the first $(m-1)$ payments after the first and a coupon rate of $g_2$ for the remaining $(m-n)$ payments is:

$$P=v^{f 1} \cdot \left\{k+\sum_{i=m}^{m-1} \frac{g_{1}}{h} \cdot  v^{i}+\sum_{i=m}^{n-1} \frac{g_{2}}{h} \cdot  v^{i}\right\}+\left\{C+\frac{g}{h} \cdot  f 2\right\} \cdot  v^{n+f 1 s f 2-1}(5.18)$$

It can be seen that both these formulae are very similar to equation 5.4.

Formulae can be created in a similar way for securities with irregular coupon payments, dual currency bonds based on some assumptions of future exchange rates, and even indexed bonds.

### 5.3.7  Other redemption yields

Some markets use 'redemption yields' that do not agree with the previously discussed formulae.

The most common method uses simple interest for the first broken period and compound interest thereafter.

Variations of this method are those of the U.S. Federal Reserve (not the U.S. 'Street' method) and the German Braess-Fangmeyer and Moosmiller approaches.

The general redemption yield formula (5.3):

$$P=\sum_{i=1}^{n}C F_{i}\cdot  v^{L I}$$

where: P = gross price (= clean price plus accrued interest) n = number of future cash flows

38

$$ Yields $$

CFI $_{t}$ = ith cash flow $L_{it}$ = time in periods to the ith cash flow $\nu$ = discounting factor i.e. if the yield is y then $\nu$ = 1/(1+y/t) (y = 0.08 for a yield of 8%) h = number of periods per year

is effectively replaced by:

$$p = \frac{N}{| \mathcal { I } |} \frac{CF_i - f(y)}{(1 + f)y}.$$

if the ith cash flow $C_{1}t$ has an outstanding life $L_{i}$ which is equal to $n/l+1$, where $l_{i}$ is the fraction of a period from the value date to the first/next interest payment.

In other words instead of discounting each cash flow which is $(n-1)$ periods plus a fractional period $fl$ in the future by:

$$(1+y)^{n+f-1}$$

it is discounted at the rate:

$$(1+f1\cdot  y)\cdot (1+y)^{n-1}$$

39



<!-- bnd_page-26.md -->

## CHAPTER 6

## FLOATING RATE NOTE CALCULATIONS

![Figure](figures/bnd_page-26_figure_002.png)

In order to apply the standard redemption yield calculations to floating rate notes (FRNs), one has to make assumptions about future coupon payments. This is obviously a very difficult thing to do accurately, with the result that a different approach is frequently used.

Most floating rate notes have a known first/next coupon payment, while subsequent coupons will usually be set in terms of a margin over a specified indicator rate (e.g. the London Interbank Offered Rate (LIBOR) for three month U.S. dollars). As a result a current margin relative to the indicator rate is often calculated.

Two types of margin calculations are described below:

Simple Margins and Discounted Margins. Margin calculations enable FRNs to be compared with each other and with money market instruments, but not with fixed rate bonds. In order to facilitate bond comparisons a yield formula is also given in section 6.3 .

### 6.1   Simple margin

The simple margin formula measures the return that can be obtained on the FRR relative to the indicator rate. Its calculation consists of two parts:

- • the quoted margin of the security above or below the indicator rate;
• the average annual capital gain or loss to redemption, after allowing for
differences in the indicator between the last coupon fixing date and the trade
date.
40

FLOATING RATE NOTE CALCULATIONS

The simple margin is given by the formula:

$$S M = \frac { C -  A d j u s t e d P r i c e  } { L } + Q M ( 6 . 1 )$$

where: $\begin{array}{lll} SM &=&  \text{simple margin } \% \\ C &=&  \text{redemption value } \\ L &=&  \text{life of the FRN in years } \\ QM &=&  \text{quoted margin } \%\end{array}$

and where the price is adjusted for differences in the current indicator rate and that set at the last coupon fixing.

There are various ways that the price may be adjusted for interest rate changes, however, a method which does not have any discontinuities is shown in the simple margin calculation below:

$$S M = \frac { C \cdot  \left( P + ( I + Q M ) \cdot  I \cdot  1 - k \right) } { L } + Q M ( 6 . 2 )$$

where: SM = simple margin % C = redemption value P = gross price (i.e. clean price plus accrued interest) I = indicator rate to the next coupon date % QM = quoted margin % f1 = fraction of a year from the value date to the first/next coupon date (actual days divided by 360, 365 or 365/366-days according to the issue) k = first/next coupon payment % L = life in years (actual days/assumed number of days in a year)

In most currencies, including U.S. dollars but not sterling, it is conventional to quote margins on the basis of a 360-day year. Thus in the above formula it is desirable to convert any capital gain or loss onto the same basis. Hence for U.S. dollars the life is based on actual days from value date to redemption divided by 360.

In the Euro-sterling market, the quoted margins usually refer to a rate based on a 365day year or 366-days in a leap year. A year for the life calculations may be taken to be 365.25 days.

It should be noted that sterling floating rate certificates of deposit accrue interest on the basis of actual days divided by 365 even in a leap year.

41



<!-- bnd_page-27.md -->

![Figure](figures/bnd_page-27_figure_000.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

《新唐書》卷147 列传第136 《新唐書》卷150 列传第150

Consider the following U.S. dollar FRN which is redeemed at par on 31 May 2003. It pays interest on 31 May and 30 November each year at 0.25% above the six month LIBOR for U.S. dollars. On the 30 November 1997 the coupon to be paid on 31 May 1998 was set relative to a six month LIBOR rate of 9%. If on the 30 January 1998 the LIBOR rate to 31 May 1998 is 8% and the FRN is being traded at a price of 98%, then the simple margin is calculated as follows:

$$k =(9+0.23) \times \frac{182}{360}=4,676.39  as there are  182  days in the period$$

$$|f_{1}|=\left|\frac{121}{360}=0.33611\right| 121  days from settlement to coupon date$$

$$| L = (365+365+366+365+365+121) / 360=5.40833$$

$$P =98+(9+0.25) \times \frac{67}{360}=99.56736$$

$$\begin{array} { r l r } { S M } & { = } & { \frac { 1 0 0 - ( 9 9 . 5 6 7 3 6 + ( 8 + 0 . 2 5 ) \times 0 . 3 3 6 1 1 - 4 . 6 7 6 3 9 ) + 0 . 2 5 \times 0 . 3 3 6 1 1 } { 5 . 4 0 8 3 3 } } \\ & { = } & { \frac { 1 0 0 - 9 7 . 6 6 3 8 8 } { 5 . 4 0 8 3 3 } + 0 . 2 5 = 0 . 6 8 2 \% } \end{array}$$

### 62图1

The simple margin formula discussed in section 6.1 has two significant drawbacks. It does not allow for the current yield effect on the margin if the price is above or below par, and it assumes that any capital gain or loss occurs evenly over the life of the note, as opposed to being compounded at a constant rate.

The discounted margin formula overcomes these drawbacks, however, in order to make it easier to compute, it is desirable to assume that all coupons after the first one are paid with a constant frequency period.

Floating rate notes (FRNs) in the international and some domestic markets tend to pay interest on different days each year, with the coupon being based on the actual number of days between the coupon dates, which may vary, (see chapters 2 and 11).

The coupons paid after the first/next one, which has already been declared, are all assumed to be the same. Each one being the assumed annual coupon rate, adjusted for the number of days in the year (by convention for FRNs other than Eurostering this is assumed to be 365.25 days) divided by the number of payments per year.

2018年7月1日,中国与欧盟建立全面战略伙伴关系。 2019年6月,欧盟正式加入中国。

Floating OATING Rate ATE Note OTE Calculations ALCULATIONS

The discounted margin for FRNs redeemed on a normal coupon date may be obtained by solving:

$$P \cdot  \left(1+\frac{(I+D M)}{100}-f 1\right)=k+\frac{\beta}{2} \frac{\left(I_{2}+Q M\right)}{h} \cdot  v^{1}+C \cdot  v^{i-1}(6.3)$$

where: $DM = $ required discounted margin % $P = $ gross price (i.e. clean price plus accrued interest) $I = $ current market indicator rate from the value date to the first coupon date % $I2 = $ assumed market indicator rate for subsequent coupon payments % $f1 = $ fraction of a year from the value date to the first/next coupon date (actual days divided by 360, 365 or 365/366 days according to the issue) $k = $ first/next coupon payment % $n = $ number of future coupon payments $QM = $ quoted margin % $h = $ number of coupon payments per year adjusted if not Euro-sterling for the assumed number of days in the year e.g. for a U.S. dollar FRN with two coupon payments per year, $h$ will be $2 \times 360/365.25$ $C = $ redemption value $v = $ discounting factor i.e. $v = 1/(1 + (I2 + DM)/100h) $

In the above formula it can be seen that the left hand side is just the cost of the security adjusted using current indicator rates to the first coupon date.

Similarly each coupon payment after the first is assumed to be $(I2+QM)/h$.

Equation (6.3) can be compared with equation (5.4) for fixed rate bonds. The major difference being that the period to the first coupon date now uses simple interest as opposed to compound interest throughout, as in equation (5.19).

Example ›

Consider the same U.S. dollar FRN as that used in the simple margin calculation example. It pays interest on 31 May and 30 November each year at 14% above the six month LIBOR for U.S. dollars, and will be redeemed at par on 31 May 2003. The coupon to be paid on 31 May 1998 was set relative to a LIBOR rate of 9%. On 30 January 1998 the LIBOR rate to 31 May 1998 is 8%, and the FRN is being traded at a price of 98%. If it is assumed that the LIBOR for six month dollars during the life of the bond is 8% then the discounted margin (DM) is given by solving:

43



<!-- bnd_page-28.md -->

### _

The calculation of current and redemption yields enable floating rate notes (FRNs) to be compared with fixed rate bonds.

The calculation of a current yield is the same as for a fixed rate bond, although any calculations are only valid up to the next coupon payment.

1234

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

$$\begin{array} { r l } { ( 9 8 + 1 . 5 6 7 3 6 ) \times \Bigg ( 1 + \frac { 8 + D M } { 1 0 0 } \cdot  \frac { 1 2 1 } { 3 6 0 } \Bigg ) } & { = 4 . 6 7 6 3 9 } \\ & { + \sum _ { i = 1 } ^ { 1 0 } \left( \frac { ( 8 + 0 . 2 5 ) } { 1 . 9 7 1 2 5 3 } \cdot  v ^ { i } + 1 0 0 \cdot  v ^ { 1 0 } \right) } \end{array}$$

where: $v={\frac {1}{1+{\begin{matrix}\displaystyle \frac {DM}{(197.1253)}\end{matrix}}}}$

This gives $DM=0.789\%$

For undated FRNs (perpetuals) the discounted margin formula (6.3) simplifies to:

$$P \left(1+\frac{I \cdot  D M}{100} \cdot  f\right) \mid)=k+100 \cdot \left(\frac{f 2+Q M}{f 2-D M}\right) .(6.4)$$

$$ Example  \to $$

Consider an undated U.S. dollar FRN on 31 March, which pays coupons every six months on 31 March and 30 September. It pays interest at 1/4% over six month U.S. dollar LIBOR, and is currently trading at 99%. The current LIBOR rate is 9 3/4% p.a. and the first interest payment is:

$$(9.75+0.25)\times 183/360=5.083\%$$

If both l and l2 are taken to be 9.75%, the discounted margin (DM) is given by:

$$9 \times \left( t + { \frac { ( 9 . 7 5 + D M ) } { 1 0 0 } } \times { \frac { 1 8 3 } { 3 6 0 } } \right) = 5 . 0 8 3 + 1 0 0 \times { \frac { ( 9 . 7 5 + 0 . 2 5 ) } { ( 9 . 7 5 + D M ) } }$$

which gives:

$$D M=0.351 \%$$

FLOATING RATE NOTE CALCULATIONS

On the other hand the general redemption yield formula (5.3) can be applied to FRNs as below.

It can be re-written:

$$P = \sum _ { i } k _ { i } \cdot  v ^ { f 1 + i } + C \cdot  v ^ { f 1 + m } ( 6 . 5 )$$

where: $$ $P$ = gross price (i.e. clean price plus accrued interest) $h$ = number of coupon payments per year $n$ = number of coupon payments to assumed redemption $f1$ = fraction of a period from value date to the first/next coupon payment. A period is defined as the normal time between two consecutive coupon payments $C$ = redemption value $k_i$ = assumed ith coupon payment % $t_i$ = time in periods from the next to the ith coupon payment $v$ = discounting factor i.e. $v = 1/(1 + \gamma v h)$ $y$ = required redemption yield compounded $h$ times per annum $(v = 0.08$ for a yield of 8%)

To solve this equation satisfactorily means that future coupon rates have to be predicted. One objective way is to assume that the current rates will not change in the future.

This formula can be simplified if it is assumed that all future coupon dates are equidistant and redemption occurs on a normal coupon date. Equation (6.5) can then be re-written:

$$P = v ^ { f } \cdot  \left\{ v + \sum _ { h } \frac { g } { h } \, v ^ { h } \, , v ^ { i } + C \cdot  v ^ { e i } \right\} ( 6 . 6 )$$

where: known first/next coupon payment % assumed adjusted annual coupon rate, for payments after the known first coupon payment. Rates, which are quoted on the basis of a 360-day year, are multiplied by 565.25/360.

Equation (6.6) now looks very similar to equation (5.4) for fixed rate bonds and can be solved in a similar way.

Example ▶

Consider a U.S. dollar FRN, which pays interest on 15 March, June, September and December each year until redemption on 15 December 2007 at par. It pays interest at

45



<!-- bnd_page-29.md -->

46

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

a 14% over three month LIBOR for U.S. dollars. The current LIBOR rate is 8%, and the next interest payment on 15 March 1998 was set at 2%, based on a LIBOR rate of 7.34%. It is trading for a value date of 15 January 1998 at 98%.

There are 90 days between 15 December 1997 and 15 March 1998, so the accrued interest on 15 January 1998 is:

$$2 \times 31 / 90=0.689 \%$$

Hence:

$$P \ = \ 98 + 0 . 6 8 9$$

$$k = \ 2$$

$$g ~=~(8 + 0.25) \times 365.25/360 = 8.3703$$

$$n=40$$

This gives a redemption yield compounded quarterly of 8.653%, or compounded annually of 8.949%, (see Appendix II).

## CHAPTER 7

## CONVERTIBLE CALCULATIONS

Convertible bonds are securities that give the holder the option to convert into another security at predefined dates and rates. The rates are normally subject to adjustment in the event of certain capital changes which affect the underlying security. The new security is usually an equity share.

In addition to the normal bond calculations, it is possible to calculate conversion ratios, exercise costs, conversion premiums or discounts, income differentials, breakeven periods and value the option itself. There are many methods of valuing options, which are not discussed in this book.

### 7.1.   Conversion premium/discount - ratio

The conversion terms of an issue usually give the holder the right to convert stock into shares between specific dates. With the exception of Swiss convertibles (discussed below) there is normally no cash adjustment at the time of conversion. Fractions on conversion are usually ignored.

When the conversion is exercised any accrued interest on the bond is lost, although the holder is frequently entitled to the next equity dividend payment.

The conversion price is the nominal value of the convertible which may be exchanged for one share. The conversion price is normally quoted in the currency of the equity share. If the convertible bond is in a different currency to the share, a fixed exchange rate for converting from one currency to the other will usually have been agreed at the time of issue.

The conversion ratio is simply the number of shares into which each bond may be converted i.e. assuming they are in the same currency it is the bond denomination divided by the conversion price.

47



<!-- bnd_page-30.md -->

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

The exercise cost of purchasing an equity share via a convertible in the currency of the equity is given by:

$$E C = \frac { P \cdot  P C \cdot  C R } { 1 0 0 \cdot  F R } ( 7 . 1 )$$

where: $$ EC = exercise cost $$ P = gross price of the bond (i.e clean price plus accrued interest) $$ PC = conversion price (in the currency of the share) $$ FR = fixed exchange rate, expressed in units of the underlying equity currency that can be purchased for one unit of the bond denominated currency e.g. if a U.S. dollar convertible bond is convertible into Japanese yen shares at the rate of USD 1 = JPY 125 then the rate will be 125 $CR$ = current exchange rate, expressed as above

If the convertible and the shares are in the same currency FR and CR are both 1.

This exercise cost (EC) can be compared with the cost of buying the equity share directly, to give a premium/discount.

The conversion premium/discount % is given by:

$${\begin{array}{l}}R={\frac {CR}{ER}}\\V=V_{0}\end{array}}$$

$$\begin{array} { r l r } { \theta = ( \rho + \lambda ) } & {  } & { \tau = \frac { \rho \cdot  C _ { T } \cdot  R } { \rho + \lambda } - 1 0 \theta ^ { * } \, . } \end{array}$$

$$ \begin{array} { r l r } {  w h e r e :  P M } & { = } & {  c o n v e r s i o n p r e m i u m / d i s c o u n t  \% } \\ { S P } & { = } & {  s h a r e p r i c e  = \frac { ( \rho + \lambda ) \cdot  ( \rho + \lambda ) } { \rho } \cdot  \frac { \rho } { \rho } \cdot  \frac { R } { \rho } \cdot  1 0 0 \, . } \end{array}$$

In the above the conversion premium/discount calculation uses the gross price as any accrued interest on the bond is lost on conversion, however the market often quotes the premium/discount on clean bond prices.

Example ›

Consider the following bond:

Kinki Sogo Bank 2.875% USD convertible bonds due 31 March 2003 with semiannual payments

<table><tr><td>Bond price</td><td>-</td><td>USD</td><td>124.0%</td></tr><tr><td>Accrued interest for settlement on 8 March 1989</td><td></td><td></td><td></td></tr><tr><td>(158 days accrued interest)</td><td>-</td><td>USD</td><td>1.262%</td></tr><tr><td>Conversion price</td><td>-</td><td>JPY</td><td>1069.1</td></tr><tr><td>Share price</td><td>-</td><td>JPY</td><td>1500.0</td></tr><tr><td>Current exchange rate</td><td>-</td><td>JPY</td><td>146.75 = USD 1</td></tr><tr><td>Fixed exchange rate</td><td>-</td><td>JPY</td><td>130.20 = USD 1</td></tr></table>


48

$$ CONVERTIBLE CALCULATIONS $$

Conversion premium/discount including accrued interest in the convertible bond price.

$$\begin{array} { r l } { = } & {  \left\{ \frac { 1 2 5 . 2 6 2 \times 1 0 9 9 . 1 \times 1 4 6 . 7 5 } { 1 0 0 \times 1 5 0 0 \times 1 3 0 . 2 } - 1 \right\} \times 1 0 0 } \\ { = } & {  0 . 6 2 7 \% } \end{array}$$

Conversion premium/discount excluding accrued interest in the convertible bond price.

$$\begin{array} { r l } { = } & {  \left\{ \left[ \begin{array} { l } { 1 2 4 \times 1 0 6 9 . 1 \times 1 4 6 . 7 5 } \\ { 1 0 0 \times 1 5 0 0 \times 1 3 0 . 2 } \end{array} - 1 \right] \times 1 0 0 } \end{array}$$
$$ - 0 . 3 8 7 \%$$

It is normal for conversion terms to be protected and adjusted if there is a capital change such as a scrip or rights issue in the underlying equity shares.

Swiss convertibles differ from most other convertible issues in that when the bonds are converted there is frequently a cash adjustment, which represents the dilution or increase in the conversion price following a capital change.

Example ▶

Paribas Suisse (Bahamas) Ltd. 6 1/4% 1990 debentures of USD 1225 convert into five bearer shares of Banque Paribas (Suisse) S.A. of CHF 100 each and USD 562.34 of cash.

In order to calculate the premium/discount on such a Swiss convertible the convertible price must first be reduced by the cash payment. Similar partly convertible bonds are not unknown in the domestic bond markets.

### 7.2 Income differential and break-even period

The optimal date to convert a bond into the underlying equity share, subject to the timing of individual coupon and dividend payments, is usually as soon as the income from holding the equity shares is expected to be greater than that of holding the convertible bonds. There may of course be reasons why a holder might not wish to convert under such circumstances e.g. tax considerations or the equity dividend is not expected to be maintained.

If one assumes no change in equity dividends, then the optimal conversion date for a security that does not vary its conversion terms over time, is either the first or last opportunity. In practice this is not the case and people frequently assume annual

49



<!-- bnd_page-31.md -->

![Figure](figures/bnd_page-31_figure_000.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

percentage rises in equity dividends, which give rise to optimal conversion dates in the middle of the conversion period.

A break-even period can be calculated, which measures the number of years one would have to hold the convertible before the additional income received on the convertible compared with the equity, assuming no change in dividend, compensates for the conversion premium paid. It does not allow for the differences in the timings of the cash flows.

The break-even period for a convertible and equity in the same currency is given by the formula:

$$B E=\frac{E C \cdot  S P}{\left(g \cdot  \frac{P C}{100} \cdot  d\right)}(7.3)$$

where: BE = break-even period in years EC = exercise cost of purchasing one share via the convertible SP = share price PC = conversion price g = annual convertible coupon rate % d = gross equity dividend payment

The numerator in equation (7.3) is just the additional cost of purchasing a share via the convertible as opposed to directly, whilst the denominator is the loss of income (income differential) per share.

Example ▶

An XYZ Company 8% sterling issue is convertible into XYZ ordinary shares at a conversion price of GBP 4.00 per share. The ordinary shares currently pay a gross dividend of 20p per annum, and are trading in the market at GBP 3.80. The current price of the convertible is 105%.

The exercise cost (EC) of a share is: $105 \times 4/100 = 4.20$

The income differential per share is: $8\times 4/100-0.20=0.12$

Hence the break-even period is: ${\frac {4.20-3.80}{0.12}}=3.33{\text{ years}}$

In the above example, if one were to forecast that the equity dividend would increase by 2p per year after the current year then the 'break even' period, ignoring any cash flow timings would increase to 5 years. This is because the income differentials in each of the first 5 years would be 12p, 10p, 8p, 6p and 4p respectively, which add up to 40p which is the difference between the exercise cost and the share price.

50

## CHAPTER 8  $$  WARRANTS  $$

A warrant gives the holder the right to purchase an asset at a defined price between specified dates. The same terms usually apply to the entire exercise period, although there is normally protection against changes in the underlying asset. The asset on which there is an option could be a bond, an equity share, an index, a commodity, a currency, or any other financial instrument.

### 8.1    Bond warrants

A bond warrant gives the holder the right to purchase bonds with a face value of EV (exercise value) at a percentage price of EP (exercise price). The bonds issued on exercise of the warrants could be either a further tranche of an existing issue or a new issue.

In other words the exercise cost of purchasing the underlying bond via the warrant is given by:

$$E C=\left\{W P \cdot  C R+\frac{E P \cdot  E V}{100}\right\} \cdot  \frac{100}{E V} .(8.1)$$

where: $$ $EC$ = exercise cost in the currency of the underlying bond $WP$ = warrant price $CR$ = current exchange rate, expressed in units of the bond currency that can be purchased for one unit of the warrant currency. If they are the same currency then $CR=1$ $EP$ = exercise price of the bond (% price basis) $EV$ = face (par) value of the underlying bonds which may be purchased per warrant

In the international bond market, it is normal to express bond warrant prices as the actual cost of the warrant.

51



<!-- bnd_page-32.md -->

2018年

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

When the warrant is exercised the purchaser has to pay in addition to the exercise price the accrued interest at that date.

Example »

London and Scottish Marine Oil PLC - warrant to subscribe for USD 9 1/2% bonds due 1996.

Each warrant will entitle the holder to subscribe for USD 1,000 principal amount of the Company's 9 1/2% bond due 1996 at the exercise price of 100 percent of the principal amount plus accrued interest from the preceding 12 July. The warrants will be exercisable up to and including 12 July 1992.

If the warrants are priced at USD 24, the exercise cost (EC) of purchasing the USD 1000 principal amount of the 9 12% bonds will be:

$$\begin{aligned}
EC& =(24+(100\times1000)/100)\times100/1000\\
& =102.4\%  plus any accrued interest 
\end{aligned}$$

If the warrant gives the holder the right to purchase a bond which already exists a premium/discount of purchasing the bond via the warrant as opposed to directly may be calculated.

The premium/discount is given by:

$$ P M  = { \left[ \begin{array} { l } { E C } \\ { C P } \end{array} \right] } \cdot  { \mathbb { I } } _ { 1 0 0 } ( 8 . 2 )$$

where: PM = warrant premium/discount % EC = exercise cost CP = clean price of the underlying bond

N.B. in this formula the clean price is used as the purchaser has to pay any accrued interest when the warrant is exercised.

Example ▶

If in the above London and Scottish Marine Oil example, the 9 1/2% bonds exist and are trading at 98%, as the exercise cost of the bonds via the warrant is 102.4%, the premium (PM) is:

$$\begin{aligned}
PM&=\left(\frac{102.4}{98}-1\right)\\
&=4.490%
\end{aligned}$$

WARRANTS

### 8.2      Equity warrants

If an equity warrant gives the holder the right to purchase n shares at a price of $EP$ per share, then $EP$ is termed the exercise price and the exercise cost of purchasing a share via the warrant is:

$$E C = \frac { W P \cdot  C R } { n } + E P ( 8 . 3 )$$

where: $$ $EC$ = exercise cost $WP$ = warrant price $CR$ = current exchange rate, expressed in units of the equity currency that can be purchased for one unit of the warrant currency. If they are the same currency then $CR=1$ $EP$ = exercise price $n$ = number of shares that can be purchased per warrant

N.B. in the above the warrant price is the price that has to be paid for the warrant. It is not the market quoted percentage price.

Example ›

The Mitsui & Co. U.S. dollar warrant of February 1989, gives the holder of a USD 5,000 warrant the right to purchase 565 shares in Mitsui & Co. at a current price of JPY 1138 between 20 February 1989 and 22 January 1993.

If such a warrant is priced at USD 20 per cent the cost of one warrant is 20 x 5000/100 = USD 1000.

The exercise cost (EC) of shares in Mitsui via the warrant would then be:

$$EC={\frac {1000\times 150}{565}}+{\frac {1138}{}}$ assuming an exchange rate of USD 1 = JPY 150.
$$=265.5+1138=JPY1403.5\text{ per share}$$

The premium/discount of purchasing an equity via a warrant as opposed to purchasing direct is calculated as below:

$$P M = \left| { \begin{array} { l } { E C } \\ { S P } \end{array} } - 1 \right| \cdot  1 0 0 ( 8 . 4 )$$

where: PM = warrant premium/discount % EC = exercise cost of purchasing a share via the warrant SP = share price

53



<!-- bnd_page-33.md -->

![Figure](figures/bnd_page-33_figure_000.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

Example ›

In the example above, if the equity share price is JPY 1140, then the conversion premium is given by:

$$\begin{array} { r l r } { P M } & {  = } & { \left( \left[ \begin{array} { l } { 1 4 0 3 . 5 } \\ { 1 1 4 4 0 } \end{array} \right] - I \right) \times 1 0 0 = 2 3 . 1 \% } \end{array}$$

A warrant has an intrinsic value when the exercise price is less than the share price.

The intrinsic value is given by:

$$I V=(S P-E P) \cdot  n if  S P>E P(8.5)$$

where: IV = intrinsic value SP = share price EP = exercise price n = number of shares that can be purchased per warrant

For warrants which are expected to be exercised, there is a tendency for the premium or discount to remain stable in the short term, when the share price moves. However, since the warrant price per share is usually considerably less than the share price, the percentage price movement is usually much greater. The effect is known as warrant gearing or leverage and is given by:

$$ W G = \frac { S P \cdot  n } { W P \cdot  C R } ~$$

where: $WG = warrant gearing$ $SP = share price$ $WP = warrant price$ $CR = current exchange rate, expressed in units of the equity currency that can be purchased for one unit of the warrant currency. If they are the same currency then $CR=1$ $n = number of shares that can be purchased per warrant$

Because of the gearing and the volatility of the value of the underlying asset, warrants are priced at more than their intrinsic value.

### 8.3 Commodity/currency warrants

Premiums and discounts on commodity and currency warrants may be calculated in the same way as for equity warrants. An example of a currency warrant is given below:

54

$$ WARRANTS $$

$$ Example  \to $$

On 26 February 1987 Merrill Lynch issued a currency warrant at USD 50 per warrant which entitles the holder to purchase USD 500 at any time between 3 March 1987 and 15 February 1990 at a fixed exchange rate of DEM 1.81$ = USD 1.

55



<!-- bnd_page-34.md -->

## CHAPTER 9三幣制MONEY MARKET INSTRUMENTS

Fixed rate money market instruments are generally traded on a discount or yield basis as opposed to a price. However, floating rate instruments (e.g. medium term floating rate certificates of deposit), are quoted on a price basis until there is only one known coupon payment outstanding.

### 9.1 Discounts

Treasury bills, commercial paper, bankers acceptances etc. are frequently traded on the basis of a discount to par or redemption value. This discount is sometimes referred to as a discount yield and should not be confused with a bond yield.

Discounts are quoted at an annual rate based normally on a 360 or 365-day year in accordance with market convention (e.g. a 365-day year is used for sterling instruments even in a leap year and a 360-day year is used for U.S. dollar ones).

The percentage price paid for a money market instrument quoted at a discount rate $R$ is:

$$P = 1 0 0 \cdot  \left[ 1 - { \frac { R \cdot  f ( 1 ) } { 1 0 0 } } \right] ( 9 . 1 )$$

where: P = percentage price R = discount rate % fl = fraction of a year from settlement to redemption based on actual days divided by the assumed number of days in the year (i.e. 360 or 365)

56

MONEY MARKET INSTRUMENTS

Example ▶

Consider a bill which will be redeemed on 30 June 1998, and is being traded for settlement on 12 February 1998 at a discount rate of 8.0%. If it were a sterling bill, it would be traded at a percentage price (P) given by:

$$\begin{aligned}
P&=100\times\left\{1-\frac{8}{100}\times\frac{138}{365}\right\}\\
&=96.9753\%
\end{aligned}\text{as there are 138 days between}
\text{settlement and redemption.}$$

On the other hand if it were a U.S. dollar bill, it would be traded at a percentage price (P) where:

$$\begin{aligned}
P&=100\times\left\{I-\frac{8}{100}\times\frac{138}{360}\right\}\\
&=96.9333\%,
\end{aligned}$$

Any discount rate can readily be converted into a yield for comparison with other money market instruments. The relationship between them is:

$$MMY=\frac{R}{P}\cdot 100$$

$$ M M Y  = \frac { R } { \left( 1 - R \cdot  f / 1 0 0 \right) } ( 9 . 2 )$$

where: $MMY = money market yield \%$ $R = discount rate \%$ $P = percentage price$ $f1 = fraction of a year from settlement to redemption$

Example ▶

In the above example, the yield on the sterling instrument will be:

$$MMY = 8/0.969753 = 8.250\%$$

and for the U.S. dollar instrument:

$$MMY=8/0.969333=8.253\%$$

Equation (9.2) above may be re-stated as

$$\begin{array} { r l r } { M M Y } & {  = } & { \frac { 1 0 0 - f } { ( P - f ) } . } \end{array}$$

57



<!-- bnd_page-35.md -->

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

$${ \underline { { u } } } = { \frac { 1 0 0 - P } { P } } \cdot  { \frac { a } { d } } ( 9 . 3 )$$

where $d = \frac{\text{number of days according to the relevant calendar until redemption.}}{a = \text{number of days in the calendar year.}}$

This formula is the equivalent of the money market yield formula (5.12) for a security which is redeemed at par.

### 9.2   Yields

Some money market instruments are quoted on a yield as opposed to a discount basis. One important group of such instruments is fixed rate certificates of deposit (CDs). These are issued at par and accrue interest at a specified rate. The calculation of prices from yields differs according to whether there is one or more further coupon payments. It should be noted that these yields are not the same as the bond yields discussed in chapter 5 .

### 9.2.1 Calculations for instruments with one coupon payment

For a certificate of deposit (CD) or other instrument being traded on a yield basis, with one coupon payment on redemption, the percentage price is given by:

$$P = \frac { ( C + k ) } { ( 1 + y \cdot  f ) } , ( 9 . 4 )$$

where: P = percentage price C = percentage redemption value (with CDs normally 100%) k = percentage coupon payment on redemption i.e. $k = g \cdot  f$ where g is the quoted annual interest rate and f is the fraction of a year from either the last coupon date or the issue date to redemption y = quoted yield (y = 0.08 for a yield of 8%) f1 = fraction of a year from settlement to redemption

In the above formula the fractions of a year are the actual number of days between the dates divided by the assumed number of days in a days in a year, which is usually 360 or 365 days, depending on the market convention (e.g. for instruments in U.S. dollars it is 360 days, whereas for sterling instruments it is 365 days even in a leap year).

$$ Example > $$

A U.S. dollar CD was issued on 15 August 1997 for redemption on 15 December 1997 with a 9% coupon.

If for settlement on the 16 October 1997 it was trading at 8.4%, the percentage price (P) paid for the CD would have been:

58

MONEY MARKET INSTRUMENTS

$$P=\frac{(100+9\times122/360)}{(1+0.084\times60/360)}=\frac{103.05}{1.014}=101.627\%$$

On the other hand if it were still trading at 9% the price would have been:

$$P=\frac{(100+9\times122/360)}{(1+0.09\ 60/360)}=\frac{103.05}{1.015}=101.527\%$$

### 9.2.2 Calculation for instruments with more than one coupon

The principle used to calculate the settlement price $P$ of a certificate of deposit (CD) or other money market instrument with more that one future coupon payment, being quoted on a yield basis, is effectively just repeated applications of equation (9.4) for each coupon period in turn allowing for the number of days between each successive coupon date and using simple interest for each period including the first possible part period.

The percentage price of a CD quoted on a yield basis y is given by:

$$P = ( 1 + y \, f ) = \sum _ { n = 1 } ^ { \infty } { \frac { G _ { n } } { E _ { n } } } + { \frac { C } { E _ { n } } } ( 9 . 5 )$$

where: $$ $P = $ percentage price of the CD, including any accrued interest $f1 = $ fraction of a year from the value date to the first/next coupon date i.e. it is the number of days between the two dates divided by the assumed number of days in the year (i.e. 360 or 365) $y = $ quoted yield. This yield will be compounded at the same frequency as the coupon payment. $G_t = $ ith coupon payment. If the CD has a fixed coupon of $g\%$ p.a. then $G_t = g$ times the number of days since the previous coupon or issue date divided by the assumed number of days in a year $E_i = $ aggregate discounting factor for each of the cash flows $E_1 = 1$ $E_i = E_{i-1} \cdot  (1 + y \cdot  f_i)$ for $i = 2$ to $n$ $f_i = $ fraction of a year of the ith coupon period i.e. number of days divided by the assumed number of days in the year $n = $ number of future coupon payments $C = $ percentage redemption value

Example ▶

Consider the following U.S. dollar 9% certificate of deposit which pays interest semiannually on 1 March and 1 September. It will be redeemed on 1 March 1999, 100%,

59



<!-- bnd_page-36.md -->

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

It is being traded for a value date of 1 February 1998 at a yield of 9.25%, having been issued some time ago. What is its price?

The CD has three future coupon payments on 1 March 1998, 1 September 1998 and 1 March 1999. It paid a coupon on 1 September 1997. The three coupon payments are thus $9 × 181/360$, $9 × 184/360$ and $9 × 181/360$ respectively.

Similarly the discounting factors are:

$$E_{i}=1$$

$$E_{2}=(1+0.0925\times 184/360)=1.04728$$

$$E_{3}=1.04728\times(1+0.0925\times181/360)=1.09598$$

Thus the price (P) is given by:

$$\begin{aligned}
P\times(1+0.0925\times28/360)=&\frac{9}{360}\times(\frac{181}{1}+\frac{184}{1.04728}+\frac{181}{1.09598})\\
&+\frac{100}{1.09598}
\end{aligned}$$

$$P=103.543 \%$$

### 9.3 Floating rate certificates of deposit

Floating rate certificates of deposit (FRCDs) are dealt on a clean price as opposed to a discount or yield basis.

In a similar way to bonds the gross price that has to be paid for a FRCD is given by:

$$P=C P+g \cdot  f$$

where: $P$ = gross price $CP$ = clean price $g$ = current coupon rate % $f$ = fraction of a year from the last coupon date or issue date to value date. This is measured as actual days divided by 360 or if sterling 365.

N.B. for sterling FRCDs the accrued interest is calculated, unlike Eurosterling FRNs, on the basis of a 365-day year even in a leap year. In other respects FRCDs are evaluated in the same way as FRNs (see chapter 6).

60

## CHAPTER 10三七MISCELLANEOUS

### 10.1   Bonds in default

International bonds in default are governed by ISMA Rule 187.

Rule 187 Bonds in Default.

Where a debtor fails to pay the interest or principal of a bond on the due date such bond must henceforth be traded at a "flat" price and contracts must be marked accordingly. Bonds which are traded at a "flat" price must have all unpaid or partly paid coupons attached.

Other markets often have similar rules. For such bonds any calculations are purely speculative and depend on one's assumptions.

### 10.2    Tax

Most international securities pay coupons gross, however this is frequently not the case with domestic issues.

It is conventional only to calculate gross yields in Euromarkets, however the formulae can be extended to allow for tax.

There are two main types of tax that may be applied to bond yield calculations, income and capital gains taxes. It is conventional to ignore the timing of any tax payments and assume that they coincide with coupons and capital repayments.

To allow for income tax, if coupon payments are scaled down by the tax rate, the formulae can be applied as normal to produce net yields.

61



<!-- bnd_page-37.md -->

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

Example ▶

A bond with an 8% annual coupon is redeemed in 2003 at 100%. It is currently priced at 90%. Coupons are subject to a 25% tax in the hands of the holder, who does not have any capital gains tax liability.

A net after tax coupon of 5 × (1 / 25 / 100) = 6% is calculated and put in the yield calculations. However if the bond has not been held for the full period, the tax liability on the first coupon payment may be different.

i.e. an 8% bond subject to 25% income tax is treated as if it were a 6% bond which is not subject to income tax, with the same gross price, and possibly a different first coupon payment.

The standard redemption yield formulae can usually be adapted for capital gains taxes as well. As this tax is frequently applied to the difference between a possibly adjusted purchase price and the selling or redemption price of the security, the normal formulae can be used with the redemption (realization) value reduced by the capital gains tax liability.

Example ▶

If an investor holds a bond until redemption at 100% and is subject to capital gains tax at 25% on the difference between the purchase price of 90% and the redemption price, then his return is identical (subject to possible timing considerations) to holding a bond on which he does not have to pay any capital gains tax which is redeemed on the same date at a price of $(100 - (100 - 90) \times 25 / 100) = 97.5%$.

### 10.3    Prices from yields

It is sometimes desirable to trade a bond on a yield as opposed to a price basis, and then calculate the price/value of the transaction. This is in fact the norm in some domestic markets. This situation may occur in the Euromarkets with new issues before the final terms are fixed.

The formulae used to derive prices are the standard redemption yield ones discussed in chapter 5, however they should only be used in certain situations. Some of the considerations and limitations are listed below:

- • the calculation of a price from a yield only applies to fixed rate bonds, including
zero coupon bonds. The suggested method cannot be used for floating rate notes or
money market instruments.
62

MISCELLANEOUS

- • for dated bonds, the redemption dates should be agreed/known at the time of the
trade.
• for undated (perpetual) bonds, yields are based on the assumption that the bond is
never redeemed and the issuer continues to pay coupons at the same rate.
• the quoted yield should unless otherwise agreed at the time of the trade be
according to the ISMA formula and compounded annually.
For a dated bond the method of calculating a price from a yield is first to convert the yield to the compounding frequency of the coupon (see Appendix II), and then substitute this yield in the appropriate redemption yield equation to derive a gross price.

Example ▶

The terms for a fixed rate Eurobond are:

- • 9% coupon payable semi-annually on 15 January and 15 July
redeemable at par on 15 July 2005
It is being traded on a yield to maturity (compounded annually) of 10.25% for settlement on 15 March 1990.

This quoted yield is equivalent to a semi-annualized yield of 10.0%, (see Appendix II).

The substitution in equation (5.5) gives:

$$P=v^{0.66667}\times\left\{4.5+4.5v\times\frac{\left(1-v^{30}\right)}{(1-v)}+100\times v^{30}\right\}$$

as:

$$y =0 . I$$

$$\nu =1 /(1+0.05)=0.9238$$

$$k = 4.5$$

$$g = \ 9$$

$$h =2$$

$$f1=120/180=0.66667$$

$$\begin{matrix} \varphi & = & \theta \end{matrix}$$

$$C =100$$

$$n = 3 I$$

which gives a gross price (including accrued interest):

$$P\ \ \ \ \equiv 93.715 \%$$

63



<!-- bnd_page-38.md -->

![Figure](figures/bnd_page-38_figure_000.png)

## BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

The accrued interest on 15 March is $9 \times 60/360 = 1.5%$ and hence the clean price is 92.215%.

For undated (perpetual) bonds the method of calculating a price from the yield is first to convert the yield to the compounding frequency of the coupon (see Appendix II ) and then substitute the yield in equation (5.15) to derive a gross price.

Example ▶

An undated bond pays a coupon of 10% annually on 15 October. It is being traded on a yield of 8,75% on an annual basis, for settlement on 15 March 1998.

Substituting in equation (5.15) the gross price (P) is given by:

$$P=v^{0.58333}\times(10+10/0.0875)$$

as

$$y=0.0875$$

$$v=1/(1+0.0875)=0.91954$$

$$k = 10$$

$$g = 1 0$$

$$h = I$$

$$f 1 =210 / 360=0.58333$$

which gives a gross price:

$$P=118.351 \%$$

The accrued interest on 15 March is $10 \times 150 / 360 = 4.167\%$ and hence the clean price is 114.184$.

64

## CHAPTER 11  BOND MARKET COMPARISONS

This chapter compares the majority of European domestic bond markets, with the expected conventions for the euro market, the international bond market and the major markets elsewhere. Whilst every effort has been made to establish the validity of the data, due, at least in part, to the constantly changing nature of the markets, errors and omissions may have crept in.

It is expected that the bond markets in those countries that adopt the euro, will normally convert government debt to euro at the first appropriate date and adopt the new conventions. It is unclear how much of the non-government debt will be redenominated into euros. Some debt denominated in legacy currencies may continue to be traded in them, using the existing conventions, throughout their life.

The comparison covers:

- • how different types of instruments are normally quoted;
• how much accrued interest, if any, the buyer will have to pay in addition to
the traded price;
• the cost of the bond if it is quoted on a yield basis;
• the normal settlement period and where they may be settled;
• the rules for adjusting coupon dates if not fixed;
• the rules for whether the buyer or seller gets the coupon;
• the normal way yields are quoted and calculated together with their
compounding frequencies;
• the rates of withholding tax, together with who may reclaim it;
• how the associated money markets accrue interest.
It should be pointed out that although care has been taken to establish the normal trading practices, these are not always followed. In addition, in a few markets, information on some of the less liquid sectors has been omitted.

This comparison covers the next few pages, after which a full guide, covering the terms, abbreviations and footnotes used in the table, is provided.

65



<!-- bnd_page-39.md -->

The aim of this section is to show how the main results of our theorems are obtained by means of several important technical tools.

<table><tr><td></td><td>Government method</td><td>Government period in days</td><td>Accrued basis</td><td>Ex-coupon period</td><td>Occupation and dates</td><td>Year-end methodology</td><td>Wheat compound</td><td>Wheat settled</td><td>Working tax (%)</td><td>Money market funds</td></tr><tr><td>AUSTRALIA</td><td>Y</td><td>3</td><td>ad/365</td><td>7</td><td>norm.2</td><td>RY</td><td>bond</td><td>AUCCE</td><td>10</td><td>ac/365$^{1}$</td></tr><tr><td>Government bonds</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>AUSTRALIA</td><td>CP%</td><td>4$^{2}$</td><td>30E/360</td><td>2$^{3}$</td><td>norm.1</td><td>RY</td><td>1</td><td>C£-OKB</td><td>22$^{4}$</td><td>ac/360</td></tr><tr><td>Fixed interest</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>BILLING FOR OLO strip</td><td>CP%</td><td>3</td><td>30E/360</td><td>none</td><td>-</td><td>RY-MAY$^{1}$</td><td>1</td><td>C£-ENBB</td><td>15$^{5}$</td><td>ac/365</td></tr><tr><td>OLO strip</td><td>Y</td><td>3</td><td>30E/360</td><td>none</td><td>1</td><td>RY-MAY$^{1}$</td><td>1</td><td>C£-ENBB</td><td>15$^{5}$</td><td>ac/365$^{1}$</td></tr><tr><td>Canada</td><td>MAY$^{1}$</td><td>2nd date</td><td>ad/365</td><td>none</td><td>norm.2</td><td>RY-MAY</td><td>2</td><td>CDS-DGS, CE</td><td>none</td><td>ac/365$^{1}$</td></tr><tr><td>Treasury Bills</td><td>CP%</td><td>2 or 3$^{1}$</td><td>ad/365$^{1}$</td><td>none</td><td>norm.1</td><td>RY-MAY</td><td>1</td><td>CDS-DGS, CE</td><td>none</td><td>ac/365$^{1}$</td></tr><tr><td>Government</td><td>CP%</td><td>3</td><td>ad/365$^{1}$</td><td>none</td><td>norm.2</td><td>RY-MAY</td><td>2</td><td>CDS-BBS, CE$^{10}$</td><td>none</td><td>ac/365$^{1}$</td></tr><tr><td>Provincial/Municipal</td><td>CP%</td><td>0 or 3$^{1}$</td><td>ad/365$^{1}$</td><td>none</td><td>norm.2</td><td>RY-MAY</td><td>2</td><td>CDS-BBS, CE$^{10}$</td><td>0/25$^{11}$</td><td>ac/360</td></tr><tr><td>Corporate</td><td>CP%</td><td>31$^{2}$</td><td>30E/360</td><td>30</td><td>norm.1</td><td>RY</td><td>bond</td><td>4$^{3}$</td><td>0/25$^{11}$</td><td>ac/360</td></tr><tr><td>CZECH REPUBLIC</td><td>CP%</td><td>3</td><td>30E/360</td><td>30</td><td>1$^{4}$</td><td>RY$^{15}$</td><td>1</td><td>YP,CE</td><td>none</td><td>ac/360</td></tr><tr><td>All bonds</td><td>CP%</td><td>3</td><td>30E/360</td><td>30</td><td>4</td><td>YP$^{15}$</td><td>1</td><td>YP,CE</td><td>none</td><td>ac/360</td></tr><tr><td>DEMANK</td><td>CP%</td><td>3</td><td>30E/360</td><td>30</td><td>4</td><td>R1/MAY$^{12}$</td><td>1</td><td>YP,CE</td><td>none</td><td>ac/360</td></tr><tr><td>Foreign mortgage bonds</td><td>CP%</td><td>3</td><td>30E/360</td><td>30</td><td>4</td><td>R1/MAY$^{12}$</td><td>1</td><td>YP,CE</td><td>none</td><td>ac/360</td></tr><tr><td>Gross interest FRBs</td><td>P1$^{9}$</td><td>3</td><td>30E/360</td><td>none</td><td>-</td><td>RY-MAY</td><td>1</td><td>C£DOM</td><td>28$^{4}$</td><td>cont.</td></tr><tr><td>Zero coupon T-bills$^{10}$</td><td>Y</td><td>3</td><td>30E/360</td><td>none</td><td>norm.1</td><td>RY-MAY</td><td>1</td><td>C£DOM</td><td>28$^{4}$</td><td>cont.</td></tr><tr><td>FINLAND</td><td>Y</td><td>3</td><td>30E/360</td><td>none</td><td>norm.1</td><td>RY-MAY</td><td>1</td><td>C£DOM</td><td>28$^{4}$</td><td>cont.</td></tr><tr><td>All bonds</td><td>Y</td><td>3</td><td>30E/360</td><td>none</td><td>norm.1</td><td>RY-MAY</td><td>1</td><td>C£DOM</td><td>28$^{4}$</td><td>cont.</td></tr></table>


↑. [2018-07-03]. (原始内容存档于2018-07-03). ↑. [2018-07-03]. (原始内容存档于2018-07-03).

<table><tr><td></td><td>cont.</td><td>France</td><td>MNY</td><td>1 (Int-3)</td><td>as/350</td><td>none</td><td>-</td><td>MNY</td><td>STQ27</td><td>none</td><td>as/360</td></tr><tr><td>BOND MARKETPAIRSONS</td><td>MTAN, MTAN/TCN</td><td>Y</td><td>1 (Int-3)</td><td>as/350</td><td>none</td><td>1</td><td>RY</td><td>CE,SICO,Rail</td><td>none</td><td>none</td><td>as/360</td></tr><tr><td>AMT &amp; fixed-rate bonds</td><td>CP%</td><td>3</td><td>3</td><td>as/350</td><td>none</td><td>1</td><td>RY</td><td>CE,SICO,Rail</td><td>none</td><td>none</td><td>as/360</td></tr><tr><td>Post-determined TRN, incl.TEC</td><td>CP%</td><td>3</td><td>3</td><td>as/350</td><td>none</td><td>none</td><td>1</td><td>CE,SICO</td><td>none</td><td>none</td><td>as/360</td></tr><tr><td>Determined TRN, incl.TEC</td><td>CP%</td><td>3</td><td>3</td><td>as/350</td><td>none</td><td>none</td><td>1</td><td>CE,SICO</td><td>none</td><td>none</td><td>as/360</td></tr><tr><td>Germany</td><td>CP%</td><td>3</td><td>3</td><td>as/350</td><td>none</td><td>1</td><td>RY</td><td>CE,ERC</td><td>none</td><td>none</td><td>as/360</td></tr><tr><td>Fixed-rate bonds</td><td>CP%</td><td>26 (Int-3)</td><td>38(350)</td><td>none</td><td>none</td><td>none</td><td>1</td><td>RY,MNY27</td><td>1</td><td>CE,ERC</td><td>39(372)</td></tr><tr><td>Fixed-rate bonds</td><td>CP%</td><td>26(Int-3)</td><td>as/350</td><td>none</td><td>none</td><td>none</td><td>1</td><td>CE</td><td>CL,EC</td><td>none</td><td>as/360</td></tr><tr><td>CP%</td><td>2</td><td>2</td><td>as/350</td><td>none</td><td>none</td><td>none</td><td>1</td><td>DOM1</td><td>Keller RT</td><td>0/10q4</td><td>as/360</td></tr><tr><td>CP%</td><td>2</td><td>2</td><td>as/350</td><td>147</td><td>147</td><td>none,1 or 2 RY,MNY27</td><td>1</td><td>CE</td><td>0/10q4</td><td>as/360</td><td>as/360</td></tr><tr><td>CP%</td><td>147</td><td>147</td><td>as/350</td><td>147</td><td>2</td><td>RY</td><td>CE,IGSO</td><td>none</td><td>none</td><td>as/360</td><td>as/360</td></tr><tr><td>IGSO</td><td>147</td><td>147</td><td>as/350</td><td>147</td><td>1</td><td>RY</td><td>CE,IGSO</td><td>none</td><td>none</td><td>as/360</td><td>as/360</td></tr><tr><td>Government (left-edge)</td><td>147</td><td>147</td><td>as/350</td><td>147</td><td>1</td><td>RY</td><td>CE,IGSO</td><td>none</td><td>none</td><td>as/360</td><td>as/360</td></tr><tr><td>Government (right-edge)</td><td>147</td><td>147</td><td>as/350</td><td>147</td><td>1</td><td>RY</td><td>CE,IGSO</td><td>none</td><td>none</td><td>as/360</td><td>as/360</td></tr><tr><td>*Fixed-rate - 160-day27</td><td>147</td><td>147</td><td>as/350</td><td>147</td><td>4</td><td>†*</td><td>2</td><td>CE,IGSO</td><td>none</td><td>none</td><td>as/360</td></tr><tr><td>*Fixed-rate - actuar</td><td>147</td><td>147</td><td>as/350</td><td>147</td><td>4</td><td>†*</td><td>2</td><td>CE,IGSO</td><td>none</td><td>none</td><td>as/360</td></tr></table>


66

67



<!-- bnd_page-40.md -->

The aim of this section is to show a way of generalizing some of the results presented in Section 59 . In this section we assume that all multivalued mappings are determined by morphisms. We start with some notations and notions.

<table><tr><td>(cont.)</td><td>Outlook method</td><td>In the 30th year</td><td>Accrued taxes</td><td>Ex-Quarter period</td><td>Occupancy and dates</td><td>Period ending</td><td>Years ended</td><td>Working tax (%)</td><td>Money market funds</td></tr><tr><td>ISRAEL</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>ad/Year</td></tr><tr><td>Government</td><td>P96</td><td>Trade date</td><td>ac/165</td><td>$0</td><td>-</td><td>F4</td><td>1</td><td>TASE</td><td>$42</td></tr><tr><td>%Gol &amp; Gall</td><td>P96</td><td>Trade date</td><td>ac/165</td><td>$0</td><td>-</td><td>F4</td><td>1</td><td>TASE</td><td>$42</td></tr><tr><td>%Qir</td><td>P96</td><td>Trade date</td><td>ac/165</td><td>$0</td><td>-</td><td>F4</td><td>1</td><td>TASE</td><td>$42</td></tr><tr><td>%Gibes</td><td>P96</td><td>Trade date</td><td>ac/165</td><td>$0</td><td>-</td><td>RY</td><td>1</td><td>TASE</td><td>none</td></tr><tr><td>%Gibes</td><td>P96</td><td>Trade date</td><td>ac/165</td><td>$0</td><td>-</td><td>RY</td><td>1</td><td>TASE</td><td>none</td></tr><tr><td>Moham (Treasury bills)</td><td>P96</td><td>Trade date</td><td>ac/165</td><td>$0</td><td>-</td><td>RY</td><td>1</td><td>TASE</td><td>none</td></tr><tr><td>ITALY</td><td>P96</td><td>247</td><td>ac/265</td><td>-</td><td>-</td><td>MMY</td><td>-</td><td>C.E.DOM</td><td>12.51$^{a}$</td></tr><tr><td>BOT.CTZ</td><td>CTP$^{b}$</td><td>5</td><td>30/3250$^{c}$</td><td>none</td><td>norm.2</td><td>RY</td><td>lead</td><td>C.E.DOM</td><td>12.51$^{a}$</td></tr><tr><td>Other funds</td><td>PPM</td><td>2</td><td>ac/3052$^{d}$</td><td>none</td><td>-</td><td>-</td><td>-</td><td>BOJ</td><td>18</td></tr><tr><td>Government bills</td><td>MMV</td><td>3</td><td>ac/365$^{e}$</td><td>-</td><td>-</td><td>MMY$^{f}$</td><td>-</td><td>BOJ</td><td>none</td></tr><tr><td>Government (UGB)</td><td>CPB$^{g}$</td><td>2</td><td>ac/365$^{h}$</td><td>none$^{i}$</td><td>-</td><td>F5$^{j}$</td><td>-</td><td>BOJ</td><td>20$^{j}$</td></tr><tr><td>Other bonds</td><td>CPB$^{j}$</td><td>17$^{j}$</td><td>ac/365$^{k}$</td><td>none$^{l}$</td><td>norm.2</td><td>F5$^{j}$</td><td>-</td><td>BOJ</td><td>20$^{j}$</td></tr><tr><td>LUXEMBOURG</td><td></td><td>3</td><td>30/3260</td><td>none</td><td>-</td><td>RY</td><td>1</td><td>C</td><td>none</td></tr><tr><td>All bonds</td><td>CPB$^{j}$</td><td>3</td><td>30/3260</td><td>none</td><td>-</td><td>RY</td><td>1</td><td>C.E.Necigef</td><td>none</td></tr><tr><td>NETHERLANDS</td><td>CPB$^{j}$</td><td>3</td><td>30/3260</td><td>none</td><td>norm.1</td><td>RY</td><td>1</td><td>AUC</td><td>none</td></tr><tr><td>All bonds</td><td>MMV</td><td>2</td><td>ac/365</td><td>-</td><td>-</td><td>MMY</td><td>-</td><td>AUC</td><td>none</td></tr><tr><td>NEW ENGLAND</td><td>Y</td><td>21$^{j}$</td><td>ac/265</td><td>10</td><td>norm.2</td><td>RY</td><td>lead</td><td>AUCGE</td><td>none</td></tr><tr><td>Government bonds</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td>cont.</td></tr></table>


Government portal ←

<table><tr><td></td><td>CONT.</td><td>CONT.</td><td>CONT.</td><td>CONT.</td><td>&lt;nl&gt;</td></tr></table>


68

69



<!-- bnd_page-41.md -->

The following will be used to model the process as a Markov chain:

<table><tr><td>(cont.)</td><td>Duration method</td><td>Settlement period</td><td>Years$^{15}$</td><td>Around dates</td><td>Ex-occupation period</td><td>Cognition and dates</td><td>Years period</td><td>Willingness tax (%)</td></tr><tr><td>TURKEY</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>Revenue-sharing corn, A$^{17}$</td><td>P1$^{19}$</td><td>Trade date</td><td>ac/065</td><td>none</td><td>norm.1</td><td>-</td><td>1</td><td>TURK</td></tr><tr><td>Revenue-sharing corn, B$^{18}$</td><td>P2$^{19}$</td><td>Trade date</td><td>ac/065</td><td>none</td><td>norm.1</td><td>-</td><td>1</td><td>TURK</td></tr><tr><td>Corporate bonds$^{19}$</td><td>Y$^{19}$</td><td>Trade date</td><td>ac/065</td><td>none</td><td>norm.1</td><td>RY</td><td>1</td><td>ISEC-TURK</td></tr><tr><td>Fair value of assets$^{19}$</td><td>Y$^{19}$</td><td>Trade date</td><td>ac/065</td><td>none</td><td>norm.1</td><td>-</td><td>1</td><td>ISEC</td></tr><tr><td>Asset-backed securities etc.$^{19}$</td><td>MNY$^{19}$</td><td>Trade date</td><td>ac/065</td><td>none</td><td>norm.1</td><td>MNY$^{19}$</td><td>-</td><td>ISEC-TURK</td></tr><tr><td>Primary mortgage loans, P$^{19}$</td><td>MNY$^{19}$</td><td>Trade date</td><td>ac/065</td><td>none</td><td>norm.1</td><td>MNY$^{19}$</td><td>-</td><td>TURK</td></tr><tr><td>Primary mortgage loans, P$^{19}$</td><td>MNY$^{19}$</td><td>Trade date</td><td>ac/065</td><td>none</td><td>norm.1</td><td>MNY$^{19}$</td><td>-</td><td>TURK</td></tr><tr><td>UNITED KINGDOM</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>Government (girls-clad)</td><td>C1%</td><td>1</td><td>ac/065$^{19}$</td><td>p$^{19}$</td><td>norm.2</td><td>RY$^{19}$</td><td>2</td><td>COO, C.E, NSSR</td></tr><tr><td>*Fixed-rate</td><td>C2%</td><td>1</td><td>ac/065$^{19}$</td><td>p$^{19}$</td><td>4, variable$^{19}$</td><td>RY$^{19}$</td><td>2</td><td>COO, C.E</td></tr><tr><td>*Fixed-rate</td><td>C3%</td><td>1</td><td>ac/065$^{19}$</td><td>p$^{19}$</td><td>4, variable$^{19}$</td><td>RY$^{19}$</td><td>2</td><td>COO, C.E</td></tr><tr><td>*Fixed-rate notes</td><td>Y$^{19}$</td><td>1</td><td>ac/065$^{19}$</td><td>none</td><td>RY$^{19}$</td><td>RY$^{19}$</td><td>1 or 2</td><td>COO, C.E, CRESST$^{19}$</td></tr><tr><td>*Strips</td><td>Y$^{19}$</td><td>1, 3 or 5 p$^{19}$</td><td>30/50</td><td>none</td><td>none</td><td>RY$^{19}$</td><td>2</td><td>CRESST</td></tr><tr><td>Bullbog (Pendigits)</td><td>C3%</td><td>5</td><td>ac/065</td><td>p$^{19}$</td><td>norm.1 or 4</td><td>RY</td><td>2</td><td>CRESST</td></tr><tr><td>Corporate bonds</td><td>C3%</td><td>1</td><td>ac/065</td><td>-</td><td>-</td><td>RY</td><td>-</td><td>25</td></tr><tr><td>Common stock</td><td>D$^{19}$</td><td>1</td><td>ac/065</td><td>none</td><td>2</td><td>RY-MNY</td><td>-</td><td>25</td></tr><tr><td>Common stock</td><td>C3%</td><td>1</td><td>30/1560</td><td>none</td><td>2</td><td>RY-MNY</td><td>2</td><td>25</td></tr><tr><td>Treasury notes &amp; bonds</td><td>C3%</td><td>3</td><td>30/1560</td><td>none</td><td>2</td><td>RY-MNY</td><td>2</td><td>25</td></tr><tr><td>Other bonds</td><td>C3%</td><td>3</td><td>30/1560</td><td>none</td><td>2</td><td>RY-MNY</td><td>2</td><td>25</td></tr></table>


BOND MARKET COMPARISONS

<table><tr><td colspan="12">(GOLL)</td></tr><tr><td>EURO DEMINIMATED BONDS$^{1)}$</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>Fixed-rate bonds</td><td>C7%</td><td>3</td><td>as/dec$^{19}$</td><td>-</td><td>8 or 2</td><td>RY</td><td>nom.1 C.E.DOM</td><td>C.E.DOM</td><td></td><td>as/760</td></tr><tr><td>Floating-rate notes</td><td>C7%</td><td>3</td><td>as/3760</td><td>-</td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>INTERNATIONAL BONDS</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>Swaps &amp; Convertables</td><td>C7%</td><td>3</td><td>3/5E/560$^{10}$, as/none</td><td>none</td><td>nom.1</td><td>RY</td><td>1</td><td>C.E.$^{10}$</td><td>none</td><td>4$^{10}$</td></tr><tr><td>Floating-rate notes</td><td>C7%</td><td>3</td><td>as/3760$^{10}$, as/none</td><td>none</td><td>nom.2 or 4, - variable $^{10}$</td><td>-</td><td>C.E.$^{10}$</td><td>C.E.$^{10}$</td><td>none</td><td>+</td></tr></table>


For abbreviations, set accompanying text whether or not they occur, e.g.

70

71



<!-- bnd_page-42.md -->

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

### 11.1  Table Headings

The comparative table, uses the following notation in the specified columns. There is a footnote (marked by {}) where the rules for a specific market sector vary from the norm, or need further qualifications (see section 11.2).

### Quotation method

The majority of bonds are quoted as a percentage price, to which accrued interest is added. However, some bonds, e.g. French convertibles, are quoted domestically as an amount per bond while others, e.g. Swedish bonds, are quoted on a yield basis. The conventions may be different if being traded internationally.

The following notation is used:

<table><tr><td>CP%</td><td>clean percentage price, to which accrued interest is added.</td></tr><tr><td>P%</td><td>gross (dirty) percentage price (i.e. including accrued interest)</td></tr><tr><td>CP</td><td>clean price per bond, to which accrued interest is added (e.g. Portuguese OTs-Treasury bonds are quoted per PTE 10,000 bond).</td></tr><tr><td>P</td><td>actual gross price per bond including any implied accrued interest. (The bond could have a nominal value of, for example, PRF 680).</td></tr><tr><td>Y</td><td>yield.</td></tr><tr><td>MMY</td><td>money market yield.</td></tr><tr><td>R</td><td>discount rate.</td></tr></table>


### Settlement period

In most markets, the normal settlement period is a specified number of business days following the trade date.

Business days obviously differs from market to market. In the Euromarkets, a business day is defined to be a day when the cash market for the currency and Euroclear and Cedel Bank are open. (Euroclear and Cedel Bank only close on 1 January and 25 December).

Other markets settle on either fixed dates, a number of calendar days after the trade date, or the trade date itself. In some markets the normal settlement date is different domestically to internationally.

A number on its own signifies the number of business days after the trade date on which the transaction is normally settled. If the normal international settlement period is different, this is shown in brackets. For example, 4(Intl.-3) means 4 days domestically and 3 days internationally.

72

BOND MARKET COMPARISONS

## Accrual basis

In most markets interest accrues from the issue date or last coupon date (inclusive) to the settlement date (exclusive), however this is not universally true. For example, in Italy both the coupon and settlement dates are counted. The different methods are described in chapter 3.

The following notation is used in the table:

$$ ddd/yyy $$

where ddd is the day count method. Unless it is specified to the contrary, the day count is from the issuer or last coupon date (inclusive) up to but excluding the value date. and yyy is the number of days in the year.

$ddd $ may take the values:

act = actual number of calendar days 30E = 30 day month - European style (see chapter 3) 30U = 30 day month - U.S. style (see chapter 3).

$yyy $ may take the values:

360 = days 365 = 365 days year = 365 days normally but 366 days in a leap year. act = n times the actual number of days in the period, where n is the number of periods in the year.

For securities with one payment per year, the act/year and act/act methods are normally equivalent.

## Ex-coupon period

In some markets (e.g. Denmark, Ireland, Sweden and the U.K.), transactions of securities for settlement just before a coupon date, entitle the seller instead of the buyer, to the coupon, whereas in other markets (e.g. France and the International bond markets) this is not the case.

The rules for when securities start to trade ex the next coupon vary from country to country and sometimes different securities within a country behave differently. In the ex-coupon period accrued interest is normally calculated backwards from the interest payment date to the settlement date.

A number in the column specifies the normal ex-coupon period in calendar days before an interest date.

2019年8月27日 , 中国中央电视台播出的《中国好歌曲》第二季第11期节目 , 节目在开场后 , 节目组邀请了全国知名音乐人一起为观众献唱歌曲。 《中国好歌曲》在开场后 , 节目组邀请了全国知名音乐人一起为观众献唱歌曲。



<!-- bnd_page-43.md -->

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

## Coupon payment frequency and payment dates

In some markets, there is a tradition for bonds to normally have one payment per year (e.g. Belgium and France), whereas in others they normally pay twice a year (e.g. U.K. and U.S.). This in turn has an impact on the normal compounding periodicity for redemption yields.

Coupon payment dates are usually fixed for the life of the bond; however, with most international floating-rate notes the coupon dates vary from year to year according to predefined rules. These rules essentially ensure that a coupon date does not fall on a weekend or a bank holiday.

The rules of how the interest payment dates change are given in a footnote (marked $\dagger$ ). The absence of a footnote implies that the payment dates are fixed.

## Yield calculations

For the majority of fixed rate bonds, redemption yields are calculated according to the ISMA redemption yield formula. However, in some markets for bonds with a life to maturity of less than one year, a money market yield is used.

The main difference between a money market yield and the ISMA redemption yield calculation is that the money market yield uses simple interest, whereas the redemption yield uses compound interest. It can be seen that the two are, in fact, identical for a bond with an annual coupon with exactly one year to redemption, assuming the yield compounding period is one year.

The ISMA redemption yield and the money market yield formulae are described in chapters 5 and 9. In particular, equation (5.3) is the general redemption yield formula, and equations (5.12) and (9.3) the money market yield formulae.

The following notation is used in the table:

<table><tr><td>RY</td><td>-</td><td>ISMA redemption yield throughout the life of the security.</td></tr><tr><td>RY - MMY</td><td>-</td><td>ISMA redemption yield until the last coupon period, when a money market yield is used.</td></tr><tr><td>MMY</td><td>-</td><td>Money market yield.</td></tr></table>


In the majority of European markets, redemption yields are quoted with the interest being compounded annually, whereas in the U.K. and U.S. they are quoted with a semi-annual compounding period. This difference reflects the normal coupon payment frequency in the markets. It is easy to convert a yield with one compounding frequency to another. (See Appendix II).

In some markets, the yields on bonds are compounded with the frequency of the bond's coupon payments. This means that yields cannot always be easily compared

74

BOND MARKET COMPARISONS

between two bonds. The word 'bond' signifies this in the compounding frequency column.

## Where settled

The majority of European bonds tend to be settled on a domestic system. However, increasingly, they can also be settled on one of the International clearing houses, Cedel Bank and Euroclear.

The following abbreviations are used:

<table><tr><td>AUC</td><td>=</td><td>Austraclear</td></tr><tr><td>BOJ</td><td>=</td><td>Bank of Japan</td></tr><tr><td>C</td><td>=</td><td>Cedel Bank</td></tr><tr><td>CDS-BBS</td><td>=</td><td>Canadian Depository for Securities - Book based system</td></tr><tr><td>CDS-DCS</td><td>=</td><td>Canadian Depository for Securities - Debt clearing system</td></tr><tr><td>CGO</td><td>=</td><td>U.K. Central Gift Office</td></tr><tr><td>CREST</td><td>=</td><td>U.K. Crest System</td></tr><tr><td>CVB</td><td>=</td><td>Central de Valores Mobiliarios</td></tr><tr><td>DC</td><td>=</td><td>Deutsche Böræ Clearing (formerly the Deutscher Kassenverein)</td></tr><tr><td>DOM</td><td>=</td><td>Domestic</td></tr><tr><td>E</td><td>=</td><td>Euroclear</td></tr><tr><td>IGSO</td><td>=</td><td>Irish Gilt Settlement Office operated by the Central Bank of Ireland</td></tr><tr><td>ISEC</td><td>=</td><td>Istanbul Stock Exchange Clearing &amp; Settlement Bank</td></tr><tr><td>KDPW</td><td>=</td><td>Polish Domestic Clearing House</td></tr><tr><td>NBB</td><td>=</td><td>National Bank of Belgium</td></tr><tr><td>NSSR</td><td>=</td><td>National Savings Stock Register</td></tr><tr><td>OKB</td><td>=</td><td>Oesterreichische Kontrollbank</td></tr><tr><td>SEGA</td><td>=</td><td>Swiss Securities Clearing Corporation</td></tr><tr><td>SICO</td><td>=</td><td>Sicovam</td></tr><tr><td>SLOVK</td><td>=</td><td>Slovakian Securities Centre</td></tr><tr><td>STN</td><td>=</td><td>Saturne</td></tr><tr><td>TASE</td><td>=</td><td>Israeli domestic clearing house</td></tr><tr><td>TURK</td><td>=</td><td>Central Bank of Turkey</td></tr><tr><td>VN</td><td>=</td><td>Russian Vneschlorbank</td></tr><tr><td>VP</td><td>=</td><td>Danish Securities Centre (Vaerdipapircentralen)</td></tr></table>


## Withholding tax

In some markets bond coupons are distributed after withholding tax has been deducted, whereas in others this is not the case. The standard rate of withholding tax is frequently specified, together with a note on who may reclaim the tax.

75



<!-- bnd_page-44.md -->

BOND MARKETS: STRUCTURES AND Y 173

### Money market interest accrual basis

It is important to consider how bond markets and the associated money markets work together. This is especially true with the development of the repo and swap markets, where the final consideration is dependent on both money market interest and bond coupon accrual rates and conventions.

The money markets often have different rules to the bond markets for accruing interest. In some currencies, even the domestic and international money markets have different conventions (e.g. Canadian dollars and Japanese yen accrue interest with a year of 365 days domestically, but with a year of 360 days in Europe).

The notation used in the table is the same as for the coupon interest accrual.

### Other abbreviations used

<table><tr><td>BOT</td><td>Buoni Ordinair del Tesoro</td></tr><tr><td>BMTN</td><td>Bons à Moyen Terne Negotiables</td></tr><tr><td>BTAN</td><td>Bons du Trésor à Interêt Anneau</td></tr><tr><td>BTF</td><td>Bons du Trésor à Taux Fixe</td></tr><tr><td>CTZ</td><td>Certificat del Tesoro - Zero Coupon</td></tr><tr><td>DIBOR</td><td>Dublin interbank offer rate</td></tr><tr><td>FRN</td><td>Floating-rate note</td></tr><tr><td>JGB</td><td>Japanese Government Bond</td></tr><tr><td>LIBORLondon</td><td>interbank offer rate</td></tr><tr><td>OAT</td><td>Obligations Assimilables du Trésor</td></tr><tr><td>OLE</td><td>Obligation Linéaire - Lineaire obligatie</td></tr><tr><td>OT</td><td>Obligacies du Tessour</td></tr><tr><td>OTC</td><td>Over the counter market</td></tr><tr><td>TCN</td><td>Tires de Créance Negotiables</td></tr><tr><td>TEC</td><td>Taux de l’Echéance Constante</td></tr></table>


### 11.2 Footnotes (♖)

- 1.
Accrues on an actual/365-day basis domestically, but on an actual/360-
day basis on the Euromarkets.

2. AT
The first banking business day of the second week after the trade date.
This rule will be changed in the near future to trade date + 5 business
days (T+5) and, later on, to trade date + 3 business days (T+3).

3. AT
When the coupon date is between the 10th and 24th of the month, then
the ex-coupon date is the first Monday of the same month. When the
coupon date is between the 25th of the ongoing month and the 9th of
the following month, the ex-coupon date is the third Monday of the
ongoing month.
76

BOND MARKET COMPARISONS

<table><tr><td>4.</td><td>AT</td><td>Foreigners not resident in Austria, and companies, are not subject to the withholding tax.</td></tr><tr><td>5.</td><td>BE</td><td>Belgian residents receive payments after a withholding tax of 15%. There is no withholding tax for non-residents and certain exempt organisations such as Credit Institutions.</td></tr><tr><td>6.</td><td>BE</td><td>The accrual basis is actual/365 (the money market convention) when the strip has a life of less than one year.</td></tr><tr><td>7.</td><td>BE</td><td>OLO (Obligation lineaire - lineaire obligatie) strips have a price calculated from an ISMA yield (on a 30€/360-day basis) if their life to maturity is greater than one year. For strips with a life of less than one year, a price based on a money market yield using an actual/365 day year is calculated.</td></tr><tr><td>8.</td><td>CA</td><td>Bonds with a life to maturity of over 3 years settle after 3 days. Shorter bonds settle after 2 days.</td></tr><tr><td>9.</td><td>CA</td><td>The Investment Dealer Association (IDA) rule 800.35 states: Where interest on a transaction involves an amount greater than that represented by the half-yearly coupon, interest is to be calculated on the basis of the full amount of coupon less one or two days, as the case may be.</td></tr></table>


Example ▶

If a bond pays a coupon on 15 May and 15 November, where there are 184 days between 15 May and 15 November.

The number of days accrued on the following dates are:

<table><tr><td>12 November</td><td>181 days</td></tr><tr><td>13 November</td><td>182 days - unchanged</td></tr><tr><td>14 November</td><td>183 days - adjusted to 182½-1 = 181½ days</td></tr><tr><td>15 November</td><td>0 days - coupon date</td></tr></table>


<table><tr><td>10.</td><td>CA</td><td>It is planned that eventually all Canadian securities will be cleared domestically through the DCS system</td></tr><tr><td>11.</td><td>CA</td><td>Certain long term debt has 0% withholding tax. Others have 25%.</td></tr><tr><td>12.</td><td>CZ</td><td>There is no normal period in the OTC market.</td></tr></table>


77



<!-- bnd_page-45.md -->

![Figure](figures/bnd_page-45_figure_000.png)

![Figure](figures/bnd_page-45_figure_001.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

13. CZ Bonds can be settled on the Prague Stock Exchange, the Securities Central Registry and the RM-System. Treasury bills settle in the TKD System, which is run by the Czech National Bank.

14. CZ Government bonds are tax-free. Bonds issued by banks, municipalities and companies are subject to taxation at 25%. This may be reclaimed by foreign residents of countries which have double taxation agreements with the Czech Republic.

15. DK Usually 1 for Government bonds and Treasury notes, and 2 or 4 for Mortgage Bonds.

16. DK On mortgage bonds, which are issued over a period of time, the exact cash flows used in the yield calculations are calculated and published by the issuer. During the issuing period, a synthetic profile is projected on the anticipated final amount of the issue.

For index-linked bonds, the calculations disregard the inflation index element resulting in real-interest yields.

17. DK The coupon rate is computed from the average yield $r$ on government fixed-rate notes and bonds with a remaining life of more than three months, and less than three years. The average yield is calculated from a period running from 6 months and 10 days before the coupon-date to 3 months and 10 days before the coupon-date. Since all fixed-rate government issues pay coupons annually, the coupon rate $C$ on FRN's is :

$$C = \left\{ ( 1 + r ) ^ { 0 . 2 5 } \cdot  1 \right\} \cdot  1 0 0$$

18. DK Skatkammerbeviser

They are usually issued with a life of 3, 6 or 9 months.

19. DK The actual price is for an amount of DKK 1,000,000.

20. DK Yields are calculated according to both money market and bond market conventions.

The official conversion from price to yield, and vice versa, takes place according to money market practice. Using this convention, the yield is given by:

$$Money market yield = \frac{1,000,000 \cdot  Price}{Price}, 360$$

where $d$ = actual number of calendar days remaining.

78

BOND MARKET COMPARISONS

For the same security a bond yield may also be calculated.

It is given by:

$$B o n d y i e l d = \left[ 1 + \frac { 1 , 0 0 0 , 0 0 0 \cdot   P r i c e  } {  P r i c e  } \right] ^ { 3 6 0 / d b } - 1$$

where $db=$ number of bond days (on a 360E basis) to maturity.

21. FI Only for domestic private investors.

22. FR BTFs and BTANs will be settled on RGV/Relit from mid 1997.

23. FR Internationally, French Convertible issues are sometimes traded on a percentage price basis.

24. FR A few convertible issues are quoted on the 'monthly settlement' market as equities.

25. FR It is possible to settle these through Euroclear and Cedel Bank.

26. DE Although the ISMA method of calculating yields is most commonly used, it should be noted that some domestic institutional investors and savings banks prefer the Brass/Fangmeyer or Moosmann methods. Both these methods discount the interest in any fractional period on a simple interest, rather than a compound interest, basis. For bonds with annual coupon payments, the two methods are equivalent.

27. DE Foreign investors are not subject to withholding tax. Some residents (e.g. foundations) may reclaim all, or part, of the withholding tax.

28. The interest payment dates on floating-rate notes are not fixed dates, but are usually determined as described in chapter 2.

Interest dates for Euro-French Franc floating-rate notes are usually the third Wednesday of the third month of each quarter. (MATF settlement date).

29. GR Includes foreign currency indexed bonds. There are currently no fixed rate drachma bonds, although some are expected in the not too distant future.

30. GR In the domestic market, securities may be in physical or book-entry form. Book-entry securities are settled through the Bank of Greece. It is planned for all domestic securities to be only in book-entry form and for settlement to be also possible through Cedel Bank and Euroclear.

31. Actual days ignoring leap days (29 February) divided by 365, i.e. there are 2 days between 27 February and 1 March, even in a leap year.

79



<!-- bnd_page-46.md -->

![Figure](figures/bnd_page-46_figure_000.png)

↑. 中华人民共和国国家统计局 . 2023-06-30 (中文(中国大陆)). ↑. 中华人民共和国国家统计局 . 2023-06-30 (中文(中国大陆)).

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

32. HU     Applies to OTC trades.

33. HU     The money market yield applies whenever the maturity is within 365 days.

34. HU The 10% withholding tax only applies to private individuals when they do not buy through a broker/dealer firm.

35. IE Irish government (gilt-edged) fixed-rate stocks issued before 14 June 1993 accrue interest on a 365-day year and have two coupons per year. Stocks issued between June 1993 and August 1997 accrue interest on a 360-day year with one coupon per year, and from September 1997 on an actual/actual day basis.

36. IE Traditionally, settlement was for 'cash' i.e. next business day. It is now common to have settlement from anywhere between one and five business days.

37. IE Stocks normally trade ex-coupon from the nearest Wednesday which is three weeks before each coupon date. The actual schedule is issued annually by the Central Bank of Ireland. (For 1996, it was issued in July 95).

38. IE The coupon rate for each stock is declared by the authorities two days before the start of the coupon period to which the rate will apply: i.e. two days before the coupon date for the previous period. The coupon rate is based on the average DIBOR over the preceding 10 business days, plus or minus a margin associated with the particular stock. The margin currently ranges from -0.04 to +0.04 for different stocks. This rate is then divided by four to give the quarterly coupon rate.

39. IE The redemption yield is sometimes calculated with the assumption that the coupon rate remains fixed for the rest of the bond's life. It is more usual to treat these bonds as 3-month money market instruments and to calculate a simple interest rate.

40.  IL     Usually 2 weeks.

41. IL The Sagi and Galli are CPI (consumer price index) linked bonds with a fixed coupon of 4%. The Sagi is issued with a maturity of 6 years and the Galli with 15 years.

The price is given by:

$$P = \left[ \begin{array} { l } { \sum _ { i = 1 } ^ { n } g _ { i } f _ { i } t ^ { i + 1 } + C \cdot  y f _ { t + 1 } } \\ { M } \end{array} \right] \frac { 1 } { M 0 } .$$

80

BOND MARKET COMPARISONS

where $P$ = bond price $g$ = annual coupon rate % $n$ = number of coupon payments to redemption $f1$ = fraction of a period from value date to the first/next interest payment $C$ = redemption value (= 100) $M0$ = base CPI $M1$ = known CPI $v$ = discounting factor i.e. $v = 1/(1+y)$ $y$ = redemption yield. $(y = 0.08$ for a yield of 8%).

42. IL Tax rates vary according to the status of the investors. Israeli investors pay a maximum tax of 35% on coupon payments. (This applies to private individuals, companies and mutual funds). On the other hand, non-profit organisations - including pension funds and provident funds - are exempt from tax for the holding period.

Foreign investors usually pay 25% tax, but this depends on the double taxation treaty agreement.

43. IL The $Kfir$ is a CPI-linked bond which is issued with a maturity of 7 years. The interest is variable and determined semi-annually according to the average yield-to-maturity on CPI-linked government bonds with a maturity of 3-5 years.

The price P is given by:

$$P = v ^ { f 1 } \cdot  \left[ k ^ { * } + \sum _ { i = 2 } ^ { n } g ^ { * , i } v ^ { 0 . 5 ( i - 1 ) } + 1 0 0 \cdot  v ^ { 0 . 5 ( n - 1 ) } \right] \cdot  \frac { M 1 } { M 0 }$$

where: $P = $ bond price $k* = $ next known semi-annual coupon $k* = \left((1 + k/100)^{0.5} - 1\right) \cdot  100$ $k = $ next known annual coupon $g* = $ the forecast semi-annual coupon $g* = \left((1 + g/100)^{0.5} - 1\right) \cdot  100$ $g = $ variable interest rate as published by the Bank of Israel $M0 = $ base CPI $M1 = $ known CPI $n = $ number of coupon payments to redemption $f1 = $ fraction of a year from the value date to the first/next interest payment $v = $ discounting factor i.e. $v = 1/(1+y)$ $y = $ redemption yield. $(y = 0.08$ for a yield of 8%).

81



<!-- bnd_page-47.md -->

![Figure](figures/bnd_page-47_figure_000.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

44. IL The Gilboa is a government bond linked to the U.S. dollar with a maturity of five years. The coupon rate is set to (LIBOR - 0.25%).

The price P is given by:

$$P = v f \left( 1 + \left\{ \frac { k } { 2 \pi } \sum _ { j = 2 } ^ { n } \frac { v ^ { 0 . 5 ( j - 1 ) } } { 2 } \right. \right) + 1 0 0 \cdot  v ^ { 0 . 5 ( j - 1 ) } , M \geq 1 0 0 .$$

where: $P$ = bond price $k$ = known next semi-annual coupon payment $g$ = expected subsequent coupon payments, based on the current value of LIBOR $M0$ = base U.S. dollar rate $M1$ = known U.S. dollar rate, adjusted for forecast monthly devaluation rate $n$ = number of coupon payments to redemption $f1$ = fraction of a year from the value date to the first/next interest payment $v$ = discounting factor i.e. $v = 1/(1+y)$ $y$ = redemption yield. $(y = 0.08$ for a yield of 8%).

45. IL The Gilon is an unlinked variable-rate bond, with the interest being based on the weighted average yield of Makam (Treasury bills) with maturities of between 3-12 months, plus a fixed premium.

The price P is given by:

$$p = v f ^ { 1 } \cdot  \left( k ^ { * } + \sum _ { i = 2 } ^ { n } g ^ { * , y , 0 . 5 ( i - 1 ) } + 1 0 0 \cdot  y ^ { 0 . 5 ( n - 1 ) } \right)$$

where $P = $ bond price $k^{*} = $ next known semi-annual coupon $k^{*} = [(1+k/100)^{0.5}-1] \cdot  100$ $k = $ next known annual coupon $g^{*} = $ assumed subsequent semi-annual coupon This is based on the variable Makam interest rate as published by the Bank of Israel and the fixed premium. $n = $ number of coupon payments to redemption $f1 = $ fraction of a year from the value date to the first/next interest payment $\nu = $ discounting factor i.e. $\nu = 1/(1+y)$ $y = $ redemption yield. $(y = 0.08$ for a yield of 8%).

46. IL A bond redemption yield is used, not a money market yield, based on a 365-day year.

47. IT CTZ's settle on trade date plus 3 business days.

82

BOND MARK COMPARISONS

48. IT The withholding tax is based on the difference between the issue price and par. BOT's and CTZ's issued after January 1997 will not be subject to withholding tax, nor will existing CTZ's maturing in 1998 or later.

49. IT Bonds are currently traded with the net accrued interest added to the price. This will change after the bond's first coupon payment in 1997 to the gross accrued interest being added.

50. IT The number of days accrued includes both the last coupon date and the settlement date, i.e. it is one more day than the norm.

51. IT Currently coupons on newly issued securities are subject to a withholding tax of 12.5%. However, for older issues, this rate could be 0%, 6.25% or 10.0%.

There is no withholding tax on Italian domestic securities for nonresidents in countries with double taxation agreements, and residents subject to corporation tax.

The withholding tax is based on the coupons paid and the difference between the issue price and the redemption price.

52. JP The Japanese Ministry of Finance announces a yield that is based on a number of days which counts both the issue date and the maturity date.

53. JP Prior to the first coupon payment date, the issue date and the settlement date are included in the number of days accrued.

54. JP Japanese bonds have periods when they cannot be traded. For JGBs, the last trading day is eight business days ahead of the coupon payment day, and for non-JGBs the 'lock up' period is three weeks.

55. JP     Frequently quote a simple yield to maturity - see chapter 5.

56. JP For non-exempt Japanese domestic corporations and individuals.

57. JP Usually settled on the 10th, 20th and last day of each month. If this is not a business day, the following business day is used. It is proposed to change this to T+7 in December 1997.

58.   NZ   Internationally 7 calendar days.

59. NO Money markets accrue interest on a variety of methods. (i.e. 30E/360, actual/360, actual/365 and actual/actual).

83



<!-- bnd_page-48.md -->

![Figure](figures/bnd_page-48_figure_000.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

60. NO Some floating rate notes have four coupons a year. These often have coupon dates that vary in the same way as international floating rate notes.

61. PL In the secondary block market, settlement is after two days. In the public market, it is after three days. In the primary market two-year notes are settled on the 5th day of the next month after the auction. Five-year notes are settled on the 12th day of the next month after the auction.

Fixed-rate notes are not traded internationally.

62. PT Treasury bonds - OTs (Obrigações do Tesouro) are priced domestically as a price per bond, to which accrued interest has to be added.

63. PT Treasury bonds (TOs) cannot be traded for four business days before the coupon payment dates.

64. PT Yields are compounded with the fractional period being calculated as actual days/365, although bonds accrue interest on a 30E/360-day basis.

65. PT Most bonds are subject to 20% withholding tax, although some OT's have coupons paid gross. Corporate euro-escudo bonds have a withholding tax of 25% if there is no paying agent in Portugal. The withholding tax may be reclaimed by non-residents, if there is a suitable double taxation agreement, and some tax free domestic institutions.

66. RU Not tradable in the 30 days before a coupon date.

67.   SK   Calculated to the trade date, not the settlement date.

68. ES Government bonds do not accrue interest until the first normal coupon date with the result that the first coupon payment is a full one. The period before the first normal coupon payment, during which the bond is effectively priced gross ( $P_{Gross}$ ) can be several months.

69. ES A reduction to 3 business days is being considered.

70. ES The yields are compounded with fractional periods being calculated as actual days/365, although bonds accrue interest on an actual/actual basis.

71. ES Government bonds and Public Debt (Deuda Publica Española) can be only settled on Euroclear and Cedel. Private debt and Matadors (Peseta Foreign Bonds) can settle on Expacare as well.

84

BOND MARKET COMPARISONS

72. ES Foreign investors, who are not in tax havens, may reclaim the withholding tax.

73. CH For money market instruments in securities form (European Commercial Paper-ECP) the rules of the Euromarket apply, i.e. interest accrues on an actual/360 day basis.

74. CH The accrued interest is calculated from the last coupon date before the trade date (not before the settlement date).

Example ›

For a bond with:

<table><tr><td>• annual coupon date</td><td>30 August</td></tr><tr><td>• trade date</td><td>28 August 1995</td></tr><tr><td>• settlement date</td><td>4 September 1995</td></tr></table>


the number of days accrued interest is 364 (which means that the amount of accrued is larger than the coupon amount). On the other hand, the bond is delivered with the coupon due 30 August 1995.

75. CH For non-Swiss issuers, there is no withholding tax. For domestic issuers, there is a withholding tax of 35%. Depending on the domicile of the holder any withholding tax may be partially, or completely, reclaimed.

76. TR Indexed to foreign exchange or wholesale prices.

77. TR These securities are issued by the Privatisation Administration, a governmental body which conducts privatisation operations. They are hardly marketable. Banks buy them for their reserve requirements at the Central Bank of Turkey and construction companies hold them against public debt.

78. TR These instruments are not traded in the secondary market. Hence there is no accepted pricing method.

79. TR Indexed to foreign currency.

80. TR The price P is given by:

$$P = \frac{(1 + \text{ERP}) \cdot  R}{1 + (\text{LIBOR} + S) \cdot  \text{DTM}/36500}$$

85



<!-- bnd_page-49.md -->

![Figure](figures/bnd_page-49_figure_000.png)

![Figure](figures/bnd_page-49_figure_001.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

where: R = Central Bank of Turkey foreign currency buying rate S = spread over LIBOR DTM = days to maturity or next coupon date ERP = expected next revenue payment

81. TR Corporate bonds are issued mainly by family-owned enterprises. The secondary market is provided by banks or brokerage houses which underwrite the issue. This has a negative effect on the pricing.

82. TR 11% for publicly open companies. Otherwise, 22%.

83. TR No standard method exists, as not actively traded.

84. TR      Domestically, trade date. Internationally, trade date plus two business days.

85. TR Asset backed securities, commercial paper, and bank bills.

86. TR FRNs are priced as if they were redeemed on the first coupon date.

87. TR A money market yield is used in the organised bond market on the Istanbul Stock Exchange. On the other hand, the Central Bank of Turkey uses the following convention for the reserve requirement calculations.

$$ Price = Nominal (100,000)+ Coupon  \cdot  f 1$$

where: $f1 = \frac{\text{the fraction of a period from the last coupon date to the value date.}}$

88. TR The price P is given by:

$$P = \frac{1}{1 + (LIBOR + 1) \cdot  d / 36500} \cdot  R$$

where:      R =      Central Bank of Turkey foreign currency buying rate S =      margin over LIBOR d =      number of days to maturity

89. GB The accrual basis will change to actual/actual days in the period during 1998.

90. GB The ex-coupon period is 7 business days with the exception of War Loan where it is 10 days.

86

BOND MARKET COMPARISONS

91. GB From 6 April 1998, all gilt interest will be payable without deduction of withholding tax.

92. GB A 'real' rate of return after assuming an inflation rate is calculated - see Appendix III.

93. GB The Treasury Floating Rate 2001, which can only be settled in the CGO does not go ex-coupon.

94. GB The normal settlement period for a bulldog bond is dependent on where the bonds are held and in what form (i.e. registered or bearer).

- • If the bonds are held on the Central Gilts Office (CGO) register,
then the normal settlement period is 1 day.
• If they are held in registered form, settlement is through Crest
after five days.
• If, on the other hand, they are held in bearer form, then they will
normally be settled at Cedel Bank or Euroclear after three days.
95. GB This market still retains many anomalies and exceptions to the following rules.

96. GB Convertible bonds are sometimes traded on a gross (dirty) price basis P%.

97. GB Some, but not all corporate bonds are traded ex-coupon. The period during which they are traded ex-coupon varies from bond to bond.

98. EU Anticipated rules.

99. EU Some debt issued originally in European Currency Units (XEU), which will be automatically converted to euro (EUR), may continue to trade using the existing conventions.

100. In the international markets, interest is normally calculated on an actual/360-day basis. However some currencies calculate interest on an actual/365-day basis and some even have two standards. Japanese Yen (JPY) and Canadian Dollars (CAD) are examples of currencies with two standards. e.g. Japanese yen lent in Japan would calculate on an actual/365-day basis, but Japanese yen lent in Europe (euroyen) would calculate on an actual/360-day basis.

Currencies which accrue on an actual 365-day basis include Belgian francs, domestic Canadian dollars, Irish pounds, Italian lire, domestic Japanese yen, sterling and domestic U.S. dollars.

↑. [2018-07-03]. (原始内容存档于2018-07-03). ↑. [2018-07-03]. (原始内容存档于2018-07-03). ↑. [2018-07-03]. (原始内容存档于2018-07-03).



<!-- bnd_page-50.md -->

88

## BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

101. The market practice is for Canadian dollar global bonds to behave normally as domestic Canadian dollar bonds, unless the prospectus says otherwise, i.e. they accrue interest on an actual/365-day basis.

102. It is proposed that all new international bonds issued after 1 January 1999 will accrue interest on an actual/actual basis, regardless of whether the European single currency is introduced on that date.

103. It is also possible to settle euro French franc bonds on Sicovam.

104. Eurosterling and Irish pound bonds accrue interest on an actual/365day basis as opposed to actual/360.

## APPENDIX I  GENERAL REDEMPTION YIELD FORMULA

The redemption yield $y$ of a security, compounded annually, is given by solving an equation of the form:

$$P=\sum_{i=1}^{n}C F_{i}\cdot  v^{L i}$$

where: $$ $P$ = gross price (i.e. clean price plus accrued interest) $n$ = number of future cash flows, where n may be infinite $CF_i$ = ith cash flow $L_i$ = time in years to the ith cash flow, taking into account the market conventions for calculating the fraction of a year, (e.g. does the year have 360 or 365-days). $\nu$ = discounting factor i.e. $\nu = 1/1 + y$ $y$ = required redemption yield compounded annually (y = 0.08 for a yield of 8%).

This general redemption yield formula, which assumes that all cash flows irrespective of their timing are discounted at the same rate, works for all securities. In the case of partly paid issues, future price calls are regarded as negative cash flows. Similarly for unbonded bonds it is infinite, as it is assumed that the issuer never defaults.

In chapter 4 we stated that the modified duration $MD$ of a bond was given by:

$$M D = - \, { \frac { d P } { d y } } P$$

where: P = gross price (i.e. clean price plus accrued interest) dp = small change in price dy = corresponding small change in yield

89



<!-- bnd_page-51.md -->

![Figure](figures/bnd_page-51_figure_000.png)

![Figure](figures/bnd_page-51_figure_001.png)

BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

From the redemption yield formula above we have:

$$\frac{dP}{dy}=\frac{dP}{dv}\cdot \frac{dv}{dy}=\left(\sum_{i=1}^{n}CF_{i}\cdot  L_{i}\cdot  v^{Li-1}\right)\cdot \left\{\frac{-1}{(1+y)^{2}}\right\}$$

$$ Hence: $$

$$M D = \frac { 1 } { P } \sum _ { i } C F _ { i } \cdot  L _ { i } \cdot  U ^ { i + 1 }$$

On the other hand, the duration $D$ (equation 4.4) is just:

$$D = \frac{1}{P} \sum _ { i } C F _ { i } \cdot  l _ { i } \cdot  v ^ { L _ { i } }$$

thus:

$$MD=D\cdot  v$$

which is equation (4.8).

Similarly convexity $CX$ is defined in chapter 4 to be:

$${ \begin{array} { r l } { C X } & { = \frac { 1 } { P } \cdot  { \frac { d ^ { 2 } P } { d y ^ { 2 } } } = \frac { 1 } { P } \cdot  { \frac { d } { d y } } \left( { \frac { d P } { d y } } \right) } \\ & { = \frac { 1 } { P } \cdot  \sum _ { i } C F _ { i } \cdot  L _ { i } \cdot  \left( L _ { i } + 1 \right) \cdot  v ^ { L i + 2 } } \end{array}}$$

The redemption yield formula can be solved in a general way using the NewtonRaphson method.

$$Let f ( v ) = P - \sum _ { i } C F _ { i } , \mu  _ { L }$$

then the first derivative $df/dv = f^1(v)$ is given by;

$$f ^ { \prime } ( v ) = - \sum _ { i = 1 } ^ { M } L _ { i } \cdot  C _ { i } , \, v ^ { I } .$$

We want to establish a value of $\nu$ which is a root of $f(\nu)$, (i.e., $f(\nu)=0$). This value then defines the required redemption yield $y$.

90

APPENDIX I - THE GENERAL REDEMPTION YIELD FORMULA

The method uses an iterative process for solving the equation. The process is started by estimating a discounting value $v_0$ . A better estimate $v_1$ is then given by:

$$v _ { 1 } = v _ { 0 } \cdot  f ( v _ { 0 } ) g ^ { - 1 } ( v _ { 0 } )$$

This process is then repeated as often as necessary, i.e.

$$v _ { i + 1 } = v _ { i } \cdot  f ( v _ { i } ) f ^ { - 1 } ( v _ { i } )$$

until the change in v from one iteration to the next is within the required accuracy. Assuming that i=m when this is achieved, the required redemption yield y compounded annually is given by:

$$v_{m}=1 /\left(1+y^{\prime}\right)$$

or $y=(1\cdot  v_m)/v_m$

Similarly the duration D is:

$$D = - \frac{1}{p} \int f ( m ) \, \, v _ { m }$$

An initial approximation which is reasonable in most circumstances is:

$$y _ { o } = \frac { \displaystyle \sum _ { i = 1 } ^ { n } C F _ { i } \cdot  P } { \displaystyle \sum _ { i = 1 } ^ { n } C F _ { i } } .$$

where:

$$v_{0}=1 /\left(1+y_{0}\right)$$

91



<!-- bnd_page-52.md -->

## APPENDIX Ⅱ COMPOUNDING FREQUENCY ADJUSTMENTS

The normal redemption yield formulae described produce yields that are compounded with the periodicity of the coupon payments. For zero-coupon bonds, this is normally assumed to be the same as for the compounding frequency of the market.

A redemption yield which is compounded annually can be converted to a semi-annual compounding yield, and vice versa, very easily – irrespective of the coupon frequency.

Redemption yields with different compounding frequencies are related by the formulae:

$$(1+y_{a})=\left(1+\frac{y_{a}}{2}\right)^{2}=\left(1+\frac{y_{a}}{q}\right)^{4}=\left(1+\frac{2 y_{a}}{4}\right)^{1/3}$$

where: $y_{u} = $ yield compounded annually $y_{u} = $ yield compounded semi-annually $y_{q} = $ yield compounded quarterly $y_{m} = $ yield compounded monthly

In the above formulae, yields of 12% would be substituted as 0.12 etc.

If it is required to convert a yield with a compounding frequency of h times per year to one with a compounding frequency of r times per year, the equation may be restated as:

$$y _ { r } = r \cdot  \left[ \left( 1 + \frac { y _ { h } } { h } \right) ^ { \frac { d r } { d t } } - 1 \right]$$

92

APPENDIX II - COMPOUNDING FREQUENCY ADJUSTMENTS

where: $y_{r}=$ yield compounded r times per year $y_{h}=$ yield compounded h times per year $r=$ required compounding frequency per year $h=$ original compounding frequency per year

Example ▶

If a bond has a yield (y) compounded quarterly of 10% then it will have yields compounded semi-annually (y) and annually (y) given by:

$${\begin{array}{l}\displaystyle y_{s}=2\times \left(1+{\frac {y_{q}}{4}}\right)^{2}\\\displaystyle =2\times \left(1.025\right)^{2}\\\displaystyle =0.10125=10.125\%\end{array}}}$$

$${ \begin{array} { r l } { y _ { a } } & { = \left( 1 + { \frac { y _ { q } } { 4 } } \right) ^ { 4 } \cdot  1 } \\ & { = \left( 1 . 0 2 5 \right) ^ { 4 } \cdot  1 } \\ & { = 0 . 1 0 3 8 1 = 1 0 . 3 8 1 \% } \end{array} }$$

Example ›

If a bond has an annually compounded yield ( $y_{0}$ ) of 8%, then its semi-annually compounded yield ( $y_{0}$ ) is given by:

$$\begin{array} { r l } { y _ { s } } & { = 2 \times \left\{ \left( t + y _ { a } \right) ^ { 0 . 5 } - 1 \right\} } \\ & { = 2 \times \left\{ 1 . 0 8 ^ { 0 . 5 } - 1 \right\} = 0 . 0 7 8 4 6 = 7 . 8 4 6 \% } \end{array}$$

93



<!-- bnd_page-53.md -->

## APPENDIX III  INDEX-LINKED STOCKS AND REAL RETURNS

In some markets, stocks have been issued where the coupons and final redemption value are linked to a measure of purchasing power or inflation. An example of such stocks are the British index-linked gilt-edged securities where the coupon and redemption values are linked to the U.K. Retail Price Index, albeit lagged by 8 months.

For such stocks it is conventional to calculate a 'real' redemption yield which discounts the effect of any rise in the index, and the corresponding increase in the payments.

For index-linked stocks, it is normal for the first payment to be known, and for there to be a lag between the index reference date and the indexed payment dates.

For a stock which pays an indexed coupon $h$ times a year, with a similarly indexed redemption value the general redemption yield formula:

$$P=\sum_{i=1}^{n} C F_{i} \cdot  v^{L i}$$

where: $$ $P $ = gross price (i.e. clean price plus accrued interest) $n $ = number of future cash flows $C I_{t} $ = ith cash flow, which changes with the underlying index. $L_{t} $ = time in years to the ith cash flow $v $ = the gross discounting factor, i.e. $v=1/(1+y/h)$ $h $ = number of periods in year $y $ = the required redemption yield compounded h times per annum. (y = 0.08 for a yield of 8%)

can be restated as follows.

94

APPENDIX III - INDEX-LINKED STOCKS AND REAL RETURNS

If the assumed rate of indexing is $r$ % per period, the next known coupon payment is $k$ , and the best estimate of the following coupon is $k_2$ , then it is assumed that the $i$ th coupon payment is:

$$k _ { 2 } \cdot  ( 1 + r ) ^ { i - 2 }  f o r  i \geq 2$$

It should be noted that it is often possible to make a better estimate of $k_2$ than $k \cdot  (1 + r)$, since the index value for at least part of the period is already known due to the lagging.

Similarly the assumed redemption value is estimated as:

$$C \cdot  ( 1 + r ) ^ { n - 2 }$$

where C is the redemption value if the index was the same as for $k_{2}$

The real rate of return y is given by solving:

$$P = v ^ { f 1 } \cdot  \left\{ k + \sum _ { i = 2 } ^ { n } k _ { 2 } \cdot  ( 1 + r ) ^ { i - 2 } \cdot  v ^ { i - 1 } + C \cdot  ( 1 + r ) ^ { n - 2 } \cdot  v ^ { n - 1 } \right\}$$

where: $C = $ redemption value calculated at the same index level as the next coupon payment k $k_{1} = $ next known coupon payment $k_{2} = $ best estimate of the subsequent coupon payment. $f1 = $ fraction of a period from value date to the first/next coupon payment. A period is defined as the normal time between two consecutive coupon payments $v = $ overall discounting factor, i.e. $v = \frac{1}{(1+r) \cdot  (1+y/h)}$ $r = $ assumed indexing rate per period $h = $ number of coupon payments per year $y = $ real rate of return per year (i.e. y = 0.04 for a real return of 4.0%).

This formula may be restated as:

$$P = \left\{ \frac { w } { 1 + r } \right\} ^ { f 1 } \cdot  \left\{ k + \frac { w } { 1 + r } \cdot  \left( \sum _ { i = 2 } ^ { n } k _ { 2 } \cdot  w ^ { j - 2 } + C \cdot  w ^ { n - 2 } \right) \right\}$$

where: $w=$ 'real' discounting factor, i.e. $w=1/(1+y/\nu )v=(1+r)$

95



<!-- bnd_page-54.md -->

## BOND MARKETS: STRUCTURES AND YIELD CALCULATIONS

In the U.K., the Retail Price Index used in the calculations reflects the index value two months before the start of the coupon period, i.e. 8 months before the actual payment, as they all have two payments per year.

96

