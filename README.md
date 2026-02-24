# 🐻 login_with_animation

A Flutter login screen featuring an interactive Rive bear animation 🔒

---

## 📋 Brief Description of Functionalities

**login_with_animation** is a Flutter application that presents an animated login screen using **Rive**. The animation features a bear that reacts in real time to user actions, turning the login process into a fun and engaging experience.

**Main Features:**
- 👀 The bear follows the user's typing while entering the email.
- 🙈 When typing the password, the bear covers its eyes.
- ✅ If both the email and password meet the validation criteria (email regex, and password with at least 8 characters, one uppercase, one number, and one special symbol), a **success animation** plays.
- ❌ Otherwise, a **failure animation** is displayed.

---

## 🧠 What is Rive and What is a State Machine?

**Rive** is a powerful tool for creating real-time, interactive animations that respond to app logic.  
A **State Machine** in Rive controls transitions between animations based on logic and input events.

In this project, the State Machine **"Login Machine"** manages the bear's animations and reactions throughout the login process.

---

## 💻 Technologies Used

- **FLUTTER** – Cross-platform UI framework  
- **DART** – Programming language  
- **RIVE** – Real-time animation tool  

---

## 🗂️ Basic Project Structure (lib folder)

```
lib/
├── main.dart                 # App entry point
└── screens/
    └── login_screen.dart     # Login UI with Rive character integration

assets/
└── animated_login_character.riv   # Rive animation file
```

### Main Files Description:
- **main.dart** – Initializes the Flutter app and navigates to `LoginScreen`.
- **login_screen.dart** – Contains the login interface with text fields, validation logic, and the Rive animated bear. It loads the `.riv` file, connects to the "Login Machine" state machine, and sends inputs based on user actions (typing, submitting, validation results).

---

## 🎥 Demo (GIF)

> ⚠️ *Placeholder – replace with actual GIF path.*  
![20260223_194046 https://reccloud.com/es/u/ihoe8u4)  
*The GIF above shows the bear reacting to email typing, covering eyes during password entry, and displaying success/failure animations based on validation.*

---

## 📚 Subject Name

**Graficación** (Computer Graphics)

---

## 👨‍🏫 Teacher

**Rodrigo Fidel Gaxiola Sosa**

---

## 🙌 Credits

Original animation: **Remix of Login Machine**  
Created and published on **Rive Marketplace**.  
🔗 [View the original animation on Rive Marketplace](https://rive.app/community/...) *(replace with actual link)*

---

⭐ *Made with Flutter, Dart & Rive*
