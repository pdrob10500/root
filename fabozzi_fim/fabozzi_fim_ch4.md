![Figure](figures/fabozzi_fim_ch4_page_001_figure_000.png)

CHAPTER FOUR

## PRESENT VALUE

In the previous chapter, we illustrated how to compute the future value of an investment. In this chapter, we show how to work the process in reverse; that is, given the future value of an investment, we show how to determine the amount of money that must be invested today in order to realize the future value. The amount of money that must be invested today is called the present value . Since, as we shall explain later in this chapter, the price of any financial instrument is the present value of its expected cash flows, it is necessary to understand present value in order to be able to price a fixed income instrument. In the appendix to this chapter, we explain how to compute the present value when continuous compounding is assumed.

### PRESENT VALUE OF A SINGLE AMOUNT TO BE RECEIVED IN THE FUTURE

Recall from the previous chapter that the future value of a sum invested for N years can be expressed as

$$FV=P(1+i)^{N},$$

where $FV = Future value ($); $P = Original principal ($); $i = Interest rate (in decimal form)$; $N = Number of years$; $(1+i)^{N} = Future value of \$1 invested at i for N years$.

How do we determine the amount of money that must be invested today, earning an interest rate of $i$ for $N$ years, in order to produce a specific future value? This is done by solving the future value formula for $P$ , the original principal:

$$P=FU\frac{1}{(1+\rho)^{k}}.$$

Instead of using $P$ in the formula, we shall denote the present value as $PV$ . Therefore, the present value formula can be rewritten as

$$PV=FU\left[\frac{1}{(1+i)^{N}}\right]$$

---

38

PART 1 Time Value of Money

The term in the brackets is equal to the present value of $1: that is, it indicates how much must be set aside today, earning an interest rate of $i$, in order to have $1N years from now.

The process of computing the present value is referred to as discounting. Therefore, the present value is sometimes referred to as the discounted value, and the interest rate is referred to as the discount rate.

The following four illustrations demonstrate how to compute the present value.

Illustration 4-1. A pension fund manager must satisfy a liability of $9 million 6 years from now. Assuming that an annual interest rate of 7.5% can be earned on any sum invested today, the pension fund manager must invest $5,831,654 today in order to have $9 million 6 years from now, as shown below:

$$FV=\$9,000,000;$$

$$i=0.075 ;$$

$$N = 6 .$$

$$\begin{aligned}
PV&=\$9,000,000\left[\frac{1}{(1.075)^{6}}\right]\\
&=\$9,000,000\left[\frac{1}{1.543302}\right]\\
&=\$9,000,000(0.647961)\\
&=\$5,831,654.
\end{aligned}$$

Illustration 4-2. Suppose now that the pension fund manager could earn 8.3% instead of 7.5%; then the present value of the $9 million to be paid 6 years from now would be $5,577,912, as shown below:

$$FV=\$9,000,000;$$

$$i=0.083 ;$$

$$N = 6 .$$

$$\begin{aligned}
PV&=\$9,000,000\left[\frac{1}{(1.083)^{6}}\right]\\
&=\$9,000,000\left[\frac{1}{1.613507}\right]\\
&=\$9,000,000(0.619768)\\
&=\$5,577,912.
\end{aligned}$$

Illustration 4-3. Suppose a money manager has the opportunity to purchase a financial instrument that promises to pay $800,000 in 4 years. The price of the

---

CHAPTER 4 Present Value

39

financial instrument is $572,000. Should the money manager invest in this financial instrument if she wants a 7.8% annual interest rate?

To answer this, the money manager must determine the present value of the $800,000 to be received 4 years from now. The present value is $592,400, as shown below:

$$FV=\$800,000;$$

$$i=0.078 ,$$

$$N = 4 .$$

$$\begin{aligned}
PV& =\$800,000\left[\frac{1}{(1.078)^{4}}\right]\\
& =\$800,000\left[\frac{1}{1.350439}\right]\\
& =\$800,000(0.740500)\\
& =\$592,400.
\end{aligned}$$

As the price of the financial instrument is $572,000, the money manager will realize more than a 7.8% annual interest rate if the financial instrument is purchased and the issuer pays $800,000 in 4 years. In the next chapter, we'll show how to compute the annual interest rate that the money manager would realize.

Another way of looking at the problem faced by this money manager is to ask how much the $572,000 would grow to in 4 years if invested at 7.8%. Using the formula for the future value of an investment, we find that the future value is $772,451, as shown below:

