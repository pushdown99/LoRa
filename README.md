# LoRa
How to build wireshark lua plugin 
for LoRa Development


1) install wireshark
2) Edit C:\Program Files\Wireshark\init.lua
  append line to init.lua (@last line)
 
 
 dofile(DATA_DIR.."json.lua")
 dofile(DATA_DIR.."lora.lua")
3) Capture Packet thuru wireshark w/ filter (LoRa) 
