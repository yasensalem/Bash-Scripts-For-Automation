# Expo Wizard

This repository contains a Bash script named `expo-wizard.sh` that acts as a wizard for setting up an Expo app called **crudler** using the blank template. The script guides you through creating the app, logging into your Expo account, opening the project in Visual Studio Code, and starting the Expo server in different modes based on your environment (local machine or Replit).

---

## Prerequisites

Before running the script, ensure you have the following installed:

- [Node.js and npm](https://nodejs.org/)
- [Expo CLI](https://docs.expo.dev/workflow/expo-cli/) (will be automatically downloaded via `npx` if not already installed)
- [Git](https://git-scm.com/)
- [Visual Studio Code](https://code.visualstudio.com/) (optional, if you want the script to open the project in VS Code)

> **Note:** When running on Replit, ensure that the `REPLIT_DEV_DOMAIN` environment variable is set. This variable is provided automatically by Replit and is used to configure network settings for Expo.

---

## Cloning the Repository

### Using Git in the Terminal

1. Open your terminal.
2. Clone the repository by running:

   ```bash
   https://github.com/yasensalem/Bash-Scripts-For-Automation.git
Change into the repository directory:


cd Bash-Scripts-For-Automation

## Using GitHub Desktop

---

Open GitHub Desktop.

Click on File > Clone Repository….

In the URL tab, enter the repository URL (e.g. https://github.com/your-username/your-repo-name.git).

Choose your local folder and click Clone.



## Usage


### Make the Script Executable:

In your terminal, navigate to the repository directory and run:


chmod +x expo-wizard.sh


### Run the Script:

Execute the script by running:


./expo-wizard.sh



### Follow the Prompts:

The script will guide you through the following steps:

Step 1: Create the Expo app named crudler using the blank template.

Step 2: Change into the newly created crudler directory.

Step 3: Log in to your Expo account.

Step 4: Open the project in Visual Studio Code.

Step 5: Select your environment and connection mode:

### Local machine:


The script starts Expo in Tunnel mode for mobile app testing.

### Replit:

You will be prompted to choose one of three connection modes:

### Public domain for mobile app:

This uses Replit environment variables to set the public URL.

### Tunnel with Ngrok:


This uses Tunnel mode.


Mobile browser (use if all else fails!!!!):


This publishes the Expo app.





## Licence


This project is open source. You are free to modify and distribute it as needed.
