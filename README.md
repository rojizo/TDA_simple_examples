# Very simple examples of persistent homology computations

We will using [Dionysus](https://mrzv.org/software/dionysus2/) or/and [GUDHI](https://gudhi.inria.fr/). 
There are other packages like, [Ripser](https://github.com/Ripser/ripser) or [TDA-bats](https://bats-tda.readthedocs.io/en/latest/index.html).
[GUDHI](https://gudhi.inria.fr/) page have very good examples (look at [tutorials](https://gudhi.inria.fr/tutorials/)) 
much better than the simple examples found here. They can be a very good self study material.

If you  try to make 
[the code](https://github.com/WolfByttner/thesis_code/tree/master) from
the bachelor thesis *Classifying RGB Images with multi-colour Persistent 
Homology* , work you may have some problems if you are using Python3. 
I have some troubles with [diamorse](https://github.com/AppliedMathematicsANU/diamorse) package, 
that seems to be program for Python 2. I have changed a couple of bit to make it work in Python3 
(`python3` branch of this [repo](https://github.com/rojizo/diamorse)).


## Some usual problems...

Let us write here the problems we face when using the packages... 

* On Gudhi, you may encounter some problems related with LaTeX... You may need to install some LaTeX package on your system or
  disable LaTeX rendering altogether with `gudhi.persistence_graphical_tools._gudhi_matplotlib_use_tex=False` after importing gudhi,
  ofcourse ([see here](https://gudhi.inria.fr/python/latest/installation.html)).
