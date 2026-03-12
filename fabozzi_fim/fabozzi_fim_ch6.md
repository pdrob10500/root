CHAPTER SIX

## THE PRICE OF A BOND

In Chapter 4 we explained that the price of any financial instrument is equal to the present value of the expected cash flows. The interest rate or discount rate used to compute the present value depends on the yield offered on comparable securities in the market. In this chapter we explain how to compute the price of an optionfree bond (i.e., a bond that is not callable, putable, or convertible). Options and the valuation of securities with embedded options are discussed in later chapters.

### DETERMINING THE CASH FLOWS

The first step in determining the price of a bond is to determine its cash flows. The cash flows of an option-free bond consist of (1) periodic coupon interest payments to the maturity date and (2) the par (or maturity) value at maturity. While the periodic coupon payments can be made over any time period during the year (weekly, monthly, quarterly, semiannually, or annually), most bonds issued in the United States pay coupon interest semiannually.

In our illustrations, we shall assume that the coupon interest is paid semianually. To simplify the analysis, we also assume that the next coupon payment for the bond will be made exactly 6 months from now. Later in the chapter we generalize the pricing model to allow for a coupon payment that is more or less than 6 months from now.

Consequently, the cash flows for an option-free bond consist of an annuity (that is, the fixed coupon interest paid every 6 months) and the par or maturity value. For example, a 20-year bond with a 9% coupon rate (4.5% each 6 months) and a par or maturity value of $1,000 has the following cash flows:

$$\begin{aligned}
 Semiannual coupon interest  & =\$ 1,000 \times 0.045 \\
& =\$ 45 ; \\
 Maturity value  & =\$ 1,000 .
\end{aligned}$$

Therefore, there are 40 semiannual cash flows of $45, and a $1,000 cash flow 40 6-month periods from now.

Notice the treatment of the par value. It is not treated as if it is received 20 years from now. Instead, it is treated on a consistent basis with the coupon payments, which are semiannual.

---

66

PART 2 Option-Free Bonds and Conventional Yield Measures

## DETERMINING THE REQUIRED YIELD

The interest rate or discount rate that an investor wants from investing in a bond is called the required yield . The required yield is determined by investigating the yields offered on comparable bonds in the market. By comparable, we mean optionfree bonds of the same credit quality and the same maturity. $^1$

The required yield is typically specified as an annual interest rate. When the cash flows are semiannual, the convention is to use one-half the annual interest rate as the periodic interest rate with which to discount the cash flows. As explained at the end of the previous chapter, a periodic interest rate that is one-half the annual yield will produce an effective annual yield that is greater than the annual interest rate.

## PRICING A BOND

Given the cash flows of a bond and the required yield, we have all the necessary data to price the bond. The price of a bond is the present value of the cash flows, which can be determined by adding

- 1. The present value of the semiannual coupon payments.
2. The present value of the par or maturity value.
In general, the price of a bond can be computed using the formula:

$$p=\frac{c}{(i+1)^{2}}+\frac{c}{(i+1)^{3}}+\frac{c}{(i+1)^{4}}+\cdot s+\frac{c}{(i+1)^{n}}+\frac{M}{(i+1)^{n}}.$$

where

$p = \text{Price (\$)}$; $c = \text{Semiannual coupon payment (\$)}$; $i = \text{Periodic interest rate (required yield/2) (in decimal form)}$; $n = \text{Number of periods (number of years $\times$ 2)}$; $m = \text{Maturity value}$.

Since the semiannual coupon payments are equivalent to an ordinary annuity, the present value of the coupon payments, that is, the present value of

$$p=\frac{c}{(1+i)^{n}}+\frac{c}{(1+i)^{2}}+\frac{c}{(1+i)^{3}}+\cdot s+\frac{c}{(1+i)^{n}}.$$

1. In Chapter 13, we introduce a measure of interest-rate risk known as duration. Instead of talking in terms of a bond with the same maturity as being comparable, the analysis can properly be recast in terms of the same duration.

---

CHAPTER 6 The Price of a Bond

67

can be expressed

$$c\left[1-\left[\frac{1}{(1+i)^{n}}\right]\right]$$

This formula is the same as the formula for the present value of an ordinary annuity for $n$ periods introduced in Chapter 4 (see Exhibit 4-1). Instead of using $A$ to represent the annuity, we have used $c$, the semiannual coupon payment.

Illustration 6-1. Compute the price of a 9% coupon bond with 20 years to maturity and a par value of $1,000 if the required yield is 12%.

The cash flows for this bond are as follows:

- 1. 40 semiannual coupon payments of $45;

2. $1,000, 40 6-month periods from now.
The semiannual or periodic interest rate is 6%.

The present value of the 40 semiannual coupon payments of $45 discounted at 6% is $677.08, as shown below:

$$
c=\$ 45 ; 
$$

$$
n=40 ; 
$$

$$i=0.06 .$$

$$\begin{aligned}
&45\left[\frac{1-{\left[\frac{1}{(0.06)^{40}}\right]}}{0.06}\right]\\
&=\$45\left[\frac{1-{\left[\frac{1}{0.28572}\right]}}{0.06}\right]\\
&=\$45(15.04630)=\$677.08.
\end{aligned}$$

The present value of the par or maturity value 40 6-month periods from now

discounted at 6% is $97.22, as shown below:

$$M=\$1,000;$$

$$n=40 ;$$

$$i=0.06 .$$

$${ \begin{array} { r l } & { 1 , 0 0 0 \left[ { \frac { 1 } { ( 1 . 0 6 ) ^ { 4 0 } } } \right] } \\ & { = 1 , 0 0 0 \left[ { \frac { 1 } { 1 0 . 2 8 5 7 2 } } \right] } \\ & { = 1 , 0 0 0 ( 0 . 0 9 7 2 2 2 ) } \\ & { = \$ 9 7 . 2 2 . } \end{array} }$$

---

68

PART 2 Option-Free Bonds and Conventional Yield Measures

The price of the bond is then equal to the sum of the two present values:

<table><tr><td>Present value of coupon payments</td><td>$677.08</td></tr><tr><td>Present value of par (maturity) value</td><td>97.22</td></tr><tr><td>Price</td><td>$774.30</td></tr></table>


Illustration 6-2. Compute the price of the bond in Illustration 6-1 assuming that the required yield is 7%.

The cash flows are unchanged, but the periodic interest rate is now 3.5% (7%/2).

The present value of the 40 semiannual coupon payments of $45 discounted at 3.5% is $960.98, as shown below:

$$c=\$ 45 ;$$

$$n=40;$$

$$i=0.035 .$$

$$\begin{aligned}
&45\left[4\frac{1-\left[\frac{1}{(1.035)^{20}}\right]}{0.035}\right]\\
&=45\left[4\frac{1-\left[\frac{1}{3.95926}\right]}{0.035}\right]\\
&=45(21.35509)\\
&=960.98.
\end{aligned}$$

The present value of the par or maturity value of $1,000 40 6-month periods

from now discounted at 3.5% is $252.57, as shown below:

$$M=\$1,000;$$

$$
n=40 ; 
$$

$$i=0.035.$$

