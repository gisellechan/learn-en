# Case 07: Remote Control 

## Purpose
---

- Build a Wonder Rugged Kit that can be controlled by Joystick:bit. 

## Materials
---

- micro:bit Wonder Rugged Kit
- Joystick:bit

## Background Knowledge

------

## Software

------

[MicroSoft makecode](https://makecode.microbit.org/#)

## Program

------

### Step 1

Click "Advanced" in the drawer of MakeCode to see more choices. 

![](https://raw.githubusercontent.com/elecfreaks/learn-cn/master/microbitKit/Mecanum_wheel_car_kit/images/Mecanum%20wheel%20car%20kit_case_01_01.png)

For programming the Wonder Rugged Kit, we need to add a package. Click "Extensions" at the bottom of the drawer and then search "Wukong" in the dialogue box to download it. 

![](https://raw.githubusercontent.com/elecfreaks/learn-cn/master/microbitKit/Mecanum_wheel_car_kit/images/Mecanum%20wheel%20car%20kit_case_01_02.png)

For programming the Joystick:bit, we need to add a package. Click "Extensions" at the bottom of the drawer and then search "joystickbit" in the dialogue box to download it. 

![](https://raw.githubusercontent.com/elecfreaks/learn-cn/master/microbitKit/Mecanum_wheel_car_kit/images/Mecanum%20wheel%20car%20kit_case_07_04.png)



Note：If you get a warning indicating some packages will be removed because of incompatibility issues, you can follow the prompts or create a new project in the menu.

### Step 2

Below is the code for Wonder Rugged Kit:


![](https://raw.githubusercontent.com/elecfreaks/learn-cn/master/microbitKit/Mecanum_wheel_car_kit/images/Mecanum%20wheel%20car%20kit_case_07_05.png)


先设置无线设置组，然后初始化麦克纳姆轮小车舵机。将无线接收到的数据存入`I`。然后通过判断变量`I`的值来控制麦克纳姆轮小车的动作。Begin with radio set group and initialize the servos. Save the radio received value in `I` to control the movement of the car. 


### Step 3

Below is the code for Joystick:bit:


![](https://raw.githubusercontent.com/elecfreaks/learn-cn/master/microbitKit/Mecanum_wheel_car_kit/images/Mecanum%20wheel%20car%20kit_case_07_06.png)


设置无线设置组，然后通过判断手柄摇杆和按键的状态来发送数字。Begin with the radio set group and send number through the status of the joystick handle and the buttons. 


### Program

Links for Wonder Rugged Kit: [https://makecode.microbit.org/_T2iiDyJyEJyp](https://makecode.microbit.org/_T2iiDyJyEJyp)

You can also download it directly below:

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_T2iiDyJyEJyp]" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>  


Links for Joystick:bit: [https://makecode.microbit.org/_e5dHb6c9xbt8](https://makecode.microbit.org/_e5dHb6c9xbt8)

You can also download it directly below:

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_e5dHb6c9xbt8]" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>  

### Result

The movement of the car can be controlled via Joystick:bit.

## Exploration

------

## FAQ

------

## Relevant Files

---