## Problem 2.2 ##
> Coulomb and Biot-Savart Laws
> $$\mathbf{E}(\mathbf{r}) = \frac{1}{4 \pi \epsilon_0} \int{d^3r'\ \rho(\mathbf{r'})\frac{\mathbf{r-r'}}{|\mathbf{r-r'}|^3}}$$
> $$\mathbf{B}(\mathbf{r}) = \frac{\mu_0}{4 \pi} \int{d^3r' \ \mathbf{j}(\mathbf{r'})\times\frac{\mathbf{r-r'}}{|\mathbf{r-r'}|^3}}$$

### a) ###
> $\nabla \cdot \mathbf{E}$

recognizing that
$$\frac{\mathbf{r-r'}}{|\mathbf{r-r'}|^3} = \frac{1}{|\mathbf{r-r'}|^2} = -\nabla \frac{1}{|\mathbf{r-r'}|}$$

$$\rightarrow E(r) = -\frac{1}{4 \pi} \int{d^3r' \ \rho(r') \nabla \frac{1}{|r-r'|}}$$

$$\rightarrow \nabla \cdot E = -\frac{1}{4 \pi} \int{d^3r' \ \rho(r') \nabla^2 \frac{1}{|r-r'|}}$$

and 

$$\nabla^2 \frac{1}{|r-r'|} = 4 \pi \delta (r-r')$$

$$\rightarrow \nabla \cdot E = -\frac{1}{4 \pi} \int{d^3r' \ \rho(r') 4 \pi \delta (r-r')}$$

$$\rightarrow \nabla \cdot E = \frac{\rho(r)}{\epsilon_0}$$


> $\nabla \times \mathbf{E}$

recognizing that
$$\frac{\mathbf{r-r'}}{|\mathbf{r-r'}|^3} = \frac{1}{|\mathbf{r-r'}|^2} = -\nabla \frac{1}{|\mathbf{r-r'}|}$$

$$\rightarrow E(r) = -\frac{1}{4 \pi} \int{d^3r' \ \rho(r') \nabla \frac{1}{|r-r'|}}$$

$$\rightarrow \nabla \times E = -\frac{1}{4 \pi} \int{d^3r' \ \rho(r') \nabla \times \nabla \frac{1}{|r-r'|}}$$

and 

$$\nabla \times \nabla F = 0$$

$$\rightarrow \nabla \times E = 0$$


> $\nabla \cdot \mathbf{B}$

$$\nabla \cdot B = \frac{\mu_0}{4 \pi} \int{d^3r' \nabla \cdot \ (j(r')\times\frac{r-r'}{|r-r'|^3})}$$

applying the scalar triple product rule:

$$A \cdot (B \times C) = B \cdot (C \times A) = C \cdot (A \times B)$$

$$\frac{r-r'}{|r-r'|^3} \cdot (\nabla \times j) = 0 \leftarrow \nabla \cdot j = 0$$ for steady current 

$$\nabla \cdot B = 0$$


> $\nabla \times \mathbf{B}$

$$\nabla \times B = \frac{\mu_0}{4 \pi} \int{d^3r' \nabla \times \ (j(r')\times\frac{r-r'}{|r-r'|^3})}$$

applying the triple cross product rule:

$$A \times B \times C = B (A \cdot C) + C(A \cdot B)$$

$$\nabla \times j \times r = j (\nabla \times r) + r (\nabla \times j)$$ where $$r=\frac{r-r'}{|r-r'|^3}$$

$$\nabla \times j \times r = -4 \pi \delta (r-r')j  + r (\nabla \cdot j)$$ 

$$\nabla \cdot j = 0$$ for steady current

$$\rightarrow \nabla \times B = -\mu_0 \int{d^3r' j(r')\delta (r-r')}$$

$$\rightarrow \nabla \times B = -\mu_0 j(r')$$

why is it negative??

