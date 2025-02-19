# Development-of-CANoe-Network
- Understanding and analyzing the specifications. 
- Understanding the Requirement of message’s and signals and number of ECU’s that is used to create database 
- Automate the test scripts through CAPL. 
- Developing the panels by using Panel editor & panel designer. 
- Attaching panel to panel. 
- Attaching environmental variables through CAPL script

# DataBase:
- Netwrok Node: BCM(Body Control Module), IPC(Instrument Panel CLuster)
- Messages: BCMMessage 0x100
- Signals;BCM_Signal
- Environment Variables: Env_BCM, Env_IPC
- Value Table: 0x0 OFF, 0x1 ON

# Tool:
- Create Configuration
- Create Database
- Create simulation setup
- Create Panel
- Write node behaviour using CAPL

# CAPL:
- Once Enc_BCM gets value, send to CAN via BCM_Signal
- IPC receives the messafe and assign it to Env_IPC and displays output.
