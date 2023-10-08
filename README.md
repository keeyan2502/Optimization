# Portfolio Optimization

This is my biggest project in programming so far; a tool intended to be used by 2000+ paying financial advisors in India and the pinnacle of my itnernship at NGEN Research. Highly requested by the users, the basic functionality of this program was to simply input a list of assets, and then return 6 optimized portfolios which each allocate different weights to each fund in order to maximise returns, volatility, or Sharpe ratio. 

NOTE: The actual algorithm is hosted on a private API, on this repo is only a demonstration of how it works (the demonstration is a full-stack and works as the website would for a limited set of assets, for which permission was provided by the company)

My prior experience allowed me to run proper statistical analysis on different portfolios, using covariance matrices and other statistical algorithms to evaluate the proficiency of a particular portfolio. My first idea was to try out every single possible portfolio, but time complexity wise, this was completely infeasible as the number of permutations increase by O(n!) when inputting n funds. 

After significant research, I settled on a value-based and raning-based model on past returns, and while I cannot go into detail on the exact algorithm, I made many tweaks throughout the process to optimize my results. This included the introduction of an 'amplifier', an innovation that allowed users to try out riskier and more extreme positions at the expense of an equal distribution of assets. This was very well recieved by the user-base, and was a breakthrough in my algorithm.

Anyone can try this out for themselves, you can either add stocks from the search engine or generate the random portfolio to run the optimization, the working model/demo is on the link: 

https://keeyan2502.github.io/Portfolio-Optimization/
