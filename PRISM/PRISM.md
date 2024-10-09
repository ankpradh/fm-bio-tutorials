# Probabilistic Model Checking and PRISM
Systems exhibiting random or probabilistic behavior can be modelled and analyzed using probabilistic model checking. 

The most simplest formal probabilistic models include Markov Chains and Markov Decision Processes which are used in a wide variety of fields outside of computer systems. These models are analyzed using properties specified in a probabilistic logic (like PCTL or CSL) which extends temporal logic with probabilistic operators, as well as extensions for quantitative specifications and costs/rewards.

The probabilistic model checker [PRISM](https://www.prismmodelchecker.org/) is a versatile tool incorporating symbolic data structures and algorithms that can operate on many probabilistic models including support for approximate/statistical model checking.

## PRISM
### Installation and Executing PRISM
1. Download a pre-compiled version from the [PRISM website](https://www.prismmodelchecker.org/download.php)
2. Follow [instructions](https://www.prismmodelchecker.org/manual/InstallingPRISM/Instructions) for installing on your OS. PRISM needs Java version 9 or above which can be downloaded from [Oracle](https://jdk.java.net/) or [AdoptOpenJDK](https://adoptium.net/).

### Tutorials and Examples
PRISM has a dedicated [tutorial](https://www.prismmodelchecker.org/tutorial/) with many simple examples. Check out the following:
1. [DTMC] [6-sided die from a fair coin](https://www.prismmodelchecker.org/tutorial/die.php)
2. [CTMC] [Circadian clock](https://www.prismmodelchecker.org/tutorial/circadian.php)
3. [MDP] [Dining philosophers](https://www.prismmodelchecker.org/tutorial/phil.php)

### Lectures on Probabilistic Model Checking
By David Parker: https://www.prismmodelchecker.org/lectures/pmc.

### Biological Examples:
From PRISM case studies:

1. [Cell cycle control in Eukaryotes](https://www.prismmodelchecker.org/casestudies/cyclin.php) (Lecca and Priami)
2. [FGF (Fibroblast Growth Factor) signalling](https://www.prismmodelchecker.org/casestudies/fgf.php) (Heath, Kwiatkowska, Norman, Parker and Tymchyshyn)
3. [MAPK cascade](https://www.prismmodelchecker.org/casestudies/mapk_cascade.php) (Huang and Ferrell) 
4. [DNA walkers](https://www.prismmodelchecker.org/casestudies/dna_walkers.php) (Dannenberg, Thachuk, Turberfield, Hahn, Barbot and Kwiatkowska)
5. [Simple molecular reactions](https://www.prismmodelchecker.org/casestudies/molecules.php) (Shapiro)
