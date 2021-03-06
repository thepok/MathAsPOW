
#The Dream of more useful Proof of Work
 from Marcel Richter

## abstract
Since the beginning of Bitcoin there was the Quest for an Proof of Work system  not only useful to Bitcoins security, but other realms too. 

## Proof of Work - Required properties

* **Hard to Compute but easy to verify:** Although any given solution to such a problem can be verified quickly, there is no known efficient way to locate a solution in the first place. Such Problems are part of the complexity class NP or NP-Hard as long as they are not part of P.

* **Abundant Input:** You must be able to generate your work yourself. Else you may would have to wait for some third person to provide Work for you. That may not be possible in a trust free manner.

* **small memory-space requirements:** Because all the Proof of Work Inputs and Results have to be saved in the Blockchain to be able to verify the consistency of it in a trust free manner. 

* **adjustable worksize:** Otherwise the Cryptocurrencynetwork wouldn't be able to set the median time that passes between two found solutions/blocks. 

* **Parallelizable:** Work has to be derivative from a nuance that can be free chosen, so miners can start searching on different parts of the workinputspace, or the problem itself has to offer many points to start from.

* **(Satisfieable)** in the sens, that an solution to an Problem must be foundeable in any case. Else it would be possible to get stuck in an search for a solution for an input for ever.

* **(No pre-calculating of future Blocks:)** It should not be possible, to pre-calculate to reduce the work of a specific future block beside the current one. That does not mean, it should not be possible to make the search for an solution more efficient by calculating some general information usable for every future block.(Hash-tables or so).

## Proof of Work - nice to have properties
* **save from the invasion of botnets**
* **suitable for pooled mining** to combine computing power to reduce payment variation


## Evaluations of the Current Prof of Work: Hashing

To find a fitting hash is hard, but its easy to proof a found input is correct. The Workinput is allways given by transforming the Last POW Output to the Input of the next Run. Finaly the space requirements are minimal. One Large Input and Outputnumber, and some variable X. Around 80 Bytes. But the Found hashes have no other Value to the World. At some point, further development of ASICs may be fostered by the quest of ever faster hashing. But new motivation isn't really necessary in this field of science. So a lot of energy is used up rather useless beside maybe warming some glasshouses to grow vegetables.
One big positiv site of this PoW-system must be named. Botnets have no chance, since highly specialized hardware rather than software is used.

It is not clear, weather for each difficulty an solution can be found!

## What benefits are possible with a new PoW?
### Foster scientific progress
###Build up of usefull Databases

## Other possible Proofs Of Work and there advantages

## NP-Complete Problems
In general you derivate the input for a decision problem from a nuance following some deterministic rules. Than you search for a solution satisfying some lower boarder for that Input. If found, the solution is the Proof of Work. 



### Traveling Salesman
If we would use Instances of the Traveling Salesman Problem, we would still not get solutions that in general can be reused, but the arms race to ever more efficient solvers for this kind of Problem could help find new Algorithmens and specialiced Hardware with great usecases in the real world. The biggest Problem of this Proof of Work is the high requirement of space to save a solution. Its $\mathcal{O}(n*\log_2(n))$  At the time of writing maybe an n ( n = count of Cities to visit) of 100 could be enough( and only growing $\mathcal{O}(\log  t)$), but would result in 1kb of Data per Blockchainblock. The input is derivitad from an nance. Than a path shorter than some k has to be found. Or some new Input has to be derivated from a new nuance. The method to derivate the Input from some nuance should be relativ expensive to focus the development of the solver. And the derived input should in generaly not be solvable in an optimal manner. Else the search for some nuance that has an solution at all would become the main probleme. To show, that n is to small could in it self be part of the POW: If solution is optimal, increase n by 1.

It may should be made progressivly more expensiv to change the nuance, to foster solving a given problem, rather than searching for an especially easy problem. 

The required work to find a solution is adjustable by k and n. Maybe in a stepping fine enough to satisfy the requirements of Cryptocoins. 

In this Fasion other NP-Complete Problems can be used as Proof of work. (SAT KNAPSACK CLIQUE MAXCUT and so on)

To derivate a Problem from some seed, you may use a Formal grammar.

## An automatic Mathematician
In Mathematics, it is possible to derivate (nearly?) all the know Theorems from some Axioms. The Proof of Work could be, given some axioms, to find new usefull Theorems and there derivationchains aka mathematical proofs. This is a NP-Hard problem. That means a Problem is maybe not solvable in finit Time at all.
 
## How to switch to new Proof of Work system in consens with Miners
The transition must be partial, the gain in recocnition of Bitcoin and so Value has to be bigger as the loss of current Miners, a slow transiton is the only way for Bitcoin to stay save. Maybe of 0.5\% per Month

Knowladgebase:
I think Andrew Miller put it best: "The trouble with Proof-of-stake is that there is nothing at stake."
Consider the basic function of proof-of-work and the blockchain: together, they let the network come to a consensus when there are two (or more) different, competing chains.
Miners must decide to dedicate their hashing power to just one chain-- they cannot "bet on" more than one. So their best strategy is to work on the chain that they think most other miners are working on, and that quickly drives the system to a consensus on a single, best chain.
The trouble with proof-of-stake is there is no natural incentive stopping a miner from assigning their stake to multiple, competing chains. If you try to create such a system, you "go meta" -- you started by trying to solve the transaction double-spend problem (which proof-of-work and the blockchain handle nicely), and end up trying to solve a proof-of-stake double-spend problem.