$$P=5572,000;$$

$$i=0.078 ;$$

$$N = 4 .$$

$$\begin{aligned}
F V & =\$ 572,000(1.078)^{t} \\
& =\$ 572,000(1.350439) \\
& =\$ 772,451 .
\end{aligned}$$

A $572,000 investment at 7.8% would grow to only $772,451. Yet, an investment of $572,000 in the particular financial instrument produces $800,000 in 4 years. Consequently, the financial instrument offers more than a 7.8% annual interest rate. The present value of $592,400 tells the money manager that as long as she pays no more than $592,400, an annual interest rate of at least 7.8% will be earned from this investment.

---

40

PART 1 Time Value of Money

Illustration 4-4. Instead of promising $800,000 in 4 years, suppose that the financial instrument in the previous illustration promises to pay $800,000 in 5 years. Assume that the money manager still wants an annual interest rate of 7.8%. Is the investment still attractive if it is selling for $572,000?

As shown below, the present value of the $800,000 in 5 years is $549,536:

$$FV=\$800,000;$$

$$i=0.078;$$

$$N = 5 .$$

$$\begin{aligned}
PV&=800,000\left[\frac{1}{(1.078)^{5}}\right]\\
&=800,000\left[\frac{1}{1.455733}\right]\\
&=800,000(0.686920)\\
&=549,536.
\end{aligned}$$

Here the present value is less than the price of $572,000, so the financial instrument offers an annual interest rate that is less than 7.8% .

## PRESENT VALUE FOR A FRACTIONAL PERIOD

If a future value is to be received or paid over a fractional part of a year, the number of years is adjusted accordingly. For example, if $1,000 is to be received 9 years and 3 months from now and the interest rate is 7%, the present value is determined as follows:

$$FV=\$1,000;$$

$$i=0.07 ;$$

$$N=9.25  years (3 months is  0.25  years).$$

$$\begin{aligned}
PV&=1,000\left[\frac{1}{(1.07)^{0.25}}\right]\\
&=1,000\left[\frac{1}{1.86982}\right]\\
&=1,000(0.53481)\\
&=534.81.
\end{aligned}$$

---

CHAPTER 4 Present Value

41

## PROPERTIES OF PRESENT VALUE

There are two properties of present value that you should recognize.

First, for a given future value at a specified time in the future, the higher the interest rate (or discount rate) is, the lower the present value. To see this, compare the present value in Illustration 4–1 to that in Illustration 4–2. When the annual interest rate increased from 7.5% to 8.3%, the present value of the $9 million needed 6 years from now decreased from $5,831,654 to $5,577,912. The reason that the present value decreases as the interest rate increases should be easy to understand. The higher the interest rate that can be earned on any sum invested today, the less has to be invested today to realize a specified future value.

The second property of the present value is that for a given interest rate (discount rate), the farther into the future the future value will be received, the lower the present value is. This is demonstrated in Illustrations 4–3 and 4–4. When the amount of $800,000 is to be received 4 years from now, the present value is $592,400; if $800,000 is to be received 5 years from now, the present value declines to $549,536. The reason is that the farther into the future a given future value is to be received, the more time there is for interest to accumulate. The result is that fewer dollars have to be invested.

## PRESENT VALUE OF A SERIES OF FUTURE VALUES

In most applications in investment management and asset/liability management, a financial instrument will offer a series of future values, or a financial institution will have multiple liabilities in the future. To determine the present value of a series of future values, the present value of each future value must first be computed. Then, the present values are added to obtain the present value of the series of future values. This procedure is demonstrated in the following three illustrations.

Illustration 4-5. A pension fund manager knows that the following liabilities must be satisfied:

<table><tr><td>Years from Now</td><td>Liability</td></tr><tr><td>1</td><td>$200,000</td></tr><tr><td>2</td><td>340,000</td></tr><tr><td>3</td><td>500,000</td></tr><tr><td>4</td><td>580,000</td></tr></table>


Suppose that the pension fund manager wants to invest a sum of money that will satisfy this liability stream. Let's assume that any amount that can be invested today can earn an annual interest rate of 8.5%. How much must be invested to satisfy this liability stream?

---

42

PART 1 Time Value of Money

The answer is the present value of the liability stream. Consequently, the present value of each liability must be calculated and the results must be totaled, as shown below.

