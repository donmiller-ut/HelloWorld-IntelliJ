# UToledoHelloWorld

A simple Java application demonstrating basic calculation functionality. This project serves as a "Hello World" example for the University of Toledo.

## Project Overview

This application contains:
- **Main.java**: Entry point that demonstrates a simple addition calculation
- **Calculate.java**: Utility class with methods for performing calculations

## Requirements

- Java JDK 8 or higher
- IntelliJ IDEA (any recent version)

## IntelliJ IDEA Setup Instructions

### 1. Open the Project
1. Launch IntelliJ IDEA
2. Select **File** → **Open**
3. Navigate to the project directory (`HelloWorld-IntelliJ`)
4. Select the folder and click **OK**

### 2. Configure Project SDK
1. Go to **File** → **Project Structure** (or press `Ctrl+Alt+Shift+S`)
2. Under **Project Settings** → **Project**, set the **Project SDK**:
   - If no SDK is listed, click **New...** and select your JDK installation path
   - Choose JDK 8 or higher
3. Set the **Project language level** to match your JDK version
4. Click **Apply** and **OK**

### 3. Configure Module Settings
1. In **Project Structure**, go to **Modules**
2. Ensure the module is selected and the **src** folder is marked as a **Sources** folder (should show in blue)
3. If not, right-click the `src` folder in the project view → **Mark Directory as** → **Sources Root**

### 4. Run the Application
1. Open `src/edu/utoledo/Main.java`
2. Right-click in the editor or on the file in the project tree
3. Select **Run 'Main.main()'**
   - Alternatively, click the green play button next to the `main` method
   - Or use the shortcut: `Shift+F10`

## Project Structure

```
HelloWorld-IntelliJ/
├── src/
│   └── edu/
│       └── utoledo/
│           ├── Main.java          # Entry point
│           └── Calculate.java     # Calculation utility
├── GitHubDemo.iml                 # IntelliJ module file
└── README.md                      # This file
```

## Running the Application

When you run the application, you should see the following output:
```
Here is a calcuation 2 + 3 =5.0
```

## Testimonial

> This is amazing!
