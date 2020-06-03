# NBA_xPOA

This is my first attempt at creating an xG-like metric for the NBA. Expected Points Over Average or xPOA for short uses a logistic regression model to calculate the probability of a given shot to be made given the distance from the basket. This probability is multiplied by 2 or 3 (depending on the shot) which yields the expected value of the shot. Then the expected value is subtracted from the actual value (0 or 2/3). That is the xPOA for one shot.

# How to interpret the numbers?
To put it simply, I'd interpret the numbers as follows: Total xPOA is the margin of points a player scores more than the average player that takes the exact same shots from the exact same positions on the court.

This metric is by no means perfect and absolutely not the be-all metric for determining the quality of NBA scoring. However, I do believe it provides an interesting perspective to evaluate players.
