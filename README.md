<<<<<<< HEAD
# HA3Dynamics-
Jacobians, Trajectories of manipulator!!!
=======
Task 1: {#task-1 .unnumbered}
=======

Derive FK equations for the robot depicted in figure [fig:mesh1]. Use
$\theta_1$, $\theta_2$, $d_3$ as joint space variables, $p_x$, $p_y$,
$p_z$ as operational space variables. Parameters $d_1$, $a_2$ are known
(assign them some positive values for succeeding tasks).

![RRP robot.](Image1 "fig:") [fig:mesh1]

Task 2 {#sec:Task 2 .unnumbered}
======

Derive IK equations.

Task 3: {#task-3 .unnumbered}
=======

Compute the manipulator Jacobian for representation of linear and
angular velocity of point **p**.

-   Use classical approach (partial derivatives).

-   Use geometric approach (cross products).

Task 4: {#task-4 .unnumbered}
=======

Analyze the Jacobian for singularities. Characterize each singular
configuration if any.

Task 5: {#task-5 .unnumbered}
=======

Compute the velocity of the tool frame when joint variables are changing
with time as follows:

<span>$\theta_1(t) = sin(t)$, $\theta_2(t) = cos(2t)$,
$d_3(t) = sin(3t)$. </span>

Add some fancy graphs showing evolution of all variables

Task 6: {#task-6 .unnumbered}
=======

Let tool coordinates changing with time as follows:

<span>$p_x(t) = 2a_2sin(t)$, $p_y(t) = 2a_2cos(2t)$,
$p_z(t) = d_1sin(3t)$ </span>

Determine a feasible joint trajectory for this tool trajectory.

-   Use IK solution.

-   Use inverse differential kinematics approach. Consider only linear
    velocity part of Jacobian.


>>>>>>> test
