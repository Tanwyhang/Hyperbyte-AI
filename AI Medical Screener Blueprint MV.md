# **🔥 AI Medical Screener – Expo iOS App MVP (Local Storage Only) 🔥**  
A **minimalist AI-powered health app** built using **Expo + React Native**, focusing on **local storage** for user data and featuring **AI image analysis, chatbot, and clinic locator**.  

---

## **1️⃣ Core Features (MVP, Local-Only)**  

✔ **AI Image Recognition for Health Screening** (Scan & analyze skin/eye conditions).  
✔ **AI Chatbot for Symptom Analysis** (Conversational health guidance).  
✔ **Nearby Clinic Finder** (Map-based clinic locator).  
✔ **Local Health Log Storage** (Store past AI analyses and chatbot logs on the device).  

---

## **2️⃣ Optimized Tech Stack (Expo + Local Storage)**  

### **📱 Frontend (Expo + React Native for iOS)**  
✅ **Expo (Managed Workflow)** – Fast development and deployment.  
✅ **React Navigation (Bottom Tabs)** – iOS-style tab navigation.  
✅ **Tailwind CSS** – Minimalist, utility-first styling.  
✅ **Lucide Icons** – Simple, lightweight icons for a clean UI.  

### **🖥️ Backend**  
- **No External Backend** – The app will store all data locally using **Expo SecureStore** or **AsyncStorage**.  
- **TensorFlow Lite** – For local on-device AI image analysis.  

### **🌍 Essential Integrations**  
✅ **Google Maps API** – To locate nearby clinics.  

---

## **3️⃣ UI & App Flow (Tab-Based with Centered Scan Button)**  

### **📌 Bottom Tab Navigation (iOS Style, 4 Tabs)**  
| **Tab**       | **Lucide Icon**      | **Function** |
|--------------|---------------------|-------------|
| 🏠 **Home**  | `home`               | Access AI chatbot and health tips. |
| 💬 **Chatbot** | `message-circle`   | Symptom-based AI chatbot assistant. |
| 🔍 **Scan (Center Button)** | `scan` | Opens AI image analysis for screening. |
| 📍 **Clinics** | `map-pin` | Shows nearby clinics using Google Maps. |
| 📝 **History** | `clock` | View past AI scans & chatbot logs. |

---

### **🏠 1. Home Screen (Tab: Home)**  
📌 **Function:** Quick access to chatbot and basic health tips.  
🔹 **Main UI Elements:**  
- **"Describe Symptoms" Button (💬) [Lucide: "message-circle"]**  
- **"Find Clinics" Button (📍) [Lucide: "map-pin"]**  
- **"View History" Link (📑) [Lucide: "clock"]**  

---

### **🔍 2. AI Scan Screen (Floating Center Button on Tab Bar)**  
📌 **Function:** Core AI image analysis for health screening.  
🔹 **Main UI Elements:**  
- **Centered Camera Button (📸) [Lucide: "scan"]** – Tapping opens camera/gallery for scanning.  
- **AI Diagnosis Output:**  
  - **Condition Name (Large Text)**  
  - **Risk Level (🟢🟡🔴 Indicator)**  
  - **Basic Advice (Text Box)**  
- **Save to History (💾) [Lucide: "save"]** – Save analysis result locally for review later.  

---

### **💬 3. AI Chatbot Screen (Tab: Chatbot)**  
📌 **Function:** Text-based symptom checker for health guidance.  
🔹 **Main UI Elements:**  
- **User Input Box (📝) [Lucide: "edit"]** – Text box for users to describe symptoms.  
- **AI Response Bubbles (Text)** – Chat-based interaction with AI.  

---

### **📍 4. Clinic Finder Screen (Tab: Clinics)**  
📌 **Function:** Locate nearby clinics using Google Maps.  
🔹 **Main UI Elements:**  
- **Map View (🗺️) [Lucide: "map"]** – Full-width interactive map.  
- **Clinic List Below:**  
  - **Clinic Name (Bold Text)**  
  - **Distance & Address (Small Text)**  
  - **Call Button (📞) [Lucide: "phone"]** – To directly call the clinic.  

---

### **📝 5. Health Log Screen (Tab: History)**  
📌 **Function:** View past AI scans & chatbot responses.  
🔹 **Main UI Elements:**  
- **List of Previous AI Scans** – Displays saved health scans.  
- **Tap to Expand Details** – Each entry can be expanded for further details, including date and diagnosis.  

---

## **4️⃣ Development Phases for iOS App (Local Storage Only)**

| **Phase**  | **Tasks**  | **Time Frame**  |  
|------------|------------|-----------------|  
| **Setup & UI**  | Initialize Expo, create bottom tab navigation.  | **0-3 hrs**  |  
| **Image Recognition**  | Integrate TensorFlow Lite model for local image analysis.  | **3-6 hrs**  |  
| **Chatbot Integration**  | Implement simple symptom-based logic with AI responses.  | **6-9 hrs**  |  
| **Google Maps API**  | Add nearby clinic locator using Google Maps API.  | **9-12 hrs**  |  
| **Local Storage**  | Use **SecureStore** or **AsyncStorage** to save health data locally.  | **12-18 hrs**  |  
| **Testing & Deployment**  | Expo testing, debugging, and deployment using EAS for iOS.  | **18-24 hrs**  |  

---

## **5️⃣ Why This MVP Works (iOS, Local Storage)**  

🚀 **Fast Development** – Expo and React Native ensure rapid mobile development.  
📱 **Native iOS Feel** – Seamless tab navigation and minimal interface.  
🔥 **Privacy-First** – All data is stored locally using **SecureStore** or **AsyncStorage**, ensuring privacy.  
🔍 **Efficient AI Processing** – On-device TensorFlow Lite for fast AI image analysis.  
📍 **User-Centric** – Focused on delivering quick and easy access to health resources and logs.  
