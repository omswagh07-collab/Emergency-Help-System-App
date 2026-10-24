# Emergency-Help-System-App
A smart Emergency Help System featuring live location sharing, emergency SOS alerts, trusted contacts, safety check-in timers, an interactive crime risk map, and an audio guardian for personal safety.

# 🚨 Emergency Help System (EHS)
### A Rapid Response and Personal Safety Application

Emergency Help System (EHS) is a personal safety application designed to help users respond to emergencies, share their location with trusted contacts, identify potentially risky areas, and access essential emergency services quickly.

The application combines emergency assistance, location-based safety awareness, timed check-ins, and audio-based threat detection in a unified interface.

---

## 📌 Project Overview

EHS aims to make personal safety tools accessible through a simple, intuitive interface. Users can monitor their safety status, view risk zones on a map, share their location, contact emergency services, and configure safety preferences.

The application is organized into five main sections:

- 🏠 Home — Emergency assistance and safety status
- 🗺️ Map — Location-based risk visualization
- ⏱️ Check-In Timer — Timed safety check-ins
- 🎙️ Audio Guardian — Audio-based threat detection interface
- ⚙️ Settings — Emergency contacts and safety preferences

---

## ✨ Features

### 1. 🏠 Emergency Help Dashboard

The Home screen provides access to the application's primary safety functions.

- **Live Safety Status:** Displays the current safety status and nearby risk information.
- **Risk Information:** Shows the nearest identified risk zone, distance, risk score, and last update.
- **Live Location Tracking:** Provides a control to start or stop tracking.
- **Trusted Circle:** Offers options to share location information with trusted contacts.
- **SMS Sharing:** Provides an option to share information through SMS.
- **WhatsApp Sharing:** Provides an option to share information through WhatsApp.
- **Emergency Services:** Quick-access buttons for ambulance and police assistance.
- **Panic Button:** Provides access to the emergency panic action.
- **Silent SOS:** Provides access to a discreet emergency action.

### 2. 🗺️ Interactive Safety Map

The Map section presents geographical information to help users understand potential safety risks.

Features include:

- City search and selection.
- Map zoom controls.
- Visual markers for different risk categories.
- Identification of high-risk areas.
- Identification of medium-risk areas.
- Visualization of safer areas.
- Help-point markers.
- A safety summary displaying the user's risk status.

The interface uses color-coded markers to make different safety categories easier to distinguish.

### 3. ⏱️ Check-In Timer

The Check-In Timer is designed to provide an additional safety mechanism when a user is travelling or visiting an unfamiliar location.

Features include:

- Preset countdown durations of 1, 5, 10, 15, 30, and 60 minutes.
- A custom-duration input.
- A Start Timer control.
- A safety deadline concept.
- An automatic panic-trigger workflow if the user misses a check-in.
- A location-sharing workflow intended to notify trusted contacts in an emergency.

The interface is designed to help users establish a time limit and check in before the countdown expires.

### 4. 🎙️ Audio Guardian

Audio Guardian provides an interface for audio-based threat detection.

Its intended detection scenarios include:

- Screams and distress signals.
- Emergency keywords such as "HELP".
- Hindi distress keywords such as "BACHAO".
- Other high-volume distress sounds.

The interface includes an activation control and a monitoring status indicator.

**Note:** Actual audio monitoring, keyword recognition, background execution, and automatic emergency triggering depend on the application's implemented audio-processing functionality and device permissions.

### 5. ⚙️ Settings and Preferences

The Settings section allows users to configure contact information and safety preferences.

**Emergency Contact**
- Enter an emergency contact number.
- Save the emergency contact.
- View the saved-contact status.

**Trusted Circle**
- Enter trusted contacts' phone numbers.
- Save trusted contact information.
- Configure contacts intended for check-in alerts and location sharing.

**Smart Safety Settings**
- Sound Alerts.
- Auto-Activate Guardian.
- Auto-Track on Open.
- Vibrate on Danger.

**Quick Actions**
- Open the safety map.
- Access Audio Guardian.
- Access the Check-In Timer.

