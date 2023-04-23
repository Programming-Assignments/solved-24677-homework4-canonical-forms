Download Link: https://assignmentchef.com/product/solved-24677-homework4-canonical-forms
<br>
<strong>Exercise 1. </strong><em>Canonical forms </em>Consider the system given by:

Find the controllable canonical form state representation.

<strong>Exercise 2. </strong><em>Realization matrix form of realizable MIMO system </em>

Find a state-space realization for

<strong>Exercise 3. </strong><em>Minimum Realizations </em>

Are the two state equations

and

equivalent, i.e. do they have the same transfer function? Are they minimal realizations?

<strong>Exercise 4. </strong><em>Realization </em>

Consider the following transfer function

<ul>

 <li>Determine the standard controllable realization.</li>

 <li>Determine the standard observable realization.</li>

 <li>Determine a minimal realization.</li>

</ul>

<strong>Exercise 5. </strong><em>Controllable decomposition </em>

Reduce the state equation

to a controllable form. Is the reduced state equation observable?

<strong>Exercise 6. </strong><em>kalman decomposition </em>

Decompose the state equation

to a form that is both controllable and observable.

<strong>Exercise 7. </strong><em>Controllable Canonical Form </em>

Figure 1: An electromechanical system

The dynamic model of this system can be derived in three segments: a circuit model, electromechanical coupling, and a rotational mechanical model. For the circuit model, Kirchoff’s voltage law yields a first order differential equation relating the armature current to the armature voltage; that is,

)                                                       (1)

Motor torque is modeled as being proportional to the armature current, so the electromechanical coupling equation is

<em>τ</em>(<em>t</em>) = <em>k<sub>T</sub>i</em>(<em>t</em>)                                                               (2)

where <em>k<sub>T </sub></em>is the motor torque constant. For the rotational mechanical model, Euler’s rotational law results in the following second-order differential equation relating the motor shaft angle <em>θ</em>(<em>t</em>) to the input torque <em>τ</em>(<em>t</em>).

<em>Jθ</em><sup>¨</sup>(<em>t</em>) + <em>bθ</em><sup>˙</sup>(<em>t</em>) = <em>τ</em>(<em>t</em>)                                                        (3)

Converting the ODEs into transfer functions and multiplying them together, we eliminate the intermediate variables to get the overall transfer function:

(4)

Write the controllable canonical form of this system.