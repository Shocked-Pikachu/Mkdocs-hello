# Introduction to Finance Course Notes

## Introduction

### Real Assets v.s. Financial Assets

Net Worth = Assets - Liabilities

Leverage = Liabilities / Assets

Financial assets and financial liabilities will cancel out if we aggregate all balance sheets, leaving only **real assets**.

### Types of Financial Assets

+ **Fixed-income securities (debt securities):** The stream of income is determined when issued. Therefore, it's considered less risky.
+ **Equity (common stock):** Represents ownership share in a corporation. Creditors are not owners of the corporation, so common stock only represents a **residual claim**. Common stock is closely related to the condition of business, which is different from debt securities.
  + **Limited liability**. The Stockholders have no obligations to pay more money to meet the shortfall of debt securities.
+ **Derivatives**: options, futures, structured finance

### Finacial Markets and the Economy

Financial assets allow us to make the most of economy's real assets.

+ The information role: efficient allocation of resources
+ Consumption timing: smooth consumption (If there is no storage or investment, the consumption is always less than income.)
+ Allocation of risk: Different types of financial assets have different risks, which satisfies various tastes for risk.
+ Separation of ownership and management

### Financial System

**Financial intermediaries** often have high leverage.

Bank is the major part of financial intermediaries.

Surplus Units & Deficit Units & Intermediaries & Markets

## Allocating Resources Over Time

### Time Value of Money

**Interest rate** represents the time value of fund in the equilibrium.

**General equilibrium:**

+ Surplus unit is the fund *supplier*.
+ Deficit unit is the fund *demander*.
+ In equilibrium, the fund supplied meets the fund demanded (The same mechanism as market price. Interest rate is the relative "price" of today's funds and tomorrow's funds).

### Compounding, Future Value and Present Value

Discounting future values back to the present

### Annuity and Perpetuity

APR (Annual Percentage Rate) and EFF (Effective Annual Rate)

$APR = {\rm period\ rate\times number\ of\ periods\ per\ year}$​

$EFF=(1+\frac{APR}{m})^m-1$, where $m$ is the number of periods per year

APR does not take into account the compounding of interest within a specific year (simple interest)

## Asset Classes

### Fixed-Income Market

