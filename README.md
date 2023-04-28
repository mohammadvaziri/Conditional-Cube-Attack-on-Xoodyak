# Conditional-Cube-Key-Recovery-Attack-on-Round-Reduced-Xoodyak
Generating_MILP_Model

Generating_MILP_Model_for_6round_Xoodyak.py: is meant to build the MILP model for 6-round and search for 31 cube variable and also solve the built MILP model

MILP_Model_for_6round_Xoodyak.lp: is the MILP model built by the python file "Generating_MILP_Model_for_6round_Xoodyak.py"

MILP_Model_for_6round_Xoodyak.sol: is the solution file of "MILP_Model_for_6round_Xoodyak.lp", solved by the Gurobi


Generating_MILP_Model_for_7round_Xoodyak.py: is meant to build the MILP model for 7-round and search for 63 cube variable and also solve the built MILP model

MILP_Model_for_7round_Xoodyak.lp: is the MILP model built by the python file "Generating_MILP_Model_for_7round_Xoodyak.py"

MILP_Model_for_7round_Xoodyak.sol: is the solution file of "MILP_Model_for_7round_Xoodyak.lp", solved by the Gurobi



Key_Recovery_experiments_for_6round

Key_recovery_on_6round_Xoodyak.cpp: is meant to recover the key-bit k67 + k90 + k104 + k195 + k218 + k323 + k346 according to Table 2 on the paper. First a random Key is generated, then by knowing the correct value of k67 + k90 + k104 + k195 + k218 + k323 + k346 , all of the bit-values of 0 and 1 in the position A[0][2][21] is tested. For the correct value we will have zero cube sums.


Verifing_Correctness_of_Cube_Vars_for_6round: is meant to verify the correctness of the cube variables in table 2 and proving that different keys has no influence on having zero cube sums by the obtained cube variables on Table 2.