<table><tr><td>Years from Now</td><td>Future Value of Liability ($)</td><td>Present Value of$1 at 8.5%</td><td>Present Value of Liability</td></tr><tr><td>1</td><td>$200,000</td><td>0.921659</td><td>$184,332</td></tr><tr><td>2</td><td>340,000</td><td>0.849455</td><td>288,815</td></tr><tr><td>3</td><td>500,000</td><td>0.782908</td><td>391,454</td></tr><tr><td>4</td><td>580,000</td><td>0.721574</td><td>416,513</td></tr><tr><td></td><td></td><td>Total present value =$1,283,114</td><td></td></tr></table>


The present value of $1,283,114 means that if this sum is invested today at an annual interest rate of 8.5%, it will provide sufficient funds to satisfy the liability stream.

For those who must be convinced that this is true, let's look at what would happen if $1,283,114 were invested at 8.5% in a bank account, and at the end of each year enough money is withdrawn from the bank account to satisfy the annual liability.

<table><tr><td></td><td>(2)</td><td>(3)</td><td>(4)</td><td>(5)</td></tr><tr><td>Year</td><td>Amount at Beginning of Year ($)</td><td>Interest at 8.5% [0.085 × (2)]</td><td>Amount Withdrawn to Pay Liability</td><td>Amount at End of Year [(2)+(3)-(4)]</td></tr><tr><td>1</td><td>$1,283,114</td><td>$109,065</td><td>$200,000</td><td>$1,192,179</td></tr><tr><td>2</td><td>1,192,179</td><td>101,335</td><td>340,000</td><td>953,514</td></tr><tr><td>3</td><td>953,514</td><td>81,049</td><td>500,000</td><td>534,563</td></tr><tr><td>4</td><td>534,563</td><td>45,437</td><td>580,000</td><td>0</td></tr></table>


As these computations show, the $1,283,114 investment will provide enough money to pay the liability stream. At the end of the fourth year (after the last liability is paid), there is no money left in the account.

Illustration 4-6. An investor is considering the purchase of a financial instrument that promises to make the following payments:

<table><tr><td>Years from Now</td><td>Promised Payment by Issuer</td></tr><tr><td>1</td><td>$100</td></tr><tr><td>2</td><td>100</td></tr><tr><td>3</td><td>100</td></tr><tr><td>4</td><td>100</td></tr><tr><td>5</td><td>1,100</td></tr></table>


This financial instrument is selling for $1,243.83. Assume that the investor wants a 6.25% annual interest rate on this investment. Should the investor purchase this investment?

---

CHAPTER 4 Present Value

43

To answer this question, the investor first must compute the present value of the future amounts that are expected to be received, as follows:

<table><tr><td>Years from Now</td><td>Future Value of Payment</td><td>Present Value of$1 at 6.25%</td><td>Present Value of Payment</td></tr><tr><td>1</td><td>$100</td><td>$0.9412</td><td>$94.12</td></tr><tr><td>2</td><td>$100</td><td>$0.8858</td><td>$88.58</td></tr><tr><td>3</td><td>$100</td><td>$0.8337</td><td>$83.37</td></tr><tr><td>4</td><td>$100</td><td>$0.7847</td><td>$78.47</td></tr><tr><td>5</td><td>$1,100</td><td>$0.7385</td><td>$812.35</td></tr><tr><td></td><td></td><td colspan="2">Total present value =$1,156.89</td></tr></table>


The present value of the series of future values promised by the issuer of this financial instrument is less than the price of $1,243.83, so the investor would earn an annual interest rate of less than 6.25%. Thus, the financial instrument is unattractive.

## PRESENT VALUE OF AN ORDINARY ANNUITY

When the same amount of money is received or paid each year, the series is referred to as an annuity . When the first payment is received or paid 1 year from now, the annuity is called an ordinary annuity . When the first payment or receipt is immediate, the annuity is called an annuity due . In all the applications discussed in this book, we deal with ordinary annuities. —

Of course, one way to compute the present value of an ordinary annuity is to follow the procedure explained in the previous section: compute the present value of each future value and then total the present values. Fortunately, there is a formula that can be employed to compute—in one step—the present value of an ordinary annuity:

$$P V=A\left[1-\left[\frac{\left(1-\frac{1}{(i I)^{N}}\right)}{i}\right]\right]$$

where

A = Amount of the annuity ($).

The term in the large brackets is the present value of an ordinary annuity of $1 for N years.

