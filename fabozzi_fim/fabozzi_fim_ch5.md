CHAPTER FIVE

## YIELD (INTERNAL RATE OF RETURN)

![Figure](figures/fabozzi_fim_ch5_page_001_figure_002.png)

In the previous chapter we showed how to use present value to determine whether a financial instrument provides a minimum annual interest rate specified by an investor. For example, if the present value of the promised future value payments of some financial instrument selling for $944.14 is $1,039.57 when discounted at 9%, then the investment offers an annual interest rate greater than 9%. But how much greater? What yield will the investor earn by buying the financial instrument for $944.14? The purpose of this chapter is to explain how to compute the yield on any investment.

### COMPUTING THE YIELD ON ANY INVESTMENT

The yield on any investment is computed by determining the interest rate that will make the present value of the cash flow from the investment equal to its price. Mathematically, the yield, y, on any investment is the interest rate that will make the following relationship hold:

$$p=\frac{C_{1}}{(1+y)}+\frac{C_{2}}{(1+y)^{2}}+\frac{C_{3}}{(1+y)^{3}}+\cdot s+\frac{C_{N}}{(1+y)^{N}},$$

where $p=Price$; $C_{t}=Cash flow in year t$; $N=Number of years$.

The individual terms summed to produce the price are the present values of the cash flow. The yield calculated from the above relationship is also called the internal rate of return .

Alternatively, using the capital Greek letter sigma to denote summation, the above expression can be rewritten as

$$p=\sum_{r=1}^{N}\frac{C_{r}}{(1+y)^{r}}.$$

Solving for the yield (y) requires an iterative procedure. The objective is to find the interest rate that will make the present value of the cash flows equal to the

53

---

54

PART 1 Time Value of Money

## EXHIBIT 5-1

### Step-by-Step Summary of Yield Computation for Any Investment

<table><tr><td>Objective</td><td>Find the interest rate that will make the present value of the cash flow equal to the price of the investment.</td></tr><tr><td>Step 1</td><td>Select an interest rate.</td></tr><tr><td>Step 2</td><td>Compute the present value of each cash flow by using the interest rate selected in Step 1.</td></tr><tr><td>Step 3</td><td>Total the present value of the cash flows found in Step 2.</td></tr><tr><td>Step 4</td><td>Compare the total present value found in Step 3 with the price of the investment. Then, if the total present value of the cash flows found in Step 3 is equal to the price of the investment, the interest rate selected in Step 1 is the yield. If the total present value of the cash flows found in Step 3 is more than the price of the investment, the interest rate used is not the yield. Go back to Step 1 and use a higher interest rate. If the total present value of the cash flows found in Step 3 is less than the price of the investment, the interest rate used is not the yield. Go back to Step 1 and use a lower interest rate.</td></tr></table>


process. Exhibit 5-1 explains the iterative procedure. The following two illustrations demonstrate how it is carried out.

Illustration 5-1. A financial instrument offers the following annual payments:

<table><tr><td>Years from Now</td><td>Promised Annual Payments (Cash Flow to Investor:$)</td></tr><tr><td>1</td><td>$2,000</td></tr><tr><td>2</td><td>2,000</td></tr><tr><td>3</td><td>2,500</td></tr><tr><td>4</td><td>4,000</td></tr></table>


Suppose that the price of this financial instrument is $7,704. What is the yield or internal rate of return offered by this financial instrument?

To compute the yield, we must try different interest rates until we find one that makes the present value of the cash flows equal to $7,704 (its price). Trying an annual interest rate of 10% gives the following present value:

<table><tr><td>Years from Now</td><td>Promised Annual Payments (Cash Flow to Investor;$)</td><td>Present Value of Cash Flow at 10% ($)</td></tr><tr><td>1</td><td>$2,000</td><td>$1,618</td></tr><tr><td>2</td><td>2,000</td><td>1,652</td></tr><tr><td>3</td><td>2,500</td><td>1,878</td></tr><tr><td>4</td><td>4,000</td><td>2,732</td></tr><tr><td></td><td colspan="2">Total present value =$9,080</td></tr></table>


---

CHAPTER 5   Yield (Internal Rate of Return)

55

The present value computed using a 10% interest rate exceeds the price of $7,704, so a higher interest rate must be tried. If a 14% interest rate is tried, the present value is $7,348, as shown below:

