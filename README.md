<br/>
<p align="center">
  <a href="https://www.bsic.it">
    <img src="images/bsic_logo.png" alt="Logo" height="80">
  </a>

  <h3 align="center">BSIC Systematic Factor Investing in Credit</h3>

  <p align="center">
    Code for the article on Systematic Factor Investing in Credit
    <br/>
    <br/>
    <a href="https://bsic.it/a-systematic-approach-to-credit-investing/"><strong>Read the article »</strong></a>
  </p>

## About the Code

The code is grouped in the following directories: 

* `src`
    * `preprocessing`: data gathering from *WRDS*, [*openbondassetpricing.com*](https://openbondassetpricing.com/), and *CRSP*, and Data Cleaning on the bond returns
    * `signals`: partitioning the bonds in buckets and 
    evaluating the signals for our strategy: value, equity momentum, credit momentum, carry, and quality
    * `backtesting`: backtesting the strategy and displaying the results
* `docs`: the manual from [*openbondassetpricing.com*](https://openbondassetpricing.com/) which explains the variables in the DataFrame

## Sneak Peek
<p align="center">
<img src="images/strategy_pnl_final.svg" alt="pnl of the strategy">
<img src="images/factors_correlations.svg" alt="factors correlation">
</p>