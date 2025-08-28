# 🔢 7-Segment Display using LabVIEW & NI myDAQ

This project demonstrates how to control a **7-segment LED display** using **LabVIEW software** and the **NI myDAQ device**. The system maps user input from the LabVIEW front panel into digital signals, which activate specific segments of the display to form numbers (0–9).

---

## ✨ Features
- Control a 7-segment display via **LabVIEW GUI**  
- Real-time mapping of numbers (0–9) to segments (a–g)  
- **Current-limited resistors** ensure safe LED operation  
- Demonstrates **digital electronics + software-hardware interfacing**  
- Scalable towards multi-digit display with additional logic  

---

## 🛠 Equipment Required
- NI myDAQ (with NI-DAQmx drivers)  
- LabVIEW Software  
- 7-Segment Display (Common Anode or Common Cathode)  
- Resistors (220–330 Ω, one per segment)  
- Breadboard and jumper wires  
- Computer to run LabVIEW  

---

## 📐 Theory
- A 7-segment display has 7 LEDs arranged as segments.  
- By turning ON/OFF specific segments, digits **0–9** can be displayed.  
- LabVIEW generates **digital signals** which are sent through the myDAQ to drive each segment.  
- Common cathode → segments ON when high.  
- Common anode → segments ON when low (inverted logic).  

---

## ⚡ Procedure
1. **LabVIEW Setup**  
   - Create a new VI in LabVIEW.  
   - Add input controls for digit selection.  
   - In the Block Diagram, use **Case Structures** to map each digit (0–9) to Boolean outputs for segments a–g.  

2. **Circuit Assembly**  
   - Place the 7-segment display on a breadboard.  
   - Connect each segment through a resistor (220–330 Ω) to a digital output pin on myDAQ.  
   - Connect the common pin to GND (cathode) or Vcc (anode).  

3. **Testing**  
   - Run the VI, select digits on the front panel.  
   - Verify correct segment lighting.  
   - Troubleshoot wiring and logic if segments fail.  

---

## 🧪 Observations
- Segments illuminated uniformly with proper resistor use.  
- Response time from LabVIEW to display was instantaneous.  
- Digits displayed clearly with no ghosting.  
- Occasional loose connections on the breadboard were the only anomaly.  

---

## ✅ Conclusion
The project successfully controlled a 7-segment display through LabVIEW and myDAQ, demonstrating:  
- **Interfacing hardware with graphical programming**  
- **Reliable real-time numeric display**  
- **Strong educational value** in digital electronics  

Future work may expand this system to **multi-digit displays**, integrate multiplexing, or link sensors to dynamically update the display.

---

## 📸 Prototype
<img width="798" height="785" alt="image" src="https://github.com/user-attachments/assets/93ac5c82-555b-4fca-9d52-cebef0acf60a" />
 

---

## 👩‍💻 Author
**Wrijoya Sen**  
- B.Tech, KIIT University  
- Cybersecurity & Digital Electronics Enthusiast  

---
