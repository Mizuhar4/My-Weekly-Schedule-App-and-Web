# My Weekly Schedule App

**Author:** Benjamín Fernández  

![Kotlin](https://img.shields.io/badge/Kotlin-1DA1F2?style=for-the-badge&logo=kotlin&logoColor=white)   ![HTML](https://img.shields.io/badge/HTML-FF4C1E?style=for-the-badge&logo=html5&logoColor=white)   ![CSS](https://img.shields.io/badge/CSS-2965f1?style=for-the-badge&logo=css3&logoColor=white)   ![JavaScript](https://img.shields.io/badge/JavaScript-F7E018?style=for-the-badge&logo=javascript&logoColor=black)  

---

## 📱 Android Application — *My Weekly Schedule App*

### **Overview**  
*My Weekly Schedule App* is an Android application that helps users create, view, and manage their weekly schedules directly on their mobile devices.  
It supports adding classes, tutoring sessions, and other events, with customizable details such as subject name, module, and room.  

The app uses a **WebView** to render the schedule, integrating HTML, CSS, and JavaScript for a smooth and responsive user experience.

---

### **Key Features**
- Interactive schedule table with touch support.  
- Color-coded subjects for quick identification.  
- Save and load schedules via local storage.  
- Export schedules as PNG or XLSX files.  
- Import schedules from XLSX files.  
- Mobile-optimized user interface.  

---

## 📂 Project Structure

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

### **Clone the Repository in Android Studio**

#### Method 1: From the Welcome Screen

1. Open Android Studio without a project loaded.
2. Click **"Get from VCS"**.
3. Paste the repository URL:

   ```
   https://github.com/Mizuhar4/My-Weekly-Schedule-App-and-Web.git
   ```
4. Click **Clone**.

#### Method 2: From Within an Open Project

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

## 🌐 Web Version — *My Weekly Schedule Web Page*

### **Overview**

The web-based version is a fully functional schedule builder created with HTML, CSS, and JavaScript.
It serves as the foundation for the Android WebView interface, but can also be used independently in any modern browser.

### **Key Features**

* Dropdown menus for period, day, and activity type.
* Input fields for subject, module, and room.
* Customizable color palette for classes.
* Action buttons: add, delete, clear, save, export.
* Export to PNG and XLSX formats.
* Import from XLSX files.
* Local storage persistence.
* Fully responsive design for desktop, tablet, and mobile.

> To run the web version, simply copy the files into the "Web Page" folder.

---

## Notes

* Subjects can be assigned custom colors for better visual organization.
* All schedules are stored locally on the device or browser.
* Import/export functions allow transferring schedules between web and Android versions.

