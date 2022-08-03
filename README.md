# AXI HP

## Introduction:

In this project, we are going to try the possiblity of using the AXI-HP ports in Zynq platform to 
achieve a goal: the QDK(Quantum Direct Key) transmission from the mapped memory(MM) of PS side to the PL side (DAC) on the FPGA. Due to the demande of a very large transmission debit, we are using the AXI Hgih Performance ports. 


First, we will establish a project to achieve the goal on Pynq-Z2 and if the result is optimical we will move the project on the ZCU111 board.

## TODO:

- [x] Verify the possibility of 2 HP ports concurrently to double the transfer debit (from 5.2GB/s to 10.4GB/s).

-------------------------------------- Pynq-Z2 -----------------------------------------

- [ ] Finish the block design in Vivado and generate the bitstream for Pynq-Z2

- [ ] Get registers mapping for Pynq-Z2

- [ ] Transfer a file (in txt) in C (via DMA) and evaluate the actual debit

 ------------------------------------- ZCU111 ------------------------------------------

- [ ] Finish the block design in Vivado and generate the bitstream for ZCU111

- [ ] Get registers mapping for ZCU111

- [ ] Transfer a file (in txt) in C (via DMA) and evaluate the actual debit