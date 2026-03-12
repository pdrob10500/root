CHAPTER THIRTEEN

## DURATION AS A MEASURE OF PRICE VOLATILITY

corresponds to his length of time before the arrest is due to be reperiod.

In this chapter we discuss the most commonly used measure of bond price volatility: duration. We illustrate some applications of duration in portfolio strategies and discuss its limitations.

and discuss its limitations.

Duration is a measure of the sensitivity of the asset's price to interest rate

MACAULAY DURATION movements.

In 1938, Frederick Macaulay constructed a measure that he could use as a proxy for the length of time a bond investment was outstanding. $^1$ He referred to this number as the duration of a bond and defined it as a weighted average term to maturity of the bond's cash flows. The weights in this weighted average are the present value of each cash flow as a percent of the present value of all the bond's cash flows (i.e., the weights are the present value of each cash flow as a percent of the bond's price). As we will see, Macaulay's measure is linked to the price volatility of a bond. First, let's look at how this measure, referred to as Macaulay duration , is computed.

### “disdain” generally, n/a. Computing Macaulay Duration

Mathematically, Macaulay duration is computed as follows:

$$\begin{aligned}
&  Macaulay duration (in periods)  \\
& =\frac{(1) P V C F_{1}+(2) P V C F_{2}+(3) P V C F_{3}+\cdot s+(n) P V C F_{n}}{P V T C F},
\end{aligned}$$

where $PVCF_t$ = Present value of the cash flow in period t discounted at the prevailing period yield (in the case of a semiannual-pay bond, onehalf the yield to maturity); t = Period when the cash flow is expected to be received $(t=1,\dots,n)$;

1. Frederick Macaulay, Some Theoretical Problems Suggested by the Movements of Interest Rates, Bond Yields and Stock Prices in the United States Since 1865 (National Bureau of Economic Research, 1938).

213

---

214

PART 4 Price Volatility for Option-Free Bonds

n = Number of periods until maturity (specifically, number of years to maturity times k, rounded down to the nearest whole number);

$k = \text{Number of periods, or payments, per year (i.e., } k = 2 \text{ for semiannual-}$ pay bonds, $k = 12$ for monthly-pay bonds);

$PVTCF$ = Total present value of the cash flow of the bond, where the present value is determined by using the prevailing yield to maturity.

For an option-free bond with semiannual payments, the cash flow for periods 1 to n-1 is one-half the annual coupon interest. The cash flow in period n is the semiannual coupon interest plus the maturity value. Since the bond's price is equal to its cash flow discounted at the prevailing yield to maturity, PVTCF is the current market price plus accrued interest.

The formula for Macaulay duration gives a value in terms of periods. Dividing by the number of payments per year converts Macaulay duration to years. That is,

$$Macaulay\ duration\ (in\ years)=\frac{Macaulay\ duration\ (in\ periods)}{k}.$$

Exhibits 13-1 and 13-2 show the calculation of Macaulay duration for two of our hypothetical bonds (the 10%, 5-year bond and the 14%, 5-year bond), assuming each bond is selling to yield 10%. The Macaulay duration in years for our 12 hypothetical bonds is given below:

<table><tr><td>Bond</td><td>Macaulay Duration (years)</td></tr><tr><td>0%, 5-year</td><td>5.00</td></tr><tr><td>0%, 15-year</td><td>15.00</td></tr><tr><td>0%, 30-year</td><td>30.00</td></tr><tr><td>8%, 5-year</td><td>4.18</td></tr><tr><td>8%, 15-year</td><td>8.45</td></tr><tr><td>8%, 30-year</td><td>10.20</td></tr><tr><td>10%, 5-year</td><td>4.05</td></tr><tr><td>10%, 15-year</td><td>8.07</td></tr><tr><td>10%, 30-year</td><td>9.94</td></tr><tr><td>14%, 5-year</td><td>3.85</td></tr><tr><td>14%, 15-year</td><td>7.58</td></tr><tr><td>14%, 30-year</td><td>9.63</td></tr></table>


Note in this summary that the Macaulay duration of a coupon bond is less than its maturity. It should be obvious from the formula that the Macaulay duration

2. For example, if there are 5.2 years to maturity for a semiannual-pay bond (i.e., $k = 2$), then $n = 5.2 \times 2$ $= 10.4$.

Rounding down to the nearest whole number gives a value of 10 for n.

---

CHAPTER 13   Duration as a Measure of Price Volatility

215

EXHIBIT 13-1

Calculation of Macaulay Duration and Modified Duration for a 10%, 5-year Bond Selling to Yield 10%

<table><tr><td colspan="5">Coupon rate = 10.00%; Maturity (years) = 5; Initial yield = 10.00%.</td></tr><tr><td>Period (t)</td><td>Cash Flow ($)$^{*}</td><td>Present Value of 1 at 5%</td><td>Present Value of Cash Flow (PVCF, ($)1)</td><td>t x PVCF ()</td></tr><tr><td>1</td><td>55.00</td><td>0.952380</td><td>4.761905</td><td>4.761905</td></tr><tr><td>2</td><td>5.00</td><td>0.907029</td><td>4.535147</td><td>9.070295</td></tr><tr><td>3</td><td>5.00</td><td>0.863837</td><td>4.319188</td><td>12.957563</td></tr><tr><td>4</td><td>5.00</td><td>0.822702</td><td>4.113512</td><td>16.454049</td></tr><tr><td>5</td><td>5.00</td><td>0.783526</td><td>3.917631</td><td>19.588154</td></tr><tr><td>6</td><td>5.00</td><td>0.746215</td><td>3.731077</td><td>22.388461</td></tr><tr><td>7</td><td>5.00</td><td>0.710891</td><td>3.553407</td><td>24.873846</td></tr><tr><td>8</td><td>5.00</td><td>0.676839</td><td>3.384197</td><td>27.073574</td></tr><tr><td>9</td><td>5.00</td><td>0.644608</td><td>3.223045</td><td>29.007401</td></tr><tr><td>10</td><td>105.00</td><td>0.613913</td><td>64.460892</td><td>644.608920</td></tr><tr><td>Total</td><td></td><td></td><td>100.000000</td><td>810.782168</td></tr></table>


*Cash flow per $100 of par value.

$$ Macaulay duration (in half years) =\frac{810.782168}{100.000000}+8.11 .$$

$$Macaulay  duration (in years) =\frac{8.11}{2}=4.05 .$$

$$Modified duration (in years) =\frac{4.05}{1.0500}=3.86 .$$

of a zero-coupon bond is equal to its maturity. The lower the coupon, generally the greater the duration of the bond.$^{3}$

Notice the consistency between the properties of bond price volatility that we discussed in the previous chapter and the properties of duration. We showed that, all other factors constant, the greater the maturity, the greater the price volatility. A property of duration is that, all other factors constant, the greater the maturity, the greater the duration. We also showed that the lower the coupon rate, all other factors constant, the greater the bond price volatility. As we just noted, generally the lower the coupon rate, the greater the duration. It appears that duration is telling us something about bond price volatility.

3. This property does not necessarily hold for some long maturity deep discount coupon bonds, as explained below.

---

216

PART 4 Price Volatility for Option-Free Bonds

$$ EXHIBIT 13-2 $$

Calculation of Macaulay Duration and Modified Duration for a 14%, 5-year Bond Selling to Yield 10%

Coupon rate = 14.00%;

Maturity (years) = 5;

Initial yield = 10.00%

<table><tr><td>Period (t)</td><td>Cash Flow ($)*</td><td>Present Value of$1 at 5%</td><td>Present Value of Cash Flow (PVCF; ($) )</td><td>t × PVCF ($)</td></tr><tr><td>1</td><td>$7.00</td><td>0.952380</td><td>$6.666667</td><td>$6.666667</td></tr><tr><td>2</td><td>7.00</td><td>0.907029</td><td>6.349206</td><td>12.698412</td></tr><tr><td>3</td><td>7.00</td><td>0.863837</td><td>6.046863</td><td>18.140589</td></tr><tr><td>4</td><td>7.00</td><td>0.822702</td><td>5.758917</td><td>23.035669</td></tr><tr><td>5</td><td>7.00</td><td>0.783526</td><td>5.484683</td><td>27.423415</td></tr><tr><td>6</td><td>7.00</td><td>0.746215</td><td>5.232508</td><td>31.341046</td></tr><tr><td>7</td><td>7.00</td><td>0.710861</td><td>4.974769</td><td>34.823385</td></tr><tr><td>8</td><td>7.00</td><td>0.676839</td><td>4.737876</td><td>37.903004</td></tr><tr><td>9</td><td>7.00</td><td>0.644608</td><td>4.512262</td><td>40.510361</td></tr><tr><td>10</td><td>107.00</td><td>0.613913</td><td>65.686718</td><td>656.887180</td></tr><tr><td>Total</td><td></td><td></td><td>$115.443470</td><td>$889.529728</td></tr></table>


*Cash flow per $100 of par value.

$$ Macaulay duration (in half years) =\frac{889.529728}{115.443470}=7.71 .$$

$$Macaulay\ duration\ (in\ years)=\frac{7.71}{2}=3.85.$$

$$Modified duration (in years) =\frac{3.85}{1.0000}=3.67 .$$

## Short-Cut Formulas for Macaulay Duration

Mathematically, Macaulay duration for a semiannual-pay bond can be shown to be equivalent to: $^{4}$

$$Macaulay duration (in 6-month periods) =\left[\frac{1+y}{y}\right] H+\left[\frac{y-c}{y}\right] n(1-H),$$

4. The mathematical proof is given in Frank J. Fabozzi, Bond Markets, Analysis and Strategies (Englewood Cliffs, NJ: Prentice-Hall, 1993, 2nd ed), pp. 70-71.

---

CHAPTER 13   Duration as a Measure of Price Volatility

217

where

$y$ = One-half the yield; $H$ = Ratio of the present value of the annuity of the semiannual coupon payments to the price of the bond; $c$ = One-half the annual coupon rate.

From Chapter 4, the present value of the semiannual coupon payments is:

$$100c\left[1-\frac{\left(\frac{1}{(1+y)^{2}}\right)}{y}\right]$$

Illustration 13-1. We can use the formula above to calculate Macaulay duration for the 14 % coupon bond with 5 years to maturity, selling to yield 10 % , by inserting the values:

$$\begin{aligned}
& y=0.05(0.10 / 2) ; \\
& c=0.07(0.14 / 2) ; \\
& n=10(5 \times 2) .
\end{aligned}$$

The price of this bond is $115.44 (see Exhibit 12-1 of Chapter 12). The present value of the coupon payments is

$$\begin{aligned}
&100(0.07)\left\{\frac{1-\left[\left(\dfrac{1}{(0.5)^{10}}\right)\right]}{0.05}\right\}\\
&=7\left\{\frac{1-0.613913}{0.05}\right\}\\
&=54.05.
\end{aligned}$$

Then,

$$H=\frac{554.05}{8155.44}=0.4682$$

$$ and $$

$$\begin{array} { r l } & {  M a c a u l a y ~ d u r a t i o n ~ ( i n ~ 6 - m o n t h ~ p e r i o d s )  } \\ & { \quad = \frac { 1 . 0 5 } { 0 . 0 5 } ( 0 . 4 6 8 2 ) + \left( \frac { 0 . 0 5 - 0 . 0 7 } { 0 . 0 5 } \right) ( 1 0 ) ( 1 - 0 . 4 6 8 2 ) } \\ & { \quad = 2 1 ( 0 . 4 6 8 2 ) + ( - 0 . 4 0 ) ( 1 0 ) ( 0 . 5 3 1 8 ) } \\ & { \quad = 9 . 8 3 2 2 - 2 . 1 2 7 2 } \\ & { \quad = 7 . 7 0 5 . } \end{array}$$

Dividing by 2 to give Macaulay duration in years, we have 3.85. Notice that this agrees with the Macaulay duration calculated for this bond in Exhibit 13-2.

---

218

PART 4 Price Volatility for Option-Free Bonds

When a bond is selling at par, c is equal to y. The formula for Macaulay duration then reduces to

$$Macaulay duration for a bond selling at par (in 6-month periods) =\left(\frac{1+y}{y}\right) H .$$

Illustration 13-2. In the formula for the Macaulay duration for a bond selling at par, the numbers needed to calculate Macaulay duration for the 10% coupon bond with 5 years to maturity selling to yield 10% are

$$y=0.05(0.10 / 2) ;$$

$$c=0.05(0.10 / 2) ;$$

$$n=10(5\times2).$$

The present value of the coupon payments is

$$\begin{array}{rcl}
$100(0.05)\left\{\dfrac{1-\left[\dfrac{1}{(1.05)^{10}}\right]}{0.05}\right\}&=&38.61.
\end{array}$$

Then,

$$H=\frac{538.61}{S100}=0.3861$$

$$ and $$

$$\begin{aligned}
 Macaulay duration (in 6-month periods)  & =\frac{1.05}{0.05}(0.3861) \\
& =21(0.3861) \\
& =8.1081 .
\end{aligned}$$

Dividing by 2 gives 4.05, the Macaulay duration in years. This result agrees with the calculation of Macaulay duration in Exhibit 13-1.

For a zero-coupon bond, the present value of the coupon payments is obviously zero, thus $H$ is zero. The Macaulay duration for a zero-coupon bond in 6-month periods is

$$\begin{array} { r } { \left( \frac { 1 + y } { y } \right) H + \left( \frac { y - c } { y } \right) \eta ( 1 - H ) = \left( \frac { 1 + y } { y } \right) 0 + \left( \frac { y - 0 } { y } \right) \eta ( 1 - 0 ) } \\ { = 0 + \left( \frac { y } { y } \right) \eta } \\ { = \eta . } \end{array}$$

---

CHAPTER 13   Duration as a Measure of Price Volatility

219

Thus we see that the Macaulay duration of a zero-coupon bond in periods is just the number of 6-month periods. Dividing by 2 gives the term of the bond in years.

## LINK BETWEEN DURATION AND BOND PRICE VOLATILITY

Now that we know how to compute Macaulay duration, how do we interpret it? Some investors continue to think of duration in the context in which it was developed by Macaulay—as a measure of the length of time a bond investment is outstanding. Forget it! The significance and interpretation of Macaulay duration lie in its link to bond price volatility.

The link between bond price volatility and Macaulay duration can be shown to be as follows: $^2$

$$Approximate percentage change in price$$
=-\left[\frac{1}{(1+y)}\right]\times Macaulay duration \times Yield change,$$

$$ where $$

$y=One-half\ the\ yield\ to\ maturity.$

Generally, the first two terms are combined, and the resulting measure is called modified duration; that is,

$$Modified\ duration=\frac{Macaulay\ duration}{(1+y)}.$$

The relationship can then be expressed as

$$\begin{array} { r } { A p p r o x i m e t e ~ p e r c e n t a g e ~ c h a n g e ~ i n ~ p r i c e } \\ { = - M o d i f i e d ~ d u r a t i o n \times Y i e l d ~ c h a n g e . } \end{array}$$

Illustration 13-3. Consider the 8%, 15-year bond selling at $4.63 to yield 10%. The Macau duration for this bond is 8.45. Modified duration is 8.05:

$$Modified\ duration=\frac{8.45}{(1.05)}=8.05.$$

If the yield increases instantaneously from 10.00% to 10.10%, a yield change of +0.0010, the approximate percentage change in price is

$$-8.05\times (+0.0010)=-0.00805=-0.81\%.$$

5. Mathematically, this relationship is derived from the first term of a Taylor series of the price function.

---

220

PART 4 Price Volatility for Option-Free Bonds

Exhibit 12-4 in Chapter 12 shows that the actual percentage change in price is -0.80%. Similarly, if the yield decreases instantaneously from 10.00% to 9.90% (a 10 basis point decrease), the approximate change in price would be +0.81%. Exhibit 12-4 shows that the actual percentage price change would be +0.80%. This example illustrates that for small changes in yield, modified duration provides a good approximation of percentage change in price.

Illustration 13-4. Instead of a small change in yield, let's assume that yields increase by 300 basis points, from 10% to 13% (a yield change of +0.03). The approximate percentage change in price estimated using modified duration would be

$$-8.05\times(+0.03)=-0.2415=24.15\%.$$

How good is this approximation? As can be seen from Exhibit 12–4 in Chapter 12 the actual percentage change in price is only ~20.41%. Moreover, if the yield decreases by 300 basis points, from 10% to 7%, the approximate percentage change in price based on duration would be +24.15%, compared to an actual percentage change in price of +29.03%. Thus, not only is the approximation off, but we can see that modified duration estimates a symmetric percentage change in price, which, as we pointed out in Chapter 12, is not a property of the price/yield relationship for bonds.

Exhibit 13–3 shows the estimated percentage change in price using modified duration for our 12 hypothetical bonds. The difference between the actual percentage price change, as reported in Exhibit 12–4 , and the estimated percentage change in price using modified duration, as reported in Exhibit 13–3 , is shown in Exhibit 13–4 . The property that we just illustrated — that modified duration gives a good estimate of the percentage price change for small changes in yield but a poor estimate for large changes — can be seen in Exhibit 13–4 . The percentage price change not explained by modified duration increases the greater the change in yield. For some bonds, however, the approximation is in error by less than others. For example, for the 14 % , 30-year bond, the unexplained percentage price change for a 300 basis point increase is 5.5 % , while for the zero-coupon bond of the same maturity it is 28.41 % .

The reason that modified duration provides a good approximation for small changes in yield but a poor approximation for large changes in yield lies in the convex shape of the price/yield relationship. This point is examined fully in the next chapter.

## Modified Duration as a Measure of Percentage Price Change per 100 Basis Point Yield Change

Ignoring the direction of the change in yield, for a 100 basis point change in yield, the percentage change in the bond's price is

$$Modified duration $\times(0.01)$.$$

---

EXHIBIT 13-2 Percentage Change in Price Estimated Using Modified Duration

<table><thead><tr><th>Coupon (%)</th><th>Term (years)</th><th>Duration (years)</th><th>Yield Change (in basis points) from 10%</th></tr></thead><tbody><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td><td></td></tr><tr><td></td

---

$$ EXHIBIT 13-3 $$

Percentage Change in Price Estimated Using Modified Duration (Continued)

<table><tr><td rowspan="3"></td><td rowspan="3">Term (years)</td><td rowspan="3">Modified Duration (years)</td><td colspan="6">Yield Change (in basis points) from 10%</td></tr><tr><td>-1</td><td>-10</td><td>-50</td><td>-100</td><td>-200</td><td>-300</td></tr><tr><td colspan="6">New Yield Level</td></tr><tr><td>Coupon (%)</td><td>5</td><td>4.76</td><td>9.99%</td><td>9.90%</td><td>9.50%</td><td>9.00%</td><td>8.00%</td><td>7.00%</td></tr><tr><td>0.00%</td><td>15</td><td>14.29</td><td>0.14</td><td>1.43</td><td>7.15</td><td>14.29</td><td>28.58</td><td>42.87</td></tr><tr><td>0.00</td><td>30</td><td>28.57</td><td>0.29</td><td>2.86</td><td>14.29</td><td>28.57</td><td>57.14</td><td>85.71</td></tr><tr><td>8.00</td><td>5</td><td>3.98</td><td>0.04</td><td>0.40</td><td>1.99</td><td>3.98</td><td>7.96</td><td>11.94</td></tr><tr><td>8.00</td><td>15</td><td>8.05</td><td>0.08</td><td>0.81</td><td>4.03</td><td>8.05</td><td>16.10</td><td>24.15</td></tr><tr><td>8.00</td><td>30</td><td>9.72</td><td>0.10</td><td>0.97</td><td>4.86</td><td>9.72</td><td>19.44</td><td>29.16</td></tr><tr><td>10.00</td><td>5</td><td>3.86</td><td>0.04</td><td>0.39</td><td>1.93</td><td>3.86</td><td>7.72</td><td>11.58</td></tr><tr><td>10.00</td><td>15</td><td>7.69</td><td>0.08</td><td>0.77</td><td>3.85</td><td>7.69</td><td>15.38</td><td>23.07</td></tr><tr><td>10.00</td><td>30</td><td>9.46</td><td>0.09</td><td>0.95</td><td>4.73</td><td>9.46</td><td>18.92</td><td>28.38</td></tr><tr><td>14.00</td><td>5</td><td>3.67</td><td>0.04</td><td>0.37</td><td>1.84</td><td>3.67</td><td>7.34</td><td>11.01</td></tr><tr><td>14.00</td><td>15</td><td>7.22</td><td>0.07</td><td>0.72</td><td>3.61</td><td>7.22</td><td>14.44</td><td>21.66</td></tr><tr><td>14.00</td><td>30</td><td>9.17</td><td>0.09</td><td>0.92</td><td>4.59</td><td>9.17</td><td>18.34</td><td>27.51</td></tr></table>


222

---

EXHIBIT 13-4

Percentage Price Change Not Explained by Modified Duration

<table><tr><td rowspan="2"></td><td rowspan="2"></td><td rowspan="2"></td><td colspan="6">Yield Change (in basis points) from 10%</td></tr><tr><td>1</td><td>10</td><td>50</td><td>100</td><td>200</td><td>300</td></tr><tr><td>Coupon (%)</td><td>Term (years)</td><td>Modified Duration (years)</td><td>10.01%</td><td>10.10%</td><td>10.50%</td><td>11.00%</td><td>12.00%</td><td>13.00%</td></tr><tr><td>0.00%</td><td>5</td><td>4.76</td><td>0.00%</td><td>0.00%</td><td>0.03%</td><td>0.12%</td><td>0.48%</td><td>1.06%</td></tr><tr><td>0.00%</td><td>15</td><td>14.29</td><td>0.00%</td><td>0.01</td><td>0.26</td><td>1.01</td><td>3.83</td><td>8.21</td></tr><tr><td>0.00%</td><td>30</td><td>28.57</td><td>0.00%</td><td>0.04</td><td>0.99</td><td>3.77</td><td>13.76</td><td>28.41</td></tr><tr><td>8.00%</td><td>5</td><td>3.98</td><td>0.00%</td><td>0.00%</td><td>0.02</td><td>0.10</td><td>0.38</td><td>0.83</td></tr><tr><td>8.00%</td><td>15</td><td>8.05</td><td>0.00%</td><td>0.00%</td><td>0.12</td><td>0.45</td><td>1.73</td><td>3.74</td></tr><tr><td>8.00%</td><td>30</td><td>9.72</td><td>0.00%</td><td>0.01</td><td>0.20</td><td>0.78</td><td>2.92</td><td>6.15</td></tr><tr><td>10.00%</td><td>5</td><td>3.86</td><td>0.00%</td><td>0.00%</td><td>0.02</td><td>0.09</td><td>0.36</td><td>0.80</td></tr><tr><td>10.00%</td><td>15</td><td>7.69</td><td>0.00%</td><td>0.00%</td><td>0.11</td><td>0.42</td><td>1.62</td><td>3.48</td></tr><tr><td>10.00%</td><td>30</td><td>9.46</td><td>0.00%</td><td>0.01</td><td>0.19</td><td>0.74</td><td>2.76</td><td>5.83</td></tr><tr><td>14.00%</td><td>5</td><td>3.67</td><td>0.00%</td><td>0.00%</td><td>0.02</td><td>0.09</td><td>0.34</td><td>0.75</td></tr><tr><td>14.00%</td><td>15</td><td>7.22</td><td>0.00%</td><td>0.00%</td><td>0.10</td><td>0.38</td><td>1.45</td><td>3.14</td></tr><tr><td>14.00%</td><td>30</td><td>9.17</td><td>0.00%</td><td>0.01</td><td>0.18</td><td>0.69</td><td>2.60</td><td>5.50</td></tr></table>


223

---

$$ EXHIBIT 13-4 $$

Percentage Price Change Not Explained by Modified Duration (Continued)

<table><tr><td rowspan="3"></td><td rowspan="3">Term (years)</td><td rowspan="3">Modified Duration (years)</td><td colspan="6">Yield Change (in basis points) from 10%</td></tr><tr><td>-1</td><td>-10</td><td>-50</td><td>-100</td><td>-200</td><td>-300</td></tr><tr><td colspan="6">New Yield Level</td></tr><tr><td>Coupon (%)</td><td>5</td><td>4.76</td><td>9.99%</td><td>9.90%</td><td>9.50%</td><td>9.00%</td><td>8.00%</td><td>7.00%</td></tr><tr><td>0.00%</td><td>15</td><td>14.29</td><td>0.00%</td><td>0.00%</td><td>0.03%</td><td>0.13%</td><td>0.52%</td><td>1.20%</td></tr><tr><td>0.00</td><td>30</td><td>28.57</td><td>0.00%</td><td>0.01</td><td>0.27</td><td>1.11</td><td>4.67</td><td>11.11</td></tr><tr><td>8.00</td><td>5</td><td>3.98</td><td>0.00%</td><td>0.00%</td><td>1.09</td><td>4.59</td><td>20.43</td><td>51.39</td></tr><tr><td>8.00</td><td>15</td><td>8.05</td><td>0.00%</td><td>0.00%</td><td>0.03</td><td>0.10</td><td>0.41</td><td>0.93</td></tr><tr><td>8.00</td><td>30</td><td>9.72</td><td>0.00%</td><td>0.01</td><td>0.12</td><td>0.49</td><td>2.06</td><td>4.88</td></tr><tr><td>10.00</td><td>5</td><td>3.86</td><td>0.00%</td><td>0.00%</td><td>0.02</td><td>0.10</td><td>3.91</td><td>9.57</td></tr><tr><td>10.00</td><td>15</td><td>7.69</td><td>0.00%</td><td>0.00%</td><td>0.11</td><td>0.45</td><td>1.91</td><td>4.52</td></tr><tr><td>10.00</td><td>30</td><td>9.46</td><td>0.00%</td><td>0.01</td><td>0.21</td><td>0.86</td><td>3.70</td><td>9.04</td></tr><tr><td>14.00</td><td>5</td><td>3.67</td><td>0.00%</td><td>0.00%</td><td>0.02</td><td>0.09</td><td>0.36</td><td>0.83</td></tr><tr><td>14.00</td><td>15</td><td>7.22</td><td>0.00%</td><td>0.00%</td><td>0.10</td><td>0.41</td><td>1.72</td><td>4.06</td></tr><tr><td>14.00</td><td>30</td><td>9.17</td><td>0.00%</td><td>0.01</td><td>0.19</td><td>0.79</td><td>3.43</td><td>8.36</td></tr></table>


224

---

CHAPTER 13   Duration as a Measure of Price Volatility

225

For example, if the modified duration is 6, the approximate percentage change in the bond's price for a 100 basis point change in yield is

$$6\times(0.01)=0.06\text{ or }6\%.$$

Thus, a bond with a modified duration of 6 would change by approximately 6% for a 100 basis point (1%) change in yield. Similarly, a bond with a modified duration of X would change by approximately X% for a 100 basis point change in yield. For this reason, some investors refer to modified duration as the approximate percentage price change of a bond per 100 basis point change in yield. So, for example, a bond with a modified duration of 5.4 will change by approximately 5.4% for a 100 basis point change in yield. For a 50 basis point change in yield, the approximate percentage price change would then be half of 5.4%, or 2.7%. For a 10 basis point change in yield, the approximate percentage price change would be one-tenth of 5.4%, or 0.54%.

## Dollar Duration

The modified duration of a bond can be used to approximate the percentage change in price for a given change in yield. Similarly, the dollar price change can be approximated given the bond's modified duration, the bond's price, and a specified number of basis points. The dollar price change is referred to as dollar duration .

The dollar duration of a basis point change in yield can be calculated as follows:

$$Dollar duration of a basis point =\frac{ Modified duration  \times  Price }{10,000} .$$

For example, consider an 8% coupon, 15-year bond selling to yield 10%. The price of this bond per $100 par value is $84,6275. The bond's modified duration is 8.05. Therefore,

$$Dollar duration of a basis point =\frac{8.05 \times 584.6275}{10,000}=$$0.068125$$

To find the dollar duration for more than one basis point, the dollar duration of a basis point is simply multiplied by the number of basis points. For example, for a 50 basis point change in yield, the dollar duration would be $3.40625.

If the dollar duration for a par value different from $100 is sought, then the dollar duration per $100 par value must be scaled appropriately. For example, in our previous example if $1 million is the par value, then the market value of the bond is $8,462,750. The dollar duration of a basis point is $6,812.51.

It should be noted that there is no standard terminology used for dollar duration. More specifically, some market participants refer to "dollar duration" when they mean the "dollar duration of a basis point." In our example, the dollar duration would then be $0.0681, since this is the dollar duration of one basis point. The

---

226

PART 4 Price Volatility for Option-Free Bonds

dollar duration of a basis point is equivalent to the price value of a basis point that we discussed in the previous chapter. Some market participants refer to the dollar duration in terms of the dollar duration of 100 basis points. In our example, the dollar duration would then be $6.81.

How good an estimate of the dollar price change is given by dollar duration? For small changes in yield, it will be good, as we saw in Illustration 13–3 , where modified duration is used to estimate the percentage price change. For large changes in yield, the approximation is not as good. Recall from Illustration 13–4 that when the yield increases by 300 basis points, the estimated percentage decline in price is greater than the actual decline in price. This means that the estimated dollar price decline will be greater than the actual price decline, so that the estimated new price is less than the actual price at a higher yield. Also in Illustration 13–4 , the estimated percentage price increase is less than the actual price increase when the yield declines by 300 basis points. The actual price increase, therefore, is underestimated using modified duration, and the estimated price at a lower yield will be less than the actual price. Thus, whether the yield rises or falls by a large number of basis points, modified duration and dollar duration will underestimate what the new price will be. A graphical explanation for this fact is given in the next chapter.

## PORTFOLIO DURATION

A portfolio's modified duration can be obtained by calculating the weighted average of the modified duration of the bonds in the portfolio. The weight is the proportion of the portfolio that a security comprises. Mathematically, a portfolio's modified duration can be calculated as follows:

$$w_{1}D_{1}+w_{2}D_{2}+w_{3}D_{3}+\cdot s+w_{K}D_{K},$$

where

$w_{i}=$ Market value of bond i/market value of the portfolio;

$D_{i}=$ Modified duration of bond i;

$K=$ Number of bonds in the portfolio.

Each term of an individual bond's weight and its modified duration has a special meaning. It is the bond's contribution to portfolio duration. That is,

$$Contribution to portfolio duration for bond $i=w_{i} D_{i}$,$$

In the same way that a portfolio's modified duration can be computed using each bond in the portfolio, it can also be computed from the market value in each sector.

To illustrate the calculation of a portfolio's modified duration, consider the hypothetical portfolio shown in Exhibit 13–5. The portfolio has 20 bonds and a market value of $ 300 million. Column (4) shows the weights and the last column

---

CHAPTER 13   Duration as a Measure of Price Volatility

227

EXHIBIT 13-5

<table><tr><td colspan="6">Illustration of the Calculation of Portfolio Duration</td></tr><tr><td>(1) Bond</td><td>(2) Mark Value (3) Duration D</td><td>(4) Weight W</td><td>(5) Contribution to Portfolio Duration D $\times$ W</td><td></td><td></td></tr><tr><td>1</td><td>25,000,000</td><td>5.21</td><td>0.0833</td><td>0.4342</td><td></td></tr><tr><td>2</td><td>15,533,000</td><td>6.26</td><td>0.0518</td><td>0.3241</td><td></td></tr><tr><td>3</td><td>18,294,000</td><td>4.27</td><td>0.0610</td><td>0.2604</td><td></td></tr><tr><td>4</td><td>29,426,000</td><td>7.15</td><td>0.0981</td><td>0.7013</td><td></td></tr><tr><td>5</td><td>2,892,000</td><td>2.14</td><td>0.0096</td><td>0.0206</td><td></td></tr><tr><td>6</td><td>8,971,000</td><td>3.16</td><td>0.0299</td><td>0.0945</td><td></td></tr><tr><td>7</td><td>29,760,000</td><td>3.75</td><td>0.0992</td><td>0.3720</td><td></td></tr><tr><td>8</td><td>3,290,000</td><td>8.26</td><td>0.0110</td><td>0.0906</td><td></td></tr><tr><td>9</td><td>12,389,000</td><td>6.85</td><td>0.0413</td><td>0.2829</td><td></td></tr><tr><td>10</td><td>2,905,000</td><td>9.11</td><td>0.0097</td><td>0.0882</td><td></td></tr><tr><td>11</td><td>8,129,000</td><td>2.87</td><td>0.0271</td><td>0.0778</td><td></td></tr><tr><td>12</td><td>19,788,000</td><td>6.42</td><td>0.0660</td><td>0.4235</td><td></td></tr><tr><td>13</td><td>22,800,000</td><td>10.17</td><td>0.0760</td><td>0.7729</td><td></td></tr><tr><td>14</td><td>16,549,000</td><td>4.55</td><td>0.0552</td><td>0.2510</td><td></td></tr><tr><td>15</td><td>14,236,000</td><td>2.58</td><td>0.0475</td><td>0.1224</td><td></td></tr><tr><td>16</td><td>24,500,000</td><td>4.77</td><td>0.0817</td><td>0.3896</td><td></td></tr><tr><td>17</td><td>1,908,000</td><td>1.13</td><td>0.0064</td><td>0.0072</td><td></td></tr><tr><td>18</td><td>23,987,000</td><td>3.75</td><td>0.0800</td><td>0.2998</td><td></td></tr><tr><td>19</td><td>11,200,000</td><td>1.65</td><td>0.0373</td><td>0.0616</td><td></td></tr><tr><td>20</td><td>8,443,000</td><td>0.95</td><td>0.0281</td><td>0.0267</td><td></td></tr><tr><td>Total</td><td>500,000,000</td><td>—</td><td>1.0000</td><td>5.1013</td><td></td></tr></table>


shows the contribution to portfolio duration of each bond. The total shown in the last row of the last column is the portfolio duration, 5.10.

A portfolio modified duration of 5.10 means that for a 100 basis point change in the yield for all 20 bonds, the market value of the portfolio will change by approximately 5.10%. But keep in mind that the yield on all 20 bonds must change by 100 basis points for the modified duration measure to be useful. This is a critical assumption and its importance cannot be overemphasized. We shall return to this point in Chapter 15.

## Portfolio Duration for a Global Portfolio

Many global money managers calculate a duration for a portfolio consisting of bonds with cash flows denominated in several currencies. For example, a U.S. portfolio

---

228

PART 4 Price Volatility for Option-Free Bonds

manager who has a portfolio of U.S. Treasury securities denominated in U.S. dollars, German government bonds denominated in euros, Japanese government bonds denominated in yen, and British government bonds denominated in pounds sterling might calculate a Macaulay duration and a modified duration for the portfolio. The question is what does a portfolio modified duration in such cases mean?

Since modified duration is a measure of the percentage price volatility of a bond to changes in yield, what yield is modified duration measuring price sensitivity to? U.S. yields, German yields, Japanese yields or British yields? There is no answer to this question. Using the modified duration measure as discussed thus far in this chapter for a global portfolio is of questionable value.

## APPROXIMATING DURATION

Since modified duration is a measure of the price sensitivity of a bond to interest rate changes, it can be approximately by simply changing yields by a small amount up and down, and then looking at how the price changes. More specifically, let

$V_{0}=$ Initial value or price of the security; $\Delta y=$ Change in the yield of a security; $V_{c}=$ Estimated value of the security if the yield is decreased by $\Delta y$; $V_{e}=$ Estimated value of the security if the yield is increased by $\Delta y$.

Then for a decrease in yield, the percentage price change is

$$\frac{V_{-}-V_{0}}{V_{0}} .$$

The percentage price change per basis point change is found by dividing the percentage price change by the number of basis points $(\Delta y \times 100)$. That is,

$$\frac{V_{-}-V_{0}}{V_{0}(\Delta y) 100}$$

Similarly, the percentage price change per basis point increase in yield is

$$\frac{V_{0}-V_{+}}{V_{+}(\Delta y) 100}$$

As explained in the previous chapter, the percentage price change for an increase and decrease in interest rates will not be the same. Consequently, the average percentage price change per basis point change in yield can be calculated. This is done as follows:

$$\frac { 1 } { 2 } \left[ \frac { V _ { - } - V _ { + } } { \Delta ( \lambda ) } l l 0 0 + \frac { V _ { 0 } - V _ { + } } { \Delta ( \lambda ) } l l \lambda \right]$$

---

CHAPTER 13 Duration as a Measure of Price Volatility

229

or, equivalently,

$$\frac{V_{s}-V_{s}}{2 V_{0}(\Delta y) 100} .$$

The approximate percentage price change for a 100 basis point change in yield is found by multiplying the previous formula by 100:

$$Approximate duration = \frac{V_{c} \Delta t}{2V_{0}(\Delta y)}$$

To illustrate this formula for approximating modified duration, consider a 20-year, 7% coupon bond selling at $74.26 to yield 10%. Suppose we evaluate the price changes for a 20 basis point change up and down. Then,

$$V_{-}=75.64 ,$$

$$V_{+}=72.92 ;$$

$$V_{0}=74.26 ;$$

$$\Delta y=0.002 .$$

Substituting into the formula:

$$\frac{75.64-72.92}{(24.726 \pm  0.002)}=9.16 .$$

The modified duration for this bond calculated using the formula presented earlier in this chapter is 9.18 .

## Effective Duration

The approximation formula above is important when we analyze bonds that are not option-free in later chapters; that is, when the bonds are putable or callable. Modified duration is not a good measure of the price sensitivity of such bonds to yield changes because it assumes that yield changes will not change the expected cash flows of a bond. For example, when a bond is callable, a decline in market yields may change the expected cash flows of the bond since it may increase the likelihood that the bond is called. In the case of mortgage-backed securities—the subject of Part 7 of this book—a change in market yields will change prepayments of borrowers.

In such instances where the cash flow is interest-rate sensitive (interest-ratedependent), the price sensitivity of a bond to yield changes must take into consideration how yield changes affect the expected cash flows and, in turn, the price of a bond. A duration measure that does allow for changes in cash flows as yields change is called an effective duration . The formula we gave above for approximating the modified duration is the formula that is used to calculate the effective duration

---

230

PART 4 Price Volatility for Option-Free Bonds

of a bond. We shall see how this formula is used for bonds with interest-rate sensitive cash flows in later chapters.

## APPLICATIONS

### Dollar Duration Weighting of Yield Spread Swap Strategies

A common active bond portfolio strategy is to position a portfolio to capitalize on expectations regarding the yield spread between sectors in the market. It is critical when assessing yield spread strategies to compare positions that have the same dollar duration. To understand why, consider two bounds, X and Y. Suppose that the price of bond X is $80 and has a modified duration of 5 while bond Y has a price of $90 and has a modified duration of 4. Since modified duration is the approximate percentage change per 100 basis point change in yield, a 100 basis points change in yield for bond X would change its price by about 5 % . Based on a price of $80, its price will change by about $4 per $80 of market value. Thus, its dollar duration for a 100 basis point change in yields is $4 per $80 of market value. Similarly, for bond Y, its dollar duration for a 100 basis point change in yield per $90 of market value can be determined. In this case it is $3.6. So, if bonds X and Y are being considered as alternative investments in some strategy other than one based on anticipating interest-rate movements, the amount of each bond in the strategy should be such that they will both have the same dollar duration.

To illustrate this, suppose that a portfolio manager owns $10 million of par value of bond X which has a market value of $8 million. The dollar duration of bond X per 100 basis point change in yield for the $8 million market value is $400,000. Suppose further that this portfolio manager is considering exchanging bond X that it owns in its portfolio for bond Y. If the portfolio manager wants to have the same interest-rate exposure (i.e., dollar duration) for bond Y that she currently has for bond X, she will buy a market value amount of bond Y with the same dollar duration. If the portfolio manager purchased $10 million of par value of bond Y and therefore $9 million of market value of bond Y, the dollar price change per 100 basis point change in yield would be only $360,000. If, instead, the portfolio manager purchased $10 million of market value of bond Y, the dollar duration per 100 basis point change in yield would be $400,000. Since bond Y is trading at $90, $11.11 million of par value of bond Y must be purchased to keep the dollar duration of the position for bond Y the same as for bond X.

Mathematically, this problem can be expressed as follows:

Let:


$D_{X}$ = Dollar duration per 100 basis point change in yield for bond X for the market value of bond X held;

$MD_{Y}$ = Modified duration for bond Y; $MV_{Y}$ = Market value of bond Y needed to obtain the same dollar duration as bond X.


1

---

CHAPTER 13 Duration as a Measure of Price Volatility

231

Then, the following equation sets the dollar duration for bond X equal to the dollar duration for bond Y:

$$SD_{X}=(MD_{Y}/100)MV_{Y}.$$

Solving for $MV_{Y_1}$,

$$MV_{Y}=SD_{X}/(MD_{Y}/100),$$

Dividing by the price per $1 of par value of bond Y gives the par value of bond Y that has an approximately equivalent dollar duration as bond X.

In our illustration, $D_{X}$ is $400,000 and $MD_{Y}$ is 4, so

$$MY_{Y}=\$400,000/(4/100)=\$10,000,000.$$

Since the market value of bond Y is $90 per $100 of par value, the price per $1 of par value is $0.9. Dividing $10 million by 0.9 indicates that the par value of bond Y that should be purchased is $11.11 million.

Failure to adjust a portfolio repositioning based on some expected change in yield spread so as to hold the dollar duration the same means that the outcome of the portfolio will be affected by not only the expected change in the yield spread but also a change in the yield level. Thus, a manager would be making a conscious yield spread bet and possibly an undesired bet on the level of interest rates.

## Using Dollar Duration to Compute the Hedge Ratio

Modified duration is related to percentage price volatility. As explained in the previous chapter, in hedging we are interested in dollar price changes. Consequently, to compute the hedge ratio using duration, dollar duration should be used, not modified duration. The hedge ratio is computed from dollar duration as follows:

$$\begin{aligned}
&  Dollar duration for bond to be hedged  \\
&  Dollar duration for hedging vehicle 
\end{aligned} \times  Yield beta.$$

Recall that the dollar duration per basis point per $100 of par value is the same as the price value of a basis point. Therefore, dollar duration will produce the same hedge ratio as the price value of a basis point.

## Role of Duration in Immunization Strategies

In Chapter 9, we explained that the return that is realized by investing in a coupon security will depend on the interest rate earned on the reinvestment of the coupon payments. When interest rates rise, interest on interest from the reinvestment of the coupon payments will be higher, but if the investment horizon is shorter than the maturity of the bond, a loss will be realized upon the sale of the bond. The reverse is true if interest rates fall: price appreciation will be realized when the bond is sold, but interest on interest from reinvesting the coupon payments will be lower. Because of these two risks, the investor cannot be assured of locking in the yield at the time of purchase.

---

232

PART 4 Price Volatility for Option-Free Bonds

Because interest-rate risk and reinvestment risk offset each other, however, is it possible to select a bond or bond portfolio that will lock in the yield at the time of purchase regardless of interest rate changes in the future? That is, is it possible to immunize the bond or bond portfolio against interest rate changes? Fortunately, under certain circumstances, it is. This can be accomplished by constructing a portfolio so that its Macaulay duration is equal to the length of the investment horizon. Thus, a portfolio manager with an investment horizon of 5 years who wants to lock in a return over that time period should select a portfolio with a Macaulay duration of 5 years. This is demonstrated using an example.

Suppose a portfolio manager knows that a liability of $17,183,033 must be~paid in 5.5 years. Also suppose that interest rates are currently 12.5% on a bond-~equivalent basis. The present value of the $17,183,033 liability 5.5 years from now~assuming interest can be earned at a rate of 6.25% per 6-month period is $8,820,262.~Thus, if the portfolio manager invested $8,820,262 at the current rate of 6.25% per 6-month period for the next 11 6-month periods, the accumulated value would be sufficient to satisfy the liability.

Suppose the portfolio manager buys $8,820,262 par value of a bond selling at par with a 12.5% yield to maturity that matures in 5.5 years. The Macaulay duration for this bond is 4.14 years, which is shorter than the length of the investment horizon. Will the portfolio manager be assured of realizing the target yield of 12.5% or, equivalently, a target accumulated value of $17,183,033? As we explained in Chapter 7, the portfolio manager will realize a 12.5% yield only if the coupon interest payments can be reinvested at 6.25% every 6 months. That is, the accumulated value will depend on the reinvestment rate.

To illustrate this, suppose that immediately after investing the $8,820,262 in the 12.5% coupon, 5.5-year maturity bond, yields in the market change and stay at the new level for the remainder of the 5.5 years. Exhibit 13–6 illustrates what happens at the end of 5.5 years. The first column shows the new yield. The second column shows the total coupon interest payments. The third column gives the interest on interest over the entire 5.5 years if the coupon interest payments are reinvested at the new yield shown in the first column. The price of the bond at the end of 5.5 years, shown in the fourth column, is the par value. The fifth column is the accumulated value from all three sources: coupon interest, interest on interest, and price of bond. The total return is shown in the last column.

When yields do not change, so that the coupon payments can be reinvested at 12.5% (6.25% every 6 months), the target accumulated value will be achieved by the portfolio manager. If market yields rise, an accumulated value (total return) higher than the target accumulated value (target yield) will be achieved, because the coupon interest payments can be reinvested at a rate higher than the initial yield to maturity. Contrast this circumstance with what happens when the yield declines. The accumulated value (total return) will be less than the target accumulated value (target yield). Therefore, investing in a coupon bond with a yield to maturity equal to the target yield and a maturity equal to the investment horizon does not assure that the target accumulated value will be achieved.

---

EXHIBIT 13-6

Accumulated Value and Total Return 5.5-Year, 12.5% Coupon Bond Selling to Yield 12.5%

<table><tr><td colspan="6">Investment horizon (years) = 5.5; Coupon rate = 12.5%; Maturity (years) = 5.50; Yield to maturity = 12.5%; Price = 100,00000; Par value purchased =$8,820,262; Purchase price =$8,820,262; Target accumulated value =$17,183,033.</td></tr><tr><td rowspan="2">New Yield (%)</td><td colspan="5">Over 5.5 Years</td></tr><tr><td>Coupon ($)</td><td>Interest on Interest ($)</td><td>Price of Bond ($)</td><td>Accumulated Value ($)</td><td>Total Return (%)</td></tr><tr><td>16.0%</td><td>$6,063,930</td><td>$3,112,167</td><td>$8,820,262</td><td>$17,996,360</td><td>13.40%</td></tr><tr><td>15.5</td><td>$6,063,930</td><td>$2,990,716</td><td>$8,820,262</td><td>$17,874,908</td><td>13.26</td></tr><tr><td>14.5</td><td>$6,063,930</td><td>$2,753,177</td><td>$8,820,262</td><td>$17,637,369</td><td>13.00</td></tr><tr><td>14.0</td><td>$6,063,930</td><td>$2,637,037</td><td>$8,820,262</td><td>$17,521,230</td><td>12.88</td></tr><tr><td>13.5</td><td>$6,063,930</td><td>$2,522,618</td><td>$8,820,262</td><td>$17,406,810</td><td>12.75</td></tr><tr><td>13.0</td><td>$6,063,930</td><td>$2,409,894</td><td>$8,820,262</td><td>$17,294,086</td><td>12.62</td></tr><tr><td>12.5</td><td>$6,063,930</td><td>$2,298,840</td><td>$8,820,262</td><td>$17,183,033</td><td>12.50</td></tr><tr><td>12.0</td><td>$6,063,930</td><td>$2,189,433</td><td>$8,820,262</td><td>$17,073,625</td><td>12.38</td></tr><tr><td>11.5</td><td>$6,063,930</td><td>$2,081,648</td><td>$8,820,262</td><td>$16,965,840</td><td>12.25</td></tr><tr><td>11.0</td><td>$6,063,930</td><td>$1,975,462</td><td>$8,820,262</td><td>$16,859,654</td><td>12.13</td></tr></table>


233

---

$$ EXXIBIT 13-6 $$

Accumulated Value and Total Return (Continued)

<table><tr><td rowspan="2">New Yield (%)</td><td colspan="5">Over 5.5 Years</td></tr><tr><td>Coupon ($)</td><td>Interest on Interest ($)</td><td>Price of Bond ($)</td><td>Accumulated Value ($)</td><td>Total Return (%)</td></tr><tr><td>10.5%</td><td>$6,063,930</td><td>$1,870,852</td><td>$8,820,262</td><td>$16,755,044</td><td>12.01%</td></tr><tr><td>10.0</td><td>$6,063,930</td><td>1,767,794</td><td>$8,820,262</td><td>16,651,986</td><td>11.89</td></tr><tr><td>9.5</td><td>$6,063,930</td><td>1,666,266</td><td>$8,820,262</td><td>16,550,458</td><td>11.78</td></tr><tr><td>9.0</td><td>$6,063,930</td><td>1,566,246</td><td>$8,820,262</td><td>16,450,438</td><td>11.66</td></tr><tr><td>8.5</td><td>$6,063,930</td><td>1,476,712</td><td>$8,820,262</td><td>16,351,904</td><td>11.54</td></tr><tr><td>8.0</td><td>$6,063,930</td><td>1,370,642</td><td>$8,820,262</td><td>16,254,834</td><td>11.43</td></tr><tr><td>7.5</td><td>$6,063,930</td><td>1,275,014</td><td>$8,820,262</td><td>16,158,206</td><td>11.32</td></tr><tr><td>7.0</td><td>$6,063,930</td><td>1,180,808</td><td>$8,820,262</td><td>16,065,000</td><td>11.20</td></tr><tr><td>6.5</td><td>$6,063,930</td><td>1,088,003</td><td>$8,820,262</td><td>15,972,195</td><td>11.09</td></tr><tr><td>6.0</td><td>$6,063,930</td><td>996,577</td><td>$8,820,262</td><td>15,880,769</td><td>10.96</td></tr><tr><td>5.5</td><td>$6,063,930</td><td>906,511</td><td>$8,820,262</td><td>15,790,703</td><td>10.87</td></tr><tr><td>5.0</td><td>$6,063,930</td><td>817,785</td><td>$8,820,262</td><td>15,701,977</td><td>10.77</td></tr></table>


234

---

CHAPTER 13 Duration as a Measure of Price Volatility

235

Suppose that instead of investing in a bond maturing in 5.5 years, the portfolio manager invests in a 15-year bond with a coupon rate of 12.5% and selling at par to yield 12.5%. The Macaulay duration for this bond is 7.12 years, which is longer than the 5.5-year investment horizon. The accumulated value and total return if the market yield changes immediately after the bond is purchased and remains at the new yield are presented in Exhibit 13–7. The fourth column in Exhibit 13–7 is the market price of a 12.5% coupon, 9.5-year bond (since 5.5 years have passed), assuming that the market yield is as shown in the first column. If the market yield increases, the portfolio will fail to achieve the target accumulated value; the opposite is true if the market yield decreases—the accumulated value (total return) will exceed the target accumulated value (target yield).

The reason for this result can be seen in Exhibit 13–8 , which summarizes the change in interest on interest and the change in price resulting from a change in the market yield. For example, if the market yield rises instantaneously by 200 basis points, from 12.5% to 14.5%, interest on interest will be $ 454,336 greater; the market price of the bond, however, will decrease by $ 894,781. The net effect is that the accumulated value will be $ 440,445 less than the target accumulated value. The reverse is true if the market yield decreases: the change in the price of the bond will more than offset the decline in the interest on interest, resulting in an accumulated value that exceeds the target accumulated value. Exhibit 13–8 clearly demonstrates the trade-off between interest-rate (or price) risk and reinvestment risk.

Consider an 8-year, 10.125% coupon bond selling at $88,20262 to yield 12.5 % , which has a Macaulay duration of 5.5 years. Suppose $10,000,000 of par value of this bond is purchased for $8,820,262. For this bond, Exhibit 13–9 provides the same information as Exhibits 13–6 and 13–7. Looking at the last two columns, we see that the accumulated value and the total return are never less than the target accumulated value and the target yield. Thus, the target accumulated value is assured regardless of what happens to the market yield. Exhibit 13–10 shows why. When the market yield rises, the change in the interest on interest more than offsets the decline in price. On the other hand, when the market yield declines, the increase in price exceeds the decline in interest on interest.

Notice that the last bond, which assures that the target accumulated value will be achieved regardless of what happens to the market yield, has a Macaulay duration equal to the length of the investment horizon. This is the key. To immunize a portfolio's target accumulated value (target yield) against a change in the market yield, a portfolio manager must invest in a bond (or a bond portfolio) such that (1) the Macaulay duration is equal to the investment horizon, 6 and (2) the present value of the cash flow from the bond (or bond portfolio) equals the present value of the liability.

6. This is equivalent to equating the modified duration of the portfolio to the modified duration of the investment horizon. This is because the Macaulay duration of the liability is the length of the investment horizon and dividing by one plus one-half the yield to maturity gives a modified duration that is the same as the portfolio.

---

EXHIBIT 13-7

Accumulated Value and Total Return

15-Year, 12.5% Coupon Bond Selling to Yield 12.5%

<table><tr><td colspan="6">Investment horizon (years) = 5.5;</td></tr><tr><td>Coupon rate = 12.5%;</td><td>Maturity (years) = 15;</td><td>Yield to maturity = 12.5%;</td><td>Price =$100,00000;</td><td>Par value purchased =$8,820,262;</td><td>Purchase price =$8,820,262;</td></tr><tr><td colspan="6">Target accumulated value =$17,183,033.</td></tr><tr><td rowspan="2">New Yield (%)</td><td colspan="5">Over 5.5 Years</td></tr><tr><td>Coupon ($)</td><td>Interest on Interest ($)</td><td>Price of Bond ($)</td><td>Accumulated Value ($)</td><td>Total Return (%)</td></tr><tr><td>16.0%</td><td>$6,063,930</td><td>$3,112,167</td><td>$7,337,902</td><td>$16,514,000</td><td>11.73%</td></tr><tr><td>15.5</td><td>$6,063,930</td><td>2,990,716</td><td>7,526,488</td><td>16,581,134</td><td>11.81</td></tr><tr><td>14.5</td><td>$6,063,930</td><td>2,753,177</td><td>7,925,481</td><td>16,742,587</td><td>12.00</td></tr><tr><td>14.0</td><td>$6,063,930</td><td>2,637,037</td><td>8,136,542</td><td>16,837,510</td><td>12.11</td></tr><tr><td>13.5</td><td>$6,063,930</td><td>2,522,618</td><td>8,355,777</td><td>16,942,325</td><td>12.23</td></tr><tr><td>13.0</td><td>$6,063,930</td><td>2,409,894</td><td>8,583,555</td><td>17,057,379</td><td>12.36</td></tr><tr><td>12.5</td><td>$6,063,930</td><td>2,298,840</td><td>8,820,262</td><td>17,183,033</td><td>12.50</td></tr><tr><td>12.0</td><td>$6,063,930</td><td>2,189,433</td><td>9,066,306</td><td>17,319,669</td><td>12.65</td></tr><tr><td>11.5</td><td>$6,063,930</td><td>2,081,648</td><td>9,322,113</td><td>17,467,691</td><td>12.82</td></tr><tr><td>11.0</td><td>$6,063,930</td><td>1,975,462</td><td>9,588,131</td><td>17,627,523</td><td>12.99</td></tr><tr><td>10.5</td><td>$6,063,930</td><td>1,870,852</td><td>9,864,831</td><td>17,799,613</td><td>13.18</td></tr></table>


236

---

<table><tr><td></td><td>10.0</td><td>6,063,930</td><td>1,767,794</td><td>10,152,708</td><td>17,984,432</td><td>13.38</td></tr><tr><td></td><td>9.5</td><td>6,063,930</td><td>1,666,266</td><td>10,452,281</td><td>18,182,477</td><td>13.59</td></tr><tr><td></td><td>9.0</td><td>6,063,930</td><td>1,566,246</td><td>10,764,095</td><td>18,394,271</td><td>13.82</td></tr><tr><td></td><td>8.5</td><td>6,063,930</td><td>1,467,712</td><td>11,088,723</td><td>18,620,366</td><td>14.06</td></tr><tr><td></td><td>8.0</td><td>6,063,930</td><td>1,370,642</td><td>11,426,770</td><td>18,861,342</td><td>14.31</td></tr><tr><td></td><td>7.5</td><td>6,063,930</td><td>1,275,014</td><td>11,778,867</td><td>19,117,812</td><td>14.57</td></tr><tr><td></td><td>7.0</td><td>6,063,930</td><td>1,180,808</td><td>12,145,682</td><td>19,390,420</td><td>14.85</td></tr><tr><td></td><td>6.5</td><td>6,063,930</td><td>1,088,003</td><td>12,527,914</td><td>19,679,847</td><td>15.14</td></tr><tr><td></td><td>6.0</td><td>6,063,930</td><td>996,577</td><td>12,926,301</td><td>19,986,808</td><td>15.44</td></tr><tr><td></td><td>5.5</td><td>6,063,930</td><td>906,511</td><td>13,341,617</td><td>20,312,058</td><td>15.76</td></tr><tr><td></td><td>5.0</td><td>6,063,930</td><td>817,785</td><td>13,774,677</td><td>20,656,393</td><td>16.09</td></tr></table>


237

---

238

PART 4 Price Volatility for Option-Free Bonds

EXHIBIT 13-8

Change in Interest on Interest and Price due to Interest Rate Change 15-Year, 12.5% Coupon Bond Selling to Yield 12.5%

<table><tr><td>New Yield (%)</td><td>Change in Interest on Interest ($)</td><td>Change in Price ($)</td><td>Total Change in Accumulated Value ($)</td></tr><tr><td>16.0%</td><td>$813,327</td><td>-$1,482,360</td><td>-$669,033</td></tr><tr><td>15.5</td><td>691,875</td><td>-1,293,774</td><td>-601,898</td></tr><tr><td>14.5</td><td>454,336</td><td>-894,781</td><td>-440,445</td></tr><tr><td>14.0</td><td>338,197</td><td>-683,720</td><td>-345,523</td></tr><tr><td>13.5</td><td>223,778</td><td>-464,485</td><td>-240,707</td></tr><tr><td>13.0</td><td>111,054</td><td>-236,707</td><td>-125,654</td></tr><tr><td>12.5</td><td>0</td><td>0</td><td>0</td></tr><tr><td>12.0</td><td>-109,407</td><td>246,044</td><td>136,636</td></tr><tr><td>11.5</td><td>-217,192</td><td>501,851</td><td>284,659</td></tr><tr><td>11.0</td><td>-323,378</td><td>767,869</td><td>444,491</td></tr><tr><td>10.5</td><td>-427,989</td><td>1,044,569</td><td>616,581</td></tr><tr><td>10.0</td><td>-531,046</td><td>1,332,446</td><td>801,400</td></tr><tr><td>9.5</td><td>-632,574</td><td>1,632,019</td><td>999,445</td></tr><tr><td>9.0</td><td>-732,594</td><td>1,943,833</td><td>1,211,239</td></tr><tr><td>8.5</td><td>-831,128</td><td>2,268,461</td><td>1,437,333</td></tr><tr><td>8.0</td><td>-928,198</td><td>2,606,508</td><td>1,678,309</td></tr><tr><td>7.5</td><td>-1,023,826</td><td>2,958,605</td><td>1,934,779</td></tr><tr><td>7.0</td><td>-1,118,032</td><td>3,325,420</td><td>2,207,388</td></tr><tr><td>6.5</td><td>-1,210,838</td><td>3,707,852</td><td>2,496,814</td></tr><tr><td>6.0</td><td>-1,302,263</td><td>4,106,039</td><td>2,803,776</td></tr><tr><td>5.5</td><td>-1,392,329</td><td>4,521,355</td><td>3,129,026</td></tr><tr><td>5.0</td><td>-1,481,055</td><td>4,954,415</td><td>3,473,360</td></tr></table>


In this example, we assume a one-time instantaneous change in the market yield. In practice, the market yield will fluctuate over the investment horizon. As a result, the Macaulay duration of the portfolio will change as the market yield changes. In addition, the Macaulay duration will change with the passage of time. In the face of changing market yields, a manager can still immunize a portfolio by rebalancing it so that the Macaulay duration of the portfolio is equal to the remainder of the investment horizon. For example, if the investment horizon is initially 5.5 years, the initial portfolio should have a Macaulay duration of 5.5 years. After 6 months, the remaining investment horizon is 5 years. The Macaulay duration then will probably be different from 5 years. Thus the portfolio must be rebalanced so that its Macaulay duration is equal to 5 years. Six months later, the portfolio must be rebalanced so that its Macaulay duration is equal to 4.5 years, etc.

---

EXHIBIT 13-9

Accumulated Value and Total Return 8-Year, 10.125% Coupon Bond Selling to Yield 12.5%

<table><tr><td rowspan="2">w Yield (%)</td><td colspan="5">Over 5.5 Years</td></tr><tr><td>Coupon ($)</td><td>Interest on Interest ($)</td><td>Price of Bond ($)</td><td>Accumulated Value ($)</td><td>Total Return (%)</td></tr><tr><td>16.0%</td><td>$5,568,750</td><td>$2,858,028</td><td>$8,827,141</td><td>$17,253,919</td><td>12.58%</td></tr><tr><td>15.5</td><td>5,568,750</td><td>2,746,494</td><td>8,919,852</td><td>17,235,096</td><td>12.56</td></tr><tr><td>14.5</td><td>5,568,750</td><td>2,528,352</td><td>9,109,054</td><td>17,206,158</td><td>12.53</td></tr><tr><td>14.0</td><td>5,568,750</td><td>2,421,697</td><td>9,205,587</td><td>17,196,034</td><td>12.51</td></tr><tr><td>13.5</td><td>5,568,750</td><td>2,316,621</td><td>9,303,435</td><td>17,188,807</td><td>12.51</td></tr><tr><td>13.0</td><td>5,568,750</td><td>2,213,102</td><td>9,402,621</td><td>17,184,473</td><td>12.50</td></tr><tr><td>12.5</td><td>5,568,750</td><td>2,111,117</td><td>9,503,166</td><td>17,183,033</td><td>12.50</td></tr><tr><td>12.0</td><td>5,568,750</td><td>2,010,644</td><td>9,605,091</td><td>17,184,485</td><td>12.50</td></tr><tr><td>11.5</td><td>5,568,750</td><td>1,911,661</td><td>9,708,420</td><td>17,188,831</td><td>12.51</td></tr><tr><td>11.0</td><td>5,568,750</td><td>1,814,146</td><td>9,813,175</td><td>17,196,071</td><td>12.51</td></tr><tr><td>10.5</td><td>5,568,750</td><td>1,718,078</td><td>9,919,380</td><td>17,206,208</td><td>12.53</td></tr></table>


239

---

EXHIBIT 13-9

Accumulated Value and Total Return (Continued)

<table><tr><td colspan="6">Over 5.5 Years</td></tr><tr><td>New Yield (%)</td><td>Coupon ($)</td><td>Interest on Interest ($)</td><td>Price of Bond ($)</td><td>Accumulated Value ($)</td><td>Total Return (%)</td></tr><tr><td>10.0%</td><td>$5,568,750</td><td>$1,623,436</td><td>$10,027,059</td><td>$17,219,245</td><td>12.54%</td></tr><tr><td>9.5</td><td>$5,568,750</td><td>1,530,199</td><td>10,136,236</td><td>17,235,185</td><td>12.56</td></tr><tr><td>9.0</td><td>$5,568,750</td><td>1,438,347</td><td>10,246,936</td><td>17,254,033</td><td>12.58</td></tr><tr><td>8.5</td><td>$5,568,750</td><td>1,347,859</td><td>10,359,184</td><td>17,275,793</td><td>12.60</td></tr><tr><td>8.0</td><td>$5,568,750</td><td>1,258,715</td><td>10,473,006</td><td>17,300,472</td><td>12.63</td></tr><tr><td>7.5</td><td>$5,568,750</td><td>1,170,897</td><td>10,586,428</td><td>17,328,075</td><td>12.66</td></tr><tr><td>7.0</td><td>$5,568,750</td><td>1,084,383</td><td>10,705,477</td><td>17,358,610</td><td>12.70</td></tr><tr><td>6.5</td><td>$5,568,750</td><td>999,156</td><td>10,824,180</td><td>17,392,086</td><td>12.73</td></tr><tr><td>6.0</td><td>$5,568,750</td><td>915,197</td><td>10,944,565</td><td>17,428,511</td><td>12.77</td></tr><tr><td>5.5</td><td>$5,568,750</td><td>832,486</td><td>11,086,660</td><td>17,467,895</td><td>12.82</td></tr><tr><td>5.0</td><td>$5,568,750</td><td>751,005</td><td>11,190,494</td><td>17,510,248</td><td>12.86</td></tr></table>


1

---

CHAPTER 13 Duration as a Measure of Price Volatility

241

EXHIBIT 13-10

Change in Interest on Interest and Price due to Interest-Rate Change 8-Year, 10.125% Coupon Bond Selling to Yield 12.5%

<table><tr><td>New Yield (%)</td><td>Change in Interest on Interest ($)</td><td>Change in Price ($)</td><td>Total Change In Accumulated Value ($)</td></tr><tr><td>16.0%</td><td>$746,911</td><td>-$676,024</td><td>$70,987</td></tr><tr><td>15.5</td><td>635,377</td><td>-583,314</td><td>52,063</td></tr><tr><td>14.5</td><td>417,235</td><td>-394,112</td><td>23,123</td></tr><tr><td>14.0</td><td>310,580</td><td>-297,579</td><td>13,001</td></tr><tr><td>13.5</td><td>205,504</td><td>-199,730</td><td>5,774</td></tr><tr><td>13.0</td><td>101,985</td><td>-100,544</td><td>1,441</td></tr><tr><td>12.5</td><td>0</td><td>0</td><td>0</td></tr><tr><td>12.0</td><td>-100,473</td><td>101,925</td><td>1,452</td></tr><tr><td>11.5</td><td>-199,456</td><td>205,254</td><td>5,798</td></tr><tr><td>11.0</td><td>-296,971</td><td>310,010</td><td>13,038</td></tr><tr><td>10.5</td><td>-393,039</td><td>416,215</td><td>23,176</td></tr><tr><td>10.0</td><td>-487,681</td><td>523,894</td><td>36,212</td></tr><tr><td>9.5</td><td>-580,918</td><td>633,071</td><td>52,153</td></tr><tr><td>9.0</td><td>-672,770</td><td>743,771</td><td>71,000</td></tr><tr><td>8.5</td><td>-763,258</td><td>856,019</td><td>92,760</td></tr><tr><td>8.0</td><td>-852,402</td><td>969,841</td><td>117,439</td></tr><tr><td>7.5</td><td>-940,221</td><td>1,085,263</td><td>145,042</td></tr><tr><td>7.0</td><td>-1,026,734</td><td>1,202,311</td><td>175,578</td></tr><tr><td>6.5</td><td>-1,111,961</td><td>1,321,014</td><td>209,053</td></tr><tr><td>6.0</td><td>-1,195,921</td><td>1,441,399</td><td>245,478</td></tr><tr><td>5.5</td><td>-1,278,632</td><td>1,563,494</td><td>284,962</td></tr><tr><td>5.0</td><td>-1,360,112</td><td>1,687,328</td><td>327,216</td></tr></table>


Constructing a portfolio so that its Macaulay duration is equal to the investment horizon will assure that the target yield will be realized only if the yields on all bonds change by the same amount. For example, if short-term yields fall but long-term yields rise, then the offsetting of interest rate risk and reinvestment risk by matching duration will not work. A decline in short-term yields will reduce reinvestment income, while a rise in long-term rates will result in a capital loss of bonds with a maturity greater than the investment horizon. This risk of failing to immunize can be reduced, however.?

7. See H. Gifford Fong and Oldrich Vasicek, "A Risk Minimizing Strategy for Multiple Liability Immunization," Journal of Finance (December 1984), pp. 1541-1546. For a less technical description, see H. Gifford Fong and Frank J. Fabozzi, Fixed Income Portfolio Management (Homewood, IL: Don Jones-Irinus, 1985), pp. 133-136.

---

242

PART 4 Price Volatility for Option-Free Bonds

## Duration of an Interest-Rate Swap

As explained in Chapter 2, an interest-rate swap is an agreement whereby two parties (called counterparties) agree to exchange periodic interest payments. The dollar amount of the interest payments exchanged is based on some predetermined dollar principal, which is called the notional amount . The dollar amount each counterparty pays to the other is the agreed-upon periodic interest rate times the notional amount. The only dollars that are exchanged between the parties are the interest payments, not the notional amount. In the most common type of swap, one party agrees to pay the other party fixed interest payments at designated dates for the life of the contract. This party is referred to as the fixed-rate payer . The other party agrees to make interest-rate payments that float with some reference rate and is referred to as the fixed-rate receiver .

For example, suppose that for the next 5 years party X agrees to pay party Y 10% per year, while party Y agrees to pay party X 6-month LIBOR. Party X is a fixed-rate payer, while party Y is a fixed-rate receiver. Assume that the notional amount is $50 million, and that payments are exchanged every 6 months for the next 5 years. This means that every 6 months, party X (the fixed-rate payer) will pay party Y $2.5 million (10% times $50 million divided by 2). The amount that party Y (the fixed-rate receiver) will pay party X will be 6-month LIBOR times $50 million divided by 2. For example, if 6-month LIBOR is 7%, party Y will pay party X $1.75 million (7% times $50 million divided by 2). Note that we divide by two because one-half year's interest is being paid.

Interest rate benchmarks commonly used for the floating rate in an interestrate swap are those on various money market instruments: Treasury bills, London interbank offered rate (LIBOR), commercial paper, bankers acceptance, certificates of deposit, federal funds rate, and prime rate.

One way to interpret an interest-rate swap position is as a package of cash flows from buying and selling cash market instruments. To understand why, consider the following. Suppose that an investor enters into the following transaction:

- • Buys $50 million par of a 5-year floating-rate bond that pays 6-month
LIBOR every 6 months;

• Finances the purchase of the 5-year floating-rate bond by borrowing
$50 million for 5 years with the following terms: 10% annual interest
rate paid every 6 months.
The cash flow of this transaction is presented in Exhibit 13–11 . The second column of the exhibit sets out the cash flow from purchasing the 5-year floatingrate bond. There is a $50 million cash outlay and then cash inflows. The amount of the cash inflows is uncertain because they depend on future LIBOR. The third column shows the cash flow from borrowing $50 million on a fixed-rate basis. The last column shows the net cash flow from the entire transaction. As can be seen in the last column, there is no initial cash flow (no cash inflow or cash outlay). In all

---

CHAPTER 13 Duration as a Measure of Price Volatility

243

$$ EXHIBIT 13-11 $$

Cash Flow for the Purchase of a 5-Year Floating-Rate Bond Financed by Borrowing on a Fixed-Rate Basis

<table><tr><td colspan="4">Transaction: Purchase for$50 million a 5-year floating-rate bond: floating rate = LIBOR, semiannual pay; Borrow$50 million for 5 years; fixed rate = 10%, semiannual payments.</td></tr><tr><td>6-Month Period</td><td>Floating-Rate Bond</td><td>Borrowing Cost</td><td>Net</td></tr><tr><td>0</td><td>-$50</td><td>+$50.0</td><td>$0</td></tr><tr><td>1</td><td>+(LIBOR/2) × 50</td><td>-2.5</td><td>+(LIBOR/2) × 50 - 2.5</td></tr><tr><td>2</td><td>+(LIBOR/2) × 50</td><td>-2.5</td><td>+(LIBOR/2) × 50 - 2.5</td></tr><tr><td>3</td><td>+(LIBOR/2) × 50</td><td>-2.5</td><td>+(LIBOR/2) × 50 - 2.5</td></tr><tr><td>4</td><td>+(LIBOR/2) × 50</td><td>-2.5</td><td>+(LIBOR/2) × 50 - 2.5</td></tr><tr><td>5</td><td>+(LIBOR/2) × 50</td><td>-2.5</td><td>+(LIBOR/2) × 50 - 2.5</td></tr><tr><td>6</td><td>+(LIBOR/2) × 50</td><td>-2.5</td><td>+(LIBOR/2) × 50 - 2.5</td></tr><tr><td>7</td><td>+(LIBOR/2) × 50</td><td>-2.5</td><td>+(LIBOR/2) × 50 - 2.5</td></tr><tr><td>8</td><td>+(LIBOR/2) × 50</td><td>-2.5</td><td>+(LIBOR/2) × 50 - 2.5</td></tr><tr><td>9</td><td>+(LIBOR/2) × 50</td><td>-2.5</td><td>+(LIBOR/2) × 50 - 2.5</td></tr><tr><td>10</td><td>+(LIBOR/w/2) × 50 + 50</td><td>-52.5</td><td>+(LIBOR/w/2) × 50 - 2.5</td></tr></table>


Note: The subscript for LIBOR indicates the 6-month LIBOR as per the terms of the floating-rate bond at time t.

ten 6-month periods the net position results in a cash inflow of LIBOR and a cash outlay of $2.5 million. This net position, however, is identical to the position of a fixed-rate payer.

It can be seen from the net cash flow in Exhibit 13–11 that a fixed-rate payer has a cash market position that is equivalent to a long position in a floating-rate bond and borrowing the funds to purchase the floating-rate bond on a fixed-rate basis. But the borrowing can be viewed as issuing a fixed-rate bond, or equivalently, being short a fixed-rate bond. Consequently, the position of a fixed-rate payer can be viewed as being long a floating-rate bond and short a fixed-rate bond.

What about the position of a floating-rate payer? It can be easily demonstrated that the position of a fixed-rate receiver is equivalent to purchasing a fixed-rate bond and financing that purchase at a floating rate, with the floating rate being the reference interest rate for the swap. That is, the position of a fixed-rate receiver is equivalent to a long position in a fixed-rate bond and a short position in a floating-rate bond.

As with any fixed income contract, the dollar value of a swap will change as interest rates change. Duration is a measure of the sensitivity of a bond's price to

---

244

PART 4 Price Volatility for Option-Free Bonds

a change in interest rates. From the perspective of the party who pays floating and receives fixed, the position can be viewed as follows:

$$Long a fixed-rate bond + Short a floating-rate bond.$$

This means that the dollar duration of an interest-rate swap from the perspective of a fixed-rate receiver is just the difference between the dollar duration of the two bond positions that make up the swap. That is,

$$\begin{aligned}
&  Dollar duration of a swap  \\
& = Dollar duration of a fixed-rate bond  \\
&  - Dollar duration of a floating-rate bond. 
\end{aligned}$$

Most of the interest rate sensitivity of a swap will result from the dollar dura- tion of the fixed-rate bond since the dollar duration of the floating-rate bond will be small. It will always be less than the length of time to the next reset date. Therefore, the duration of a floating-rate bond for which the coupon rate resets every 6 months will be less than 6 months. The dollar duration of a floating-rate bond is smaller, the closer the swap is to its reset date.

## SPREAD DURATION

Another duration measure commonly cited is spread duration. For a given benchmark, spread duration is the approximate percentage change in the bond's price for a 100 basis point change in the yield spread. For example, a spread duration for a bond of 1.8 means that for a 100 basis point change in the bond's yield spread, the bond's price will change by approximately 1.8 % .

A spread duration can be further qualified based on the risk factor that causes the yield spread. For example, for a particular corporate bond issue, the spread may be due primarily to credit risk. Hence, the spread duration is labeled credit spread duration . However, a portion of the yield spread could also be due to an issue being callable. One of the objectives of fixed income analysis is to separate the spread duration attributable to changes in the credit spread and that due to the yield spread because of the call option embedded in an issue.

For agency mortgage-backed securities, discussed in Part 7 of this book, credit risk is minimal and as a result, the spread duration reflects the change in the yield spread sought by the market to compensate for prepayment risk. For nonagency mortgage-backed securities and residential asset-backed securities, part of the spread duration is due to credit risk and part is due to prepayment risk.

The spread duration for a portfolio is found by computing a market weighted average of the spread duration for each bond. For a portfolio, the spread duration is the sensitivity of portfolio to the change in the yield spread for all spread sectors included in the portfolio. The same is true for the spread duration for a bond index; that is, it is the sensitivity of a portfolio to the change in the yield spread for the sectors (or bonds) included in the bond index.

---

CHAPTER 13 Duration as a Measure of Price Volatility

245

## 1997年

Modified duration measures the percentage price change for a 100 basis point change in rates. Dollar duration indicates the dollar price change. To assess the potential price risk of a portfolio, it is necessary to assess the volatility of yields themselves. For example, high-yield bonds (so-called junk bonds) trade at higher yield levels than same-maturity Treasury bonds. Given the properties of duration discussed in this chapter, this means that a Treasury bond would have a higher modified duration than a high-yield bond. Does this mean that high-yield bonds expose investors to less interest-rate risk? The answer is no. How much price volatility a portfolio will be exposed to depends on how volatile yields are. Since high-yield bonds have greater yield volatility (i.e., spreads to Treasuries change even when Treasury yields are unchanged), it would not be correct to say that there is less potential price volatility despite a lower duration.

Similarly, in Switzerland, 10-year government bonds trade at lower yields than U.S. 10-year government bonds. Thus, Swiss government bonds have a higher duration. However, the volatility of 10-year Swiss government bonds in Switzerland is less than that of 10-year U.S. government bonds. Consequently, there is greater potential price volatility for 10-year U.S. government bonds despite the lower duration.

The key to understanding the price volatility of a portfolio is to look not only at duration but yield volatility. We postpone our discussion of this topic to Chapter 26.

## FINAL NOTE ON DURATION

In this chapter and in several other instances in this book, duration is stated in terms of temporal terms (e.g., "a duration of 5 years" or "a duration in half years"). While this is common practice in the industry, describing duration in temporal terms has lead to confusion in the marketplace. Here are three examples.

First, there are securities whose duration exceeds their final maturity. Some portfolio managers have viewed a duration that exceeds its final maturity as an error and substitute their own estimate of what the duration should be. The estimate was considerably lower than the true duration. For the funds managed by these portfolio managers, particularly funds claiming to be limited duration funds (i.e., duration between 1 and 3), performance was astoundingly good when interest rates declined; however, performance was disastrous for clients/fund shareholders when interest rates rose, leading to lawsuits and SEC administrative sanctions.

Second, portfolio managers and clients who view duration in temporal terms find it difficult to understand why a long position in a security could have a negative duration. If one thinks about duration in terms of its link to price volatility when interest rates change, one understands that a negative duration means a security whose price moves in the same direction as the change in interest rates.

Consequently, while it is correct to state the duration of a security or portfolio in terms of years, it is the author's preference to avoid the use of years. That

---

246

PART 4 Price Volatility for Option-Free Bonds

is, I prefer to state the duration for a security or portfolio as "X" rather than "X years" and interpret duration in terms of the approximate percentage price change rather than some present-value weighted average of the cash flows.

Moreover, it is also common to refer to duration as the "first derivative" of the price/yield relationship. This is because the formula for duration for an optionfree security can be obtained by computing the first derivative of the price/yield relationship. As we will see when we describe how to analyze securitized products and bonds with embedded options later in this book, there is no closed-form solution to obtain the value of a security. Hence, no closed-form equation for the first derivative is available.

## SUMMARY

In this chapter we have discussed a popular measure of price volatility called duration. Macaulay duration is related to price volatility and is commonly used as some measure of the weighted-average term-to-maturity of the bond's cash flows. Modified duration is the approximate percentage price change of a bond for a 100 basis point change in interest rates. Dollar duration is a measure of the dollar price change of a bond to changes in interest rates; for a one-basis-point change in yield, dollar duration is equal to the price value of a basis point.

A portfolio's modified duration is found by computing the weighted-average modified duration of all the bonds in the portfolio, where a particular bond's weight is the market value of the bond relative to the market value of the portfolio.

There are several problems with duration as a measure of the sensitivity of a bond or a portfolio to changes in yield:

- 1. Duration does a good job of estimating the sensitivity of a bond or port-
folio to small changes in yield only. This is due to the convex shape of
the price/yield relationship.
2. A portfolio's duration is a good measure of price sensitivity only if the
yields of all bonds in the portfolio change by the same amount.
3. For a portfolio consisting of bonds denominated in multiple currencies,
modified duration as conventionally calculated does not provide insight
into the price sensitivity of the portfolio to interest-rate changes.
4. For bonds with interest-rate-sensitive cash flows, modified duration is
inappropriate since it assumes that cash flows will not change as yields
change. A more appropriate measure in such instances is effective
duration.
In the next chapter, we will take a look at the first problem. In Chapter 15, we will look at the second problem. Finally, when we look at bonds with embedded options, we will focus on the last problem.

There are several applications of duration: dollar duration weighting trades, determining the hedge ratio, immunizing a portfolio against interest rate changes, and determining the duration of an interest-rate swap.

