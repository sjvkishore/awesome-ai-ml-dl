# Python Performance

- [Python High Performance - Second Edition](https://github.com/PacktPublishing/Python-High-Performance-Second-Edition)
- [Python and performance](https://github.com/ameroueh/performance)
- [NumPy aware dynamic Python compiler using LLVM ](https://github.com/ameroueh/numba) | [Numba](http://numba.pydata.org/)
- [Profiling in Python](https://github.com/mkunesch/profiling-talk) - by [Markus Kunesch](https://github.com/mkunesch)
  - Profiling: [Profiling with Pycharm 1](https://stackoverflow.com/questions/32926847/profiling-a-python-program-with-pycharm-or-any-other-ide#32926882) | [Profiling with Pycharm 2](https://softwaretester.info/python-profiling-with-pycharm-community-edition/) | [PyCharm and cProfile](https://intellij-support.jetbrains.com/hc/en-us/community/posts/115000057970-Is-there-a-way-to-force-PyCharm-to-use-cProfile-) | [Call tree with Python Profilers](https://stackoverflow.com/questions/4544784/how-can-you-get-the-call-tree-with-python-profilers)
- Speed up Python/Pandas
  - [How to optimise your Pandas code](https://kanoki.org/2019/01/09/how-to-optimize-your-pandas-code/)
  - [Python Itertools: For a faster and memory efficient code](https://kanoki.org/2019/02/08/python-itertools/)
  - [Python/Pandas performance](https://www.youtube.com/results?search_query=%2Bpython+%2Bpandas+%2Bperformance) ([notebook](https://github.com/softhints/python/blob/master/notebooks/pandas/How_to_Optimize_and_Speed_Up_Pandas.ipynb))
  - [High-Performance Pandas: eval() and query()](https://jakevdp.github.io/PythonDataScienceHandbook/03.12-performance-eval-and-query.html)
  - [Fast, Flexible, Easy and Intuitive: How to Speed Up Your Pandas Projects](https://realpython.com/fast-flexible-pandas)
  - [From Python to Numpy](https://www.labri.fr/perso/nrougier/from-python-to-numpy/)
  - [Speeding up python code using numpy](https://www.kdnuggets.com/2019/06/speeding-up-python-code-numpy.html)
  - [Using Cython Nuitka Numba ShedSkin Pythran Transonic](https://twitter.com/ianozsvald/status/1226436048428900353)
  - [using Dask / Vaex / Modin to speed up Pandas-like operations](https://twitter.com/ianozsvald/status/1225748724363780096)
- Pandas GroupBy speedup
  - [Improving the performance of Pandas Group](https://stackoverflow.com/questions/47392758/improving-the-performance-of-pandas-groupby)
  - [Pandas groupby](https://realpython.com/pandas-groupby/)
  - [Faster pandas with parallel processing](https://towardsdatascience.com/faster-pandas-with-parallel-processing-cudf-vs-modin-f2318c594084)
  - [Optimize Custom Grouping Function](https://medium.com/dunder-data/pandas-challenge-001-optimize-custom-grouping-function-44a9f2f321f8)
  - [Speed up pandas 4x](https://www.kdnuggets.com/2019/11/speed-up-pandas-4x.html)
  - Faster than `for` loops or fast loops
    - [Speeding up Python Code: Fast Filtering and Slow Loops](https://towardsdatascience.com/speeding-up-python-code-fast-filtering-and-slow-loops-8e11a09a9c2f)
    - [If you have slow loops in Python, you can fix it…until you can’t](https://www.freecodecamp.org/news/if-you-have-slow-loops-in-python-you-can-fix-it-until-you-cant-3a39e03b6f35/)
    - [PythonSpeed: PerformanceTips: Loops](https://wiki.python.org/moin/PythonSpeed/PerformanceTips#Loops)
- Vectorizations
  - [Python & Vectorization](https://towardsdatascience.com/python-vectorization-5b882eeef658?fbclid=IwAR0sS8uNZlf_iiXw3_qwvUXxh-0UlrJ_nNIFlPJ0hBSHFvGtW2y2fFETqsQ)
  - [SO: what-is-vectorization?](https://stackoverflow.com/questions/1422149/what-is-vectorization)
  - [numpy.vectorize()](https://numpy.org/doc/stable/reference/generated/numpy.vectorize.html)
  - [Array Programming With NumPy: What is Vectorization?](https://realpython.com/numpy-array-programming/#what-is-vectorization)
  - [numba.vectorize()](https://numba.pydata.org/numba-doc/dev/user/vectorize.html)
  - [Fast, Flexible, Easy and Intuitive: How to Speed Up Your Pandas Projects](https://realpython.com/fast-flexible-pandas/) (**See Vectorization section**)
- [numba](http://numba.pydata.org/)
  - [Using numba](https://tedboy.github.io/pandas/enhancingperf/enhancingperf2.html)
  - [Performance Tips](http://numba.pydata.org/numba-doc/latest/user/performance-tips.html)
    - [@njit explained](https://github.com/numba/numba/issues/3523)
  - [Compiling Python code with @jit](https://numba.pydata.org/numba-doc/latest/user/jit.html)
    - [Automatic parallelization with @jit](https://numba.pydata.org/numba-doc/latest/user/parallel.html#numba-parallel)
  - [numba.vectorize()](https://numba.pydata.org/numba-doc/dev/user/vectorize.html)
- High Performance Python talk by [Ian Oszvald](https://twitter.com/ianozsvald/): Blogs: [1](https://ianozsvald.com/2019/11/16/higher-performance-python-at-pydatacambridge-2019/) o [2](https://ianozsvald.com/2019/11/22/higher-performance-python-odsc-2019/)  | [Slides](https://speakerdeck.com/ianozsvald/higher-performance-python-odsc-2019) | [Useful resources shared](https://twitter.com/DataChaz/status/1197608275606413312)
  - [Making Pandas Fly (EuroPython 2020)](https://speakerdeck.com/ianozsvald/making-pandas-fly-europython-2020) | [Blog](https://ianozsvald.com/2020/07/24/making-pandas-fly-at-europython-2020/)
  - [Making Pandas Fly (PyDataAmsterdam 2020)](https://speakerdeck.com/ianozsvald/making-pandas-fly-pydataamsterdam-2020) | [Blog](https://ianozsvald.com/2020/06/23/making-pandas-fly-for-pydataamsterdam-2020/)
  - [Making Pandas Fly (PyDataUK 2020)](https://speakerdeck.com/ianozsvald/pydatauk-making-pandas-fly) | [Blog](https://ianozsvald.com/2020/04/27/flying-pandas-and-making-pandas-fly-virtual-talks-this-weekend-on-faster-data-processing-with-pandas-modin-dask-and-vaex/)
  - [Making Pandas Fly (PyDataBudapest 2020)](https://speakerdeck.com/ianozsvald/making-pandas-fly) | [Blog](https://ianozsvald.com/2020/04/27/flying-pandas-and-making-pandas-fly-virtual-talks-this-weekend-on-faster-data-processing-with-pandas-modin-dask-and-vaex/)
  - [Flying Pandas - Dask, Modin and Vaex (Remote Pizza Python 2020)](https://speakerdeck.com/ianozsvald/flying-pandas-modin-dask-and-vaex) | [Blog](https://ianozsvald.com/2020/04/27/flying-pandas-and-making-pandas-fly-virtual-talks-this-weekend-on-faster-data-processing-with-pandas-modin-dask-and-vaex/)
  - [Tools for Higher Performance python (ODSC 2019)](https://speakerdeck.com/ianozsvald/higher-performance-python-odsc-2019) | [Blog](https://ianozsvald.com/2019/11/22/higher-performance-python-odsc-2019/)
  - [Tools for Higher Performance python (PyDataCambridge 2019)](https://speakerdeck.com/ianozsvald/higher-performance-python) | [Blog](https://ianozsvald.com/2019/11/16/higher-performance-python-at-pydatacambridge-2019/)
- Performance highlights (notes)
  - best practice - when and how to focus on performance
  - profiling - understand what's slow to focus your efforts (timeit,line_profiler, pyspy)
  - making numerical code faster - better algorithms, numpy, numba,joblib for parallelisation
  - faster pandas - solving tasks faster, avoiding subtle errors that will eat your time
  - unit tests - use of unit tests to support correctness during optimisation
  - estimate benefits in scenarios for optimisation vs refactoring vs buying hardware vs other options

# Contributing

Contributions are very welcome, please share back with the wider community (and get credited for it)!

Please have a look at the [CONTRIBUTING](CONTRIBUTING.md) guidelines, also have a read about our [licensing](LICENSE.md) policy.

---

Back to [main page (table of contents)](README.md)