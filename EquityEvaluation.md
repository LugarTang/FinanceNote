Consider a holding period of one year, current share price $P_0$, future (uncertain) price $P_1$, and dividend-per-share $D_1$

Both $P_1$ and $D_1$ are random variables, with expected values $E(P_1)$ and $E(D_1)$ respectively

According to CAPM

The **market capitalization rate** (市场资本化率) $k$ of a security is the expected return which is commensurate with its risk $\beta$

$$
k = r_f+\beta(E(r_m)-r_f).
$$

This is also called the **required rate of return** (必要收益率)

The **fundamental value** $V_0$ of a security is the price at which its expected return equals its market capitalization rate; Sometimes called the intrinsic value (内在价值)

Equation:

$$
k=\frac{E[P_1]+E[D_1]-V_0}{V_0}
$$

## The Dividend Discount Model

To determine an asset’s fundamental value, we need to estimate its expected price

But how can we estimate future prices?

If we can get a reliable forecast of future dividends, and their rate of growth, we can estimate fundamental value using the dividend discount model (股利贴现模型)

Key assumption: **prices equal fundamental values in future**

Constant growth DDM

Suppose dividend grows at **constant annual rate** $g$

$$
V_0=\frac{D_1}{k-g}
$$

The DDM model is meaningless when $k < g$.

What if a stock never pay dividend? Can it have positive value?(asset bubble)

### Multi-stage DDM

Constant growth DDM is a useful benchmark, but constant growth is not realistic

Examples:

- Startups may be unprofitable for years (Amazon)
- Firms may need temporary restructuring (US Airways)

Multistage DDM allows for this

Some involve non-constant growth for finite periods, and one involves constant growth for infinite periods

## Price-Earning Ratios

Let $E_1$ denote expected earnings-per-share after interest and taxes.

Earnings are either retained or paid out as dividends

Let $b$ denote retention ratio (or plowback ratio) (收益留存率),

and $1−b$ the dividend payout ratio (股利支付率)

Then expected dividends are $D_1 = (1−b)E_1$.

ROE: return on equity (how well the company utilizes its equity to generate profits.)

a higher retention ratio (reinvestment) entails a higher growth rate at the cost of lowering current dividend

$$
g=ROE\times b.
$$

The value of the firm equals the value of the assets already in place, the **no-growth** value of the firm

plus

the net present value (NPV) of its future investments, which is called the **present value of growth opportunities (PVGO)**.

$$
P_0'=\frac{E_1}k+PVGO.
$$

Implication

PVGO > 0 when investment project’s ROE > k

It is better to pay out earnings as dividends for a firm with less investment opportunity. (ROE < k)

- “cash cow”

Firms with limited investment opportunities but stable earnings are often referred to as "cash cows." These firms generate consistent cash flows but have limited growth prospects. Paying out dividends allows them to distribute excess cash to shareholders, who can then invest it elsewhere to earn their required rate of return.

So the P/E ratio (市盈率) is

$$
P_0/E_1=(1-b)/(k-g).
$$

**how long a company needs to sustain its current earnings to pay back the current stock price.**

If the P/E ratio is above this: asset is overpriced

If the P/E ratio is below this: asset is underpriced

Note that P/E ratio depends on growth, risk, retention ratio

It will be lower if g is lower, or k is higher, or b is higher

Does this mean that a rise in b will result in a price decline?

Not if the rise is a signal of new growth prospects...

Since P/E ratios depend on risk and growth, different firms will have different P/E ratios even if all are correctly priced

So when comparing two firm, the one with the smaller P/E ratio is not necessarily the better bargain

Example: high growth firms will have higher P/E ratios, even if they are not mispriced
