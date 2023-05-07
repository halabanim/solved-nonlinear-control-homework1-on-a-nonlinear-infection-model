Download Link: https://assignmentchef.com/product/solved-nonlinear-control-homework1-on-a-nonlinear-infection-model
<br>



Reference: <em>Can the COVID-19 epidemic be managed on the basis of daily data? </em>by Francesco Casella, Dipartimento di Elettronica, Informazione e Bioingegneria Politecnico di Milano, Italy.

The standard and basic SIR model is used to model the population dynamics of some infection as COVID-19. It considers a population of <em>N </em>individuals, consisting in three compartments:

<ul>

 <li><em>S </em>is the amount of Safe individuals, not yet infected and Susceptible to become infected. Their population will decrease if the Safe patients have the opportunity to encounter Infected patients. This sub-population does not include patients which were infected but have Recovered from the infection.</li>

 <li><em>I </em>represents the amount of Infected patients. Their population will increase when some ”S” individuals get infected, and it decreases when Infected people Recover from the disease.</li>

 <li><em>R </em>is the amount of population which was infected, but has Recovered from the infection and is healthy again.</li>

</ul>

Note that by definition <em>N </em>= <em>S </em>+ <em>I </em>+ <em>R</em>.

The dynamics is thus described by the differential equations

(1)

(2)

(3)

The amount of newly infected patient is proportional to both <em>S </em>and <em>I</em>. The parameter <em>β </em>is a virulence factor which depends on drugs (if any), on vaccine and eventually on political regulations on the mobility of the population. Thus, <em>β </em>is considered to be the control input. <em>γ </em>is the inverse of the constant duration of the disease for an individual.

QUESTION 1: Among the three variables <em>S</em>, <em>I </em>and <em>R </em>how many are independent, or transcendent with respect to the field of real numbers ?

ANSWER 1 : Only two variables, say <em>S </em>and <em>I</em>. In fact, we got the algebraic relation <em>R </em>= <em>N</em>−<em>S</em>−<em>I</em>. Furthermore, there is no way to get an algebraic relation (over real number) involving the two remaining variables <em>S </em>and <em>I</em>. The latter are thus independent, or transcendent with respect to the field of real numbers.

We may drop equation (3) above to get the well-posed nonlinear state space representation:

(4)

(5)

1

Define further the two output equations

<table width="307">

 <tbody>

  <tr>

   <td width="27"><em>Y</em><sub>1</sub></td>

   <td width="24">=</td>

   <td width="83"><em>S</em></td>

   <td width="173">(6)</td>

  </tr>

  <tr>

   <td width="27"><em>Y</em><sub>2</sub></td>

   <td width="24">=</td>

   <td width="83"><em>I</em></td>

   <td width="173">(7)</td>

  </tr>

 </tbody>

</table>

QUESTION 2: Check whether or not the two outputs <em>Y</em><sub>1 </sub>an <em>Y</em><sub>2 </sub>are differentially algebraically dependent or transcendent with respect to the field of real numbers. I.e., does there exist a (possibly nonlinear) differential equation <em>F</em>(<em>Y</em><sub>1</sub><em>,Y</em><sub>2</sub><em>,Y</em><sup>˙</sup><sub>1</sub><em>,Y</em><sup>˙</sup><sub>2</sub><em>,…</em>) = 0 which does not involve the control input <em>β </em>?

Recall that <em>N </em>and <em>γ </em>are constant real numbers and my be involve in such a differential equation.

ANSWER 2:……………………………………….