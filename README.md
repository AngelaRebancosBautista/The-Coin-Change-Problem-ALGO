# The-Coin-Change-Problem-ALGO

This uses dynamic programming to count the ways to make change. We build an array dp where dp[i] is the number of ways to make sum i; for each coin, we update dp[i] += dp[i - coin].