$$\begin{aligned}
&1,000\left[\frac{1}{(1.035)^{40}}\right]\\
&=1.000\left[\frac{1}{3.95926}\right]\\
&=1.000(0.252572)\\
&=252.57.
\end{aligned}$$

---

CHAPTER 6 The Price of a Bond

69

The price of the bond is then equal to the sum of the two present values:

<table><tr><td>Present value of coupon payments</td><td>$960.98</td></tr><tr><td>Present value of par (maturity) value</td><td>252.57</td></tr><tr><td>Price</td><td>$1,213.55</td></tr></table>


Illustration 6-3. Compute the price of the bond in Illustration 6-1 assuming that there are 16 years to maturity rather than 20 years. (Assume that the required yield is still 12%)

The cash flows for this bond are as follows:

- 1. 32 semianual coupon payments of $45;
2. $1,000, 32-6 month periods from now.
The semiannual or periodic interest rate is 6%.

The present value of the 32 semiannual coupon payments of $45 discounted at 6% is

$$c=\$ 45;$$

$$n=32 ;$$

$$i=0.06$$

$$\begin{aligned}
& \$45\left[1-\frac{1}{\left(1.06\right)^{32}}\right] \\
& =\$ 45\left[1-\frac{\left[6.45339\right]}{0.06}\right] \\
& =\$ 45(14.08404) \\
& =\$ 633.78 .
\end{aligned}$$

The present value of the par or maturity value 32 6-month periods from now discounted at 6% is:

$$M=\$1,0000$$

$$n=32 ;$$

$$i=0,06$$

$$\begin{aligned}
&1,000\left[\frac{1}{(1.06)^{3T}}\right]\\
&=1,000\left[1\frac{1}{0.54539}\right]\\
&=1,000(0.154957)\\
&=154.96.
\end{aligned}$$

---

70

PART 2 Option-Free Bonds and Conventional Yield Measures

The price of the bond is then equal to the sum of the two present values:

<table><tr><td>Present value of coupon payments</td><td>$633.78</td></tr><tr><td>Present value of par (maturity) value</td><td>154.96</td></tr><tr><td>Price</td><td>$788.74</td></tr></table>


Illustration 6-4. Compute the price of a 14-year bond with a 9% coupon rate assuming that the required yield is 7%.

The cash flows for this bond are as follows:

- 1. 28 semiannual coupon payments of $45;
2. $1,000, 28 6-month periods from now.
The periodic interest rate is 3.5%.

The present value of the 28 semiannual coupon payments when discounted at 3.5% is

$$
c=\$ 45 ; 
$$

$$n=28 ;$$

$$i=0.035 .$$

$$\begin{aligned}
& \$45\left[\frac{1-\left[\frac{1}{(1.035)^{28}}\right]}{0.035}\right] \\
& =\$ 45\left[\frac{1-\left[\frac{1}{2.62017}\right]}{0.035}\right] \\
& =\$ 45(17.66700) \\
& =\$ 795.02 .
\end{aligned}$$

The present value of the par or maturity value 28 6-month periods from now discounted at 5.5% is

$$M=\$1,000;$$

$$n=32 ;$$

$$i=0.035 .$$

$$\begin{aligned}
&1,000\left[\frac{1}{(1.035)^{28}}\right]\\
&=1,000\left(\frac{1}{2.62017}\right)\\
&=1,000(0.381654)\\
&=381.65.
\end{aligned}$$

---

CHAPTER 6 The Price of a Bond

71

The price of the bond is then equal to the sum of the two present values:

<table><tr><td>Present value of coupon payments</td><td>$795.02</td></tr><tr><td>Present value of par (maturity) value</td><td>381.65</td></tr><tr><td>Price</td><td>$1,176.67</td></tr></table>


## RELATIONSHIP BETWEEN REQUIRED YIELD AND PRICE AT A GIVEN TIME

The price of a bond changes in the direction opposite from the change in the required yield. The reason is that the price of the bond is the present value of the cash flows. As the required yield increases, the present value of the cash flows decreases; hence, the price decreases. The opposite is true when the required yield decreases: the present value of the cash flows increases and, therefore, the price of the bond increases.

We can see this by comparing the price of the 20-year, 9% coupon bond that we priced in Illustrations 6-1 and 6-2. When the required yield is 12%, the price of the bond is $774.30. If, instead, the required yield is 7%, the price of the bond is $1,213.55. Exhibit 6-1 shows the price of the bond for required yields from 5% to 14% for the 20-year, 9% coupon bond.

EXHIBIT 6-1

Price/Yield Relationship for a 20-Year, 9% Coupon Bond

<table><tr><td>Required Yield (%)</td><td>Present Value of 40 Coupon Payments ($)*</td><td>Present Value of Par Value in 40 Periods ($)**</td><td>Price of Bond ($)</td></tr><tr><td>5%</td><td>$1,129.62</td><td>$372.43</td><td>$1,502.05</td></tr><tr><td>6</td><td>1,040.16</td><td>306.56</td><td>1,346.72</td></tr><tr><td>7</td><td>960.98</td><td>252.57</td><td>1,213.55</td></tr><tr><td>8</td><td>890.67</td><td>208.29</td><td>1,098.96</td></tr><tr><td>9</td><td>828.07</td><td>171.93</td><td>1,000.00</td></tr><tr><td>10</td><td>772.16</td><td>142.05</td><td>914.21</td></tr><tr><td>11</td><td>722.08</td><td>117.46</td><td>839.54</td></tr><tr><td>12</td><td>677.08</td><td>97.22</td><td>774.30</td></tr><tr><td>13</td><td>636.55</td><td>80.54</td><td>717.09</td></tr><tr><td>14</td><td>599.93</td><td>66.78</td><td>666.71</td></tr></table>


"Computed as follows: where / is one-half the required yield. "Computed as follows: where / is one-half the required yield.

---

72

PART 2 Option-Free Bonds and Conventional Yield Measures

EXHIBIT 6-2

Price/Yield Relationship for an Option-Free Bond

![Figure](figures/fabozzi_fim_ch6_page_008_figure_004.png)

If we graph the price/yield relationship for any option-free bond, we will find it has the "bowed" shape shown in Exhibit 6-2. This shape is referred to as convex . The convexity of the price/yield relationship has important implications for the investment properties of a bond. In Chapter 12 we examine this relationship more closely.

## RELATIONSHIPS AMONG COUPON RATE, REQUIRED YIELD, AND PRICE

For a bond issue, the coupon rate and the term to maturity are fixed. Consequently, as yields in the marketplace change, the only variable that can change to compensate for the new yield required in the market is the price of the bond. As we saw in the previous section, as the required yield increases (decreases), the price of the bond decreases (increases).

Generally, a bond's coupon rate at the time of issuance is set at approximately the prevailing yield in the market. $^2$ The price of the bond will then be approximately equal to its par value. For example, in Exhibit 6-1, we see that when the required yield is equal to the coupon rate, the price of the bond is its par value ($1,000). Consequently, we have the following properties:

2. The exception is an original issue deep-discount bond such as a zero-coupon bond. We'll discuss zero-coupon bonds later in this chapter.

---

CHAPTER 6 The Price of a Bond

73

When the coupon rate equals the required yield, then the price equals the par value.

When the price equals the par value, then the coupon rate equals the required yield.

