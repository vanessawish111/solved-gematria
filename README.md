Download Link: https://assignmentchef.com/product/solved-gematria
<br>
<a href="https://www.youtube.com/playlist?list=PLhOuww6rJJNMI45XbeSAiLdivKhzygwgr" rel="nofollow">https://www.youtube.com/playlist?list=PLhOuww6rJJNMI45XbeSAiLdivKhzygwgr</a>

Write a program that will encode each word of a given text by summing the ASCII values of the characters. The text may come from the command line:

<pre><code>$ ./gematria.py 'The quick brown fox jumps over the lazy dog.'289 541 552 333 559 444 321 448 314</code></pre>

Or from an input file:

<pre><code>$ ./gematria.py ../inputs/fox.txt289 541 552 333 559 444 321 448 314</code></pre>

When run with no arguments, the program should print a brief usage:

<pre><code>$ ./gematria.pyusage: gematria.py [-h] strgematria.py: error: the following arguments are required: str</code></pre>

Or a longer usage for <code>-h</code> and <code>--help</code>:

<pre><code>$ ./gematria.py -husage: gematria.py [-h] strGematriapositional arguments:  str         Input text or fileoptional arguments:  -h, --help  show this help message and exit</code></pre>

Run the test suite to ensure that your program is working correctly:

<pre><code>$ make testpytest -xv test.py============================= test session starts ==============================...collected 6 itemstest.py::test_exists PASSED                                              [ 16%]test.py::test_usage PASSED                                               [ 33%]test.py::test_text PASSED                                                [ 50%]test.py::test_fox PASSED                                                 [ 66%]test.py::test_spiders PASSED                                             [ 83%]test.py::test_sonnet PASSED                                              [100%]============================== 6 passed in 0.60s ===============================</code></pre>