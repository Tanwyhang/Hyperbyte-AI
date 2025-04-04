# 🧪 **AI Medical Screener – Frontend Blueprint (Centered Scan UX)**  
**Expo | nativewind | shadcn-inspired | Mobile-first**

---

## 📱 **Updated Tab Layout – Central Floating Scan**

**🧭 Bottom Navigation Structure**:
- 3-tab layout with a prominent **center circular Scan button** (floating-style).
- Left Tab: **Chat**
- Center: **Scan** (as a large circle button, floating slightly above the nav bar)
- Right Tab: **EMS**

---

### 🔘 **Center Tab – Scan (Primary Action)**
> **Visual**: Large, circular button (like Instagram's post button or iOS camera shortcut)

- **Functionality**:
  - Taps to open the full-screen camera instantly.
  - UI shows instructions overlayed (e.g., *“Scan a visible health issue”*).
  - After scan → route to result screen with AI-powered analysis.

- **Design Notes**:
  - Floating circle with a soft glow/shadow.
  - Pulsing animation on idle to encourage engagement.
  - Stays fixed while navigating between tabs (acts as main CTA).

---

### 💬 **Left Tab – AI Med Chat**
> Conversational assistant for symptom checking.

- Text input at the bottom, AI-generated replies appear in clean bubbles.
- Chat history saved locally via `AsyncStorage`.
- Supports:
  - Typing symptoms.
  - Tap-to-copy suggestions.
  - Voice input (optional).
- **UI Style**: Minimalist layout, shadcn-like bubble cards, typing animation for AI replies.

---

### 🚑 **Right Tab – EMS (Emergency Services)**  
> Map + emergency hospital info

- Shows user location + nearby hospitals via map view.
- Scrollable list of hospitals under map:
  - Name
  - Distance
  - “Call” and “Directions” buttons
- Call option integrates with native dialer (via `Linking.openURL('tel:123456')`)
- **Design**: Rounded cards, clean spacing, prominent emergency red/teal call button.

---

## 🎨 **Floating Tab Design Considerations**

| Element | Style |
|--------|-------|
| Bottom Nav Bar | Slightly elevated, rounded top corners, dark background with blur |
| Scan Button | Circular, 64-80px, light border, drop shadow, pulsating idle animation |
| Icons | Lucide-style, consistent line weight, labels below (except center scan) |

---

## 🧪 **UX Behavior Summary**

- **Default Launch Screen**: Scan Tab (center) opens by default.
- **Smooth Transition**: Tapping Chat or EMS slides horizontally; Scan opens vertically.
- **Feedback Loop**:
  - Scan result shows diagnostic insight → option to chat or view nearest hospital.

---

## ⚡ Why This UI Works for Medical Apps

- 🔘 **Floating scan button = immediate action access**
- 📊 **Chat = low-barrier medical assistance**
- 🗺️ **EMS = fast emergency navigation**
- 📱 **All optimized for one-hand use & fast reflex navigation**

---
