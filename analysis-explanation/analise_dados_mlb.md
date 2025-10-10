### Choosing the best offencive player

I used the steps below:

* I organized the third quartiles (and the first quartile for strikeout) of all the attributes I used to compare the best players.
* I analyzed which players in the dataset had values ​​above the third quartile for the attributes (or below the first quartile for strikeout).
* From the previous list of players, I used MinMaxScalar to standardize the data.
* I averaged the previously attributes to form an overall score.
* I found the player with the highest score.

Some questions that you may have:

* **Why did I choose to standardize the data?** *Because it needed to be balanced to be used together in a single score.*

* **Why did I choose MinMaxScaler?**  *Because it standardized the values ​​between [0, 1] which makes it easier to compare better players (represented by 1) and worse players (represented by 0).*