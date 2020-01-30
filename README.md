# Moment-Invariant
Symbolic calculation of a minimal generating set for 2D geometric moment invariants in the  Jupyter notebook file amd in Maple file

Short manual for  Jupyter notebook
 1. Install Python package sympy on your computer --> pip install numpy
 2. Run the cell with operators --> 
 3. The procedure II(d) returns the list of minimal renerating set of 2D geometric moment invariants of order d.  Just type II(d) in a cell and the run the cell.
 For instance 
 II(4) 
 $$
 \displaystyle \left[ {\eta}_{0,2} + {\eta}_{2,0}, \  {\eta}_{0,2}^{2} - 2 {\eta}_{0,2} {\eta}_{2,0} + 4 {\eta}_{1,1}^{2} + {\eta}_{2,0}^{2}, \  {\eta}_{0,3}^{2} - 6 {\eta}_{0,3} {\eta}_{2,1} + 9 {\eta}_{1,2}^{2} - 6 {\eta}_{1,2} {\eta}_{3,0} + 9 {\eta}_{2,1}^{2} + {\eta}_{3,0}^{2}, \  {\eta}_{0,3}^{2} + 2 {\eta}_{0,3} {\eta}_{2,1} + {\eta}_{1,2}^{2} + 2 {\eta}_{1,2} {\eta}_{3,0} + {\eta}_{2,1}^{2} + {\eta}_{3,0}^{2}, \  i \left(2 {\eta}_{0,2} {\eta}_{0,3} {\eta}_{1,2} + 2 {\eta}_{0,2} {\eta}_{0,3} {\eta}_{3,0} + 2 {\eta}_{0,2} {\eta}_{1,2} {\eta}_{2,1} + 2 {\eta}_{0,2} {\eta}_{2,1} {\eta}_{3,0} - 2 {\eta}_{0,3}^{2} {\eta}_{1,1} - 4 {\eta}_{0,3} {\eta}_{1,1} {\eta}_{2,1} - 2 {\eta}_{0,3} {\eta}_{1,2} {\eta}_{2,0} - 2 {\eta}_{0,3} {\eta}_{2,0} {\eta}_{3,0} + 2 {\eta}_{1,1} {\eta}_{1,2}^{2} + 4 {\eta}_{1,1} {\eta}_{1,2} {\eta}_{3,0} - 2 {\eta}_{1,1} {\eta}_{2,1}^{2} + 2 {\eta}_{1,1} {\eta}_{3,0}^{2} - 2 {\eta}_{1,2} {\eta}_{2,0} {\eta}_{2,1} - 2 {\eta}_{2,0} {\eta}_{2,1} {\eta}_{3,0}\right) + {\eta}_{0,2} {\eta}_{0,3}^{2} + 2 {\eta}_{0,2} {\eta}_{0,3} {\eta}_{2,1} - {\eta}_{0,2} {\eta}_{1,2}^{2} - 2 {\eta}_{0,2} {\eta}_{1,2} {\eta}_{3,0} + {\eta}_{0,2} {\eta}_{2,1}^{2} - {\eta}_{0,2} {\eta}_{3,0}^{2} - {\eta}_{0,3}^{2} {\eta}_{2,0} + 4 {\eta}_{0,3} {\eta}_{1,1} {\eta}_{1,2} + 4 {\eta}_{0,3} {\eta}_{1,1} {\eta}_{3,0} - 2 {\eta}_{0,3} {\eta}_{2,0} {\eta}_{2,1} + 4 {\eta}_{1,1} {\eta}_{1,2} {\eta}_{2,1} + 4 {\eta}_{1,1} {\eta}_{2,1} {\eta}_{3,0} + {\eta}_{1,2}^{2} {\eta}_{2,0} + 2 {\eta}_{1,2} {\eta}_{2,0} {\eta}_{3,0} - {\eta}_{2,0} {\eta}_{2,1}^{2} + {\eta}_{2,0} {\eta}_{3,0}^{2}, \  i \left(4 {\eta}_{0,3}^{3} {\eta}_{3,0} - 12 {\eta}_{0,3}^{2} {\eta}_{1,2} {\eta}_{2,1} + 8 {\eta}_{0,3} {\eta}_{1,2}^{3} + 12 {\eta}_{0,3} {\eta}_{1,2}^{2} {\eta}_{3,0} - 24 {\eta}_{0,3} {\eta}_{1,2} {\eta}_{2,1}^{2} - 12 {\eta}_{0,3} {\eta}_{2,1}^{2} {\eta}_{3,0} - 4 {\eta}_{0,3} {\eta}_{3,0}^{3} + 12 {\eta}_{1,2}^{3} {\eta}_{2,1} + 24 {\eta}_{1,2}^{2} {\eta}_{2,1} {\eta}_{3,0} - 12 {\eta}_{1,2} {\eta}_{2,1}^{3} + 12 {\eta}_{1,2} {\eta}_{2,1} {\eta}_{3,0}^{2} - 8 {\eta}_{2,1}^{3} {\eta}_{3,0}\right) + {\eta}_{0,3}^{4} + 6 {\eta}_{0,3}^{2} {\eta}_{1,2}^{2} - 6 {\eta}_{0,3}^{2} {\eta}_{2,1}^{2} - 6 {\eta}_{0,3}^{2} {\eta}_{3,0}^{2} + 24 {\eta}_{0,3} {\eta}_{1,2}^{2} {\eta}_{2,1} + 24 {\eta}_{0,3} {\eta}_{1,2} {\eta}_{2,1} {\eta}_{3,0} - 8 {\eta}_{0,3} {\eta}_{2,1}^{3} - 3 {\eta}_{1,2}^{4} - 8 {\eta}_{1,2}^{3} {\eta}_{3,0} + 18 {\eta}_{1,2}^{2} {\eta}_{2,1}^{2} - 6 {\eta}_{1,2}^{2} {\eta}_{3,0}^{2} + 24 {\eta}_{1,2} {\eta}_{2,1}^{2} {\eta}_{3,0} - 3 {\eta}_{2,1}^{4} + 6 {\eta}_{2,1}^{2} {\eta}_{3,0}^{2} + {\eta}_{3,0}^{4}\right]
 $$
