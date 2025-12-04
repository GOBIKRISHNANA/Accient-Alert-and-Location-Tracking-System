# Accident Alert & Location Tracking System (GPS + GSM)

A real-time accident detection and emergency alert system using **Arduino**, **GPS**, and **GSM** modules.  
When a collision is detected, the system automatically sends an SMS with the exact location (Google Maps link) and triggers emergency calls to predefined contacts.

---

## 🚀 Features
- ✅ Real-time GPS tracking (Latitude & Longitude)
- ✅ Automatic SMS alert with accident location
- ✅ Emergency calling (GSM SIM800L)
- ✅ Vibration-based accident detection (SW-420)
- ✅ Buzzer alert + manual reset button
- ✅ Arduino-compatible & low-cost build

---

## 🛠️ Hardware Components
- Arduino Uno / Nano  
- Neo-6M GPS module  
- SIM800L GSM module  
- SW-420 vibration sensor  
- Buzzer  
- Pushbutton (reset)  
- 9–12V power source  

---

## 🧠 System Workflow
1. **Accident Detected** → Sensor triggers interrupt  
2. **Location Fetching** → GPS module reads coordinates  
3. **Emergency Alerts** → SMS + call to contacts  
4. **Notification Broadcast** → Ambulance, hospital & family  
5. **Manual Reset** → Cancel false triggers  

---

## 🗂 Project Files
- `code.c` → Arduino implementation  
- `/docs/Project_Report.pdf` → Full documentation  
- `/docs/Presentation_Slides.pptx` → Project slides  
- `/media/` → Circuit diagram, prototype images, SMS screenshots  

---

## 🧪 Results
- SMS delivered with live location link  
- Automatic emergency calls placed  
- Prototype validated successfully  

---

## 📌 Future Enhancements
- Mobile app integration  
- IoT dashboard for hospitals  
- Accelerometer-based crash analysis  
- Solar-powered battery module  
- Vehicle engine lockout system  

---

## 📄 License
This project is open-source under the **MIT License**.

---

## 🤝 Contributing
Pull requests and suggestions are welcome!  
Please open an issue for feature requests or bug reports.

