# osedatools
script file to install open source eda[Electronic Design Automation] tools.

[script with OpenLane](https://github.com/zakirhussainoseda/osedatools/blob/main/oseda_withOpenLane.sh)

It will install the following tools:                                        
1. Magic       - Layout tool                                                  
2. Yosys       - Logic synthesis tool                                         
3. OpenSTA     - Static Timing Analysis tool                                  
4. iverilog    - HDL simulator                                                
5. gtkwave     - waveform viewer                                              
6. klayout     - Layout tool                                                  
7. OpenLane tool chain - RTL-to-GDSII tool

[script wthout OpenLane](https://github.com/zakirhussainoseda/osedatools/blob/main/oseda_withoutOpenLane.sh)

It will install the following tools:                                        
1. Magic       - Layout tool                                                  
2. Yosys       - Logic synthesis tool                                         
3. OpenSTA     - Static Timing Analysis tool                                  
4. iverilog    - HDL simulator                                                
5. gtkwave     - waveform viewer                                              
6. klayout     - Layout tool                                                  


These scripts only been tested in Ubuntu latest destop edition. To install these tools in ubuntu:
1. Open the terminal 
2. First ensure you have git installed else do install git first
3. After git installed, clone this repository: git clone https://github.com/zakirhussainoseda/osedatools.git
4. Then navigate to the cloned repository/folder
5. do either one according to your needs: chmod 777 oseda_withOpenLane.sh  OR chmod 777 oseda_withoutOpenLane.sh
6. After that simply from the terminal and from the same repository just do this, again it is your requirement : ./oseda_withOpenLane.sh  OR ./oseda_withoutOpenLane.sh
7. do keep watching it may prompt at moments for the password, do enter your ubutntu system's password.
