# Instruction Fusion on Rocket Core
Fuse `lui` instruction and `addi` instruction as a single macro-operation in the decode stage of Rocket Core CPU. The rest of stages see them as a signle macro-operation. That means number of instructions to be executed is reduced and performance is increased.

How to use:
- Set up Chipyard and simulate the default example.
- Run command `make clean`
- Relace the original RocketCore.scala file in Chipyard with this one.
- Run command `make`
- Run benchmarks.
