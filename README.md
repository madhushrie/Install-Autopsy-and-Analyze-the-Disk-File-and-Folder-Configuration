# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results
<img width="848" height="408" alt="Screenshot 2026-11-02 105557" src="https://github.com/user-attachments/assets/60e7ccf4-8dae-4a70-9ee5-adadfcb840cb" />
<img width="900" height="433" alt="Screenshot 2026-11-02 105551" src="https://github.com/user-attachments/assets/48d0211e-b2a2-437d-baeb-0ce4666df2fc" />

<img width="838" height="411" alt="Screenshot 2026-11-02 105545" src="https://github.com/user-attachments/assets/16b754d3-3dcc-4ff7-ac53-5a3d0bb9bcbf" />
<img width="1001" height="475" alt="Screenshot 2026-11-02 105540" src="https://github.com/user-attachments/assets/fbff2847-d7f8-48e7-8f5a-017913bd8a2a" />
<img width="959" height="499" alt="Screenshot 2026-11-02 105533" src="https://github.com/user-attachments/assets/8737e441-7f5e-49e6-a541-b04ac3371270" />
<img width="1003" height="520" alt="Screenshot 2026-11-02 105528" src="https://github.com/user-attachments/assets/33274361-2fbf-4835-90f1-d412a21359d5" />
<img width="1700" height="1005" alt="Screenshot 2026-11-02 105431" src="https://github.com/user-attachments/assets/d624b4e6-02bb-4dd3-adfc-4f465e21729a" />

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
