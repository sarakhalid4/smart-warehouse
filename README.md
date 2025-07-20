📦 Automated Store Warehouse Robot


This project aims to design and implement a robot system to automate a food warehouse without human intervention.

⸻

1. 🔁 Execution Algorithm
	1.	The robotic arm starts at the home position.
	2.	It scans or receives item data.
	3.	Based on item type, it identifies the correct path/bin.
	4.	The arm picks the item from the loading area.
	5.	It moves the item to the corresponding path using conveyor belts.
	6.	Items are dropped into labeled boxes automatically.
	7.	The robot returns to the home position and repeats the process.

⸻

2. 🤖 Robot Design
	•	A 5-DOF robotic arm is used to handle picking and placing.
	•	The system includes:
	•	A loading zone (input shelf).
	•	A detection system to classify items (via RFID/barcode/vision sensor).
	•	Conveyor belts to direct items to paths.
	•	Three labeled bins (for example: ONE, TWO, THREE) for sorting.
	•	The robot is mounted on a fixed base with reachable range covering all paths and bins.

⸻

3. 📐 Working Envelope Components
	•	Robotic Arm (5-DOF) – for flexible item manipulation.
	•	Shelves – where items are initially placed.
	•	Sensors – to detect and classify items.
	•	Conveyors – to transport items based on category.
	•	Bins – final destinations for sorted items.
	•	Arduino/Controller – for controlling robotic movements and sensors.
	•	Power Supply – stable power for motors and sensors.
	•	Safety Measures – including emergency stop and obstacle detection
