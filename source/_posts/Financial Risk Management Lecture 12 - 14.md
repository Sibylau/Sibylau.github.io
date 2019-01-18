---
title: Financial Risk Management Lecture 12-14
date: 2018-12-26 21:37:04
tags: [Finance Risk Management,Course]

---

## lecture 12 Intro to Corporate Bond & Credit Risk

### Introduction

Focus: Corporate Bond (公司债券), Credit Risk Derivatives (CDS)

回顾一下Treasury Bonds:

| Treasury                | Minimum denomination | Sold at  | Maturity                    | Interest payments                                  |
| ----------------------- | -------------------- | -------- | --------------------------- | -------------------------------------------------- |
| **U.S. Treasury bills** | $1,000               | Discount | 4-, 13-, 26-, and 52-week   | Interest and principal paid at maturity            |
| **U.S. Treasury notes** | $1,000               | Coupon   | 2-, 3-, 5-, 7-, and 10-year | Interest paid semi-annually, principal at maturity |
| **U.S. Treasury bonds** | $1,000               | Coupon   | 30-year                     | Interest paid semi-annually, principal at maturity |

Good Source! For every bond that has not matured in 2002, we can find info from `FINRA` website, the `TRACE` database. The price reported to `FINRA` is always the clean price.

> Convention:
>
> Corporate Bond | 30/360 day count

Three types of defaults defined in major rating companies: `missed coupon payment` , `bankruptcy` and `distressed exchanges`.

Other contractual provisions to protect the bond holder: `sinking fund provisions`, `callable`, `puttable`, `convertible`. 是为了保护债券持有者而声明的合约条例。

#### Questions:

1. Seniority Level of a Bond? Senior/Subordinated

2. Collateral of a Bond? unsecured...

#### New Words:

`indenture契约` `default违约` `rating companies评级公司` 

`grace period ` | In the U.S., corporate bond issuer has the 90-day grace period. It means that once a bond issuer misses a coupon payment, it still has 90 days to make up this coupon to avoid bankruptcy. 感觉是宣告破产前给予的90天尊严...

 `contractual provisions合同条款` 

`sinking fund provisions偿债基金准备金` | require the debt to be retired periodically by a predetermined amount.

`callable bonds` | Callable bonds are bonds that give the issuer the right to redeem or buy back all or part of the bond before it matures. 

`puttable bonds ` | A puttable bond is a bond that gives the bondholder the ability to sell the bond back to the issuer at a predetermined price on predetermined dates. The bondholder has the option to require the early redemption of this bond at its face value.

`convertible bonds` | A convertible bond is where the bondholder has the right to exchange the bond for a specified number of the company’s common shares. The bondholder has
the option to convert the corporate debt into a certain number of shares of the common stock issued by the same firm.

For more info refer to https://thedailycpa.com/2018/02/08/callable-putable-and-convertible-bonds/

`redemption赎回` 

### Backgrounds

#### Trading

Corporate bonds are traded much less frequently than stocks (trading volume交易体量差异巨大)  -> liquidity premium

Corporate bonds are traded in OTC markets, not in centralized open outcry exchange as stocks. stocks在证券交易所，债券在场外交易所。如果要购买公司债券，需要call your broker，broker will ask a dealer to make a quote. OTC会有round trip cost，e.g. dealer A has on inventory, he will ask dealer B. deal B sell the bond at $92 to A, and A will sell it at $92.5 to you. $0.5 is round trip cost. It can be viewed as the effective bid-ask spread.

Effective bid-ask spreads are large for small trades.

Today the transaction prices of corporate bonds are usually established by individual negotiations. 二战后，公司债券的交易体量相比于股票几乎可以忽略不计。散户几乎不持有公司债券。

#### New Words

`equity股市` `centralized open outcry exchange集中公开叫价交易所:bid and ask prices are well established`  `broker经纪人/中间商` `fixed commissions固定佣金` `pension fund养老保险基金` `retail investors散户投资者`

### Yields and Accrued Interest

full price/invoice price = accrued interest + clean price/flat price

accrued interest = the additional interest i=since the last coupon payment

Example:

| 11      | 12   | 1    | 2    | 3    | 4    | 5    |
| ------- | ---- | ---- | ---- | ---- | ---- | ---- |
| 30-9=21 | 30   | 30   | 30   | 30   | 30   | 3    |

accrued interest =  $\frac{2.95}{2}\times\frac{174}{180}=1.4258$ 

 The invoice price is the price of a bond when discounting future cashflows with the proper discount rate.

To Review~ convert the par yield curve to zero yield curve with the bootstrap method.

YTM of treasury bond is much lower than the equivalent corporate bond.

#### New Words

`Settlement day结算日` 

### Credit Ratings

worldwide major rating agencies: Moody’s, S&P, Fitch/Duff & Phelps. They all follow issue-pay model. 意思是issuer可以选择一个最高的评级，比如Moody‘s的评级不如S&P高，我们就选S&P，pay a large commission fee to the agency to publish this rating. Moral Hazard!

financial policy(reserve better), geographical diversity, ...

Credit ratings are always assigned to the bond issuer instead of a particular bond issue. 

> Yield spread = Expected Default Loss + Default Risk Premia
>
> Expected Default Loss = Default Probability $\times$ Loss Given Default (loss ratio scaled by the face value of default debt, = 1 - Recovery Rate)
>
>

#### New Words

`cohort合伙人，同伙` `speculative grade bond投机级` `investment grade bond投资级,high yield bond/junk bond` `Basel II` `solvency ratio偿付能力比率 ` 

`corporate yield spread: difference between corporate bond yield and yield on the otherwise identical treasury bond`  

 `risk neutral:a mindset where an investor is indifferent to risk when making an investment decision. ` 

