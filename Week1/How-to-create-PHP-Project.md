# How to Create a PHP Project Using XAMPP

This guide will help you set up a PHP project using XAMPP on your local machine.

## Prerequisites

Ensure you have the following installed:

- **XAMPP**: Download and install XAMPP from [apachefriends.org](https://www.apachefriends.org/index.html).
- **Text Editor**: Use a text editor like VSCode, Sublime Text, or Notepad++.

## Step 1: Set Up the Project Directory

1. **Open the XAMPP Control Panel**: Start the XAMPP Control Panel and ensure that the Apache server is running.

2. **Create a Project Directory**: Navigate to the `htdocs` directory within your XAMPP installation folder. The `htdocs` folder is typically found at:

   - **Windows**: `C:\xampp\htdocs`
   - **macOS**: `/Applications/XAMPP/htdocs`

   Inside the `htdocs` folder, create a new directory for your project:

   ```bash
   mkdir C:\xampp\htdocs\my-php-project

## Step 2 : Write Basic PHP Code
1. **Create a PHP File** : Create Initial Files: Inside your project directory, create the following files:
   ```bash
   touch index.php


2. **Edit the PHP File** : Edit index.php: Open index.php in your text editor and add the following code:
   ```bash
   <?php
      // print hello world
      echo "Hello, World!";
   ?>

