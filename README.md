# Solidity Employee Contracts
Contract address for AssociateProfitSplitter.sol: 0x48D1B811D9e827DF247E36B4cf892Dc9ac469a11

Contract address for tieredProfitSplitter.sol: 0x7e790946D5242912f1929DCeBB0e623c0643097e

Contract address for DefferedEquityPlan.sol: 0x2184026E688a855d859DD4e9F8ef51A7B29358FF

## Three contracts were developed on Ganache blockchain: 
AssociateProfitSplitter contract accepts Ether into the contract and divide the Ether evenly among the associate level employees.

TieredProfitSplitter distributes different percentages of incoming Ether to employees at different tiers/levels. For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%.

DeferredEquityPlan that models traditional company stock plans. This contract automatically manages 1000 shares with an annual distribution of 250 over 4 years for a single employee.

After development, the contracts are deployed on Kovan Testnet. 
Raw files are available in the repository, which can be copied into remix IDE. 
