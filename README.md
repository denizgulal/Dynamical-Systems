# Dynamical-Systems
The mathematical representation of the spread of an infectious disease using differential equations.

* ### The Question Stream is
* ### 1 
  * Setting up a system of differential equations to describe the course of S (t) and I(t).
  * Interpreting the proportionality constant in the model in biological terms. Possibility of estimate its size?
  * Reducing the system to a single differential equation. Determining the long-term behaviour of the solutions. The biological interpretation of this behaviour.

 * ### 2
   Assuming that everyone is infected and that the disease does not spread.
   * In this situation, model the recovery process with an ordinary differential equation for the (expected) number of infecteds I(t).
   * How long does it take, on average, to recover? Estimation of γ.
     
 * ### 3
   * Adding the recovery process to the model.
   * Introducing a new time variable τ = γt. Also introducing new variables that describe the proportions of susceptibles and infecteds in the population at time t = τ/γ as a function of τ. Stating the system of differential equations in these variables.
   * Let R0 be the only combination of parameters that remains in the model. What is the biological interpretation of R0?
  
 * ### 4
   * Introducing variables for the deviation from the equilibrium, and determining the linear
system of equations that approximates the solutions near this equilibrium.
   * For what values of R0 will an epidemic break out? Giving a biological interpretation of this criterion?
  
 * ### 5
   * Keeping the assumptions on recovery from Section 2, but assuming that the resistants are no longer susceptible. Description of the new model of the spread of disease within a population.
   * Appropriate rescaling (inspired by Sec. 3).
  
 * ### 6
   * The dynamics take place in a limited part of the phase space (that is, the plane of
the dependent variables). What part of the phase space is biologically relevant?
   * Studying the solutions of the two-dimensional system numerically. Choosing different parameter values and study the differences. How do the solutions look in the phase space? Conclusion about the long-term behaviour of the solutions? Does everyone end up being infected?
  
 * ### 7
   * Giving the biologically relevant equilibrium solutions.    
   * For a chosen disease-free equilibrium, determining under what conditions the number of infecteds increases with time when a single infected individual is introduced.
  
 * ### 8
   * Dividing the equation for the proportion of resistants by that for the proportion of susceptibles to obtain a new equation in which the proportion of resistants changes as a function of the proportion of susceptibles. Deducing a relation between the proportions of susceptibles and resistants if there were no resistants at the beginning.
   * Showing that both proportions must have a limit as t → ∞. What about the limit values?
   * Deducing an equation for the final proportion of the population that is infected as a result of the epidemic.
   * Considering the equation in the situation where, initially, everyone is susceptible. What is the difference between R0 < 1 and R0 > 1. How does R∞ depend on R0?

* ### 9
  * Setting up this closed differential equation for the proportion of resistants.
  * Approximating the right-hand side of the differential equation with a quadratic function in the case where R0 is slightly greater than 1.
  * Solving this differential equation and determine the (long-term) behaviour of the solution. How does this depend on R0?
  * Showing that for R0 slightly greater than 1, the right-hand side of the differential equation may indeed be approximated as in part 9/2.
 
* ### 10
  Number of deaths per week during the plague epidemic in Bombay in 1906, from The Journal of Hygiene (London), Vol. 7, No. 6, Reports on Plague Investigations in India (Dec. 1907), p. 753  
  <div align="center">
     Week | Death | Week | Death | Week | Death | Week  | Death 
     ---- | ----- | ---- | ----- | ---- | ----- | ----  | ----- 
     1    | 8     | 7    | 51    | 13   | 442   | 25    | 106     
     2    | 10    | 8    | 92    | 14   | 644   | 26    | 64    
     3    | 12    | 9    | 124   | 15   | 779   | 27    | 46    
     4    | 16    | 10   | 178   | 16   | 702   | 28    | 3z5    
     5    | 24    | 11   | 280   | 17   | 695   | 29    | 27    
     6    | 48    | 12   | 387   | 18   | 870   | 30    | 28    
  
  <div>  

    * Based on the previous part, determining an explicit formula for the incidence of new deaths for the approximation of the SIR model where R0 is slightly greater than 1.
    * Determining parameter values that approximate the mortality rates of the Bombay plague as closely as possible. In particular, relating the width of the peak to the value of R0. What changes under the more realistic assumption that only part of the resistants consists of deceased individuals?
  
 *  ### 11
    Assume that we vaccinate a specific part of the (wholly susceptible) population beforehand.
    * Describe how the model changes.
    * Determine what proportion of the population must be vaccinated to ensure that the disease does not spread.

* ### 12
  *  Drawing up a flow diagram in which the arrows between classes of individuals represent transitions from one class to the other; include transition rates.
  * Assuming that births take place at a rate proportional to the population size. Setting up the differential equations that correspond to this assumption and rescaling for the sake of clarity.
  * Next, assuming that the birth rate is equal to the natural death rate and that the diseasdoes not cause any additional deaths. Determining R0 again (that is, determine a combination of parameters in the model such that the disease spreads if R0 > 1).
  * How does R0 change if the disease does cause additional deaths?
 
Last part includes an extension for the model.






