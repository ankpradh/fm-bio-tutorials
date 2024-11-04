# Boolean Networks modelling and AEON
Biological systems exhibit complex dynamic behavior that are very hard to study using quantitative methods based on ODEs. However, it possible to model and study qualitative behaviors in these systems and Boolean network models are one of the simplest models that were developed for this very purpose.

A Boolean network is defined by a set of boolean variables $\mathcal{B}$ and a set of boolean functions $\mathcal{F}_\mathcal{B}$ where each variable $b \in \mathcal{B}$ is associated with a (possibly distinct) boolean function $f_b \in \mathcal{F}_\mathcal{B}$. The state of variable $b$ is updated according to $f_b$ which can take as input any subset of variables from $\mathcal{B}$ and assign its output as the next state for $b$. The update for all variables considered can be either synchronous, asynchronous or probabilistic. Note that for $n$ variables, the total number of states in the Boolean network is $2^n$ and thus the dynamics of the system will eventually bring it back to a previously visited state. These steady states or cycles in the trajectory of the system are called *attractors*. Search for attractors is very important as it sheds light on the nature of dynamics of the Boolean network.

There are many tools for analyzing Boolean networks. A recent tool called [AEON](https://biodivine.fi.muni.cz/aeon/) provides a great interface for modelling regulatory networks in systems biology using efficient symbolic BDD-based algorithms and has support for attractor finding, bifurcation and stability analysis.

## AEON
### Installing and Executing AEON
AEON has a Python library. For the latest version of AEON, ensure that Python version >= 3.9 as the errors are not very transparent otherwise.

Install using pip:
```
pip install biodivine_aeon
```

For a quick intro, look at [AEON Manual](https://biodivine.fi.muni.cz/aeon/manual/v0.4.0/foreword.html). There is also an [Online tool](https://biodivine.fi.muni.cz/aeon/v0.4.0/index.html). For more details on the API, refer [AEON API documentation](https://biodivine.fi.muni.cz/docs/aeon-py/latest/biodivine_aeon.html).

### Tutorials and Examples
Check out the following:
1. [Butanol Production](https://deepnote.com/app/daemontus/Aeonpy-Examples-091df719-b9b2-4b67-b8b6-aa9909c0b08c)
2. [T-cell signalling](https://github.com/sybila/biodivine-aeon-py/blob/main/example/case-study/t-cell-signalling/main.ipynb)
3. [Interferon Signalling](https://github.com/sybila/biodivine-aeon-py/blob/main/example/case-study/interferon-pathway/main.ipynb)