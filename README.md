# Reading Comprehension Assets

This repository contains split zip archives of the complete reading passages and generated illustrations.

## How to extract:
To combine the files and extract the zip archive:

### Windows (PowerShell):
```powershell
# Combine split files
Get-Content reading_comprehension_assets.zip.* -Encoding Byte -ReadCount 0 | Set-Content reading_comprehension_assets.zip -Encoding Byte

# Extract zip
Expand-Archive -Path reading_comprehension_assets.zip -DestinationPath .
```

### Linux / macOS (Bash):
```bash
# Combine split files
cat reading_comprehension_assets.zip.* > reading_comprehension_assets.zip

# Extract zip
unzip reading_comprehension_assets.zip
```
