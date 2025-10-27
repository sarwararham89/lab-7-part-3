Project: automaton
Aothors: David J. Barnes and Michael Kölling

This project is part of the material of the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 7.
Question 27: yes it creates the same patern over and over again.
Question 28: It just brings it back to zero for a reset. 
Question 29:No the partern stay the same its just their positions that change. Yes they are deterministic. The start starts from a different position but they produce the same patern.
Question 30: for(int i = 0; i < state.length; i++){
                 int left, center, right;;
              left = (i==0) ? 0 : state [i-1];
            center = state[i];
             right = (i+1 < state.lenght) ? state [i+1] : 0;
             nextstate[i] = (left + center + right) %2;
}
state = nextState;
Question 31: We use the nextState because then it wouldnt calculate for the next cells that are gonna be added and if we use state then it would mess up the looping calculations. When i changed it the automaton behavior changed. In the terminal window, after state 0 cell 1, we cant calculate the next state meaning there isntt any cell in state 1. It happens because the calculation messed up without having the nextState since it cant catch it. 
Question 32: 
Question 33: Check my bluej code
need help for 32 34 35 and 36.