When yields in the marketplace rise above the coupon rate at a particular time, the price of the bond has to adjust so that the investor can realize additional inter- est income. This adjustment happens when the bond's price falls below the par value. The difference between the par value and the price is a capital gain and represents a form of interest income to the investor to compensate for the coupon rate being lower than the required yield.

When a bond sells below its par value, it is said to be selling at a discount. We can see this in Exhibit 6-1. When the required yield is greater than the coupon rate of 9%, the price of the bond is always less than the par value ($1,000). Consequently, we have the following properties:

When the coupon rate is less than the required yield, then the price is less than the par value.

When the price is less than the par value, then the coupon rate is less than the required yield.

Finally, when the required yield in the market is below the coupon rate, the bond must sell above its par value. This occurs because investors who would have the opportunity to purchase the bond at par would be getting a coupon rate in excess of what the market requires. Because its yield is attractive, investors would bid up the price of the bond to a price that offers the required yield in the market.

A bond whose price is above its par value is said to be selling at a premium . Exhibit 6–1 shows that for a required yield less than the coupon rate of 9%, the price of the bond is higher than its par value. Consequently, we have the following properties:

When the coupon rate is higher than the required yield, then the price is higher than the par value.

When the price is higher than the par value, then the coupon rate is higher than the required yield.

## $$  TIME PATH OF A BOND  $$

If the required yield is unchanged between the time a bond is purchased and the maturity date, what will happen to the price of the bond? For a bond selling at par value, the coupon rate is equal to the required yield. As the bond moves closer to maturity, the bond will continue to sell at par value. Thus, the price of a bond selling at par will remain at par as the bond moves toward the maturity date.

The price of a bond will not remain constant for a bond selling at a premium or a discount. This can be seen for a discount bond by comparing the price found

---

74

PART 2 Option-Free Bonds and Conventional Yield Measures

in Illustration 6-1 to that found in Illustration 6-3. In both illustrations the bond has a 5% coupon rate and the required yield is 12%. In Illustration 6-1, the maturity of the bond is 20 years, while in Illustration 6-3 the maturity is 16 years. With 20 years to maturity, the price of the bond is $774.30. Four years later, when the bond has 16 years remaining to maturity, the price of the bond increases to $788.74. For all discount bonds the following is true: as a bond moves toward maturity, its price will increase if the required yield does not change.

Exhibit 6-3 shows the price of the 20-year, 9 % coupon bond as it moves towards maturity, assuming that the required yield remains at 12 % . The price of the bond is decomposed into the present value of the coupon payments and the present value of the par value. Notice that as the bond moves towards maturity, there are fewer coupon payments to be received by the bondholder. The present value of the coupon payments decreases. Since the maturity date is closer, however, the present value of the par value increases. The increase in the present value of the par value is greater than the decline in the present value of the coupon payments, resulting in a price increase. Exhibit 6-4 graphs the time path of a bond selling at a discount.

For a bond selling at a premium, the price of the bond declines as it moves towards maturity. Illustrations 6-2 and 6-4 show this property for a 9% coupon bond for which the required yield is 7%. When the bond has 20 years to maturity, its price is $1,213.5$. Six years later, when the bond has 14 years remaining to maturity, the price of the bond declines to $1,176.67.

EXHIBIT 6-3

Time Path of the Price of a Discount Bond: 20-Year, 9% Coupon, 12% Required Yield

<table><tr><td>Years Remaining to Maturity</td><td>Present Value of Coupon Payments of$45 at 6% ($)</td><td>Present Value of Par Value at 6% ($)</td><td>Price of Bond ($)</td></tr><tr><td>20</td><td>$677.08</td><td>$97.22</td><td>$774.30</td></tr><tr><td>18</td><td>$657.94</td><td>$122.74</td><td>$780.68</td></tr><tr><td>16</td><td>$633.78</td><td>$154.96</td><td>$788.74</td></tr><tr><td>14</td><td>$603.28</td><td>$195.63</td><td>$798.91</td></tr><tr><td>12</td><td>$564.77</td><td>$256.98</td><td>$811.75</td></tr><tr><td>10</td><td>$516.15</td><td>$311.80</td><td>$827.95</td></tr><tr><td>8</td><td>$454.77</td><td>$393.65</td><td>$848.42</td></tr><tr><td>6</td><td>$377.27</td><td>$496.97</td><td>$874.24</td></tr><tr><td>4</td><td>$279.44</td><td>$627.41</td><td>$906.85</td></tr><tr><td>2</td><td>$155.93</td><td>$792.09</td><td>$948.02</td></tr><tr><td>1</td><td>$82.50</td><td>$890.00</td><td>$972.50</td></tr><tr><td>0</td><td>$0.00</td><td>$1,000.00</td><td>$1,000.00</td></tr></table>


---

CHAPTER 6 The Price of a Bond

75

$$ EXXIIIT 6-4 $$

![Figure](figures/fabozzi_fim_ch6_page_011_figure_003.png)

The time path of the 20-year, 9 % coupon bond selling to yield 7% is shown in Exhibit 6-5. As the bond moves toward maturity, the present value of the coupon payments decreases, and the present value of the par value increases. Unlike a bond selling at a discount, the increase in the present value of the par value is not

EXHIBIT 6-5

Time Path of the Price of a Premium Bond: 20-Year, 9% Coupon, 7% Required Yield

<table><tr><td>Years Remaining to Maturity</td><td>Present Value of Coupon Payments of$45 at 3.5% ($)</td><td>Present Value of Par Value at 3.5% ($)</td><td>Price of Bond ($)</td></tr><tr><td>20</td><td>$960.98</td><td>$252.57</td><td>$1,213.55</td></tr><tr><td>18</td><td>913.07</td><td>289.83</td><td>1,202.90</td></tr><tr><td>16</td><td>858.10</td><td>332.59</td><td>1,190.69</td></tr><tr><td>14</td><td>795.02</td><td>381.65</td><td>1,176.67</td></tr><tr><td>12</td><td>722.63</td><td>437.96</td><td>1,160.59</td></tr><tr><td>10</td><td>639.56</td><td>502.57</td><td>1,142.13</td></tr><tr><td>8</td><td>544.24</td><td>576.71</td><td>1,120.95</td></tr><tr><td>6</td><td>434.85</td><td>661.78</td><td>1,096.63</td></tr><tr><td>4</td><td>309.33</td><td>759.41</td><td>1,068.74</td></tr><tr><td>2</td><td>165.29</td><td>871.44</td><td>1,036.73</td></tr><tr><td>1</td><td>85.49</td><td>933.51</td><td>1,019.00</td></tr><tr><td>0</td><td>0.00</td><td>1,000.00</td><td>1,000.00</td></tr></table>


---

76

PART 2 Option-Free Bonds and Conventional Yield Measures

EXHIBIT 6-6

![Figure](figures/fabozzi_fim_ch6_page_012_figure_003.png)

sufficient to offset the decline in the present value of the coupon payments. As a result, the price of a bond selling at a premium decreases over time if the required yield does not change. A graphical depiction of the time path of any premium bond is presented in Exhibit 6-6.

## ANALYSIS OF BOND PRICE CHANGES

