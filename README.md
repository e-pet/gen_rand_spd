# gen_rand_spd
A simple function to generate a random symmetric positive definite matrix with a specified condition number in Matlab.

Based on the specified condition number, a set of eigenvalues is generated. Then, an orthonormal eigenvector matrix U is generated using the [RandOrthMat FEX function by Ofek Shilon](https://se.mathworks.com/matlabcentral/fileexchange/11783-randorthmat), and the result is given by SPD=UDU'. (The distribution of the matrices U is uniform over the manifold O(n) w.r.t. the induced R^(n^2) Lebesgue measure.)
