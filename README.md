# Arbitrage using flash loans


Flash loans allow users to borrow instantly a large sum of money without any collateral, as long as the borrowed money is returned within the same transaction. In this repo, AAVE flash loans are being used to execute the same arbitrage logic as seen in the youtube video by Finematics.

--> DAI is borrowed from AAVE using flash loan 
--> DAI is swapped for USDC through Uniswap
--> USDC is swapped back into DAI using Curve Finance
--> DAI is sent back to AAVE with some fees at the end of transaction.

