VHDL 6502 processor(s)

Original source from The Free IP Project and David Kessner\s\s
Modified by Sprow for BCD support

Bug fix by Mike\s\s
was\s\s
`--        when MC_BIT =>          n_flag <= alu_out(7); -- mike was here`\s\s
now\s\s
`        when MC_BIT =>          n_flag <= data_in(7); -- mike was here`\s\s

Two files:
free6502.vhd
microcode.vhd
