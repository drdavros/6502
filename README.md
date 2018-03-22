VHDL 6502 processor(s)

Original source from The Free IP Project and David Kessner
Modified by Sprow for BCD support

Bug fix by Mike
--        when MC_BIT =>          n_flag <= alu_out(7); -- mike was here
        when MC_BIT =>          n_flag <= data_in(7); -- mike was here

Two files:
free6502.vhd
microcode.vhd