+ Money market: short-term debt securities, liquid (good liquidity, easy to sell), low risk
  + [Treasury bills (T-Bills)](https://www.investopedia.com/terms/t/treasurybill.asp): auction
  + T-bill yields: discount yield, investment yield
+ Fixed Income Capital Market
  + Longer term debt securities
  + Coupon paid semiannually (equal to interest rate * Face Value) + Face Value
    + The yield (yield to maturity) of a bond is defined as the interest rate at which the **present value of the payment stream** equals the **bond price**
  + More examples
    + Zero-coupon bond (ZCB)
    + Perpetuity
  + Coupon rate & interest rate? (related to $p_0 / FV$)
+ Factors that influence yields

### Equities

Dividends & capital gains

Market capitalization = share price * shares outstanding

### Derivatives

#### Options

Option confers a **right**, not an **obligation** to its holder.

#### Futures

Futures -- contract

## Trading, Margin and Short Sale

### How Firms Issue Securities?

Public v.s. Private corporation

+ The requirement to disclose information
+ The liquidity of shares

Initial Public Offerings (IPOs) << investment bankers

Once IPOs is completed, **secondary market** is formed.

### How Securities are Traded?

#### 4 types of markets

Direct search (bond markets), brokered markets, dealer markets (stock markets), auction markets

#### Bid and Ask prices

+ Market orders: executed immediately, cannot ensure to buy in at the price when you submit the order
+ Limit orders: price-contingent orders, constitute bid & ask prices

The difference between bid price and ask price would reflect the intensity of competition in stock market.

### Buying on Margin

Shares serve as collateral

Margin requirements

+ Initial margin
+ Maintenance margin (sensitive to price movements, when violated, the broker has the right to sell a proportion of shares to raise the margin)

When buying on margin, investors have the opportunity to gain higher rate of return.

### Short Sales

Purpose: to profit from a decline in the price of a stock or security

Mechanics:

- Borrow stock through a dealer
- Sell it and deposit proceeds and margin in an account
- Closing out the position: Buy the stock and return to the party from which it was borrowed

Special mechanism is needed to avoid default

## Stock Market Indexes

### Stock Price Indexes

+ Price weighted indexes (do not consider the scale of corporations)
+ Value weighted indexes

### Stock Splits

Share price halves, shares outstanding doubled

Price weighted indexes must be adjusted >> Adjust the denominator after stock split

## Funds

Small investors face many problems, and investment companies allow them to circumvent these problems.

### Types of Investment Fund

**Open-end funds**: the amount of funds may change

**Closed-end funds**: the amount of funds are fixed

**Exchanged-traded funds (ETFs)**: combine the best features of open-end and closed-end funds.

### Open-End Funds

Net Asset Value = (Market value of asset - Liability) / Shares Outstanding

Mutual funds / Hedge funds

Migration to index funds and ETFs (passive funds)

### Closed-End Funds

CEF raises money in an IPO

Shares are **not redeemable** - exit by selling to other investors

Share price may deviate from NAV - *premium / discount*

Closed-end funds usually trade at a *persistent discount* to their NAV. (WHY?)

### ETFs

Exchanged-traded funds

- can redeem before the fund maturity
- can trade freely on the secondary market

## Historical Returns on Risky Portfolios

### Nominal Return and Real Return

$$
r=\frac{1+i}{1+\pi}-1\approx i-\pi
$$

Where $\pi$ is the inflation rate, $r$ is the real return, and $i$ is the nominal return

### Example: Inflation and Returns of Government Bond

Expectation, standard deviation

Dispersion of bonds: does not reflect risk of the security, but rather the changes in the *risk-free* rate over time.

### Risk Premium

Risk premium: the *expected* HPR on a risky asset and the risk-free rate.

Treasure-bonds may have risks (changes in risk-free rate overtime)

**Excess return**: the difference between the *actual* rate of return on a risky asset and the risk-free rate.

Excess return can be considered as the additional profits provided for the investors in order to attract them on riskier financial products.

Obviously, the expected value of **excess return** is **risk premium**.

## Introduction to Portfolio Choice

### Risk Aversion and Utility

Assumption: Most investors are **risk averse**, indicating that they reject investment that are fair games or worse.

Utility function
$$
U=E(r)-\frac12A\sigma^2
$$
Where $E(r)$ is the expected return on the asset, $\sigma^2$ is the varience of returns.

$A$ reflects the extent to which investors are risk averse.

- $A > 0$ : risk averse
- $A = 0$ : risk neutral
- $A < 0$ : risk loving

Here we have assumed that the utility function only relies on the **expected value** and the **standard deviation** (which is a strong assumption).

*However, in some circumstances, such as a portfolio where dominance exists, the utility function fails to describe people's choice.*

*If returns of portfolio satisfy the normal distribution, then the utility function is strictly valid.*

### Preferences & Choice

#### Certainty equivalent

For a certain investor, certainty equivalent and the risky asset have the same utility.

#### Indifference curves

Higher curves correspond to higher ranked assets.

Indifference curves must be upward-sloping (for risk-averse investors): Investors face trade-off between expected profits and risks.

Indifference curves cannot cross.

As $A$​ increases, indifference curves become steeper.

## Constructing Portfolios

### Combining Two Assets

Asset returns are random variables $r_1$ and $r_2$.

Portfolio: $r_p=\sum_{i=1}^{N}w_ir_i$

Portfolio expected return and risk:
$$
E(r_p)=w_1E(r_1)+w_2E(r_2)\\\
\sigma_p^2=w_1^2\sigma_1^2+w_2^2\sigma_2^2+2w_1w_2\sigma_{12}
$$

### Portfolios with a risk-free asset

If $\sigma_1^2=0$, then $\sigma_p^2=w_2^2\sigma_2^2$.

#### Capital Allocation Line, CAL

$$
E(r_c)=r_f+y(E(r_p)-r_f)=r_f+S\sigma_c
$$

$E(r_p)-r_f$ is called the **risk-premium** of the asset $P$​.

$S$: Reward-to-Volatility (Sharpe) Ratio
$$
S=\frac{\rm Risk\ premium}{\rm SD\ of\ excess\ returns}=\frac{E(r_p)-r_f}{\sigma_p}
$$
*What does the CAL look like if borrowing rate exceeds $r_f$?*

CAL becomes flatter when $y>1$.

**Investors will always choose the portfolio with the higher Sharpe ratio, regardless of the inverstors' preferences.**

#### Optimal Choice

The solution to optimal portfolio allocation is
$$
y^*=\frac{E(r_p)-r_f}{A\sigma_p^2}
$$
We can also obtain this solution by moving indifference curves.

Weight can be negative.

## Optimal Risky Portfolios

### Diversification and Portfolio Risk

Market-risk, also called systematic and nondiversifiable

Firm-specific risk (can be eliminated by diversification)

### Portfolio of Two Risky Assets

$$
E(r_p)=(1-x)E(r_d)+xE(r_e)\\\
\sigma_p^2=(1-x)^2\sigma_d^2+x^2\sigma_e^2+2x(1-x)\sigma_{de}
$$

**Portfolio opportunity set**: $(\sigma_p,E(r_p))$ combinations obtained by varying $x$.

We can find a point with minimum variance (when $\rho\neq1$, $\rho$ is the correlation coefficient) >> **minimum variance portfolio**.

We can prove that the portfolio opportunity set curve is a hyperbola on $E(r_p)-\sigma$ plane.

> e.g. If we have two assets $D$ and $E$ with the same expected return but different standard deviation, but their returns are independent ($\sigma_{DE}=0$), we can still combine two risky assets in a way that minimizes the risk.
> $$
> \min x^2\sigma_D^2+(1-x)^2\sigma_E^2
> $$
> Obviously, $x$ is neither 0 nor 1.

Efficient frontier: the upward-slopng segment of the portfolio opportunity set.

Optimal choice is at the tangent point of indifference curve and portfolio opportunity set >> optimal choice depends on preferences.

If the indifference curves are flatter (the investor is less risk averse), the investor would prefer a riskier choice.

## Markowitz Portfolio Selection Model

### Optimal CAL

Each risky portfolio can be combined with bills (risk-free assets).

The risky portfolio is constructed by combining two risky assets, which can be represented in a portfolio opportunity set.

Whatever the investor's preference is, he / she will always choose the **CAL with the greatest slope**. >> optimal CAL

Different investors will choose different points on the same CAL (different allocation bewteen risky and risk-free assets). >> **separation property**

The separation property holds when a risk-free asset is available and borrowing is possible at the risk-free rate. No borrowing? Higher borrowing rate?

### Multiple Risky Assets

Suppose there are $n$ assets.

Asset returns: $r_1,...,r_n$.

Expected returns: $E(r_1),...E(r_n)$.

Variances and covariances: covariance matrix
$$
\begin{pmatrix}
\sigma_1^2 & \sigma_{12} & \cdots & \sigma_{1n}\\\
\sigma_{21}& \sigma_2^2  & \cdots & \sigma_{2n}\\\
\vdots		 & \vdots			 &				& \vdots\\\
\sigma_{n1}& \sigma_{n2} & \cdots & \sigma_n^2
\end{pmatrix}
$$
This is a symmetric matrix, therefore, there is only $n(n+1)/2$ unique covariances (variances).

#### Portfolio Expected Return

Portfolio expected return is the weight average of the expected returns of the underlying assets.
$$
E(r_p)=\sum_{i=1}^{n}w_iE(r_i)
$$

#### Portfolio Risk

Portfolio variance depends on variances and covariances of the returns of underlying assets, and portfolio weights.
$$
\sigma_p^2=\sum_{i=1}^{n}\sum_{j=1}^{n}w_iw_j\sigma_{ij}
$$
Note that $\sigma_{ii}=\sigma_i^2$ and $\sigma_{ij}=\sigma_{ji}$.

### Portfolio with three risky assets

Additional assets will help us diversify the choice, so that we can obtain a portfolio with the same expected return but with lower risk.

The portfolio opportunity set for three (or more) assets is a two-dimensional **region** in $E(r)-\sigma$ space (no longer a curve).

We only focus on the **minimum variance frontier** - left boundary of the portfolio opportunity set. And the upward sloping part is the **efficient frontier**. The portfolio with the lowest attainable variance is the **global minimum variance portfolio**.

Again, if a risk-free asset is available, we will have the separation property (optimal CAL).

### Markowitz Portfolio Selection Model

*When investors can borrow freely at the risk-free rate, they will combine bills (or borrowing) with the risky portfolio on the efficient frontier which has the highest reward-to-volatility ratio (Sharpe ratio).*

*Risky component of optimal portfolio is the same for all investors.*

> When investors are prohibited from shorting assets?
>
> Restriction: $w_i\ge0$, the minimum variance frontier may differ.
>
> No risk-free asset? Borrowing rate different from lending rate? No borrowing?

## Index Models

### Excess Returns

The excess return: the difference between an asset's return and the risk-free rate, $R_i=r_i-r_f$.

Consider a market index $M$ with excess return $R_m=r_m-r_f$​.

> We often use [the Standard & Poor's 500 Index (S&P 500 Index)](https://www.investopedia.com/terms/s/sp500.asp) as the market index.

Hypothesis: movements in $R_i$ and $R_m$ are correlated.

### Index Model

$$
R_i=\alpha_i+\beta_iR_m+e_i
$$

$\beta$ is called exposure, which reflects teh sensitivity to factors that affect all securities.

$e_i$ is a random variable reflecting firm-specific risk.

#### Assumptions on $e_i$

- Zero expectation: $E(e_i)=0$
- Zero covariance with $R_m$: $cov(e_i,R_m)=0$
- Zero covariance with $e_j$: $cov(e_i,e_j)=0$
- Homoscedasticity: $\sigma^2(e_i)={\rm const}$

#### Estimating the Model

The parameters $\alpha_i$ and $\beta_i$ can be estimated by **linear regression** with $R_i$ as the dependent (explained) variable and $R_m$​ as the independent (explanatory) variable.

Linear regression model is always the best model if we have no information on the real relationship.

Residuals: $\hat{e_i}=R_i-(\hat{\alpha_i}+\hat{\beta_i}R_m)$

Predicted value: $\hat{R_i}=\hat{\alpha_i}+\hat{\beta_i}R_m$

#### Estimating Firm-specific Risk

Mean value:
$$
m=\frac{1}{T}\sum_{t=1}^{T}\hat{e_i}=0
$$
An unbiased estimator of the variance $\sigma^2(e_i)$:
$$
s^2(e_i)=\frac{1}{T-2}\sum_{t=1}^{T}\hat{e_i}^2=\frac{SSR}{T-2}
$$
Degrees of freedom of $\hat{e_i}$: $T-2$

### Variance Decomposition

We can decompose the risk of $R_i$​ into two components: systematic and idiosyncratic
$$
\sigma^2_i=\beta_i^2\sigma_m^2+\sigma^2(e_i)
$$
Here, we used $R_i=\alpha_i+\beta_iR_m+e_i$ and $cov(e_i,R_m)=0$.

### Diversification

We assume the above model holds (other factors? other models?).

Consider an equally weighted portfolio $P$
$$
R_p=\alpha_p+\beta_pR_m+e_p
$$
where $\alpha_p$, $\beta_p$, and $e_p$ are the mean value of $\alpha_i$, $\beta_i$, and $e_i$

Then the variance $\sigma^2(e_p)$​ becomes
$$
\sigma^2(e_p)=\frac{1}{n^2}\sum_{i=1}^n\sigma^2(e_i)=\frac1n\overline{\sigma^2}\to0(n\to\infty)
$$
As $n\to\infty$, $e_p$ has zero mean and (approximately) zero variance >> we can consider $e_p$ as zero.

Firm-specific risk is **diversifiable** while systematic risk is not.

## Capital Asset Pricing Model

### Capital Asset Pricing Model (CAPM)

Key idea: separation property

When the market clears, **optimal risky portfolio must be the market portfolio**.

CAPM is not aimed for predicting return, but it can provide a estimation for **fair return** (benchmark)
$$
E(r)=\frac{E(P)-P_0}{P_0}(>,<,=)\ {\rm fair\ value}
$$

### CAPM Assumption

Individual behavior & market structure

Investors would combine bills/ borrowing with the market portfolio $M$.

CML (capital market line) is the CAL that is constructed from the risk-free asset and the market portfolio

### Individual Securities

Intuition: When adding a new security into the existing market, how would this new security affect the market?

Variance of Market Portfolio:
$$
\sigma_m^2=\sum_i\sum_jw_iw_j\sigma_{ij}=\sum_iw_i\sigma_{im}
$$
Here $\sigma_{im}$ is the covariance of $r_i$ with the market return $r_m$:
$$
\sigma_{im}=Cov\left(r_i,\sum_{j}w_jr_j\right)=\sum_jw_j\sigma_{ij}
$$
Therefore, the **contribution of asset $i$ to $\sigma_m^2$ is $w_i\sigma_{im}$**

- Contribution to Variance: $\frac{w_i\sigma_{im}}{\sigma_m^2}$
- Contribution to Risk Premium: $\frac{w_i(E(r_i)-r_f)}{E(r_m)-r_f}$

The key idea is that **$i$'s contribution to risk premium = $i$'s contribution to risk variance**

Result:
$$
E(r_i)=r_f+\frac{\sigma_{im}}{\sigma_m^2}(E(r_m)-r_f)=r_f+\beta_i(E(r_m)-r_f)
$$
Risk premium is proportional to $\beta_i$, which reflects the contribution of asset $i$ to market variance

Graphically, this line is called **Security Market Line**

> Can $\beta_i<0\Rightarrow E(r_i)<r_f$ ? Why would someone choose a security with returns less than the risk-free asset?
>
> It has the property of *insurance*. When the stock market decline, assets with $\beta_i<0$​ could offer some compensation. Therefore, a negative risk premium is reasonable.
>
> Note: Negative risk premium does not mean free risk, rather it serves as a kind of insurance.

Although some assets could deviate from SML, but eventually, all assets will return to SML in equilibrium. Unfortunately, the reality is opposite...

### CAPM and the Index Models

Index model is only a econometric model, and its slope parameter is
$$
\beta_i=\frac{Cov(R_i,R_m)}{Var(R_m)}
$$
The index model beta coefficient is the same as the beta of the CAPM expected return-beta relationship.

$R_i=\alpha_i+\beta_iR_m+e_i$ v.s. $E(r_i)-r_f=\beta_i(E(r_m)-r_f)$

CAPM predicts $\alpha=0$ for all securities: positive alpha implies return without risk.

## Arbitrage Pricing Theory

### The Concept of Arbitrage

Arbitrage: a zero investment portfolio that yields a sure profit

Asset prices must satisfy a **"no arbitrage condition"**

### APT: Basic Ideas

Arbitrage plays key role in pricing of derivatives.

Two key ideas:

- Firm-specific risk can be effectively eliminated through diversification
- Asset prices should be such that arbitrage opportunities do not exist

### Returns: Individual Securities & Portfolio

Define $F=r_m-E(r_m)$, where $r_m$ is the market return ($F$ describes the change in market index).

Then according to the index model, $r_i=E(r_i)+\beta_iF+e_i$

For a portfolio (well-diversified), $r_p=E(r_p)+\beta_pF$

So there is a linear relationship between $r_p$ and $F$

### Expected Returns and Betas

For 2 **well-diversified** portfolios $P$ and $Q$, if they have equal betas then their expected returns should also be equal (Otherwise there exists a arbitrage opportunity).

Different betas? The APT states that for all well-diversified portfolios, the risk premium is proportional to beta
$$
\frac{E(r_P)-r_f}{\beta_P}=\frac{E(r_Q)-r_f}{\beta_Q}
$$
A brief proof: If $P$ and $Q$ have different betas, we can combine $P$ with a risk-free asset to construct a new portfolio $S$ that has the same beta as $Q$​. Then based on the previous discussion, we know $S$ and $Q$ should have the same expected returns.

### APT and CAPM

APT applies to well diversified portfolios and not necessarily to individual stocks.

APT does not require restrictive CAPM assumptions, and is based on **arbitrage** rather than **equilibrium**.

## Bond Prices and Yields

### Yield

For a zero-coupon bond (ZCB) maturing in $t$ years with a price of $P$, the yield $y$ of the bond solves the following equation:
$$
P=\frac{100}{(1+y)^t}
$$
Bonds are often quoted at a **spread** = yield - $r_f$

### Value of a Coupon Bond

Assume the timing is at issuance or on a coupon date

- When $y=c$​, the bond trades at **par**
- When $y<c$, the bond trades at a **premium**
- When $y>c$, the bond trades at a **discount**

### Bond Pricing between Coupon Dates

You should pay the all-in (or dirty) price = quoted (or clean) price + interest accrued

Accrued interest: $AI=C\times N_t/D$

All-in price can be obtained by calculating the present value of the bond at the trading date. Clean price equals all-in price minus accrued interest.

### Dollar Duration

The dollar duration measures the dollar change in a bond's value to a change in the market interest rate (yield).

Also call money duration of DV01.
$$
\Delta P=-DV01\times\Delta y
$$
However, this relation only holds approximately because the relation between price and yield is non-linear.

The price of a bond is a **convex** function of its yield.

### Corporate Bonds

- Callable bonds: Can be repurchased before the maturity date. The issuer (corporation) have more rights >> higher yield as a compensation.
- Puttable bonds: Give the hondholder (investor) an option to retire or extend the bond's life.
- Floating-rate bonds: Have adjustable coupon rate.
- Convertible bonds: Can be exchanged for shares of the firm's common stock. Reducing pressure on issuers' cash repayments and avoiding insolvency (debt-to-equity conversion).

### International bonds

- Foreign Bonds: Issued by a borrower from another country denominated in the curreny of which the bond is sold.
- Eurobond: Denominated in one currency but sold in other national markets.

## The Term Structure of Interest Rates

### Yield Curve

The yield curve displays the relationship between yield to maturity (YTM) and time to maturity.

We care about pure yield curve (uses zero coupon bonds).

### Zero Coupon Bonds (Zeros)

We can construct a zero coupon bond using a ZCB and a non-ZCB (long one and short another to cancel out cash flow on the coupon date).

### The Yield Curve under Certainty

spot rate: $y_2$ / short rate today: $r_1$ / short rate next year: $r_2$

A spot rate is the geometric average of its component short rates.
$$
(1+y_2)^2=(1+r_1)(1+r_2),\ r_1=y_1
$$
If $r_2>r_1$, the yield curve slopes up - May indicate rates are expected to rise.

If $r_2<r_1$, the yield curve slopes down - May indicate rates are expected to fall.

Future interest rates are uncertain?? - **Forward interest rates**: a forecast of a future short rate

In general, we have
$$
1+f_n=\frac{(1+y_n)^n}{(1+y_{n-1})^{n-1}}
$$
### The Yield Curve under Uncertainty

When future interest rates are uncertain?
$$
(1+y_2)^2=(1+r_1)(1+E(r_2))
$$
$E(r_2)$ denotes expected short rate for the following year

> Suppose a zero coupon bond has a face value of 1000.
>
> 1-year zero v.s. 2-year zero
> $$
> E(P_1)=\frac{1000}{1+E(r_2)},\quad\frac{E(P_1)-P_0}{P_0}>r_1
> $$
> Investors are risk averse, so they require a risk premium to hold a longer-term bond >> $E(r_2)<f_2$​

### Theories of Term Structure

#### The Expectations Hypothisis Theory

Liquidity premiums are zero.

An upward-sloping yield curve would be clear evidence that investors anticipate increases in interest rates.

The risk premium will be zero.

#### Liquidity Preference Theory

If the liquidity premium is zero
$$
f_n=E(r_n)
$$
A long-term horizon investor would be inclined to invest in long-term bonds, while a short-term horizon investor would be inclined to invest in short-term bonds (Suppose all investors are risk averse).

Whether the liquidity premium is positive or not depends on which kind of investors dominates the market.

In reality, there are more short-term horizon investors >> $f_n>E(r_n)$​

#### Interpreting the Term Structure

An upward sloping curve could indicate:

1. Rates and expected to rise
2. Investors require large liquidity premiums to hold long term bonds

Even if the expected short rate keeps constant in the future, the yield curve could be upward sloping due to positive liquidity premium.

## Equity Valuation

### Equity Returns

Stocks don't promise any stream of payments - Both dividends and capital gains are uncertain

Expected return from buying shares:
$$
E(r)=\frac{E(D_1)+E(P_1)-P_0}{P_0}
$$

It is important to forecast a reasonable value of $P_0$

### Market Capitalization Rate & Fundamental Value

The **market capitalization** rate $k$ of a security is the expected return which is commensurate with its risk $\beta$​.
$$
k=r_f+\beta(E(r_m)-r_f)
$$
also called the **required rate of return**

The **fundamental value** (or **intrinsic value**) of a security is the price at which its expected return equals its market capitalization rate.

If we know $k,E(P_1),E(D_1)$, we can estimate the fundamental value $V_0$ (If $P_0<V_0$, the security is underpriced).

### The Dividend Discount Model

Key assumption: prices equal fundamental values in future

$$
V_0=\frac{D_1}{1+k}+\frac{D_2}{(1+k)^2}+\frac{D_3}{(1+k)^3}+\cdots
$$
which equals the cash flow that the shareholder will get from long-term stock ownership.

### The Constant Growth DDM

Suppose dividend grows at a constant annual rate $g$ ($g<k$)
$$
D_n=D_{n-1}(1+g)=D_1(1+g)^{n-1}
$$
We can derive that
$$
V_0=\frac{D_1}{k-g}
$$
### Multistage DDM

Key idea: divident stream has several components

### Price-Earnings Ratios

Let $E_1$ denote expected earnings-per-share and $b$ denote retention ratio (or plowback ratio)

Expected dividends: $D_1=(1-b)E_1$

ROE: return on equity (how well the company utilizes its equity to generate profits). Earnings per period are equal to ROE times equity.

The dividend growth rate is proportional to both ROE and retention ratio: $g=ROE\times b$​

The price-earning ratio is
$$
\frac{P_0}{E_1}=\frac{1-b}{k-g}
$$

## Option Strategies and Put-Call Parity

### Options

Call Option / Put Option

American Option / European Option

Option buyer (holder) pays a price (option premium) to option seller (writer)

Option is a **right** for the option buyer and an **obligation** for the option seller

Options are **in the money** if immediate exercise is profitable (the price of the underlying asset is higher than the strike price), and they are **out of the money** if not

- Why buy call options instead of just shares?
- Why write options?
- Whey do out-of-the-money options have value?

### Margin and Clearing

The writer of an option must post margin because it is possible that the writer would default

### Call Options: Payoffs and Profit

Derivatives are a zero-sum game, payoff to the writer is negative the payoff to the holder

Suppose share price is $S_T$ at expiration date $T$ and the premium is $C$

Consider a call option with strike price $X$

Payoff to the holder: $0({\rm if}\ S_T\le X),\ S_T-X({\rm if}\ S_T>X)$​

Profit to the holder: $-C({\rm if}\ S_T\le X),\ S_T-X-C({\rm if}\ S_T>X)$

### Put Options: Payoffs and Profit

Payoff to the holder: $X-S_T({\rm if}\ S_T<X),\ 0({\rm if}\ S_T\ge X)$​

Profit to the holder: $X-S_T-C({\rm if}\ S_T<X),\ -C({\rm if}\ S_T\ge X)$

### Option Strategies

#### Covered Call

Buy shares and write call options

Call written is said to be "covered"

${\rm Payoff}=S_T({\rm if}\ S_T\le X),\ X({\rm if}\ S_T>X)$

${\rm Profit}={\rm Payoff}-S_0+C$, note that $S_0$ must be greater than $C$

#### Protective Put

Buy shares and put options

Why $P>X-S_0$?

### Put-Call Parity

Option pricing is based on **principle of replication**, also known as **Law of One Price (LOOP)**

NO arbitrage!

The idea underlies the **Put-Call Parity Theorem**

Construct two strategies with identical payoffs in every contingency: Protective Put & Call + Bills
$$
S_0+P=C+\frac{X}{(1+r_f)^T}
$$
If dividend is paid, $X\to X-D$

If the equation fails to hold, there exists an arbitrage opportunity

Therefore, the prices of the call and put options are related to each other, so we only need to care about the theory of call option pricing

### More Option Strategies

- Straddle: buy call and but put with the same $X$ and $T$ (Investors would earn profit if the stock price moves a lot)
- Bull spread: buy a call with $X_1$ and short a call with $X_2$ $(X_2>X_1)$
- Bear spread: sell a put with $X_1$ and buy a put with $X_2$ $(X_2>X_1)$
- Butterfly spread: buy one $C_1$, sell two $C_2$, and buy one $C_3$ $(X_1<X_2<X_3$ and $X_1+X_3=2X_2)$

## Options Pricing

Will American call options ever be exercised early?

We need to prove that $\forall t,\ C_t\ge S_t-X$​

Consider two strategies: call option & leveraged equity >> Call payoff always not less than leveraged equity payoff
$$
C>S_0-\frac{X}{(1+r_f)^T}>S_0-X
$$
Selling the American Call is more attactive than exercising it early. They are **"worth more alive than dead"** (no dividend)

However, early exercise of American puts is possible (when the stock price is very low)

### Call Pricing

We have proven that for a given $t$, $C_t\ge S_t-X$ (or exercising call options would bring less profit than selling it), so we only need to consider how to price European calls ($C^A=C^E$​)

Consider a simple case: Suppose share price is $S_0$, and can be either $S^+$ or $S^-$ at time $T$

Option payoff at time $T$ can be either $C^+$ or $C^-$

Consider leveraged equity portfolio & call (replicating portfolio)

Alternative: covered call & risk-free assets

### Hedge Ratio

Define the hedge ratio
$$
H=\frac{C^+-C^-}{S^+-S^-}
$$
Consider the strategy: write one option, buy $H$ shares. It is easy to show that this portfolio is **perfectly hedged** (risk-free)

*Generalizing the Two-State Approach...*
$$
\begin{aligned}
C_u&=xuS_u+Ry,\ C_d=xdS_d+Ry\\\
C_0&=xS_0+y=\frac1R\left(\frac{R-d}{u-d}C_u+\frac{u-R}{u-d}C_d\right)\\\
C_0&=\frac1R[qC_u+(1-q)C_d]=\frac1RE^Q(C_1)
\end{aligned}
$$
We can regard $q$ as a probability (risk-neutral probability)

### Risk Neutral Probability

$$
\begin{matrix}
& & uS_0\\\
& \nearrow &\\\
S_0 & & \\\
& \searrow & \\\
& & dS_0
\end{matrix}\quad\begin{matrix}
& & C_u\\\
& \nearrow &\\\
C_0 & & \\\
& \searrow & \\\
& & C_d
\end{matrix}
$$

Consider the above value tree

Portfolio A: $x$ stocks + $\$y$ T-bills = Portfolio B: Call option

No arbitrage condition tells us that the two portfolio should have the same payoff as well as the same price
$$
xuS_0+yR=C_u\\\
xdS_0+yR=C_d
$$
Here $R=1+r_f$​

We can solve for $x$ and $y$, then we know $C_0=xS_0+y$
$$
\begin{aligned}
C_0&=\frac1R\left(\frac{R-d}{u-d}C_u+\frac{u-R}{u-d}C_d\right)\\\
&=\frac1R(qC_u+(1-q)C_d)
\end{aligned}
$$
Here we define the risk neutral probability $q=(R-d)/(u-d)$, note that we always have $d<R<u$ (yes?)

The underlying asset has probability of $q$ to increase in value and $(1-q)$ to decrease in value (This is NOT the real probability!)

### Finding the Call Premium

Value tree approach can be generalized to arbitrary number of states

Numerical solutions may be computed (Black-Scholes Option Valuation)

## Futures

### Future Contracts

A futures contract calls for the delivery of an asset (or its cash value) at a specified (maturity) date at a specified (futures) price paid on the maturity date

Futures contract is a zero-sum game: profit to long means loss to short and vice versa

### Trading Mechanics

Chicago Mercantile Exchange acts as a clearing house and couterparty to both sides of the trade

If you are currently long, you simply instruct your broker to enter the short side of a contract to **close out** your position (There will be no physical delivery at this situation)

Most futures contracts are closed out by reversing trades (**NO actual delivery**)

Only 1-3% of contracts result in actual delivery of the underlying commodity (This can actually be seen as a speculative behavior)

### Convergence Property

The futures price and the spot price must converge at maturity
$$
{\rm Basis}_t={\rm Spot\ Price-Future\ Price}=S_t-F_t
$$
The difference is approximately 5 percent

Why buy/sell futures?

- Hedging
- Speculation
- To foresee open price next day (futures can be traded 24/7)

### Spot-Futures Parity Theorem

Let $S_T$ denote value of index at time $T$ / Profit to short futures position is $F_0-S_T$

Buy index and short futures position >> The portfolio is risk-free
$$
F_0=S_0(1+r_f-d)^T
$$
This is the Spot-Futures Parity Theorem, where $d$ is the **divident yield**: $d=D/S_0$

If the parity is violated, there exists an arbitrage opportunity

### FX Market and Covered Interest Arbitrage

FX market is where exchange rates are determined

- the spot foreign exchange (FX) market
- currency forward
- currency future
- currency swap

Direct quotation & Indirect quotation

**Covered interest parity** (indirect quotation)
$$
(1+i_¥)\frac{F_0}{S_0}=(1+i_\$)
$$
If $i_\$$ goes up, $S_0$ goes down - RMB depreciates

The Impossible Trinity or "The Trilemma": 1. Free capital flow; 2. Sovereign monetary policy; 3. Fixed exchange rate

## Structured Finance

### Structured Finance

Structured finance involves two economic functions:

- **Pooling** cash flows from economic assets (e.g. loans, mortgages)
- Issuance of prioritized claims (**tranches**) on the collateral pool

Due to the prioritization of tranches, many of the manufactured tranches are safer than the average asset in the collateral pool

Housing markets are prominent in the history of securitization

### Prioritization of Tranches

After the collateral pool is set, the claims against the pool are prioritized into tranches that are rated by their defaults risk

- **Attachment**: level of losses where the tranche begins losing principal
- **Detachment**: level at which tranche experiences total loss of principal

### Simple Illustrantion of CDO

Consider two bonds, each with face value of \$1 and default probability of 10%

Junior tranche & Senior tranche: the probability of default for each of the two tranches depends on how defaults are correlated

The probability of joint default:
$$
p_{DD}=p_D^2+c\times p_D\times(1-p_D)
$$
**Pairwise default correlation parameter** $c$ describes to what extent two defaults are correlated

As the correlation in defaults increases, risk shifts to the senior tranche (until two tranches have the same risk)

Insight: If the two assets are independent, the senior tranche has a low risk. But if the two assets are highly correlated, the two tranches both have high risks

### Simple Illustration of CDO-Squared

The junior tranches default at a 19% rate (which is high), but if we **combine the junior tranches into another CDO**, then the senior tranche of the second-round CDO defaults with probability 3.6% (which is much lower) - [CDO-squared](https://www.investopedia.com/terms/c/cdo2.asp) (CDO$^2$)

Note that the same issue with correlation applies yet again

## Financial Fragility

### Bank Runs Occur Repeatedly through Financial History

**Bank runs**: when large numbers of depositors withdraw funds at the same time due to concerns about the health of a bank

Why do bank runs occurs? How can we prevent them?

### Diamond and Dybvig (1983) Model of Bank Runs

DD (1983) showed how the maturity mismatch (duration mismatch) of bank's assets and liabilities makes them susceptible to runs

Three central assumptions underpin the model:

1. Productive investments have long horizons (**illiquid** in the short rum)
2. Consumers may urgently need funds, or may be able to wait
3. Banks cannot identity whether an individual will need immediate access to funds until a deposit is withdrawn

Beliefs and self-fulfilling runs: The bank fails if beliefs turn sour

### Measures to Prevent Runs

1. **Suspension of convertibility**: It doesn't work quite well (The bank does not know how many depositors truly need cash)
2. **Lender of last resort**: LoLR never actually lends, the backstop is what matters. In reality the central bank plays this role
3. **Deposit insurance**: The insurance does not guarantee all deposits, so that depositors will monitor the bank

Implicit Insurance (Too big to Fail)