A money manager is interested in assessing the expected performance of a bond over an investment horizon given certain assumptions about the future direction of interest rates. We'll demonstrate how this is done in Chapter 10. Doing so requires that we know how to analyze the way a bond's price will change under a specified set of assumptions.

The price of a bond can change for one or more of the following three reasons:

- 1. A change in the required yield due to changes in the credit quality of the
issuer;

2. A change in the maturity of the bond as it moves toward maturity without
any change in the required yield (that is, the time path of the bond);

3. A change in the required yield due to a change in the yield on comparable
bonds (that is, a change in the yield required by the market).
Predicting the change in an issue's credit quality before that change is rec- ognized by the market is one of the challenges of investment management. We will

---

CHAPTER 6 The Price of a Bond

77

describe the some of the tools used for credit risk analysis in later chapters. For purposes of our illustrations below, let's suppose that the issue's credit quality is unchanged so that we can focus on the last two reasons.

It is informative to separate the effect of the change in price due to the time path of a bond from that of the change due to a change in the required yield. The next two illustrations show how this is done.

Illustration 6-5. Suppose that a money manager purchases a 20-year, 9 % coupon bond at a price of $774.30 to yield 12 % . The money manager expects to hold this bond for 4 years, at which time the money manager believes that the required yield on comparable 16-year bonds will be 8 % . On the basis of these expectations, we can investigate what will happen to the price of the bond 4 years from now.

After this bond is held for 4 years, it becomes a 16-year bond. If the required yield for a 16-year bond is 8%, the price of the bond 4 years from now will be $1,089.37.3 The price of this bond is therefore expected to increase by $315.07 ($1,089.37 -$744.30). Not all of the price change, however, is due to the decline in market yield. If the required yield remains at 12%, the price of the bond in 4 years will have increased to $788.74, an increase of $14.44 ($788.74 — $744.30). Therefore, we can decompose the expected price change after 4 years as follows:

<table><tr><td>Price change due to the time path of a discount bond</td><td>$14.44</td></tr><tr><td>Price change due to the change in the required yield</td><td>300.63</td></tr><tr><td>Total price change</td><td>$315.07</td></tr></table>


Illustration 6-6. Suppose that a money manager is considering the purchase of a 20-year, 9 % coupon bond selling at $1,213.55 to yield 7 % . If the money manager purchases this bond, she expects to hold it for 6 years, at which time she expects that the required yield on 14-year bonds may be 11 % . What would be the price performance of this bond based on the money manager's expectations?

The price of a 14-year, 9% coupon bond if an 11% required yield is assumed is $858.79.4 If the required yield remained at 7%, however, the price of a 14-year

3. The price is determined as follows:

<table><tr><td>Present value of 32 coupon payments at 4%</td><td>$804.31</td></tr><tr><td>Present value of par (maturity) value at 4%</td><td>285.06</td></tr><tr><td>Price</td><td>$1,089.37</td></tr></table>


4. The price is determined as follows:

<table><tr><td>Present value of 28 coupon payments at 5.5%</td><td>$635.47</td></tr><tr><td>Present value of par (maturity) value at 5.5%</td><td>223.32</td></tr><tr><td>Price</td><td>$858.79</td></tr></table>


---

78

PART 2 Option-Free Bonds and Conventional Yield Measures

bond with a coupon rate of 9% would be $1,176.67 (see Exhibit 6-5). The price change can be broken down as follows:

<table><tr><td>Price change due to the time path of a discount bond</td><td>-$36.88</td></tr><tr><td>Price change due to the change in the required yield</td><td>-317.88</td></tr><tr><td>Total price change</td><td>-$354.76</td></tr></table>


## THE PRICE OF A ZERO-COUPON BOND

So far we have determined the price of coupon-bearing bonds. There are bonds that do not make any periodic coupon payments. Instead, the investor realizes interest by the amount of the difference between the maturity value and the purchase price.

The pricing of a zero-coupon bond is no different from the pricing of a coupon bond: its price is the present value of the expected cash flows. In the case of a zero-coupon bond, the only cash flow is the maturity value. Therefore, the formula for the price of a zero-coupon bond that matures N years from now is

$$p=M\left[\frac{1}{(1+i)^{n}}\right]$$

where $p = \text{Price}$; $M = \text{Maturity value}$; $i = \text{Periodic interest rate (annual interest rate/2)}$; $n = 2 \times N$, where $N = \text{Number of years}$.

Pay particular attention to the number of periods used in the pricing of a zerocoupon bond. Although an issue may mature in $N$ years, the number of 6-month periods is used in the exponent, and the periodic interest rate is the required yield divided by 2. The reason is that the pricing of a zero-coupon bond must be made consistent with the pricing of a coupon bond. Recall that with a coupon bond the present value of the maturity value is computed using twice the number of years to maturity. Therefore, we handle the maturity value for the zero-coupon bond the same way.

Illustration 6-7. Compute the price of a zero-coupon bond that matures 10 years from now if the maturity value is $1,000 and the required yield is 8.6%.

The price is determined as follows:

$$\begin{array} { r } { M = 1 . 0 0 0 ; } \\ { i = 0 . 0 4 3 \, ( 0 . 0 8 6 / 2 ) } \end{array}$$

---

CHAPTER 6 The Price of a Bond

79

$$N=10 ;$$

$$n=20(2\times10).$$

$$\begin{array}{l}
p=$1,000\left[\frac{1}{(1.043)^{20}}\right]\\
=$1,000\left[\frac{1}{2.321059}\right]\\
=$1,000(0.43083)\\
=$430.83.
\end{array}$$

Illustration 6-8. Compute the price of a 7-year, zero-coupon bond with a maturity value of $100,000 if the required yield is 9.8%.

The price is $51,185.06, as shown below:

$$M=\$100,000;$$

$$i=0.049\times(0.098/2);$$

$$N=7 ;$$

$$n=14(2\times7).$$

$$\begin{array}{l}
p=\$100,000\left[\frac{1}{(1.049)^{12}}\right]\\
=\$100,000\left[\frac{1}{1.953695}\right]\\
=\$100,000\left(1.01518506\right)\\
=\$51,185.06.
\end{array}$$

## PRICE QUOTATIONS

In all but our last illustration, we have assumed that the maturity or par value of the bond is $1,000. A bond can have a maturity or par value of any amount. Consequently, traders quote bond prices as a percentage of par value.

A bond selling at par is quoted as 100, meaning 100% of its par value. A bond selling at a discount will be selling for less than 100; a bond selling at a premium will be selling for more than 100. The following examples illustrate how a price quote is converted into a dollar price.

---

80

PART 2 Option-Free Bonds and Conventional Yield Measures

<table><tr><td>(1) Price Quote</td><td>(2) Converted to a Decimal [(1)/100]</td><td>(3) Par Value</td><td>(4) Dollar Price [(2) × (3)]</td></tr><tr><td>95</td><td>0.9500000</td><td>$1,000</td><td>$950.00</td></tr><tr><td>95/2</td><td>0.9550000</td><td>100,000</td><td>95,500.00</td></tr><tr><td>98/4</td><td>0.9825000</td><td>5,000</td><td>4,912.50</td></tr><tr><td>80/8</td><td>0.8012500</td><td>10,000</td><td>8,012.50</td></tr><tr><td>74/22</td><td>0.7403125</td><td>1,000,000</td><td>740,312.50</td></tr><tr><td>100</td><td>1.0000000</td><td>10,000</td><td>10,000.00</td></tr><tr><td>103</td><td>1.0300000</td><td>1,000</td><td>1,030.00</td></tr><tr><td>106/4</td><td>1.0675000</td><td>500,000</td><td>533,750.00</td></tr><tr><td>108/8</td><td>1.0837500</td><td>25,000</td><td>27,093.75</td></tr><tr><td>111/22</td><td>1.1134375</td><td>100,000</td><td>111,343.75</td></tr></table>


