# Marvel_level_1



---

# TASK 2: API

An **API (Application Programming Interface)** is a bridge that allows two software systems to communicate and exchange data. It enables developers to access external services or data without building everything from scratch.

In my project, I used the **CoinGecko API** to fetch real-time cryptocurrency data such as **price, market cap, and coin details**. Since CoinGecko provides an **open API**, no API key is required. The data is returned in **JSON format** and displayed on the web app using **HTML, CSS, and JavaScript**.

Here is the link to my webpage that uses an API: [Crypto Price Tracker](https://anjan28052006.github.io/API/)

---

# TASK 3: Working with GitHub

In this task, I learned about the working of GitHub, such as how to create a **fork**, which essentially means creating a personal copy of a repository, and about **pull requests (PR)**, a feature used to propose changes made in someone else’s repository so that they can review and merge it into the main branch.

We were asked to **debug a basic Python code** that adds two numbers.

```
Step 1: Fork the repository
Step 2: Debug the Python code inside main.py
Step 3: Create a pull request
```

![GitHub](https://raw.githubusercontent.com/Anjan28052006/Marvel-Level_1/refs/heads/main/Screenshot%202025-09-08%20183710.png)

[Python Code Before](https://github.com/UVCE-Marvel/git-task/blob/main/main.py)  
[Python Code After](https://github.com/Anjan28052006/git-task-Marvel/blob/main/main.py)

---

# TASK 4: Working with the Command Line on Ubuntu

In this task, I learned a few **Ubuntu commands** such as **pwd, mkdir, cd, ls, cat, touch**, which are used to:

* `pwd` → print the current working directory
* `mkdir` → create a new directory
* `cd` → change the working directory
* `ls` → list the contents of a directory
* `cat` → display the contents of files
* `touch` → create a new file

Example:

```
mkdir test
cd test
touch file1.txt
touch file2.txt
echo "I am file 1" > file1.txt
echo "I am file 2" > file2.txt
cat file1.txt file2.txt
rm -r test
```

![Ubuntu](https://raw.githubusercontent.com/Anjan28052006/Marvel-Level_1/refs/heads/main/Screenshot%202025-08-18%20234114.png)
![Ubuntu](https://raw.githubusercontent.com/Anjan28052006/Marvel-Level_1/refs/heads/main/Screenshot%202025-08-18%20232548.png)

---

# TASK 7: Create a Portfolio Webpage

A portfolio is a collection of your work, skills, and achievements that showcases your abilities to potential employers, clients, or collaborators.
I created my portfolio using **HTML** and **CSS**. It contains information about myself, my education, hobbies, projects, skills, and links to my social media accounts.

Here is the link to my portfolio code: [Portfolio](https://github.com/Anjan28052006/Portfolio)

---

# TASK 8: Writing a Resource Article Using Markdown

The aim of this task was to write a technical resource article of our choice.
My resource writing project is on **Data Structures** using **Java**, which contains details regarding **Arrays, Linked Lists, Stack, Queue, HashMap, Trees, and Graphs**.

Here is the link to the resource article: [Click Here](https://anjan28052006.github.io/Data-Structures-in-Java/)

---

# TASK 9: Tinkercad Project

This task involves detecting the **presence of an unknown object** using an **ultrasonic sensor, servo motor, and Arduino Uno**.

**Ultrasonic Sensor:** Has two parts called transmitter and receiver. The transmitter sends sound waves, which bounce back upon hitting an object, and the receiver detects the echo.

**Servo Motor:** Rotates the ultrasonic sensor by 180°.

**Arduino:** A microcontroller board that controls the system.

1. Sends a trigger signal to the ultrasonic sensor.
2. Calculates the distance based on the time taken for the echo.
3. Rotates the servo motor step by step from 0° to 180°.
4. Sends the calculated distance values to the Serial Monitor.

Without Arduino, the ultrasonic sensor and servo motor would not function.

**Formula:**

$$
\text{Distance} = \frac{\text{Speed of Sound} \times \text{Time}}{2}
$$

![Tinkercad](https://raw.githubusercontent.com/Anjan28052006/Marvel-Level_1/refs/heads/main/Tinkercard.png)

---

# TASK 10: Speed Control of DC Motor

In this experiment, a DC motor was controlled using an **Arduino UNO** and the **L298N H-bridge motor driver**. The motor’s speed was varied through **PWM signals** sent from the Arduino, while the direction was controlled using digital pins.

**Components:**

```
Arduino UNO
L298N Motor Driver
Arduino IDE
VRPS
```

[Video](https://drive.google.com/file/d/1SbaEYL7SZ98Ny-E4awQbCGeBS-1EJ-Fg/view)

---

# TASK 11: LED Toggle Using ESP32

In this task, we used an **ESP32 microcontroller** to create a **standalone web server** using the **Arduino IDE**. The ESP32 connects to a Wi-Fi network and hosts a webpage with **LED ON/OFF buttons**. Clicking these buttons sends **HTTP requests** to the ESP32, which controls the LEDs connected to its **GPIO pins**.

**Connections:**

```
Long leg (Anode, +) → Connects to ESP32 GPIO pin (D26 or D27)
Short leg (Cathode, –) → Connects to Ground (GND) via 220Ω resistor
```

| Image\_1                                                                                         | Image\_2                                                                                         | Image\_3                                                                                         |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| ![Image1](https://raw.githubusercontent.com/Anjan28052006/Marvel-Level_1/refs/heads/main/1.jpeg) | ![Image2](https://raw.githubusercontent.com/Anjan28052006/Marvel-Level_1/refs/heads/main/2.jpeg) | ![Image3](https://raw.githubusercontent.com/Anjan28052006/Marvel-Level_1/refs/heads/main/3.jpeg) |

---

# TASK 12: Soldering Prerequisites

**Soldering** is a technique used to join metal parts, creating a mechanical or electrical connection. This process involves a low melting point metal alloy called solder. When heated, it melts and flows over the metal parts to form a bond as it cools.

![Soldering](https://raw.githubusercontent.com/Anjan28052006/Marvel-Level_1/refs/heads/main/soldering.jpeg)

---

# TASK 14: Karnaugh Maps and Logic Circuit

A **Karnaugh map (K-map)** is a graphical tool used in digital logic design and Boolean algebra to simplify Boolean expressions and minimize the number of logic gates required to implement a digital circuit.

This task is based on a **Burglar Alarm**, which detects unauthorized entry when the gate is opened and the key is not pressed.

![K-map](https://raw.githubusercontent.com/Anjan28052006/Marvel-Level_1/refs/heads/main/K-Map.jpeg)

---

# TASK 15: Active Participation

I participated in the event **CODEATHON**, conducted during the **International-Level Annual Technical Symposium, Phase Shift 2024**, held at **BMSCE** on **December 5th and 6th, 2024**.

![BMS](https://raw.githubusercontent.com/Anjan28052006/Marvel-Level_1/refs/heads/main/bms.png)

---

# TASK 16: Datasheets Report Writing

The **MQ135 gas sensor** is a low-cost semiconductor sensor used to detect gases like **CO₂, NH₃, NOₓ, benzene, alcohol, and smoke**. It works by changing its resistance when exposed to these gases, which can be measured and calibrated to determine gas concentration in ppm.

It is widely used in **air quality monitoring, IoT devices, and environmental safety systems**, though it requires preheating and calibration for accurate results.

Here is the link for my report: [Click Here](https://anjan28052006.github.io/Report-MQ135_Gass_Sensor/)

---

# TASK 18: Sad Servers - "Like LeetCode for Linux"

**Sadservers** is a platform to test Linux troubleshooting skills. In this task, we investigated a murder case inside the **Clmystery directory** and submitted the murderer’s name in the **mysolution** file.

**Useful Linux commands:**

```
cd [directory_path]
ls [options] [directory_path]
cat [options] [file_name]
grep [options] "pattern" [file_name]
```

![Sad Server](https://raw.githubusercontent.com/Anjan28052006/Marvel-Level_1/refs/heads/main/linux.jpeg)

---

# TASK 19: Make a Web App

The **Manga Resource Library** is a web application for manga enthusiasts to **browse, explore, and manage manga resources**. It provides access to **manga, anime, and novels** in one place.

Since manga fans are among the largest and most dedicated communities worldwide, this platform serves as a central hub. The project is built using **HTML, CSS, JavaScript, Node.js, and Express.js**, making it simple, fast, and user-friendly.

[GitHub](https://github.com/Anjan28052006/Resource-web-app)

![Web App](https://raw.githubusercontent.com/Anjan28052006/Marvel-Level_1/refs/heads/main/Screenshot%202025-09-10%20235932.png)
![Web App](https://raw.githubusercontent.com/Anjan28052006/Marvel-Level_1/refs/heads/main/Screenshot%202025-09-11%20005412.png)

---

