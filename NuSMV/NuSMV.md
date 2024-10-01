# Model Checking and NuSMV

### Handbook
[Handbook of Model Checking](https://link.springer.com/book/10.1007/978-3-319-10575-8)

### Videos 
YouTube videos to get started with formal modelling and verification:
1. [Leslie Lamport: Thinking Above the Code](https://www.youtube.com/watch?v=-4Yp3j_jk8Q)
2. [Simple models in NuSMV](https://www.youtube.com/watch?v=GIrOek9sGyQ)
3. [Model Checking Cell Biology](https://www.youtube.com/watch?v=IKkxiHxMRbs)

Other model checking interviews:
1. Turing Award Interviews: [E. Allen Emerson @ UT Austin](https://www.youtube.com/watch?v=8shcAIJne-Q) and [Joseph Sifakis](https://www.youtube.com/watch?v=qgLIoQWOPZ0).

### References for Temporal Logic and Model Checking
1. [Temporal Logic (Yde Venema)](https://staff.fnwi.uva.nl/y.venema/papers/TempLog.pdf)
2. [The Birth of Model Checking (Edmund M. Clarke) ~ Historical](https://link.springer.com/chapter/10.1007/978-3-540-69850-0_1)
3. Model Checking YouTube courses: [Srivathsan](https://www.youtube.com/playlist?list=PLK50zIm6tHRiKFJvKu1a7q_z2tcXnBUHp) and [Katoen](https://www.youtube.com/playlist?list=PLwabKnOFhE38C0o6z_bhlF_uOUlblDTjh)

## NuSMV
### Installing and Executing NuSMV
1. Go to downloads and choose the latest package: https://nusmv.fbk.eu/downloads.html.
2. Untar the downloaded binaries: `$ tar -xvzf <NuSMV-version>.tar.gz`
3. The NuSMV executable is in the `bin/` folder.
4. Run `$ ./<folder>/bin/NuSMV <file-path>`. Use appropriate flags as necessary.

### Tutorials
Version 2.6 has a short tutorial at https://nusmv.fbk.eu/tutorial/v26/tutorial.pdf.

### Examples
A few small examples from the [NuSMV webpage](https://nusmv.fbk.eu/examples.html):
1. Simple mutual exclusion algorithm: [mutex.smv](mutex.smv), [mutex1.smv](mutex1.smv) 
2. Synchronous three bit counter: [counter.smv](counter.smv)
3. Asynchronous three bit counter: [ring.smv](ring.smv)
4. Semaphore (for synchronizing two processes): [semaphore.smv](semaphore.smv)
5. Data driven pipeline example (by Sergio Campos): [periodic.smv](periodic.smv)

### Biological Examples
1. [Symbolic Model Checking of Biochemical Networks](https://link.springer.com/chapter/10.1007/3-540-36481-1_13)
2. [Modeling and Querying Biomolecular Interaction Networks](https://www.sciencedirect.com/science/article/pii/S030439750400218X)
3. [Model checking to assess T-helper cell plasticity](https://www.frontiersin.org/journals/bioengineering-and-biotechnology/articles/10.3389/fbioe.2014.00086/full)