<table><tr><td>Years from Now</td><td>Promised Annual Payments (Cash Flow to Investor;$)</td><td>Present Value of Cash Flow at 14% ($)</td></tr><tr><td>1</td><td>$2,000</td><td>$1,754</td></tr><tr><td>2</td><td>2,000</td><td>1,538</td></tr><tr><td>3</td><td>2,500</td><td>1,688</td></tr><tr><td>4</td><td>4,000</td><td>2,368</td></tr><tr><td></td><td colspan="2">Total present value =$7,348</td></tr></table>


At 14%, the present value of the cash flows is less than the $7,704 price of the financial instrument. Therefore, a lower interest rate must be tried. The present value at a 12% interest rate is shown below:

<table><tr><td>Years from Now</td><td>Promised Annual Payments (Cash Flow to Investor,$)</td><td>Present Value of Cash Flow at 12% ($)</td></tr><tr><td>1</td><td>$2,000</td><td>$1,786</td></tr><tr><td>2</td><td>2,000</td><td>1,594</td></tr><tr><td>3</td><td>2,500</td><td>1,780</td></tr><tr><td>4</td><td>4,000</td><td>2,544</td></tr><tr><td></td><td colspan="2">Total present value =$7,704</td></tr></table>


The present value of the cash flows is now equal to the price of the financial instrument when a 12% interest rate is used. Therefore, the yield is 12%.

Although the formula for the yield is based on annual cash flows, the formula can be generalized to any number of periodic payments in a year. The generalized formula for determining the yield is

$$p = \frac { C _ { 1 } } { ( 1 + y ) } + \frac { C _ { 2 } } { ( 1 + y ) ^ { 2 } } + \frac { C _ { 3 } } { ( 1 + y ) ^ { 3 } } + ... + \frac { C _ { n } } { ( 1 + y ) ^ { n } } ,$$

where $C_{t}$ = Cash flow in period t; n = Number of periods.

In shorthand notation, this can be expressed as

$$p=\sum_{t=1}^{n}\frac{C_{t}}{(1+y)^{t}}$$

---

56

PART 1 Time Value of Money

Keep in mind that the yield computed is now the yield for the period. That is, if the cash flows are semiannual, the yield is a semiannual yield. If the cash flows are monthly, the yield is a monthly yield. The annual interest rate must be computed by multiplying the yield for the period by the appropriate factor ( m ).

Illustration 5-2. In Illustration 4-11 of the previous chapter, an investor considered purchasing a financial instrument that promised the following semiannual cash flows:

10 payments of $50 every 6 months; $1,000 10-6 month periods from now.

Suppose the price of this financial instrument is $1,243.88. At the 6.5% annual interest rate sought by the investor, the present value of the cash flows is equal to $1,158.92; thus, the financial instrument would not be an attractive investment for this investor. What yield is this financial instrument offering?

The yield can be computed as summarized in the table below:

<table><tr><td>Annual Interest Rate (%)</td><td>Semiannual Interest Rate (%)</td><td>Present Value of 10-6 Month Payments of$50 ($)*</td><td>Present Value of$1,000 to 6-Month Periods from Now ($)**</td><td>Total Present Value ($)</td></tr><tr><td>6.000%</td><td>3.000%</td><td>$426.51</td><td>$744.09</td><td>$1,160.60</td></tr><tr><td>5.500</td><td>2.750</td><td>432.00</td><td>762.40</td><td>1,194.40</td></tr><tr><td>5.000</td><td>2.500</td><td>437.60</td><td>781.20</td><td>1,218.80</td></tr><tr><td>4.500</td><td>2.225</td><td>443.31</td><td>800.51</td><td>1,243.83</td></tr></table>


* $50 + present value of an ordinary annuity of 1 for 10 periods.

**$1,000 + present value of 1 for 10 periods from now.

As can be seen from the calculation, when a semiannual interest rate of 2.250% is used to find the present value of the cash flows, the present value is equal to the price of $1,243.83. Hence, 2.250% is the 6-month yield. Doubling this yield gives the annual interest rate of 4.5%. This agrees with our earlier conclusion: this financial instrument is unattractive because it offers a yield that is less than the 6.5% annual interest rate required by the investor.

Illustration 5-3. Suppose that the financial instrument analyzed in the previous illustration is selling for $944.14 instead of $1,243.83. What is the yield offered on this financial instrument at this lower price?

