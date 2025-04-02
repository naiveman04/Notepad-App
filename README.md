# Notepad - Simple Text Editor

## Overview  
**Notepad** is a lightweight, user-friendly text-editing application built using **Java Swing**. It provides essential functionalities for creating, editing, and managing plain text documents, making it a practical tool for everyday use. The project aims to deliver a simple yet effective text editor with an intuitive interface, inspired by classic notepad utilities.

## Features  
- ✍️ **Text Editing**: Create, edit, and format plain text in a central text area with word wrap support.  
- 📂 **File Management**: Supports creating new documents, opening `.txt` files, saving changes, and printing content.  
- ✂️ **Basic Editing Tools**: Includes copy, paste, cut, and select-all features with keyboard shortcuts.  
- ℹ️ **About Section**: Displays application details in a dedicated window for user reference.  

## Pages  
The **Notepad** application consists of two main components:  
1. **Main Editor Window** – The primary interface with a text area and menu bar for file and editing operations.  
2. **About Window** – A pop-up providing information about the application, including its purpose and version.  

## Technologies Used  
- **Language**: Java  
- **GUI Framework**: Java Swing, AWT (Abstract Window Toolkit)  
- **File Handling**: Java I/O (FileReader, BufferedWriter)  

## How It Works  
1. **Launch the Application**: The main window opens with a blank text area and menu bar.  
2. **File Operations**: Users can create a new document, open an existing `.txt` file, save their work, or print it using the "File" menu.  
3. **Text Editing**: Basic editing functions (copy, paste, cut, select all) are accessible via the "Edit" menu or shortcuts (e.g., Ctrl+C, Ctrl+V).  
4. **Help Access**: Clicking "About Notepad" under the "Help" menu opens a window with application details.  
5. **Exit**: The application can be closed via the "Exit" option or window controls.  

## Installation & Setup  
### Prerequisites  
- Java Development Kit (JDK) 8 or higher  
- Git (optional, for cloning the repository)  

### Steps  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/notepad-app.git
   cd notepad-app
2. Compile the Java files:
   ```bash
   javac notepad/*.java
3. Run the application:
   ```bash
   java notepad.Notepad

### Future Enhancements
- 📑 **Multi-Document Support:** Add tabbed editing for managing multiple files simultaneously.
- ☁️ **Cloud Integration:** Enable saving and syncing files to cloud storage platforms like Google Drive.
- 🔍 **Search Functionality:** Implement search-and-replace features for improved text editing efficiency.
- 🎨 **Customization:** Allow users to personalize the interface with themes and font options.
