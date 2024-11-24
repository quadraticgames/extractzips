# ExtractAndOrganizeZips

A PowerShell script to extract multiple ZIP files and move specific file types (e.g., .ttf, .otf) to a root folder.

## Features
- Extracts all `.zip` files in a specified folder.
- Moves specified file types (e.g., `.ttf`, `.otf`) to a root folder.
- Optionally removes empty subfolders.

## Requirements
- Windows PowerShell 5.1 or later.
- Administrative privileges (recommended).

## Usage
1. Open PowerShell as Administrator.
2. Run the script using the following parameters:
   ```powershell
   .\ExtractAndOrganizeZips.ps1 -ZipFolderPath "C:\Path\To\Zips" -RootFolderPath "C:\Path\To\Root"
