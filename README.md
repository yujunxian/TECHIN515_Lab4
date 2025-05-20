# TECHIN515_Lab4
## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yujunxian/TECHIN515-magic-wand.git
cd TECHIN515-magic-wand
```

### 2. Power On and Run the Device
Once the device is powered on via battery, it will automatically initialize. During initialization:

- All three LEDs (red, green, blue) will blink **twice** to indicate successful startup.

After initialization:

- **Press the physical button** on the enclosure to start gesture recognition.
- The device will then classify one gesture every **1 second**.
- After classification, it automatically returns to standby mode and waits for the next input.

### LED Color Feedback

Each gesture is mapped to a distinct LED color for real-time visual feedback:

- **Z gesture** → Red LED  
- **O gesture** → Blue LED  
- **V gesture** → Green LED

> No connection to a computer is required.  

### 3. Demo Videos

**Hardware Setup & Data Collection**  
[https://youtu.be/GhjpjkJxGcE](https://youtu.be/GhjpjkJxGcE)

**Real-Time Gesture Recognition**  
[https://youtu.be/WJPpHfRTzHo](https://youtu.be/WJPpHfRTzHo)

---

### 4. Enclosure Design

- The enclosure is a **3D-printed wand**.
- **LED positions** are left open to allow clear visibility of classification feedback.
- Powered by a **3.7V 1100mAh Li-ion battery**.
- Final images of the enclosure are included in the **report.pdf** under the *Enclosure Design* section.
