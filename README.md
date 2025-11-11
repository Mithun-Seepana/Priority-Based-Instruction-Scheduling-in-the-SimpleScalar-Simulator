# Priority-Based-Instruction-Scheduling-in-the-SimpleScalar-Simulator
This project enhances the SimpleScalar sim-outorder simulator by adding a priority-based instruction issue policy. Instructions are assigned priorities based on type and latency, allowing critical and long-latency operations to issue earlier. The modification improves pipeline efficiency and overall instruction throughput.
**How to execute the project:**
1) Replace the existing sim-outorder file with the file given.
2) **To Build:** make clean && make sim-outorder
3) **To Run in Default Mode:** ./sim-outorder -redir:sim <output.txt> <location of benchmark>
4) **To Run in Priority Mode:** ./sim-outorder -issue:policy priority -redir:sim <output.txt> <location of benchmark>