Two illustrations will show how to apply this formula.

Illustration 4-7. An investor has the opportunity to purchase a financial instrument that promises to pay $500 a year for the next 20 years, beginning 1 year from now. The financial instrument is being offered for a price of $5,300. The investor seeks an annual interest rate of 5.5% on this investment. Should the investor purchase this financial instrument?

Since the first payment to be received 1 year from now on, the financial instru- ment is offering a 20-year annuity of $500 per year. The present value of this ordinary

---

44

PART 1 Time Value of Money

annuity is calculated as follows:

$$A=\$500;$$

$$i=0.055 ;$$

$$N=20 .$$

$$\begin{aligned}
PV&=\$500\left[\frac{1-\left[\frac{1}{(1.055)^{20}}\right]}{0.055}\right]\\
&=\$500\left[\frac{1-\left[\frac{2.917757}{0.055}\right]}{0.055}\right]\\
&=\$500\left[\frac{1-0.342729}{0.055}\right]\\
&=\$500(11.950382)\\
&=\$5,975.19.
\end{aligned}$$

Since the present value of an ordinary annuity of $500 per year when discounted at 5.5% exceeds the price of the financial instrument ($5,300), this financial instrument offers an annual interest rate in excess of 5.5%. Therefore, it is an attractive investment for this investor.

Illustration 4-8. In Illustration 4-6 we computed the present value of a financial instrument that offers $100 a year for 4 years and $1,100 at the end of the fifth year. This payment series is equivalent to an ordinary annuity of $100 a year for 5 years plus a future value payment of $1,000 in 5 years. Viewing the payments of the financial instrument in this way, let's compute the present value.

The present value of an ordinary annuity of $100 per year for 5 years at an annual interest rate of 6.25% is

$$A=\$100;$$

$$i=0.0625;$$

$$N = 5 .$$

$$\begin{aligned}
PV&=100\left[\frac{1-\dfrac{1}{(1.0625)^{2}}}{0.0625}\right]\\
&=100\left[\frac{1-\dfrac{1}{1.354081}}{0.0625}\right]\\
&=100\left[\frac{1-0.738508}{0.0625}\right]\\
&=100(4.1838)\\
&=418.38.
\end{aligned}$$

---

CHAPTER 4 Present Value

45

The present value of the $1,000 to be received 5 years from now is $738.51, as shown below:

$$FV=\$1,000;$$

$$i=0.0625 ;$$

$$N=5 .$$

$$\begin{aligned}
PV&=1,000\left[\frac{1}{(1.0625)^{2}}\right]\\
&=1,000\left[\frac{1}{1.354081}\right]\\
&=1,000(0.738508)\\
&=738.51.
\end{aligned}$$

The present value of the series offered by this financial instrument is then

<table><tr><td>Present value of ordinary annuity of$100 for 5 years at 6.25%</td><td>$418.38</td></tr><tr><td>Present value of$1,000 in 5 years at 6.25%</td><td>738.51</td></tr><tr><td>Total present value</td><td>$1,156.89</td></tr></table>


This agrees with the computation in Illustration 4-6.

## Perpetual Annuity: Special Case

So far we have shown how to compute the present value of an ordinary annuity over a specific time period. Suppose, instead, that the annuity will last forever. This is called a perpetual annuity. The formula for a perpetual annuity is $^1$

$$PV={\frac{A}{i}}.$$

Illustration 4-9. An investor can purchase for $1,000 a financial instrument that promises to pay $80 per year forever. The investor wants an annual interest rate of 10% from this investment. Is this investment attractive to the investor?

The present value of the $80 perpetual annuity is equal to $800, as shown below:

$$A=\$80;$$

$$i=0.10$$

$$PV=\frac{\$80}{10}=\$800.$$

1. The formula is derived from the formula for the present value of an ordinary annuity. As the number of years gets very large, the value of $1/(1 + \gamma)$ approaches zero. The numerator in the large brackets is then equal to 1, producing the formula for the present value of a perpetual annuity.

---

46

PART 1 Time Value of Money

Since the $1,000 price for the financial instrument is greater than the present value of the perpetual annuity ($800), the investment offers an annual interest rate that is less than 10%; therefore, it is not an attractive investment, given the minimum annual interest rate required by the investor.

## PRESENT VALUE WHEN THE FREQUENCY IS MORE THAN ONCE PER YEAR

