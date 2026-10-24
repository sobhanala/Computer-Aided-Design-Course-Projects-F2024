# Computer-Aided Design Course Projects

Verilog and SystemVerilog coursework exploring neural-network hardware, gate-level design, FPGA synthesis, and convolutional processing.

## Project map

| Directory | Focus |
| --- | --- |
| `P1 - Maxnet NN/` | Maxnet neural-network datapath, control, and simulation |
| `P2 - Logic Design and FPGA Synthesis/` | Logic-gate implementation and synthesis material |
| `P3 - CNN/` | Convolutional hardware in two phases |

Assignment folders contain HDL source, testbenches, simulator scripts, input data, and design/report documents. The original README used an F2023 heading while the repository name uses F2024; this copy retains the source folder names without assigning a new course date.

## Simulation workflow

The supplied `sim_top.tcl` scripts target the original simulation setup. Use a compatible ModelSim/Questa installation and review each script's source and data paths before running it.

For example, open the simulator in:

```text
P1 - Maxnet NN/sim/
```

Then run:

```tcl
do sim_top.tcl
```

Repeat within the selected project's simulation folder. Gate-level and synthesis flows may need the original technology libraries and FPGA tools. Consult each assignment's description and report for expected waveforms and design decisions.

## Results and limitations

The repository contains original reports and waveform captures. This README does not add new simulation results or claim a measured speed, area, or accuracy improvement. Simulations were not rerun during the documentation update.

## License and credits

See [LICENSE](LICENSE).

## Project credits

This is Sobhan Alaeddini's portfolio fork of [Shahriar-0/Computer-Aided-Design-Course-Projects-F2024](https://github.com/Shahriar-0/Computer-Aided-Design-Course-Projects-F2024). The project was developed collaboratively; the upstream repository and Git history retain the original contributor credits. Documentation in this fork is maintained independently.
