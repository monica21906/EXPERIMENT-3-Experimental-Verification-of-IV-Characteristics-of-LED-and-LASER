
# Exp 3 Experimental Verification of IV Characteristics of LED and LASER
# Fiber Optic LED Characteristics and Photo Detector Response

## 🎯 AIM
To study the characteristics of fiber optic LED and plot the graph of forward current versus optical power, and to study the photo detector response.

---

## 🧰 EQUIPMENTS REQUIRED
- Power supply  
- Patch chords  
- 1-meter fiber optic cable  
- Digital Multimeter (DMM)  

---

## 📚 THEORY

- **LEDs and LASER diodes** are commonly used sources in optical communication systems for both digital and analog transmission.
- A **linear electrical-to-optical converter** is essential for intensity modulation and high-quality analog transmission.
- LEDs exhibit a **linear optical output** with respect to forward current within a specific operating range.

---


## 🧪 PROCEDURE

1. Connect the power supply to the board.
2. Ensure all switched faults are in the ‘Off’ position.
3. Set emitter 1 block to **Digital Mode**.
4. Make the following connections:
   - Connect the bias 1 preset on comparator 1 (TP13) to emitter 1 input (TP5).
   - Turn the bias 1 preset fully counterclockwise. In subdued lighting, slowly increase the setting until LED light is just visible.
5. Connect the DMM between +12V supply and TP6 (LED cathode) to measure **forward voltage (Vf)**.
6. Measure the voltage drop across the 1KΩ resistor (R9) by connecting DMM between TP6 and TP38.  
   - **Forward current (If)** = DMM reading / 1000 (in mA)
7. Vary the bias 1 preset to adjust forward voltage (e.g., 1.3V, 1.4V, … 1.7V) and note corresponding forward current (If).
8. Record values of Vf and If, and plot the characteristic curve between them.

---

## 🔌 CONNECTION DIAGRAM

<img width="780" height="462" alt="image" src="https://github.com/user-attachments/assets/4ee1001e-e559-402a-99af-f4e3957d34a1" />

---

## 📊 TABULATION
![WhatsApp Image 2025-11-18 at 14 14 29_7434ab8b](https://github.com/user-attachments/assets/1f86cc1c-5a38-442e-b9e6-e9d8904815da)



---

## 📈 MODEL GRAPH
<img width="368" height="258" alt="image" src="https://github.com/user-attachments/assets/12f41e06-0cf0-4183-9d89-c0e1dedfda75" />




![WhatsApp Image 2025-11-18 at 14 15 16_a5213df8](https://github.com/user-attachments/assets/12f6019a-585a-4ba7-81d9-2cbadc7b01e8)





![WhatsApp Image 2025-11-18 at 14 16 05_7fbcd4b6](https://github.com/user-attachments/assets/1f4cab78-8e11-44a8-8728-116a031d9526)




---

## ✅ RESULT
- The forward voltage and current characteristics of the fiber optic LED were successfully studied.
- The photo detector response was observed and analyzed.
