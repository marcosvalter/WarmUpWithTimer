# WarmUpWithTimer
Warmup program with timer trigger for Fanuc CNC Systems

This program is intended to start a warmup cycle for CNC machines, using a timer trigger for that.

Example 1

G65 P8999 D20200414 S070000 E074500 T1 U2000 K1

  The warmup will start at 14-02-2020 07:00, ends at 07:45, uses tool #1 at 2000RPM collant on.

Example 2

G65 P8999 D20200414 S070000 T1 U2000 K1

  The warmup will start at 14-02-2020 07:00 will not stop, uses tool #1 at 2000RPM collant on.

Example 3

G65 P8999

  The warmup starts imediatly, using 3000RPM by default, no collant

Example 4

G65 P8999 H1

  Display help messages
