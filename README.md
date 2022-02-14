# Quantum image representation

We analysed the following image representation ways: 
- <ins>qubit lattice</ins> [[2](https://www.researchgate.net/publication/253158806_Storing_Processing_and_Retrieving_an_Image_using_Quantum_Mechanics)];
- real ket [[3](https://arxiv.org/pdf/quant-ph/0510031)];
- <ins>flexible representation of quantum images - FRQI</ins> [[4](https://link.springer.com/content/pdf/10.1007/s11128-010-0177-y.pdf)];
- <ins>multi-channel Representation for Images - MCRQI</ins> [[5](https://ieeexplore.ieee.org/iel5/6045290/6051687/06051718.pdf)];
- <ins>novel enhanced quantum representation of digital images - NEQR</ins> [[6](https://link.springer.com/article/10.1007/s11128-013-0567-z)];
- novel quantum representation for log-polar images - QUALPI [[7](https://link.springer.com/article/10.1007/s11128-013-0587-8)];
- <ins>quantum states for M colors and quantum states for N coordinates - QSMC
and QSNC</ins> [[8](https://link.springer.com/article/10.1007/s11128-012-0521-5)];
- a simple quantum representation - SQR [[9](https://link.springer.com/article/10.1007/s11128-014-0733-y)];
- normal arbitrary quantum superposition state - NAQSS [[10](https://link.springer.com/article/10.1007/s11128-013-0705-7)];
- <ins>generalized quantum image representation - GQIR</ins> [[11](https://link.springer.com/article/10.1007/s11128-015-1099-5)];
- quantum representation of multi wavelength images - QRMW [[12](https://journals.tubitak.gov.tr/elektrik/issues/elk-18-26-2/elk-26-2-12-1705-396.pdf)];
- <ins>quantum image representation based on bitplanes - BRQI</ins> [[13](https://ieeexplore.ieee.org/iel7/6287639/6514899/08470069.pdf)];
- <ins>order-encoded quantum image model - OQIM</ins> [[14](https://link.springer.com/article/10.1007/s11128-019-2463-7)];
- quantum representation of indexed images and its applications - QIIR [[15](https://link.springer.com/article/10.1007/s10773-019-04331-0)];
- <ins>fourier transform qubit representation FTQR</ins> [[16](https://link.springer.com/article/10.1007/s11128-020-02643-3)];
The underlined representations are already implemented in the current repo.

Implementations also include some of the image processing procedures which are discribed [here](https://link.springer.com/content/pdf/10.1007/978-981-32-9331-1.pdf).

Some attention to the Classical-to-quantum and Quantum-to-classical interfaces ([C2QI and Q2CI](https://link.springer.com/article/10.1007/s11128-014-0881-0))
and [testing](https://link.springer.com/article/10.1007/s11128-016-1457-y) with it the reliability of the quantum representation methods.

# Classification

<img src="https://github.com/UralmashFox/QPI/blob/main/images/classification.PNG" width="700" height="200" />

# Metrics
- number of primitives (or big *O* notation);
- number of utilized qubits;
- circuit depth - read [more](https://quantumcomputing.stackexchange.com/questions/14431/whats-meant-by-the-depth-of-a-quantum-circuit);
- Quantum Volume - read [more](https://qiskit.org/textbook/ch-quantum-hardware/measuring-quantum-volume.html#:~:text=Quantum%20Volume%20(QV)%20is%20a,that%20the%20computer%20successfully%20implements).

metric results of the gray-scaled images encoding:

| Depth         | Utilized qubits # | Quantum Volume |
| ------------- | ------------- | ------------- |
| ![](https://github.com/UralmashFox/QPI/blob/main/images/depth.png)  | ![](https://github.com/UralmashFox/QPI/blob/main/images/qub_num.PNG)  | ![](https://github.com/UralmashFox/QPI/blob/main/images/q_vol.PNG)  |

# Authors
Marina Lisnichenko - [m.lisnichenko@innopolis.university](m.lisnichenko@innopolis.university);

Stanislav Protasov - [s.protasov@innopolis.ru](s.protasov@innopolis.ru).

# Related publication
*One day paper link will be here*
