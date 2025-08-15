# Remote-Controlled-Car
In this repository, there are links, code, circuit diagram and procedure to help you design and develop Snake Game using Arduino Uno.

## Acknowledgement
This project was developed with help from Embed Club. I would like to express my sincere Gratitude to Prof. Habeeb Ur Rahaman and Prof. Saifuddeen for guiding me throughout the process.

🌐 Website: (https://embedclub.org/)

## Introduction
This project is a Bluetooth-controlled RC car built using an Arduino UNO, an L298N motor driver, and four BO motors arranged in pairs for stable and smooth motion. Mounted on a sturdy chassis with durable wheels, the car can move forward, backward, left, and right with precise control.

An HC-05 Bluetooth module connects the car to a smartphone via the Bluetooth RC Controller App, allowing wireless control from a distance. The Arduino processes incoming commands and drives the motors in real time, creating an interactive and engaging robotics project that blends electronics, programming, and mechanical design.

## Requirements
I purchased all my components from Robocraze. It is a trusted online eCommerce for projects such as these. They also provide components at a reasonable price as compared to it's competitors. As such, I will name the components, as well as leave a link.

- Arduino UNO (https://robocraze.com/products/uno-r3-board-compatible-with-arduino)
- L298N Motor Driver (https://robocraze.com/products/l298-motor-driver-module)
- HC-05 Bluetooth Module (https://robocraze.com/products/hc-05-bluetooth-module)
- BO Motors
- Wheels
- Chassis (https://robocraze.com/products/2wd-2-wheel-smart-diy-robot-car-chassis-kit)
  (The link provided for Chassis is a kit containing BO Motor as well as wheels. And thus, I have not provided link for Wheels and BO Motors.)
- 18650 Batteries (https://robocraze.com/products/3-7v-1200mah-18650-battery)
- Battery Holder (https://robocraze.com/products/18650-dual-battery-holder-with-cover-and-on-off-switch)
- Jumper Wires (https://robocraze.com/products/jumper-wire-set-m2m-m2f-f2f-40-pcs-each)
- Type A to B Cable: (https://robocraze.com/products/usb-a-b-cable-3-0-cm) (This cable is required to upload the code from your laptop/PC to Arduino UNO microcontroller.)
- Arduino IDE (https://www.arduino.cc/en/software/) (You will need an IDE to upload the code to Arduino microcontroller. So, I have given the link to download it here.)
- Bluetooth RC Controller App (https://bluetooth-rc-car.en.softonic.com/android/download) (You need an Android Device. Does not work in IOS)

## Procedure
### Step 1: Procure the Components
- Using the link given above, or by other means, procure the components required for this project.

### Step 2: Solder the Motors
- If you have bought a new motor, they most probably won't be soldered. So, have it soldered.
- (It is better if you can color code the motors, as it will be easier to connect. Eg, Red for forward motion, and black for backward motion)

### Step 3: Attach Motors to Chassis
- Stick the Motors to the chassis, followed by which attach the wheels.

### Step 4: Upload the Code to Arduino UNO
- Open Arduino IDE, and paste the code. The code is provided in this repository as code.ino.
- Connect the Arduino UNO to your Laptop.
- Select Port and choose the available Port (Eg. COM3)
- Select Board and select Arduino UNO (If you cannot see any boards, go to Boards Manager and Install Arduino Boards.)
- Next, click on Verify (Optional)
- Click on Upload.

### Step 5: Connect the Components
- By following the Circuit Diagram, connect all the components.

### Step 6: Check the Connections
- You can never be too careful. Cross verify the circuit diagram and connections, and make sure all of them are connected properly, and no wires are loosely connected.
- Be extra careful while handling the batteries, they are fragile.
- Also, L298N Motor Drivers are sensitive and will spoil quickly.
