# OBI SPI Slave

This is an implementation of a simple SPI slave. 
An external microcontroller can use the SPI slave to access the memory of the SoC where this IP is
instantiated. The SPI slave uses the OBI bus to access the memory of the target
SoC.

It contains dual-clock FIFOs to perform the clock domain crossing from SPI to
the SoC (OBI) domain.

This IP depends on some PULP common cells like clock muxes, clock gates and
clock inverters. Those can be found in the PULP common cells repository.
