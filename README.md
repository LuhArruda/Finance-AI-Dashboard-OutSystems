# Finance-AI-Dashboard-OutSystems
Premium financial dashboard developed in OutSystems with export to Excel and reactive data analysis.

🏗️ Project Architecture

The solution was designed following OutSystems best architectural practices, dividing responsibilities into two main layers:

1. ManageExpenses_Core.oml (Core Services Layer)

This module is the "heart" of the data and business logic.

Database: Definition of Entities (Account, Transaction, SavingsGoal, FinancialSource).

Business Logic: Server Actions for complex calculations and integrity validations.

Service Actions: Export action to Excel (GetExcelFile) that serves as an internal API for the screen.

Security: Definition of access Roles.

2. ManageExpenses_UI.oml (End-User Layer)

This module focuses on user experience and interface.

Interface (UI): Reactive screens for Dashboard, Asset Management, and Expense Listing.

UX/UI: Custom themes, modular CSS, and a Navy & Indigo-based Design System.

Data Orchestration: Use of Data Actions to consolidate information from multiple sources for charts.

Charts: Advanced implementation of Highcharts (OutSystems Charts).

🛠️ Stack Tecnológica

Plataforma: OutSystems 11 / ODC

Engine de Gráficos: OutSystems Charts (Highcharts Integration)

Base de Dados: SQL Server

Estilização: CSS3 Customizado e OutSystems UI Framework

🛠️ How to View the Files

To open these files, you need to have OutSystems Service Studio installed.

Download the .oml files.

Open Service Studio.

Drag the files into the platform or use the File > Open File menu.

Note: These files are proprietary binaries of the OutSystems platform and cannot be edited in conventional text editors.
