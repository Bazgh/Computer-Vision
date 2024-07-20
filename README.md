# Computer-Vision
Image Inpainting
Project Description:
In this project, we use gradient descent method to reconstruct a noisy image through updating some pixel values (missing pixels).
The noisy image(masked_image) is given as g.
A mask is given to determine the missing values. This mask in our project is called Omega.
At the beginning, our reconstructed image u equals g, but as we update it with gradient desecent steps, we are able to inpaint it and recnstruct a denoised image.
what we mean by gradient is te derivetive of energy sentence with recpect to the image (u).
(To see the Energy and the computation related to its derivative please see the pdf file Named Calculations)
In our gradient  calculation, we used forward difference to define the derivative of u, then using boundary constraints, we were able to remove some terms and update u i  a loop of 1000 iterations, which finally led us to our desiarable denoised image.
Below you see the result of our work.
![image](https://github.com/user-attachments/assets/0bb12eb6-3361-49d4-8ad6-d584fc510bf5)
# To Do
Another method for image inpainting is Gauss Seidel. In the next updates ou our code, we will share the result of this method which will definitly outperform the Gradient Descent method.
