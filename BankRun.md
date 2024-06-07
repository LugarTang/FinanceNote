# Bankrun

Bank runs: when large numbers of depositors withdraw funds at the same time due to concerns about the health of a bank.

## Diamond and Dybvig (1983) Model of Bank Runs

DD (1983) show how the maturity mismatch (期限错配) of bank’s assets and liabilities makes them susceptible to runs.

Depositors run if they **believe** other depositors will withdraw.

- Importantly, this does not require a departure from fully rationality.

The model’s premise gets at the essence of banking:

- Banks add value by channeling funds from savers to borrowers.
- Pooling loans (asset side) diversifies the risk of default.
- Pooling deposits (liability side) diversifies funding liquidity risk.

  (People may need money in sudden, so they need to keep a lot of cash, but 10 people are not likely to all need money in a moment, so pool their money together and spend a large portion for funding)

Three central assumptions underpin the model:

1. Productive investments have long horizons.
   This makes them **illiquid in the short run**.
2. Consumers may urgently need funds, or may be able to wait.
   At the time of depositing, they’re uncertain about it.
3. Banks cannot identity whether an individual will need immediate access to funds until a deposit is withdrawn.
   But the bank knows the **likelihood** of this happening.

Why does the bank fail if beliefs turn sour?

The bank adds value by increasing the short-term payoff, which insures consumers against the project’s illiquidity.

But this is precisely what leaves it unable to pay all depositors at short-term.

## Preventative measures and their implications.

3 main strategies are available to defend against runs.

### Suspension of Convertibility

Temporary prohibition of future withdrawals. Standard 19th century remedy.

In the model, limiting near-term withdraws can stop the run.

- Suppose the bank announces at $T_0$ that it will only allow 40 customers to withdraw at $T_1$.

  Easy to see there’s no incentive to run.

In the real world, it doesn’t work nearly as well.

- The bank does not know how many depositors truly need cash.
- When do you allow withdrawals again? Cannot go on indefinitely.
- Some banks actually have bad assets and should be liquidated.

### Lender of last resort, LoLR

An entity to borrow from in the face of withdrawals, avoiding the need for costly liquidation.

In the model, there is no run if the bank can borrow from another bank to meet excess withdrawals instead of liquidating more shares.

- Again, this eliminates the incentive to run if you’re a patient type.
- Importantly, LoLR never actually lends, the backstop is what matters.
  In reality, the central bank plays this role.
- Before Lehman, this backstop was viewed as a powerful calming force.
- In the financial crisis, even though the Federal Reserve offered discount window (贴现窗口) access to the investment banks, there was a run on short-term funding.

The discount window is an instrument of monetary policy that allows eligible institutions to borrow money from the central bank, usually on a short-term basis, to meet temporary shortages of liquidity caused by
internal or external disruptions.

### Deposit Insurance

Outside guarantee on deposits, up to a limit.

Complete deposit insurance solves the run problem in the model.

- No reason to run if you know the FDIC will make you whole.
- If deposit insurance in incomplete, a run is still possible.

FDIC guarantees deposits up to $250,000 in the U.S.

- The hope it that big depositors will monitor bank solvency and withhold funds from banks that are excessively risky.

Why doesn’t the FDIC insure all depositors?

- Like other backstops, this creates a moral hazard (道德风险) problem whereby banks want to take excessive risks if their downside is limited.
- Moral hazard is a situation where an agent has an incentive to increase its exposure to risk because it does not bear the full costs of that risk.

Implicit Insurance (Too big to Fail)

Why might the FDIC (or Fed) decide to bail out all depositors, even if they are not covered by deposit insurance?

- If the bank is too big to fail, meaning its failure would causes cascading failures across the financial system and real economic harm.

Like full deposit insurance, TBTF (大而不倒) creates perverse incentives.

- Asset growth: Higher Pr(Bailout) reduces the cost of debt financing.
- Risk-taking: Shareholders get upside, while taxpayers get downside.
