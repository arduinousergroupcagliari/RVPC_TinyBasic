# RVPC_TinyBasic
Simple BASIC interpreter for Olimex RVPC (1€ PC)

NB: because resources are limited, the stack size was reduced from 256 to 192 bytes in order to fit nicely inside the ch32v003. To change this setting, open <user_home>/.platformio/platforms/ch32v/builder/frameworks/noneos_sdk.py Look for stack_size = 256 and change it to 192 (row 44).
