# Quadrotor_UAV_FLADRC
Design of FLADRC controller for UAV

Current progress：
Fuzzy controller/
LADRC/
Fuzzy-PID

Because the internal program of Px4 flight control is very complex, we need to realize the attitude loop control of UAV on the external airborne computer. Offboard is used to calculate the speed of UAV from outside and send it to flight control executive.
![image](https://github.com/Sunchanghao/Quadrotor_UAV_FLADRC/blob/main/Pic/fig1.png)
![image](https://github.com/Sunchanghao/Quadrotor_UAV_FLADRC/blob/main/Pic/%E5%9B%BE%E7%89%877.png)
![image](https://github.com/Sunchanghao/Quadrotor_UAV_FLADRC/blob/main/Pic/7.png)
