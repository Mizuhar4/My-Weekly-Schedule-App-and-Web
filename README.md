# Author: Benjamín Fernández

---

# My Weekly Schedule App

## **Project Name:** My Weekly Schedule App

**Description:**  
This Android application allows users to create, view, and manage their weekly schedules directly on their mobile devices. Users can add classes, tutoring sessions, or other events to specific periods and weekdays. Each entry can include details such as the subject name, module, and room.  

**Features:**

- Interactive schedule table with touch support.  
- Color-coded subjects for quick identification.  
- Save and load functionality using local storage.  
- Export options: PNG image of the schedule and XLSX file.  
- Import schedules from XLSX files.  
- User-friendly interface optimized for mobile screens.  

> The app uses a WebView to render the schedule interface, leveraging the original HTML, CSS, and JavaScript for a seamless experience.

---

# HTML/Web Version

## **Project Name:** My Weekly Schedule Web Page

**Description:**  
This web-based schedule builder allows users to create a customizable weekly timetable using HTML, CSS, and JavaScript.  

**Features:**

- Dropdown menus to select the period, day, and type of activity (class, tutoring, or other).  
- Input fields for subject name, module, and room.  
- Color palette to assign unique colors to classes for easy recognition.  
- Buttons to add, delete, clear, save, and export schedule data.  
- Export functionality to PNG and XLSX formats.  
- Import functionality for XLSX files.  
- Local storage support to persist schedule data between sessions.  
- Responsive design that adapts to different screen sizes, including tablets and mobile devices.  

> The HTML version is fully functional in modern web browsers and serves as the basis for the Android WebView app.

---

## Project Structure

```bash
📂 app/
└── 📂 src/
  └── 📂 main/
     ├── 📂 manifests/
     │    └── 📄 AndroidManifest.xml
     ├── 📂 kotlin+java/
     │    └── 📂 com.example.mihorarioapp/
     │          └── 📄 MainActivity.kt
     ├── 📂 assets/
     │    ├── 📄 index.html
     │    └── 📄 style.css
     └── 📂 res/
          ├── 📂 mipmap
          │   └── 📄 icono.png
          └── 📂 layout
              └── 📄 activity_main.xml
```


---

## Usage

1. Clone the repository.  
2. Open the project in Android Studio.  
3. Place `index.html`, `style.css`, and JS libraries in `app/src/main/assets/`.  
4. Run the app on an Android device or emulator.  

> The app will display the interactive schedule using a WebView.

---

## Technologies

- Kotlin / Android Studio  
- WebView  
- HTML, CSS, JavaScript  
- html2canvas (for PNG export)  
- SheetJS / XLSX (for Excel export/import)  

---

## Notes

- Subjects can be color-coded for better visual organization.  
- The app stores schedules locally on the device.  
- Export and import allow sharing schedules between devices or web/Android versions.  


