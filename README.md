# Packet_router
System verilog constrains 
  
  
  Test a networking switch. It has 8 input ports. Write a SystemVerilog class with the following constraints: rand bit [2:0] port_id; rand bit [31:0] packet_size; Total packet_size across a burst of 10 items must not exceed 4KB. In a burst of 10 items, no two consecutive items can go to the same port_id. 70% of the traffic must be "small" packets (< 64 bytes)
