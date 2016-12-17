# Math As POW

## Dream
Since the beginning of Bitcoin there was the Quest for an Proof of Work system  not only useful to Bitcoins security, but other realms too. I propose to use research in Mathematics as replacement for the currently verrie limited Proof of Work Systems in Cryptocurrencies.

## Proof of Work - Required properties
Not every computeintens operation is usabale as Proof of Work. A Worktask has to satisfy the following points:

* **Hard to Compute but easy to verify:** Although any given solution to such a problem can be verified quickly, there is no known efficient way to locate a solution in the first place. Such Problems are part of the complexity class NP or NP-Hard as long as they are not part of P.

* **Abundant Input:** You must be able to generate your work yourself. Else you may would have to wait for some third person to provide Work for you. That may not be possible in a trust free manner.

* **small memory-space requirements:** Because all the Proof of Work Inputs and Results have to be saved in the Blockchain to be able to verify the consistency of it in a trust free manner. 

* **adjustable worksize:** Otherwise the Cryptocurrencynetwork wouldn't be able to set the median time that passes between two found solutions/blocks. 

* **Parallelizable:** Work has to be derivative from a nuance that can be free chosen, so miners can start searching on different parts of the workinputspace, or the problem itself has to offer many points to start from.

* **(Satisfieable)** in the sens, that an solution to an Problem must be foundeable in any case. Else it would be possible to get stuck in an search for a solution for an input for ever.

* **(No pre-calculating of future Blocks:)** It should not be possible, to pre-calculate to reduce the work of a specific future block beside the current one. That does not mean, it should not be possible to make the search for an solution more efficient by calculating some general information usable for every future block.(Hash-tables or so).

### Proof of Work - nice to have properties
* **save from the invasion of botnets**
* **suitable for pooled mining** to combine computing power to reduce payment variation
* **unsuitable for pooled mining** to combat minercentralisation


## Current Proof Of Work: Hashing
Proof of Work: to find a solution to a problem must be hard to find but easy to verify. In Bitcoins its of the Form: Find a special Value x for that Hash(x) < k holds.

To find a fitting hash is hard, but its easy to proof a found input is correct. The Workinput is allways given by transforming the Last POW Output to the Input of the next Run. Finaly the space requirements are minimal. One Large Input and Outputnumber, and some variable X. Around 80 Bytes. But the Found hashes have no other Value to the World. At some point, further development of ASICs may be fostered by the quest of ever faster hashing. But new motivation isn't really necessary in this field of science. So a lot of energy is used up rather useless beside maybe warming some glasshouses to grow vegetables.
One big positiv site of this PoW-system must be named. Botnets have no chance, since highly specialized hardware rather than software is used.

It is not clear, weather for each difficulty an solution can be found!

## Suggested new Forms:
* Proofs for Mathematical Hypotheses are of the same quality: increasingly hard to get, but once found, easy to verify. (If written in a computerreadable form.)
* Finding shorter versions of known Proofs is hard to, but easy verrifable.
* Finding Theorems, that can be used to shorten multible know Proofs. (Verry hard, such Theorems may be realy Interesting)

## Advantages:
* MathPOW is generally usefull.
* MathPOW is workable by humans!
* MathPOW fosters research in automatic Theoremproofing and mathematical education.



## Problems:
* Not possible to adjust the difficulty to adjuste the rate of found solutions
  * solvable by combining ordenary POW and MathPOW?
* How to generate new Theorems?
  * Not solvable by the Miners, they could collide to create easy Problmes.
* When a shorter Proof is found, it could be artifical made longer, to resubmit it later a little bit shorter again...
  * Reward is a Function of the lengt of a Mathematical Proof. Only the diffrenece between Old and new Value is payed.
    * Could still be abused to create manny Blocks for the Transactionfees.

## Thoughts
* Generalizations of multiple theorems into one as MathPoW?

## Details:

Its Possible to Proof most of all known Math from Just some Axioms and Definitions on Set-theorie. These Proofs can be written down in Computercomprehensible form in Metamath (https://en.wikipedia.org/wiki/Metamath) and fast verriefied. The Project arround Methamath tries to Proof all Math without gaps. A quite big Database off allready proofen Theorems exists, that could be optimized. This would be POW-Mathoptimization. Adding new Proofs to the Database would be POW-Mathresearch.

This could be implemented into Bitcoin, its the most Valueable chain, and so would create most gain for research. As Sidechain, or in the Mainchain as an Additional kind of POW.

## How to switch to new Proof of Work system in consens with Miners
The transition must be partial, the gain in recocnition of Bitcoin and so Value has to be bigger as the loss of current Miners, a slow transiton is the only way for Bitcoin to stay save. Maybe of 0.5\% per Month