The table below shows the calculation of the yield:

---

CHAPTER 5   Yield (Internal Rate of Return)

57

<table><tr><td>Annual Interest Rate (%)</td><td>Semiannual Interest Rate (%)</td><td>Present Value of 10 6-month Payments of$50 ($)*</td><td>Present Value of$1,000, 10 6-month Periods from Now ($)**</td><td>Total Present Value ($)</td></tr><tr><td>9.000%</td><td>4.500%</td><td>$395.64</td><td>$643.93</td><td>$1,039.57</td></tr><tr><td>9.500</td><td>4.750</td><td>390.82</td><td>628.72</td><td>1,019.54</td></tr><tr><td>10.000</td><td>5.000</td><td>386.09</td><td>613.91</td><td>1,000.00</td></tr><tr><td>10.500</td><td>5.250</td><td>381.44</td><td>599.49</td><td>980.93</td></tr><tr><td>11.000</td><td>5.500</td><td>376.88</td><td>585.43</td><td>962.31</td></tr><tr><td>11.500</td><td>5.750</td><td>372.40</td><td>571.74</td><td>944.14</td></tr></table>


* $50 x present value of an ordinary annuity of $1 for 10 periods.

** $1,000 x present value of 1 to 10 periods from now.

An interest rate of 5.75% equates the present value of the cash flows to the price of the financial instrument; hence, 5.75% is the 6-month yield, and 11.50% is the annual interest rate.

Illustration 5-4. A 30-year mortgage for $50,000 is originated today. The mortgage requires that the homeowner (borrower) pay $349.60 each month for 360 months. The manager of a mortgage portfolio has the opportunity to purchase this mortgage today for $43,449. What is the yield offered for this series of monthly mortgage payments?

The computations below show that the monthly yield is 0.75% (0.0075):

<table><tr><td>Annual Interest Rate (%)</td><td>Monthly Interest Rate (%)</td><td>Present Value of 360 Monthly Payments of$349.60 ($)</td></tr><tr><td>7.50%</td><td>0.6250%</td><td>$50,000</td></tr><tr><td>8.00</td><td>0.6667</td><td>47,843</td></tr><tr><td>8.50</td><td>0.7083</td><td>45,469</td></tr><tr><td>9.00</td><td>0.7500</td><td>43,449</td></tr></table>


*$349.60 × present value of an ordinary annuity of $1 for 360 periods.

Since the monthly yield is 0.75%, the annual interest rate is 9.0% (12×0.75%).

Illustration 5-5. Issuers of financial instruments must determine the cost of the funds they obtain. The cost of funds, referred to as the all-in-cost of funds , is just the interest rate that will equate the present value of the cash payments that the issuer must pay the security holders to the net proceeds received at the time of issuance. That is, the all-in-cost of funds is the internal rate of return.

Suppose that an issuer agrees to make the following payments to security holders every 6 months:

30 payments every 6 months of $1 million, $20 million, 30 6-month periods from now.

---

58

PART 1 Time Value of Money

At the time of issuance, the issue receives net proceeds of $19,696,024. The allin-cost of funds for this issue is 5.10% semiannually, as shown below:

<table><tr><td>Annual Interest Rate (%)</td><td>Semiannual Interest Rate (%)</td><td>Present Value of 30 6-Month Payments of$1 Million ($)*</td><td>Present Value of$20 Million, 30 6-Month Periods from Now ($)**</td><td>Total Present Value ($)</td></tr><tr><td>10.000%</td><td>5.000%</td><td>$15,372,451</td><td>$4,627,549</td><td>$20,000,000</td></tr><tr><td>10.100</td><td>5.050</td><td>$15,285,221</td><td>$4,561,927</td><td>$19,847,148</td></tr><tr><td>10.200</td><td>5.100</td><td>$15,198,759</td><td>$4,497,265</td><td>$19,696,024</td></tr></table>


$1 million x present value of an ordinary annuity of$1 for 30 periods.

*$20 million x present value of an $10 period from now.

## YIELD CALCULATION WHEN THERE IS ONLY ONE CASH FLOW

There is a special case when it is unnecessary to go through the iterative procedure to determine the yield. This occurs when there is only one cash flow provided by the investment. We'll introduce the formula by means of an illustration.

