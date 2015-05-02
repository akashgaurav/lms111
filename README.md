# Drivers for laser scanners used at RCPRG
1. Source this folder in your workspace at `/src`
2. Change laser scanner IP to 192.168.0.1 and gateway to 192.168.0.10
3. `catkin_make`
4. `rosrun lms1xx LMS1xx_node`
5. Data published at topic `\scan`