Treasury notes and bonds are quoted in the secondary market on a price basis in points, where one point equals 1% of par3. The points are split into units of thirty-seconds, so a price of 98-14, for example, refers to a price of 98 and 14/12 or 98.4375. The thirty-seconds are themselves split by the addition of a plus sign or a number, with a plus sign indicating that half a thirty-second (or 1/60) is added to the price and a number indicating how many eights of thirty-seconds (or 256ths) are added to the price. A price of 98-14+ therefore refers to a price of 98 and 14/2 thirty-seconds, or 98.453125, whereas a price of 98-142 refers to a price of 98 and 14/2 thirty-seconds, or 98.4453125.

## DETERMINING THE PRICE WHEN THE SETTLEMENT DATE FALLS BETWEEN COUPON PERIODS

Dates for Computations

In computations in the bond market, there are several dates that have specific meaning. These include the trade date, settlement date, issue date, dated date, coupon dates, and the next coupon date.

The date on which a transaction is initiated is the trade date. It is also referred to as the transaction date. The date when the transaction is cleared by the delivery of the securities by the seller to the buyer and the payment of funds from the buyer to the seller is the settlement date. The earliest date on which settlement can occur is the issue date. A more important date for calculation of interest is the dated date, which is the date when interest begins to accrue. This date, also referred to as the interest accrue date, can be either before, on, or after the issue date.

5. Treasury coupon securities are quoted in yield terms in when-issued trading because coupon rates for new Treasury securities are not set until after these securities are auctioned.

---

CHAPTER 6 The Price of a Bond

81

With the exception of zero-coupon bonds, there are dates when the issuer agrees to make coupon payments. These are called the coupon dates . For a bond purchased in the secondary market, the next coupon date is the coupon date that is just after the settlement date.

Our illustrations have assumed that the next coupon payment is 6 months away. This means that settlement occurs the day after a coupon date. Typically, an investor purchases a bond between coupon dates, so that the next coupon payment is less than 6 months away. To compute the price, we have to answer three questions:

- 1. How many days are there until the next coupon payment?

2. How should we determine the present value of cash flows received
over fractional periods?

3. How much must the buyer compensate the seller for the coupon
interest earned by the seller for the fraction of the period that the bond
was held?
The first question is the “day count” question. The second is the “compounding” question. The last question asks how accrued interest is determined.

## Day Count Conventions

Market conventions for the number of days in a coupon period and the number of days in a year differ by type of bond issuer (i.e., government, government-related entity, local government, and corporate) and by country. The following notation is typically used to denote a day count convention:

Number of days in a month/Number of days in a year and “NL” is used to denote no leap year and “E” to denote European. In practice, there are eight day count conventions:6

- 1. Actual/actual (in period);
2. Actual/365;
3. Actual (NL)/365;
4. Actual/365 (366 in leap year);
5. Actual/360;
6. 30/360;
7. 30/365;
8. 30E/360.
6. Dragonic Krgin, Handbook of Global Fixed Income Calculation (Hoboken, NJ: John Wiley & Sons, 2002), p. 21. This book is the most comprehensive source for formulas and rules for not only day count conventions but also for accrued interest, which we discuss next.

---

82

PART 2 Option-Free Bonds and Conventional Yield Measures

In calculation of the actual number of days, only one of the two bracketing dates in question is included. For example, the actual number of days between August 20 and August 24 is 4 days.

Actual (NL)/365 is the same as Actual/365 with the exception that February 29 is not counted in the former method.

In the day count conventions where “30” is used for the number of days (i.e., the last three methods), there are rules for computing the number of days in between two days in assuming a 30-day month.

Day count conventions are used for calculating:

- • Accrued interest to be paid;
• Accrued interest for price/yield;
• Next coupon payment;
• The exponent used to compute the present value of the cash flow from
the next coupon date back to the settlement date;
• The coupon payment on the maturity date;
• The exponent used to compute the present value of the cash flow at the
maturity date back to the last coupon date.
Government bond markets in the United States and EMU countries, the same day count convention is used for all of the calculations above, but it is not necessary the same for other bond markets. For example, in the Canadian government bond market, Actual/365 is used for computing accrued interest to be paid and the exponent used to compute the present value of the cash flow at the maturity date back to the last coupon date. However, for all other calculations, the Actual/Actual convention is used.

Below we describe the day count conventions for U.S. Treasury, corporate, and municipal bonds. The day count convention for major non-U.S. government bond markets and the Eurobond market for computing the accrued interest to be paid is shown in Exhibit 6-7. In addition to the day count convention, the frequency of coupon payments, and ex-dividend trading (discussed later) are shown in the exhibit.

## Application to U.S. Treasury Coupon Securities

In the U.S. Treasury coupon securities market, the day count convention used is to determine the actual number of days between two dates and the actual number of days in a year. This is referred to as the “actual/actual” day count convention. For example, consider a Treasury bond whose previous coupon payment was March 1 and whose next coupon payment is on September 1. Suppose this bond is purchased with a settlement date of July 17. The actual number of days between July 17 (the settlement date) and September 1 (the date of the next coupon payment) is 46 days, as shown below:

---

CHAPTER 6 The Price of a Bond

83

### EXHIBIT 6-7

Coupon Frequency, Day Count Convention for Computing Accrued Interest Paid, and Ex-Dividend Trading Practice for Non-U.S. Government Bond Markets and the Eurobond Market

<table><tr><td>Government Bond Market of:</td><td>Coupon Payment Frequency</td><td>Day Count Convention for Calculating Accrued Interest to Be Paid</td><td>Ex-Dividend Trading</td></tr><tr><td>Australia</td><td>Semiannual</td><td>Actual/Actual (in period)</td><td>Yes</td></tr><tr><td>Canada</td><td>Semiannual</td><td>Actual/365</td><td>No</td></tr><tr><td>Czechoslovakia</td><td>Annual</td><td>360E/360</td><td>Yes</td></tr><tr><td>Denmark</td><td>Annual</td><td>Actual/Actual (in period)</td><td>Yes</td></tr><tr><td>EMU countries</td><td>Annual</td><td>Actual/Actual (in period)</td><td>No</td></tr><tr><td>Finland</td><td>Annual</td><td>360E/360</td><td>No</td></tr><tr><td>Greece</td><td>Annual</td><td>360E/360</td><td>No</td></tr><tr><td>Ireland</td><td>Annual</td><td>360E/360</td><td>Yes</td></tr><tr><td>Italy</td><td>Semiannual</td><td>360E/360</td><td>No</td></tr><tr><td>New Zealand</td><td>Semiannual</td><td>Actual/Actual (in period)</td><td>Yes</td></tr><tr><td>Norway</td><td>Semiannual</td><td>Actual/365</td><td>Yes</td></tr><tr><td>Poland</td><td>Annual</td><td>Actual/Actual (in period)</td><td>No</td></tr><tr><td>South Africa</td><td>Semiannual</td><td>Actual/365</td><td>Yes</td></tr><tr><td>Sweden</td><td>Annual</td><td>360E/360</td><td>Yes</td></tr><tr><td>Switzerland</td><td>Annual</td><td>360E/360</td><td>No</td></tr><tr><td>Eurobonds</td><td>Annual</td><td>360E/360</td><td>No</td></tr></table>


