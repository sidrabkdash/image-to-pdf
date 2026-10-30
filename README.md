\# Image to PDF – Mobile Document Scanning Application



\## 1. Project Overview



Image to PDF is a Flutter-based mobile application that allows users to select or capture images and convert them into PDF documents.



The application provides a simple interface for creating, previewing, saving, sharing, and managing PDF files.



\## 2. Main Features



\- \*\*Select Images:\*\* Choose one or multiple images from the device gallery.

\- \*\*Capture Images:\*\* Take photos directly using the device camera.

\- \*\*Image Management:\*\* View selected images and remove unwanted images.

\- \*\*PDF Conversion:\*\* Convert selected images into a single PDF document.

\- \*\*PDF Preview:\*\* Preview generated PDF documents.

\- \*\*PDF History:\*\* View previously generated PDF files.

\- \*\*Save PDF Files:\*\* Save PDF documents on the device.

\- \*\*Share PDF Files:\*\* Share generated PDF documents.

\- \*\*Delete PDF Files:\*\* Remove saved PDF records from the history.



\## 3. Technologies Used



| Technology | Purpose |

|---|---|

| Flutter | Mobile application development |

| Dart | Programming language |

| SQLite | Local database storage |

| image\_picker | Image selection and camera access |

| pdf | PDF document generation |

| printing | PDF preview and sharing |

| path\_provider | Access application storage directories |

| sqflite | SQLite database integration |

| path | File path management |



\## 4. Database



The application uses SQLite for local data storage.



The `pdf\\\_history` table stores information about generated PDF documents, including:



\- PDF ID

\- File name

\- File path

\- Creation date and time



This allows users to access and manage previously generated PDF documents.



\## 5. Project Structure



```text

image-to-pdf/

│

├── lib/

│   ├── main.dart

│   └── database\\\_helper.dart

│

├── android/

├── ios/

├── linux/

├── macos/

├── windows/

├── web/

│

├── test/

├── pubspec.yaml

├── pubspec.lock

└── README.md

```



\## 6. Installation and Setup



\### Requirements



\- Flutter SDK

\- Dart SDK

\- Android Studio or Visual Studio Code

\- Android device or emulator



\### Run the Application



1\. Clone the repository:



```bash

git clone https://github.com/sidrabkdash/image-to-pdf.git

```



2\. Open the project directory:



```bash

cd image-to-pdf

```



3\. Install dependencies:



```bash

flutter pub get

```



4\. Run the application:



```bash

flutter run

```



\## 7. Testing



The project includes Flutter widget tests and was checked using:



```bash

flutter analyze

flutter test

```



\## 8. Project Repository



GitHub: https://github.com/sidrabkdash/image-to-pdf



\## 9. Conclusion



Image to PDF provides a convenient way to convert images into PDF documents using a mobile application.



The project combines Flutter development, image processing, PDF generation, local database management, and file sharing in one application.



\---



\*\*Project:\*\* Image to PDF – Mobile Document Scanning Application

\*\*Platform:\*\* Flutter

\*\*Repository:\*\* https://github.com/sidrabkdash/image-to-pdf



\## App Screenshots



\### Home Screen

!\[Home Screen](screenshots/01-home-screen.jpg)



\### Selected Images

!\[Selected Images](screenshots/02-images-selected.jpg)



\### PDF Preview

!\[PDF Preview](screenshots/03-pdf-preview.jpg)

