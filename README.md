# A-Partially-Static-High-Frequency-18T-Hybrid-Topological-Flip-Flop-Design[4]

In this paper, an extremely low power true single phase clocking flip-flop is proposed using eighteen transistors only. The flip-flop is a synchronous bistable element that stores single-bit Information.To design this Master Slave (MS) type architecture, topological, logical, and adaptive coupling techniques are employed. The minimum numbers of transistors are maintained by using above techniques, which comprises of complementary pass transistor logic and static complementary MOS logic. It also offers low power, a low delay that speeds up the flip-flops and low complexity by reducing the transistor count. 

Index Terms - Switching Activity, CMOS, Low Power, Flip-Flop, Monte Carlo Complementary Pass Transistor.

I.  INTRODUCTION
	The basic storage element extensively used in digital system designs is a flip-flop. The flip-flop is extensively used in low power electronics applications such as smartphones, mobiles, tablets, and other hand-held devices. At the same time for fast processing speed, delay of the memory units should also minimum [1], [2]. 
Low power flip-flop techniques are used to avoid the extra
load on clock signal. The flip-flop design logic such as True Single Phase Clocking (TSPC) has been developed with the intention to alleviate clock load. 
In this paper, a hybrid logic is used for flip-flop design. The proposed flip-flop structure addresses the significant improvement in (1) Clock to Q delay when compared with the existing M-S flip-flops. (2) This work doesn’t have clock overloading problem also, that helps in reduction in power consumption. (3) Reduction in the PMOS transistor count, that reduces the delay and area as well as the power of the overall circuit. (4) Lowering the overall complexity. 

II. PROPOSED FLIP-FLOP DESIGN
For achieving lower delay, decreasing the circuit complexity and optimizing the power consumption, we have topologically and logically reduced the number of the transistor especially PMOS transistor. Figure our proposed design, named as a Hybrid flip-flop (HFF). Since, 
1) Case : Data = 0 and Clock = 0: When CLK=0 and DATA=0, P1, P2, and N4 transistors will be in ON state, that makes node ”u1” to be equal to 1. But ”master” node and node
u2 will not deliver any data to slave latch, because transistors N6 and N7 are OFF. 
2) Case: Data = 0 and Clock = 1: When CLK=1 and DATA=0, transistors N6 and N7 will be in ON state. The data stored at the “master” node and node u2, feeds to slave nodes”a” and ”b”, via N6 and N7 respectively. This provides the data at the output through the slave.
3) Case : Data = 1 and Clock = 0: When CLK=0 and DATA=1, transistors N1, P2 and P4 will be in ON condition. That pulls node u1 and u2 to logic ”0”, while master node retains the data at logic ”1”. The slave will hold its previous value at the output node.
4) Case: Data = 1 and Clock = 1: When CLK=1 and DATA=1 logic at the master node will be transferred to slave similar to the above case as CLK=1. When the master node output is at logic”1”, N7 behaves as a CB, as it passes strong”0” at node”b”. At the same time N6, behaves as an AT, as it passes weak”1” at node ”a”.
![image](https://user-images.githubusercontent.com/100616752/156107249-3670e57c-9a43-4d59-b652-742a9ddcc2e7.png)
![mr_flipflop_mr_flipflop_schematic](https://user-images.githubusercontent.com/100616752/156109836-3c8c5e61-6111-4584-8e4d-806de0b71a96.png)
![mr_flipflop_mr_flipflop_symbol](https://user-images.githubusercontent.com/100616752/156109854-abbbdc2d-182b-42d8-89d8-3c6112db5552.png)
![mr_flipflop_mr_flipflop_tb_schematic](https://user-images.githubusercontent.com/100616752/156109867-62e27d61-8388-49f1-964a-35102ac6cdae.png)
![5](https://user-images.githubusercontent.com/100616752/156109709-13929a53-cc0c-4eca-8e42-7970f4470c03.jpg)

III. EXPERIMENTAL RESULTS
![image](https://user-images.githubusercontent.com/100616752/156107418-ede5402d-299c-4849-9535-40eb14073a8a.png)

The waveforms indicate internal node voltages of the proposed Hybrid flip-flop, in which all nodes are static except node u1. The node voltage of u1 introduces small fluctuations but, logic remains at the same level hence circuit is partially static.  

IV. CONCLUSION
a new flip-flop is designed by using 18 transistors. For the proposed work, we have considered following parameters, which are C to Q delay, reduction in PMOS transistor count, no clock overloading, and lowering circuit complexity. The proposed design is also compared with the 18T TSPC FF. In which we are getting comparable results and in some comparison, proposed circuit excels over 18T TSPC and hence proves the efficiency.

V. REFERENCES
[1].	N. Kawai, S. Takayama, J. Masumi, N. Kikuchi, Y. Itoh, K. Ogawa, Ugawa, H. Suzuki, and Y. Tanaka, “A fully static opologically compressed 21-transistor flip-flop with 75% power saving,” IEEE Journal of Solid-State Circuits, vol. 49, no. 11, pp. 2526–2533, 2014.
[2].	N. Nedovic and V. G. Oklobdzija, “Hybrid latch flip-flop with improved power efficiency,” in Proceedings 13th Symposium on Integrated Circuits and Systems Design (Cat. No. PR00843). IEEE, 2000, pp. 211–215. 
[3].	J.-F. Lin, M.-H. Sheu, Y.-T. Hwang, C.-S. Wong, and M.-Y. Tsai, “Low power 19-transistor true single-phase clocking flip-flop design based on logic structure reduction schemes,” IEEE Transactions on Very Large Scale Integration (VLSI) Systems, vol. 25, no. 11, pp. 3033–3044, 2017.
[4].	Alok Kumar Mishra , Urvashi Chopra D. Vaithiyanathan, “A Partially Static High Frequency 18T Hybrid Topological Flip-Flop Design for Low Power Application” IEEE TRANSACTIONS ON CIRCUITS AND SYSTEMS II: EXPRESS BRIEF 2021

vi. Acknowledgemwnts:
Thanks to alokkumar mishra after reading this article i am interested to slove this paper,it is more helpfull to slove.
(Alok Kumar Mishra , Urvashi Chopra D. Vaithiyanathan, “A Partially Static High Frequency 18T Hybrid Topological Flip-Flop Design for Low Power Application” IEEE TRANSACTIONS ON CIRCUITS AND SYSTEMS II: EXPRESS BRIEF 2021)
Special thanks to chinmaya, kunal vsd, synopsys and iiih team to provide this hackathon


