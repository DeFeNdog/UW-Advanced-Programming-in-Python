# Lesson 10
### Profiling and Performance

## Assignments & Exercises
* Great Circle
  * great_circle_v0.py
    * Simple
  * great_circle_v1.pyx
    * Defined arguments
  * great_circle_v2.pyx
    * Defined arguments + memoization
  * great_circle_v3.pyx
    * Define argument types
    * memoization
    * remove python math and import C math
    * reduce precision by replacing double with float
    * remove PI and predefine x
  * great_circle_v4.pyx
    * Define argument types
    * memoization
    * remove python math and import C math
    * reduce precision by replacing double with float
    * remove PI and predefine x
    * factor out parts

## Learning Objectives
* use profiling strategies to identify bottlenecks in Python code;
* use timing strategies to assess code constructs;
* use PyPy to run simple Python scripts to improve their performance; and
* refactor Python code to use Cython for performance improvement.

### Required Reading
* Profiling & Timing
  * https://docs.python.org/3.6/library/debug.html
  * https://docs.python.org/3.6/library/profile.html
  * https://docs.python.org/3.6/library/timeit.html
* [PyPy](http://pypy.org/)
* [Cython](http://cython.org/)

### Supplemental Reading
* Profiling
  * https://pypi.org/project/memory_profiler/
  * https://www.jetbrains.com/help/pycharm/profiler.html
* [Python’s memory_profiler](https://pypi.org/project/memory_profiler/)
* [Work with setup files or any of the other methods to generate cython libraries](http://cython.readthedocs.io/en/latest/src/quickstart/build.html)
* [Work with Cython profiling](http://docs.cython.org/en/latest/src/tutorial/profiling_tutorial.html)
* [Create a Makefile to manage the build (compile/link steps) for all the Cython code you’re generating](https://www.gnu.org/software/make/)