**Activity Log**
- View recorded system activity.
- Access the Clear Log control.

The availability and persistence of each setting depend on the implemented application logic.

---

## 🧭 Application Navigation

The application uses a five-section bottom navigation bar.

| Section | Purpose |
|---|---|
| Home | Safety status and emergency assistance |
| Map | Geographical safety information |
| Check-In | Timed safety check-ins |
| Guardian | Audio-based threat detection |
| Settings | Contacts, preferences, and activity logs |

This navigation structure keeps the application's major safety functions accessible from its primary interface.

---

## 🎨 User Interface Design

EHS uses a clean, mobile-first interface designed around accessibility and ease of use.

Design characteristics include:

- Light, warm backgrounds.
- Rounded cards and buttons.
- Clear section headings.
- Color-coded safety indicators.
- Distinct visual treatments for emergency actions.
- Dedicated screens for individual safety functions.
- Persistent bottom navigation.
- Status indicators for important safety information.

The interface prioritizes readability and quick access to essential actions.

---

## 🛠️ Technology Stack

The exact technology stack should reflect the code used in your repository.

| Component | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript, if used in the project |
| Map | Leaflet and OpenStreetMap, if configured |
| Location | Browser or device geolocation APIs, if implemented |
| Messaging | SMS and WhatsApp sharing mechanisms, if implemented |
| Audio | Browser or device audio APIs, if implemented |

Update this section to match the actual dependencies and technologies in your project.

---

## 🚀 Getting Started

### Prerequisites

Depending on the implementation, you may need:

- A modern web browser.
- A code editor such as Visual Studio Code.
- A local development server.
- Internet connectivity for online map tiles or other external resources.

### Installation

**1. Clone the repository**

Replace `<your-username>` and `<your-repository>` with your GitHub username and repository name.

```bash
git clone https://github.com/<your-username>/<your-repository>.git
```

**2. Open the project directory**

```bash
cd <your-repository>
```

**3. Open the project**

If the project is a static HTML, CSS, and JavaScript application, open the project folder in Visual Studio Code and launch the main HTML file using Live Server.

Alternatively, use the development server specified by your project's configuration.

**4. Access the application**

Open the local development URL provided by your server.

For example:

```text
http://127.0.0.1:5500
```

The actual URL and port depend on your local server configuration.

---

## 🔐 Privacy and Safety Considerations

Because EHS deals with sensitive safety-related information, the following considerations are important:

- Obtain the appropriate permissions before accessing location or microphone data.
- Handle emergency contact information responsibly.
- Clearly communicate when location tracking or audio monitoring is active.
- Avoid collecting or storing unnecessary personal information.
- Test emergency workflows carefully before relying on them.
- Clearly distinguish simulated functionality from verified emergency communication.

**Important:** EHS should not be treated as a replacement for official emergency services. Users should contact the appropriate local emergency service when immediate assistance is required.

---

## 🔮 Future Scope

Potential future improvements include:

- More reliable location-sharing workflows.
- Improved location-based risk information.
- Enhanced audio distress detection.
- Additional emergency notification options.
- Improved accessibility.
- More comprehensive testing across mobile devices.
- Better handling of network interruptions.
- Additional privacy and permission controls.

These are potential enhancements, not claims that the functionality is already implemented.

---

## 🎯 Project Objective

The objective of Emergency Help System is to bring essential personal safety tools together in one application and provide users with convenient access to emergency assistance, location sharing, safety awareness, and check-in workflows.

---

## 👨‍💻 Project Information

**Project Name:** Emergency Help System (EHS)  
**Category:** Personal Safety / Emergency Assistance  
**Platform:** Web application or mobile-oriented web interface, depending on deployment

**Developed as an academic project.**

---

## ⚠️ Disclaimer

EHS is intended as a personal safety assistance project. The availability and reliability of its features depend on the underlying implementation, device permissions, network connectivity, and external services.

Do not rely exclusively on this application in an emergency unless its relevant functionality has been properly implemented and tested.
