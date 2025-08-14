# My Weekly Schedule App

**Author:** Benjamín Fernández  

---

## Android Application — *My Weekly Schedule App*

### **Overview**  
*My Weekly Schedule App* is an Android application designed to help users create, view, and manage their weekly schedules efficiently from their mobile devices. The app supports adding classes, tutoring sessions, and other events, each with customizable details such as subject name, module, and room.  

The interface is optimized for mobile screens and leverages a **WebView** to render the scheduling interface, integrating HTML, CSS, and JavaScript for a seamless experience.  

### **Key Features**
- Interactive schedule table with touch support.  
- Color-coded subjects for quick identification.  
- Save and load schedules via local storage.  
- Export schedules as PNG images or XLSX files.  
- Import schedules from XLSX files.  
- Mobile-friendly user interface.  

---

## Web Version — *My Weekly Schedule Web Page*

### **Overview**  
The web-based version provides a fully functional schedule builder built with HTML, CSS, and JavaScript. It serves as the foundation for the Android WebView interface while remaining independently usable in any modern browser.  

### **Key Features**
- Dropdown menus to select period, day, and activity type.  
- Input fields for subject, module, and room.  
- Customizable color palette for class identification.  
- Action buttons to add, delete, clear, save, and export schedules.  
- Export to PNG and XLSX formats.  
- Import from XLSX files.  
- Local storage persistence between sessions.  
- Responsive design for desktop, tablet, and mobile.  

---

## Project Structure

```bash
app/
└── src/
    └── main/
        ├── 📂 manifests/
        │    └── 📄 AndroidManifest.xml
        ├── 📂 kotlin+java/
        │    └── 📂 com.example.mihorarioapp/
        │          └── 📄 MainActivity.kt
        ├── 📂 assets/
        │    ├── 📄 index.html
        │    └── 📄 style.css
        └── 📂 res/
             ├── 📂 mipmap/
             │   └── 📄 icono.png
             └── 📂 layout/
                 └── 📄 activity_main.xml
```

---

## Getting Started

### **Cloning the Repository in Android Studio**

#### **Method 1: From the Welcome Screen**

1. Open Android Studio without a project loaded.
2. Click **"Get from VCS"**.
3. Paste the repository URL:

   ```
   https://github.com/Mizuhar4/My-Weekly-Schedule-App-and-Web.git
   ```
4. Click **Clone**.

#### **Method 2: From Within an Existing Project**

1. Go to **File → New → Project from Version Control…**
2. Paste the repository URL:

   ```
   https://github.com/Mizuhar4/My-Weekly-Schedule-App-and-Web.git
   ```
3. Click **Clone**.

> Once cloned, the app will display the interactive schedule using a WebView.

---

## Technologies Used

* **Kotlin** / Android Studio
* **WebView** integration
* **HTML**, **CSS**, **JavaScript**
* [html2canvas](https://html2canvas.hertzen.com/) — PNG export
* [SheetJS](https://sheetjs.com/) — XLSX export/import

---

## Notes

* Subjects can be assigned colors for improved visual organization.
* All schedule data is stored locally on the device.
* Import/export features allow easy transfer of schedules between web and Android versions.

---


