#  Markov Decision Process

Consider a world consisting of m x n a house (a matrix of height n and width m)

● A robot lives in this world that can act north, south, east and
West) move from house to house.

● The result of applying actions is not deterministic.

● Moving from one house to another has a reward (Living reward).
There are houses where only exit action is applied and upon entering these houses
, The robot gets the final reward which can be good or bad and then the game ends.

● Created the policy_compute function in the problems_mdp file to calculate v<sub>k</sub> and π<sub>k</sub> in each iteration. (Value Iteration)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