Illustration 5-6. A financial instrument that can be purchased for $6,805.82 promises to pay $10,000 in 5 years. The yield is the interest rate that will make $6,805.82 grow to $10,000 in 5 years. That is, we are looking for the value of y that will satisfy the following relationship:

$$\$10,000=\$6,805.82(1+y)^{5}.$$

We can solve this equation as follows. Divide both sides by $6,805.82:

$$\frac{\10,000}{6,805.82}=(1+y)^{2}$$

$$1.46933=(1+y)^{5}.$$

Take the fifth root of both sides:

$$(1.46933)^{1/5}=(1+y)$$

$$(1.46933)^{0.20}=(1+y)$$

$$1.0800=(1+y)$$

Subtract 1 from both sides:

$$1.0800-1=y$$

$$0.08=y$$

Hence, the yield on this investment is 8%.

---

CHAPTER 5   Yield (Internal Rate of Return)

59

It is not necessary to go through all the steps in Illustration 4-6 to compute the yield. The following formula is consistent with those steps:

$$y= (Future value per dollar invested) ^{t t}$$

$$where \quad \zeta=\sqrt[n]{\frac{E V}{P}}-1 \quad  or  \quad t=\left(\frac{E V}{P}\right)^{\frac{n}{n}}-1$$

$n=Number\ of\ periods$ until the cash flow will be received;

$$Future\ value\ per\ dollar\ invested=\frac{Cash\ flow\ from\ investment}{Amount\ invested\ (or\ price)}.$$

Illustration 5-7 An investment offers a payment 20 years from now of $84,957. The price of the investment is $20,000. The yield for this investment is 7.50%, as shown below:

$$n=20 ;$$

$$Future value per dollar invested =\frac{\$ 84,957}{\$ 22,000}=4.24785.$$

$$y = ( 4 . 2 4 7 8 5 ) ^ { x / 2 0 } - 1 \quad = 1 . 0 7 4 9 9 - 1 \quad = 0 . 0 7 4 9 9 9  ~ o r ~  7 . 5 \%$$

Illustration 5-8 In Illustration 3–8, we computed how many dollars would be available to a portfolio manager if he invests $5 million (the par value) in a bond that matures in 10 years and promises to pay an annual interest rate of 8%. The interest is assumed to be paid once per year, and these payments are assumed to be reinvested at an annual interest rate of 6.7%. We calculated that at the end of 10 years, the portfolio manager would have $10,448,884, consisting of $5 million in par value, $4 million in annual interest payments, and the balance, $1,448,884, from interest earned on the reinvestment of the annual interest payments.

The yield on this investment based on the portfolio manager's expectations can be computed by finding the yield that will make a $5 million investment grow to $10,448,884 in 10 years. Since we have reduced the problem to that of an investment that provides the portfolio manager with one cash flow, the yield can be found as follows;

$$n=10\ (N);$$

$$Future value per dollar invested=$\begin{matrix}\10,448,884 \\\5,600,000\end{matrix}=2.08978.$$

$$\begin{array} { r } { y = ( 2 . 0 8 9 7 8 ) ^ { y / 1 0 } - 1 } \\ { = 1 . 0 7 6 4 9 - 1 } \\ { = 0 . 0 7 6 4 9  or  7 . 6 5 \% } \end{array}$$

---

60

PART 1 Time Value of Money

## ANNUALIZING Yields

So far throughout this book, we have annualized interest rates by simply multiplying by the frequency of payments per year. We called the resulting rate the annual interest rate. For example, if we computed a semiannual yield, we annualized it by multiplying by 2. Alternatively, if we had an annual interest rate and wanted to use a semiannual interest rate, we divided by 2.

This single procedure given for computing the annual interest rate, given a periodic (weekly, monthly, quarterly, semiannual, etc.) interest rate is not correct. To see why, suppose that $100 is invested for 1 year at an annual interest rate of 8 % . At the end of 1 year, the interest is $8. Suppose, instead, that $100 is invested for 1 year at an annual interest rate of 8%, but interest is paid semiannually at 4% (one-half the annual interest rate). The interest at the end of 1 year is found by first calculating the future value of $100 at the end of 1 year:

$$\begin{aligned}
& \$ 100(1.04)^{2} \\
& =\$ 100(1.0816) \\
& =\$ 108.16
\end{aligned}$$

Interest is therefore $8.16 on a $100 investment. The interest rate or yield on the $100 investment is therefore 8.16% ($8.16/$100). The 8.16% is called the effective annual yield.