In the computations of present value, we have assumed that the future value is to be received or paid once each year. In practice, the future value may be received or paid more than once per year. In this situation, the formulas for the present value given earlier in this chapter must be modified in two ways. First, the annual interest rate is divided by the frequency per year. 2 For example, if the future values are received or paid semiannually, the annual interest rate is divided by 2; if quarterly, the annual interest rate is divided by 4. Second, the periods when the future value will be received or paid must be adjusted by multiplying the number of years by the frequency per year.

The general formula for the present value of a future sum is

$$PV=FU\left(\frac{1}{(1+i)^{n}}\right)$$

where

i = Periodic interest rate [annual interest rate (in decimal form) divided by m];

n = Number of periods [number of years (N) times m];

m = Frequency of receipt or payment of the future value.

Illustration 4-10. An investor is considering the purchase of a financial instrument that promises to make the following payments every 3 months (quarterly):

<table><tr><td>Period (3 months)</td><td>Promised Payments</td></tr><tr><td>1</td><td>$1,000</td></tr><tr><td>2</td><td>1,200</td></tr><tr><td>3</td><td>1,500</td></tr><tr><td>4</td><td>1,700</td></tr><tr><td>5</td><td>1,800</td></tr><tr><td>6</td><td>2,000</td></tr></table>


If the investor seeks an annual interest rate of 12% from this investment, what is the most that the investor should pay for it?

2. Technically, this is not the proper way for adjusting the annual interest rate. For example, an 8% annual interest rate is not equal to a quarterly interest rate of 2%. However, in the computation of the yield on bonds, the market has adopted a convention that embodies this approach. This will be made clearer in the next two chapters.

---

CHAPTER 4 Present Value

47

The most that the investor should pay in order to earn an annual interest rate of at least 12% is the present value of the future payments promised. As shown below, the present value is $8,212.79.

<table><tr><td>Periods from Now</td><td>Future Value of Payment</td><td>Present Value of$1 at 3.0%*</td><td>Present Value of Payment</td></tr><tr><td>1</td><td>$1,000</td><td>0.97087</td><td>$970.87</td></tr><tr><td>2</td><td>1,200</td><td>0.94260</td><td>1,131.12</td></tr><tr><td>3</td><td>1,500</td><td>0.91514</td><td>1,372.71</td></tr><tr><td>4</td><td>1,700</td><td>0.88849</td><td>1,510.43</td></tr><tr><td>5</td><td>1,800</td><td>0.86261</td><td>1,552.70</td></tr><tr><td>6</td><td>2,000</td><td>0.83748</td><td>1,674.96</td></tr><tr><td></td><td></td><td colspan="2">Total present value =$8,212.79</td></tr></table>


*0.12 annual interest rate divided by 4.

When the present value of an ordinary annuity is sought, the general formula is

$$PV=A\left[1-\frac{\left[\frac{1}{(1+i)^{n}}\right]}{\left(\frac{1}{1+i}\right)}\right]$$

$$ where $$

$$ A= Amount of the annuity (  \text { per period }). $$

Illustration 4-11 . In Illustration 4-6 , we computed the present value of the following series of future amounts, assuming an annual interest rate of 6.25 % :

<table><tr><td>Years from Now</td><td>Promised Payment by Issuer</td></tr><tr><td>1</td><td>$100</td></tr><tr><td>2</td><td>100</td></tr><tr><td>3</td><td>100</td></tr><tr><td>4</td><td>100</td></tr><tr><td>5</td><td>1,100</td></tr></table>


Instead of annual payments, let's assume that the payments are made by the issuer every 6 months, in the following way:

<table><tr><td>6-month Periods from Now</td><td>Promised Payment by Issuer</td></tr><tr><td>1</td><td>$50</td></tr><tr><td>2</td><td>50</td></tr><tr><td>3</td><td>50</td></tr><tr><td>4</td><td>50</td></tr><tr><td>5</td><td>50</td></tr><tr><td>6</td><td>50</td></tr><tr><td>7</td><td>50</td></tr><tr><td>8</td><td>50</td></tr><tr><td>9</td><td>50</td></tr><tr><td>10</td><td>1,050</td></tr></table>


---

48

PART 1 Time Value of Money

This is equivalent to an ordinary annuity of $50 per 6-month period for 10 6-month periods and $1,000 to be paid ten 6-month periods from now. Notice that the $1,000 is treated on the same time-period basis as the annuity.

The present value of the ordinary annuity, for