Source: The information in this exhibit was obtained from Exhibit 1-1 in Dragonir Krgin, Handbook of Global Fixed Income Calculation (Hoboken, NJ: John Wiley & Sons, 2002), p. 29.

<table><tr><td>July 17 to July 31</td><td>14 days</td></tr><tr><td>August</td><td>31 days</td></tr><tr><td>September 1</td><td>1 day</td></tr><tr><td></td><td>46 days</td></tr></table>


The number of days in the coupon period is the actual number of days between March 1 and September 1, which is 184 days.

### Application Federal Agency, Corporate, and Municipal Securities

In contrast to the "actual/actual" day count convention for coupon-bearing Treasury securities, for corporate and municipal bonds and agency securities, the day count convention is "30/360." That is, each month is assumed to have 30 days and each year, 360 days. For example, suppose that the security in our previous example is not a coupon-bearing Treasury security but instead either a coupon-bearing

---

84

PART 2 Option-Free Bonds and Conventional Yield Measures

corporate bond, municipal bond, or agency security. The number of days between July 17 and September 1 is as shown below:

<table><tr><td>July 17 to July 31</td><td>13 days</td></tr><tr><td>August</td><td>30 days</td></tr><tr><td>September 1</td><td>1 day</td></tr><tr><td></td><td>44 days</td></tr></table>


Basic financial calendars provide the day count between settlement and the next coupon payment. Most money managers, however, use software programs that will furnish this information.

## Compounding

Once the number of days between the settlement date and the next coupon date is determined, the present value formula must be modified to take into account that the cash flows will not be received 6 months (one full period) from now. The “street” convention is to compute the price as follows:

1. Determine the number of days in the coupon period.

2. Compute the ratio:

$$w=\frac{ Number of days between settlement and next coupon payment }{ Number of days in the coupon period }$$

For a corporate bond, municipal bond, or agency security, the number of days in the coupon period will be 180, since a year is assumed to have 360 days. For a coupon-bearing Treasury security, the number of days is the actual number of days. The number of days in the coupon period is called the basis .

3. For a bond with n coupon payments remaining to maturity, the price is:

