Spline Method Draft

https://www.uio.no/studier/emner/matnat/ifi/nedlagte-emner/INF-MAT5340/v10/undervisningsmateriale/book.pdf



B-splines in machine learning

https://www.duo.uio.no/bitstream/handle/10852/61162/thesisDouzette.pdf



四元数与三维旋转

https://krasjet.github.io/quaternion/quaternion.pdf



SMPL: A Skinned Multi-Person Linear Model

https://github.com/YunYang1994/OpenWork/releases/download/v1.0/SMPL-document.pdf



Splines

https://pages.mtu.edu/~shene/COURSES/cs3621/NOTES/

whao's notes:
$$
C(u)=\sum_{i=1}^{n}P_iN_{i,p}(u) \\
where\;the\;formulae\;N_{i,p}(u)\;is\\
N_{i,0}=\left\{
\begin{matrix}
1,\;\;\;\;  if\; u_{i+}\le u\le u_{i+1}\\
0,\;\;\;\;  otherwise
\end{matrix}
\right.
\\
N_{i,p}=\frac{u-u_i}{u_{i+p}-u_i}N_{i,p-1}(u)+\frac{u_{i+p+1}-u}{u_{i+p+1}-u_{i+1}}N_{i+1,p-1}(u)\\
$$
上式中n、m、p分别表示控制点个数减一，节点向量个数减一，样条次数，其中$N_{i,p}$表示第i个p次B样条基函数。