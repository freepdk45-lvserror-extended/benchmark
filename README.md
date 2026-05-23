# Multi-Agent System for Autonomous LVS Debugging
A multi-agent system where large language model (LLM) agents reason over schematic and layout netlists as well as LVS results to provide implicit rewards for layout modifications and guide iterative LVS debugging.

This library is made up of modified layouts of the [FreePDK45](https://eda.ncsu.edu/freepdk/freepdk45/) standard cells, incorporating multiple LVS errors such as Property, PortSwap, UnunsedText, TextShort, and TextOpen errors.


## Dataset Description
- All file structures follow the architecture of FreePDK45. 

- The extended library is contained at benchmark/freepdk45-v14-extended/FreePDK45-1.4-extended/osu_soc/lib.
(freepdk45_cells_with_LVS_errors)


## License
This project is licensed under the Apache 2.0 License.