$$A=\$50;$$

$m=2$ (that is, payments every 6 months);

$$i=0.03125(0.0625  annual interest rate divided by  2) ;$$

$$n=10  (5 years times 2)$$

$$ is $$

$${\begin{array}{rl}
PV& =50{\left[1-{\frac {1}{(1.03125)^{10}}}}\right]}\\
& =50{\left[1-{\frac {1}{1.360315}}\right]}\\
& =50{\left[1-{\frac {735124}{0.03125}}\right]}\\
& =50(8.4760)\\
& =$423.80.
\end{array}}$$

The present value of the $1,000 to be received after 10 6-month periods, for

$$FV=\$1,000;$$

$m=2$ (that is, payments every 6 months);

$$i=0.03125(0.0625  annual interest rate divided by  2) ;$$

$$n=10  (5 years times 2)$$

$$ is $$

$$\begin{aligned}
PV&=\$1,000\left[\frac{1}{(1.03125)^{10}}\right]\\
&=\$1,000\left[\frac{1}{1.360315}\right]\\
&=\$1,000(0.735124)\\
&=\$735.12.
\end{aligned}$$

The present value of the future value series offered by the financial instrument is then:

<table><tr><td>Present value of ordinary annuity of$50 for 10</td><td>$423.80</td></tr><tr><td>6-month periods at 3.125%</td><td></td></tr><tr><td>Present value of$1,000 after 10 6-month periods at 3.125%</td><td>735.12</td></tr><tr><td>Total present value</td><td>$1,158.92</td></tr></table>


---

CHAPTER 4 Present Value

49

Notice that because the payments are made more often, the present value of the future payments has increased from $1,156.89 to $1,158.92.

Illustration 4-12. Suppose a banker agrees to make a $100,000 30-year loan to an individual to purchase a home. Under the terms of the loan, the monthly payments to be made by the individual will all be the same. The annual interest rate that the banker charges for the loan is 12%. How much must the fixed monthly payment be in order for the banker to realize an annual interest rate of 12%?

We can employ the formula for the present value of an ordinary annuity to determine the fixed monthly payment. The banker wants to receive an annuity of some fixed monthly amount such that the present value of that ordinary annuity, at an annual interest rate of 12 % , is $ 100,000. In the formula for the present value of an ordinary annuity, the number of monthly payments is 360 (30 years times 12) and the interest rate is 1 % (12% divided by 12). Therefore, we know the following:

$$100,000=A\left[\frac{1-\left(\dfrac{1}{(100)^{560}}\right)}{0.01}\right]$$

The unknown is A, the monthly annuity or monthly loan payment. We can solve for A as follows:

$${\begin{array}{rl}
$100,000&={\begin{array}{c}
{\left[1-{\frac {1}{3549641}}\right]}\\
0.01
\end{array}}\\
&={\begin{array}{c}
{\left[1-{\frac {0.0278167}{0.01}}\right]}\\
0.01
\end{array}}\\
&=A(97.21833).
\end{array}}$$

Solving for A,

$$A=\frac{\$100,000}{97,21833}=\$1,028.61$$

Therefore, the fixed monthly payment must be $1,028.61.

## Unequal Discount Rates

Throughout this chapter we have assumed that the same interest rate or discount rate should be used to calculate the present value of each payment to be received. This assumption is unwarranted. As we explain in Chapter 8, there is a reason why each payment to be received should be discounted at a unique rate. The present value of a series of payments is then the sum of the present value of each payment where each payment is discounted at a unique rate.

Illustration 4-13 Let's consider Illustration 4-6, where the financial instrument makes the following five payments: $100 for 4 years and $1,100 in the fifth year. When

---

50

PART I Time Value of Money

each payment is discounted at a 625% annual interest rate, the total present value is $1,156.89. Suppose, instead, that the interest rate for each year is as shown below:

<table><tr><td>Years from Now</td><td>Promised Payment by Issuer ($)</td><td>Interest Rate (%)</td></tr><tr><td>1</td><td>$100</td><td>4.80%</td></tr><tr><td>2</td><td>100</td><td>5.25</td></tr><tr><td>3</td><td>100</td><td>5.50</td></tr><tr><td>4</td><td>100</td><td>6.00</td></tr><tr><td>5</td><td>1,100</td><td>6.25</td></tr></table>


The present value of each promised payment is shown below. Each payment is discounted at the required yield.

