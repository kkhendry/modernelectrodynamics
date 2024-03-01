## Problem 2.7 ##

> $$ \mathbf{E}' = \mathbf{E}\cos\theta + c\mathbf{B}\sin\theta $$
> 
> $$ c\mathbf{B}' = -\mathbf{E}\sin\theta + c\mathbf{B}\cos\theta $$

### a) ###

> $\nabla \cdot \mathbf{E} = 0$

$$\nabla \cdot E' = \nabla \cdot E \cos\theta + c\nabla \cdot B \sin\theta$$

per problem definition

$$\nabla \cdot E = \frac{\rho}{\epsilon_0} = 0$$

$$\nabla \cdot B = 0$$

$$\rightarrow \nabla \cdot E' = 0$$



> $\nabla \cdot \mathbf{B} = 0$

$$c\nabla \cdot B' = -\nabla \cdot E \sin\theta + c\nabla \cdot B \cos\theta$$

per problem definition

$$\nabla \cdot E = \frac{\rho}{\epsilon_0} = 0$$

$$\nabla \cdot B = 0$$

$$\rightarrow \nabla \cdot B' = 0$$



> $\nabla \times \mathbf{E} = -\frac{\partial \mathbf{B}}{\partial t}$

$$\nabla \times E' = \nabla \times E \cos\theta + c\nabla \times B \sin\theta$$

from Maxwell's Laws

$$\nabla \times E = -\frac{\partial B}{\partial t}$$

$$\nabla \times B = \frac{1}{c^2}\frac{\partial E}{\partial t}$$

$$\nabla \times E' = \frac{\partial}{\partial t}(-B\cos\theta + \frac{1}{c}E\sin\theta)$$

$$\rightarrow \nabla \times E' = -\frac{\partial B'}{\partial t}$$



> $\nabla \times \mathbf{B} = -\frac{1}{c^2}\frac{\partial \mathbf{E}}{\partial t}$

$$\nabla \times B' = -\frac{1}{c}\nabla \times E \sin\theta + \nabla \times B \cos\theta$$

from Maxwell's Laws

$$\nabla \times E = -\frac{\partial B}{\partial t}$$

$$\nabla \times B = \frac{1}{c^2}\frac{\partial E}{\partial t}$$

$$\nabla \times E' = \frac{\partial}{\partial t}(\frac{1}{c}B\sin\theta + \frac{1}{c^2}E\cos\theta)$$

$$\rightarrow \nabla \times B' = \frac{1}{c^2}\frac{\partial E'}{\partial t}$$

### b) ###

For source free solutions of the Maxwell Equations where $\mathbf{E} \perp \mathbf{b}$, the equations are invariant to reference frame rotations?

