# Simple RISC CPU
Term project for Computer Architecture and Microprocessors course (CSN-221). An implementation of 32-bit Simple RISC architecture-based CPU as described in the book `Basic Computer Architecture` by
`Smruti R. Sarangi` along with a direct mapped cache that can perform operations like load and store. A CPU has also been specially designed for the simulation of instructions. Testbenches have been written for testing for correctness when executing instructions that involve different components of the cpu.

Follow the steps to simulate the instructions:

Install Logisim: `sudo apt-get install -y logisim`

Open the file `Project CSN 221.circ` using Logism.

Set your own instructions in the CPU's `Instruction Memory` and put some data in the `Main Memory`.
Run the simulation to view the results or run the testbench instructions one at a time to view the register values, cache and Main Memory.

The ISA used in the implementation can be found in the [Report](https://github.com/kumar-devesh/Simple_RISC_CPU/blob/master/Report/CSN-221%20Report.pdf).
