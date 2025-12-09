# Invoice File Organizer
A UiPath workflow that automatically organizes invoices in a folder by year, based on the filenames. The workflow reads each invoice, identifies the year from its filename, and moves it into a dedicated folder for that year. If a folder for the year does not exist, it will be created automatically.

## ✨ Features
- Automatically scans a folder containing invoices.
- Extracts the year from each invoice filename.
- Creates folders for each year if they do not exist.
- Moves invoices to the corresponding year folder.
- Provides a confirmation message once the process is completed.

## 📋 Requirements
- UiPath Studio

## ⚙️ Setup
1. Clone or download this repository.
2. Open the project in UiPath Studio.
3. Run `Main.xaml`.
4. Set the `InvoicesDirectory` variable to the path of your invoices folder.
5. Run the workflow.
