Intro to Machine Learning

These programs walk the computer scientist through
the basic machine learning work flow. First, run
describe.py to check the contents of the url and
see what type of data you are working with. Next,
run visualize.py to visually explore the statistical
relationships within data columns. visualize.py is
a great reference tool to see what kind of algorithms
one should test based upon the statistical patterns.
By running determineAlg.py afterwards, the scientist 
can test their hypothesis by running several 
algorithms and come to a conclusion as to which works
best for the data at hand. Lastly, run predict.py which
only uses the algorithm that proved most accurate. 
In this example, the type of flower is predicted based 
upon the size of sepals and petals, which ultimately 
yielded a 96.7 accuracy rating while using the Support
Vector Machines algorithm!

To run this program:

    - Open your terminal, and cd to project directory

    - type: python describe.py
            python visualize.py
            python determineAlg.py
            python predict.py

Dependencies:

    - Python 2.7
    - Pandas
    - MatPlotLib
    - SkLearn
    - NumPy
