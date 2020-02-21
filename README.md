# simulator
This is a bash script for running Memristor robotics simulator.

After you have extracted this file to your computer open it in terminal window.    
This is the comand that you have to type only once:  

sudo chmod +x run_simulator    
  

Every time when starting robot type:    
./run_simulator      
cd mep2  
ROBOT=helloworld ./main.py helloworld sim=1

*note: run_simulator command also installs the requiered software.      
First of all you should have enough memory on your machine.       
As the installation progresses you will be asked to allow the softwares to take the required memory.     
You shold write: Y , or yes as a reply to the demands.     
If you are suspecting that some of the software hasn't been properly installed do the following: open simulator directory in terminal.    
Then type: rm simulator_installed.txt.     Afterwards type ./run_simulator again.     
