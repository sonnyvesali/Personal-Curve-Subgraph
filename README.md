// calculate TVL

that means aggregating the value in USD from all the different liquidity pools

functions probably needed

- Transfer to USDC

abis needed

- Oracle
- ERC20 Detailed
- Transfer to USDC

Things that need to be reacted to:

1. Deposit
2. Withdraw
3. Update Financials

Each pool probably has similar functions so if you can just find maybe a pool interface that they all share
that would be fire

Let's dumpster dive for the pool contract we're loooking for

Ok so do we have all we may need

# ============================================================================================================================

# ============================================================================================================================

# ============================================================================================================================

# ============================================================================================================================

# ============================================================================================================================

# ============================================================================================================================

============================================================================================================================

Ok let's think from first principles the only thing we're trying to do here is to get the TVL of all the pools in USD

- Things needed:

1. The Factory Contract to aggregate all the deposit and withdraw functions to find the TVL
2. An oracle to get those values and convert them to USD 3.
# Personal-Curve-Subgraph