<table><tr><td>Years from Now</td><td>Promised Payment by Issuer ($)</td><td>Required Yield (%)</td><td>Present Value of$1</td><td>Present Value of Payment ($)</td></tr><tr><td>1</td><td>$100</td><td>4.80%</td><td>0.954198</td><td>95.4198</td></tr><tr><td>2</td><td>100</td><td>5.25</td><td>0.902726</td><td>90.2725</td></tr><tr><td>3</td><td>100</td><td>5.50</td><td>0.851614</td><td>85.1613</td></tr><tr><td>4</td><td>100</td><td>6.00</td><td>0.792094</td><td>79.2093</td></tr><tr><td>5</td><td>1,100</td><td>6.25</td><td>0.738508</td><td>812.3590</td></tr><tr><td></td><td></td><td></td><td colspan="2">Total present value =$1,162.4219</td></tr></table>


The present value of the cash flows is $1,162.42.

## PRICING ANY FINANCIAL INSTRUMENT

The price of any financial instrument is equal to the present value of the expected cash flows from investing in the financial instrument. Determining the price, therefore, requires the following input:

- 1. Estimation of the expected cash flows;
2. Determination of the appropriate interest rate or discount rate so that the
present value of the cash flows can be computed.
The cash flow in any period is simply the difference between the cash inflow and the cash outflow from investing in the financial instrument. The expected cash flows of some financial instruments are simple to compute; for others, the task is not as simple. The determination of the interest rate or discount rate reflects the required yield for financial instruments with comparable risk.

## SUMMARY

In this chapter we explained how to compute the present value of amounts to be received in the future or payments to be made in the future. A summary of the formulas used in this chapter and the appendix to compute present values is presented in Exhibit 4-1.

---

$$ EXHIBIT 4-1 $$

## Summary of Formulas for Computing Present Value

1. Present value of a future value N years from now:

$$PV=FU\left[\frac{1}{(1+i)^{N}}\right]$$

$$ where $$

PV = Present value ($); FV = Future value ($); i = interest rate (in decimal form); N = Number of years.

2. Present value of a future value n periods from now:

$$PV=FU\left[\frac{1}{(1+i)^{n}}\right]$$

$$ where $$

i = Periodic interest rate [annual interest rate (in decimal form) divided by m] j = Annual interest paid [annual interest paid (in decimal form) multiplied by m] k = Frequency of receipt or payment of the future value.

3. Present value of an amount to be received at the end of 1 year assuming interest is continuously compounded:

$$PV=FVE^{-t}.$$

where e is the base of the natural logarithm (2.71828 . . .).

4. Present value of an amount to be received N years from now assuming interest is continuously compounded:

$$PV=FVe^{N+1}$$

5. Present value of an ordinary annuity for N years:

$$PV=A\left[1-\frac{[1}{(1+i)^{2}}\right]$$

$$ where $$

$$ A= Amount of the annuity (\$). $$

6. Present value of an ordinary annuity for n periods:

$$PV=A\left[1-\frac{[1}{(1+i)^{2}}\right]$$

$$ where $$

A = Amount of the annuity (in dollars) per period; i = Periodic interest rate [annual interest rate (in decimal form) divided by m].

7. Present value of a perpetual annuity:

$$PV=\frac{A}{T}.$$

---

52

PART 1 Time Value of Money

## APPENDIX

## Continuous Compounding

In the appendix to Chapter 3, we showed explained that the future value based on continuous compounding is

$$F V=P e^{i},$$

where e is the base of the natural logarithm (2.71828...). The present value when there is continuous compounding is a special-case formula which we will discuss in this appendix.

Solving the above equation for P and replacing P with PV (for present value), we obtain

$$PV=FU\left(\frac{1}{e^{t}}\right),$$

or, equivalently,

$$PV=FVe^{-i}$$

For example, suppose that $1,000 is to be received 1 year from now. Assuming that interest can be earned at 5% compounded continuously, the present value is

$$\begin{aligned}
PV=&1,000e^{-0.05}\\
&=951.23.
\end{aligned}$$

The formula above is for the present value when there is continuous compounding for 1 year. If it is more than 1 year into the future, say N years, then the present value after N years is computed as follows:

$$PV=VF\ e^{-N\times1}.$$

For example, the present value of $1,000 to be received 5 years from now assuming an interest rate of 5% is

$$PV=1,000e^{(5/15\times0.05)}$$
$$=778.80.$$