$$p=\frac{c}{(1+c)^{2}+c}\left(\frac{c}{(1+i)^{2}+w}+\frac{c}{(1+i)^{2}+w}+\frac{c}{(1+i)^{2}+w}+\frac{M}{(1+i)^{2}+w}\right.$$

where

p = Price ($);

c = Semiannual coupon payment ($);

i = Periodic interest rate (required yield divided by 2) (in decimal form);

n = Number of coupon payments remaining;

M = Maturity value.

we modify

---

CHAPTER 6 The Price of a Bond

85

The period (exponent) in the formula for determining the present value can be expressed generally as $t-1+w$ . For example, for the first cash flow, the period is $1-1+w$ , or simply w . For the second cash flow it is $2-1+w$ , or simply $1+w$ . If the bond has 20 coupon payments remaining, the period is $20-1+w$ , or simply $19+w$ .

Illustration 6-9. Suppose that a corporate bond with a coupon rate of 10% maturing March 1, 2012, is purchased with a settlement date of July 17, 2006. What would the price of this bond be if it is priced to yield 6.5%?

The next coupon payment will be made on September 1, 2006. Since the bond is a corporate bond, the 30/360 day count convention is that there are 44 days between the settlement date and the next coupon date. The number of days in the coupon period is 180 days. Therefore,

$$w=\frac{44}{180}=0.24444.$$

The number of coupon payments remaining, $n$, is 12. The semiannual interest rate is 3.25% (6.5%/2). Calculation of the price is shown in Exhibit 6-8.

The price of this corporate bond is $120,0281. The price calculated in this way is called the full price or dirty price because it reflects the portion of the coupon interest that the buyer will receive but that the seller has earned.

$$ EXHIBIT 6-8 $$

Calculation of Full (Dirty) Price When a Bond Is Purchased Between Coupon Payments

<table><tr><td>Period</td><td>Cash Flow per$100 of Par ($)</td><td>Present Value of$1 at 3.25% ($)</td><td>Present Value of Cash Flow ($)</td></tr><tr><td>0.24444</td><td>$5.00</td><td>$0.992244</td><td>$4.961080</td></tr><tr><td>1.24444</td><td>5.00</td><td>0.960980</td><td>4.804902</td></tr><tr><td>2.24444</td><td>5.00</td><td>0.930731</td><td>4.653658</td></tr><tr><td>3.24444</td><td>5.00</td><td>0.901435</td><td>4.507175</td></tr><tr><td>4.24444</td><td>5.00</td><td>0.873060</td><td>4.365303</td></tr><tr><td>5.24444</td><td>5.00</td><td>0.845579</td><td>4.227896</td></tr><tr><td>6.24444</td><td>5.00</td><td>0.818963</td><td>4.094615</td></tr><tr><td>7.24444</td><td>5.00</td><td>0.793184</td><td>3.965922</td></tr><tr><td>8.24444</td><td>5.00</td><td>0.768217</td><td>3.841087</td></tr><tr><td>9.24444</td><td>5.00</td><td>0.744036</td><td>3.720181</td></tr><tr><td>10.24444</td><td>5.00</td><td>0.720616</td><td>3.603081</td></tr><tr><td>11.24444</td><td>105.00</td><td>0.697933</td><td>73.283000</td></tr><tr><td></td><td></td><td></td><td>Total$120.028100</td></tr></table>


---

86

PART 2 Option-Free Bonds and Conventional Yield Measures

## Accrued Interest

The buyer must compensate the seller for the portion of the next coupon interest payment the seller has earned but will not receive from the issuer because the issuer will send the next coupon payment to the buyer. This amount is called accrued interest . Interest accrues on a bond from and including the date of the previous coupon up to but excluding a date called the value date . The value date is usually, but not always, the same as the settlement date. Unlike the settlement date, the value date is not constrained to fall on a business day. $^5$

Calculation of accrued interest assumes the coupon payment takes place on the scheduled date, even if in practice it will be delayed because the scheduled date is a nonbusiness day. In the formulas below we use the settlement date rather than the value date.

The accrued interest is calculated as follows:

$$A I=c\left|\frac{\text { Number of days from last coupon payment to settlement date }}{\text { Number of days in coupon period }}\right|$$

where $AI = Accrued interest ($); $c = Semiannual coupon payment ($).

Accrued interest is not computed for all bonds. No accrued interest is computed for bonds in default and income bonds. A bond that trades without accrued interest is said to be traded "flat."

Illustration 6-10. Let's continue with the hypothetical corporate bond in Illustration 6-9. Since the number of days between settlement (July 17, 2006) and the next coupon payment (September 1, 2006) is 44 days and the number of days in the coupon period is 180, the number of days from the last coupon payment date (March 1, 2006) to the settlement date is 136 (180 – 44). The accrued interest per $ 100 of par value is

$$Al_2=\$5\frac{136}{100} =\$3.77778.$$

Illustration 6-11. If the bond in the previous illustration were a Treasury bond rather than a corporate bond, the accrued interest would be computed as follows.

7. The term "value date" is not used consistently across markets—the definition in the text is that used by the Association of International Bond Dealers (AIBD). In some markets the interest accrues up to and including a date that is called the value date. The "dated date" is the date from which accrued interest is calculated on a newly issued security.

---

CHAPTER 6 The Price of a Bond

87

The number of days in the coupon period is based on the actual number of days. Between March 1 and September 1 the actual number of days is 184. The actual number of days between March 1 and July 17 is 138. Accrued interest per $100 of par value is then

$$AI=\$5(\frac{138}{184})=\$3.75.$$

### Cum-Dividend and Ex-Dividend Trading

When the buyer receives the next coupon, the bond is said to be traded cum-dividend (or cum-coupon), and the buyer pays the seller accrued interest. If the buyer forgoes the next coupon, the bond is said to be traded ex-dividend (or ex-coupon), and the seller pays the buyer accrued interest. In some markets (the U.S. is one) bonds are always traded cum-dividend. In other markets, bonds are traded ex-dividend for a certain period before the coupon date. The last column in Exhibit 6-7 shows the practices in major bond markets throughout the world.

## PRICE BUYER PAYS AND PRICE QUOTES

The full or dirty price includes the accrued interest that the seller is entitled to receive. For example, in the calculation of the full price in Exhibit 6-8, the next coupon payment of $5 is included as part of the cash flow. The clean price or flat price is the dirty price of the bond minus the accrued interest; that is,

$$\text{Clean price}=\text{Dirty price}-\text{Accrued interest}.$$

The price that the buyer pays the seller is the dirty price. It is important to note that in calculation of the dirty price, the next coupon payment is a discounted value, but in calculation of accrued interest it is an undiscounted value. Because of this market practice, if a bond is selling at par and the settlement date is not a coupon date, the yield will be slightly less than the coupon rate. Only when the settlement date and coupon date coincide is the yield equal to the coupon rate for a bond selling at par.

In the U.S. market, the convention is to quote a bond's clean or flat price. The buyer, however, pays the seller the dirty price. In some non-U.S. markets, the dirty price is quoted.

## TAX TREATMENT OF ORIGINAL-ISSUE DISCOUNT COUPON

A bond purchased at a price less than its redemption value at maturity is said to be bought at a discount. The tax treatment of the discount depends upon whether the discount represents original-issue discount or market discount. One application of the principles presented in this chapter is calculation of the numbers that must be

---

88

PART 2 Option-Free Bonds and Conventional Yield Measures

reported under the current tax law for a bond classified as having an original-issue discount.4

When bonds are issued, they may be sold at a price that is less than their redemption value at maturity. The difference between the redemption value and the original issue price is called the original-issue discount . Zero-coupon bonds are examples of bonds that have an original-issue discount. Under the current tax law, each year a portion of the original-issue discount must be accrued and included in the taxpayer's gross income. There is a corresponding increase in the adjusted basis of the bond. $^9$

The amount of the original-issue discount amortized is based on the constantyield method (also called the effective or scientific method ) and is included in gross income based on the number of days in the tax year that bond is held. With this method for determining the amount of the original-issue discount to be included in gross income, the interest for the year is first determined by multiplying the adjusted issue price (essentially, the adjusted basis the bond would have in the hands of the first holder of the bond) by the yield to maturity at issuance. From this interest, the coupon interest is subtracted. The difference is the amount of the original-issue discount amortized for the year. The same amount is then added to the adjusted basis.

To illustrate the tax rules for original-issue discount bonds, consider a bond with a 4 % coupon rate (interest paid semiannually), maturing in 5 years, that was issued for $7,683 and has a redemption value of $10,000. The yield to maturity for this hypothetical bond is 10 % . The original-issue discount is $2,317 ( $10,000 – $7,683). Suppose that the bond was purchased by an investor on the day it was issued, January 1, Year 1. The constant-yield method is used to determine the amortization and the adjusted basis. The procedure is as follows. Every 6 months, the investor of this hypothetical bond is assumed to realize for tax purposes interest income (including accrued original-issue discount) equal to 5 % of the adjusted issue price. The 5 % represents one-half of the 10 % yield to maturity. The original issue price is the purchase price of $7,683. In the first 6 months the bond is held, the investor realizes for tax purposes interest equal to 5 % of $7,683, or $384. The coupon payment for the first 6-month period that the bond is held is $200. Therefore, $184 ( $384 – $200) is assumed to be realized (although not received) by the investor. Thus, the amount of the original-issue discount from holding this bond for 6 months is $200 in coupon interest plus the $184 of the original-issue discount amortized. The adjusted issue price for the bond at the end of the first 6 months will equal the original-issue price of $7,683 plus the amount of the original-issue discount amortized, $184. Thus, the adjusted issue price is $7,867. The bondholder's adjusted basis in

8. For a further discussion of the tax treatment for original-issue discount bonds, market discount offerings, and the use of long-term lock agreements, see Shum, T.S., and Frank, M.H., and P.A. Frank J. Fabozzi Associates, 1996, Chapter 9.

9. In the tax code, a bond's original basis in the hands of a taxpayer is the total cost on the date of the tax-exemption basis of a capital asset is its original basis minus the amortization of a discount or premium.

---

CHAPTER 6 The Price of a Bond

89

the bond (used in calculating gain or loss from sale) will also be increased by the amount of accrued original-issue discount. This way, the increase in the value of the bond (as it approaches maturity) that is included in income as accrued originalissue discount is not taxed again as capital gain.

Let's carry this out for one more 6-month period. If the bond is held for another 6 months, the amount of interest that the investor is expected to realize for tax purposes is 5 % of the adjusted issue price. Since the adjusted issue price at the beginning of the second 6-month period is $7,867, the interest is $393. The coupon interest for the second 6 months is $200. Therefore, the amount of the original-issue discount amortized for the second 6-month period is $193 ($393 - $200). The $393 reported for holding the bond for the second 6 months is $200 in coupon interest and $193 in accrued interest of the original-issue discount. The adjusted issue price at the end of the second 6-month period is $8,060—the previous adjusted issue price of $7,867 plus $193. If this bond, which was assumed to be purchased on January 1, Year 1, were sold on December 31, Year 1 (i.e., within the same year), interest income would be $777, consisting of $400 of coupon interest and $377 of the original-issue discount amortized. If this bond were sold on December 31, Year 1 for $8,200, there would be a capital gain of $140, the difference between the sale proceeds of $8,200 and the adjusted basis of $8,060.10

Exhibit 6-9 shows the amount of the original-issue discount that must be reported as gross income for each 6-month period that the bond is held and the adjusted issue price at the end of the period. Notice that accrual is lower in the earlier years, generally increasing over the life of the bond on a compounding basis.

## Special Rules

Holders of original-issue discount tax-exempt bonds need to accrue the original-issue discount by using the constant-yield method as well. However, the amount of the original-issue discount amortized is not included as part of gross income because all interest is exempt from federal income taxes. As with taxable bonds, the amount of original-issue discount accrued on a tax-exempt bond is added to its adjusted basis.

The original-issue discount rules do not apply to non-interest-bearing obli- gations such as Treasury bills and many other taxable short-term obligations with no more than 1 year to maturity at issuance. When these obligations are held by investors who report for tax purposes on a cash rather than an accrual basis, the dis- count is not recognized until the obligation is redeemed or sold.

The original issue discount is treated as zero if the discount is less than one-fourth of 1% of the redemption value at maturity multiplied by the number of

10. Because it is assumed that the investor purchased the bond at the original issuance, the bondholder's adjusted basis equals the bond's adjusted issue price. Had the bondholder purchased the bond in the secondary market, the bondholder's adjusted basis might have been greater or less than the bond's adjusted issue price.

---

90

PART 2 Option-Free Bonds and Conventional Yield Measures

EXHIBIT 6-9

<table><tr><td colspan="5">Amortization Schedule for an Original-Issue Discount Bond</td></tr><tr><td colspan="5">Characteristics of hypothetical bond</td></tr><tr><td>Coupon = 4%</td><td>Years to maturity = 5</td><td></td><td></td><td></td></tr><tr><td>Interest payments = Semiannual</td><td>Yield to maturity = 10%</td><td></td><td></td><td></td></tr><tr><td>Issue price =$7,663</td><td>Original-Issue discount =$2,317</td><td></td><td></td><td></td></tr><tr><td>Redemption value =$10,000</td><td>Basis at time of purchase =$7,683</td><td></td><td></td><td></td></tr><tr><td colspan="5">Amortization based on constant-yield method</td></tr><tr><td colspan="5">For the Period</td></tr><tr><td>Period Held (years)</td><td>Adjusted Issue Price ($)*</td><td>Gross Income Reported ($)**</td><td>Coupon Interest ($)</td><td>Original-Issue Discount Amortized ($)***</td></tr><tr><td>0.5</td><td>$7,867</td><td>$384</td><td>$200</td><td>$184</td></tr><tr><td>1.0</td><td>8,060</td><td>393</td><td>200</td><td>193</td></tr><tr><td>1.5</td><td>8,263</td><td>403</td><td>200</td><td>203</td></tr><tr><td>2.0</td><td>8,476</td><td>413</td><td>200</td><td>213</td></tr><tr><td>2.5</td><td>8,700</td><td>424</td><td>200</td><td>224</td></tr><tr><td>3.0</td><td>8,935</td><td>435</td><td>200</td><td>235</td></tr><tr><td>3.5</td><td>9,182</td><td>447</td><td>200</td><td>247</td></tr><tr><td>4.0</td><td>9,441</td><td>459</td><td>200</td><td>259</td></tr><tr><td>4.5</td><td>9,713</td><td>472</td><td>200</td><td>272</td></tr><tr><td>5.0</td><td>10,000</td><td>486</td><td>200</td><td>286</td></tr></table>


*Adjusted issue price at the end of the period. The adjusted issue price is found by adding the original-issue discount amortized for the period to the previous period's adjusted issue price. †For gross income reported is equal to the coupon interest for the period plus the original-issue discount amortized for the period. ‡By the constant-yield method, it is found as follows: (adjusted issue price at the end of the previous period x 0.05) = $200.

complete years to maturity. For example, suppose a bond maturing in 20 years is initially sold for $990 for each $1,000 of redemption value at maturity. The discount is $10. The redemption value multiplied by the number of years to maturity is $20,000. The original-issue discount is 0.0005 of $20,000. Since it is less than one-fourth of 1 % (0.0025), the original-issue discount is treated as zero; that is, the investor does not have to amortize the discount and report it as gross income.

## SUMMARY

In this chapter we have shown how to determine the price of an option-free bond. The price is simply the present value of the bond's expected cash flows, where the discount rate is equal to the yield offered on comparable bonds. For an option-free

---

92

PART 2 Option-Free Bonds and Conventional Yield Measures

bond, the cash flows are the coupon payments and the par value or maturity value.

For a zero-coupon bond, there are no coupon payments: the price is equal to the present value of the maturity value, where the number of periods used to compute the present value is double the number of years. Exhibit 6-10 summarizes the pricing formulas presented in this chapter.

The higher (lower) the required yield, the lower (higher) the price of a bond. Therefore, a bond's price changes in the direction opposite from the change in the required yield. When the coupon rate is equal to the required yield, the bond will sell at its par value. When the coupon rate is less (higher) than the required yield, the bond will sell for less (more) than its par value. A bond selling below (above) its par value is said to be selling at a discount (premium).

Over time, the price of a bond will change. Assuming the credit quality of the issuer is unchanged, the price change can be broken down into an amount attributed to a change in the required yield and an amount attributed to the time path of the bond.

When a bond is purchased between coupon payments, the buyer must pay the seller accrued interest. To calculate the accrued interest, the following must be determined: (1) number of days between the previous coupon payment and the next coupon payment and (2) present value of the coupons. The conventions for determining these vary by market sector and from country to country. The payment made by the buyer to the seller is called the dirty price. The price quoted in the U.S. is the clean price or flat price, which is equal to the dirty price minus the accrued interest.

---

CHAPTER 6 The Price of a Bond

91

## EXHIBIT 6-10

### Summary of Pricing Formulas

1. Price of an option-free bond when next coupon payment is 6 months away:

$$c=\frac{c}{(1+i)}+\frac{c}{(1+i)^{2}}+\frac{c}{(1+i)^{3}}+\cdot s+\frac{c}{(1+i)^{6}}+\frac{M}{(1+i)^{6}}$$

where

p = Price ($); c = Semiannual coupon payment ($) ; i = Periodic interest rate (required yield/2) (in decimal form); n = Number of periods (number of years times 2); M = Maturity value.

2. Present value of the coupon payments:

$$c^{1-\left[\frac{1}{(1+i)^{n}}\right]}$$

3. Price of a zero-coupon bond:

$$p=M\left[\frac{1}{(1+i)^{n}}\right]$$

where

n = 2 x N;

N = Number of years.

4. Price of a bond purchased between coupon payments with n coupon payments remaining:

$$p=\frac{c}{(1+)^{2m}}+\frac{c}{(1+)^{2m}}+\frac{c}{(1+)^{2m-1}}+\cdot s+\frac{c}{(1+)^{2m-1}m+1}+\frac{c}{(1+)^{2m-1}m+1}$$

where r = Periodic interest rate (required yield/2) [in decimal form]; w = $\frac{\text{Number of days between settlement and next coupon payment}}{\text{Number of days in the coupon period}}$; n = Number of coupon payments remaining.

5. Accrued interest:

$$Al=c\frac{\text{Number of days from last coupon payment to settlement date}}{\text{Number of days in the coupon period}}$$

where

AI = Accrued interest ($)

6. Dirty price = Full price = Present value of the bond's cash flows.

7. Clean price = Flat price = Dirty price – Accrued interest.

