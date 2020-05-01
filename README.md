# First-and-Follow-sets-in-Parser
Program to calculate First and Follow sets of given grammar



Source program: https://www.geeksforgeeks.org/program-calculate-first-follow-sets-given-grammar/

Input :
E  -> TR
R  -> +T R| #
T  -> F Y
Y  -> *F Y | #
F  -> (E) | i


Output :
 First(E)= { (, i, }
 First(R)= { +, #, }
 First(T)= { (, i, }
 First(Y)= { *, #, }
 First(F)= { (, i, }

-----------------------------------------------

 Follow(E) = { $, ),  }
 Follow(R) = { $, ),  }
 Follow(T) = { +, $, ),  }
 Follow(Y) = { +, $, ),  }
 Follow(F) = { *, +, $, ),  }
