# Simulation of Cache Architecture using Logism

Term project for Computer Architecture and Microprocessors course (CSN-221).
An implementation of the Cache Architecture and its simulation using Logism. A 4-way set associative cache has been implemented that can perform all the operations like load, store, write-back, eviction using LRU policy (With a custom implementation) and other functionalities that are present in the Cache Architecture. A CPU has also been specially designed for the same so that instructions can be simulated with ease. Testbenches have been written specially, for each module present in the Testbenches directory. <br /><br />Follow the steps to simulate the instructions:

1. Install logisim : `sudo apt-get install -y logisim`

2. Open the file "Cache Architecture.circ" using Logism.

3. Set your own instructions in the CPU's Instruction Memory and put some data in the Main Memory. 

4. Set the state of your cache with any data you want and modify the LRU module corresponding to the data.

5. Run simulations continuously or as per your own, to test the load, store, eviction policy and other functionalities of the cache.
<br /><br />

You can load our testbenches instead. I have made a testing video for the same. You can view it [here](https://drive.google.com/file/d/1V9qUWhlp0XXxJBrigg5sImXC9yEJt-I0/view?usp=sharing). <br />

A custom ISA has been designed for our implementation and the CPU works accordingly. The instruction set along with a detailed report on the whole project can be found [here](https://drive.google.com/file/d/1In-8y0naZhXg-n6M5aEMF7KRYrfs1o_H/view?usp=sharing).



