# Jolt160 CPU
This is a CPU I'm developing to practice my CPU design and implementation
skills, as well as to provide **an easier GCC target** than my other CPU,
which is called Jolt80.


Note that since Icarus Verilog's support for SystemVerilog enums is not
complete (at least as of this writing), _when using something with better
SystemVerilog support (such as Altera Quartus II)_, it is **NECESSARY to
change the task set\_more\_alu\_config in src/alu\_control\_tasks.svinc to
use a cast**!