Investors who are familiar with certificates of deposit offered by banks and thrifts should recognize the difference between the annual interest rate and effective annual yield. Typically, both of these interest rates are quoted for a certificate of deposit, the higher interest rate being the effective annual yield.

To obtain the effective annual yield associated with a periodic interest rate, the following formula can be used:

$$Effective annual yield $=(1+ Periodic interest rate )^{m}-1, \quad  f o l o w i n t  f(0)$$

$$\left(\begin{array}{c}
1  e f f a n t l y =(1+ per o d: c)^{n-1} \quad \Delta\right.$$

$$ where $$

$m=Frequency\ of\ payments\ per\ year.$

For example, in the previous example, the periodic yield is 4%, and the frequency of payments is twice per year. Therefore,

$$\begin{aligned}
 Effective annual yield =(1.04)^{2}-1 & \\
& =1.0816-1 \\
& =0.0816  or  8.16 \% .
\end{aligned}$$

If interest is paid quarterly, then the periodic interest rate is 2% (8%/4), and the effective annual yield is 8.24%, as shown below:

$$\begin{aligned}
 Effective annual yield =(1.02)^{4}-1 & \\
& =1.0824-1 \\
& =0.0824  or  8.24 \% .
\end{aligned}$$

---

CHAPTER 5   Yield (Internal Rate of Return)

61

We can also determine the periodic interest rate that will produce a given annual interest rate. For example, suppose we want to know what quarterly interest rate would produce an effective annual yield of 12%. The following formula can be used:

$$ Periodic interest rate =(1+ Effective annual yield )^{I / m}-1 .$$

Applying this formula to determine the quarterly interest rate to produce an effective annual yield of 12%, we find

$$\begin{aligned}
 Periodic interest rate = & (1.12)^{N}-1 \\
& =1.0287-1 \\
& =0.0287  or  2.87 \%
\end{aligned}$$

## SUMMARY

In this chapter we explained how to compute the yield on any investment, given the expected cash flows and the price. The yield is the interest rate that will make the present value of the cash flows equal to the price of the financial instrument. The yield computed in this manner is also called the internal rate of return. We also demonstrated how to compute the effective annual yield of an investment. A summary of the formulas introduced in this chapter is provided in Exhibit 5-2.

---

62

PART 1 Time Value of Money

### EXHIBIT 5-2

### Summary of Yield (Internal Rate of Return) Formulas

1. Yield (or internal rate of return) on any investment from which the cash flows are observed annually is the interest rate $\gamma$ that will make the following relationship hold:

$$c_{1}=\frac{C_{1}}{(1+y)^{1}}+\frac{C_{2}}{(1+y)^{2}}+\frac{C_{3}}{(1+y)^{3}}+...+\frac{C_{n}}{(1+y)^{n}}$$

or

$$P=\sum_{i=1}^{N}\frac{C_{i}}{(1+y)^{i}}$$

where

p = Price;

C$_{i}$ = Cash flow in year t;

y = Yield;

N = Number of years.

2. Yield (or internal rate of return) on any investment from which the cash flows are observed periodically is the interest rate y that will make the following relationship hold:

$$P={\frac {C_{1}}{(1+y)^{2}}}+{\frac {C_{2}}{(1+y)^{2}}}+{\frac {C_{3}}{(1+y)^{3}}}+...+{\frac {C_{n}}{(1+y)^{n}}}$$

or

$$P=\sum_{i=1}^{N}\frac{C_{i}}{(1+y)^{i}}$$

where $C_{t}=$ Cash flow in period t $n=$ Number of periods.

3. Yield (internal rate of return) on an investment in which there is only one cash flow received n periods from now:

$$y=( Future value per dollar invested )^{1 / n}-1,$$

where

n = Number of periods when cash flow will be received;

$$ Future value =\frac{ Cash flow from investing }{ Amount invested (or price) }$$

4. Effective annual yield associated with a periodic interest rate:

$$Effective annual yield $=(1+ Periodic interest rate )^{m-1} ,$$

where

m = Frequency of payments per year.

5. Periodic interest rate consistent with an effective annual yield:

$$ Periodic interest rate =(1+ Effective annual yield )^{1 m}-1 .$$

---

PART TWO

BOND PRICING FOR OPTION-FREE BONDS AND CONVENTIONAL YIELD MEASURES

