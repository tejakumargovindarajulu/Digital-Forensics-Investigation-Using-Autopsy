# Digital Forensics Investigation Using Autopsy

## Project Overview

This project presents a practical digital crime scene investigation conducted using Autopsy 4.22.1.

A forensic workstation image was examined to identify and correlate digital artifacts associated with a simulated Snowy Owl wildlife-crime investigation.

The investigation focused on reconstructing user activity through browser history, web searches, cached communication artifacts, recently accessed documents, Windows system metadata, deleted files, Recycle Bin evidence, and Shell Bag artifacts.

The project demonstrates how multiple forensic artifacts can be correlated to reconstruct user behavior, establish a timeline of activity, and support evidence-based investigative conclusions.

---

## Investigation Objectives

The main objectives of this investigation were to:

- Analyze a forensic workstation image using Autopsy
- Identify relevant browser and web-search artifacts
- Examine browsing history and cached web content
- Investigate recently accessed documents
- Recover and examine deleted-file artifacts
- Analyze Windows system metadata
- Examine Shell Bag artifacts for directory-access history
- Correlate timestamps across multiple artifacts
- Reconstruct user activity from digital evidence
- Document findings using a structured forensic investigation process

---

## Tools Used

### Autopsy 4.22.1

Autopsy was used as the primary digital forensic analysis platform for examining the workstation image and extracting forensic artifacts.

### Additional Analysis

Extracted artifact information was reviewed and organized to support investigation documentation, timeline reconstruction, and reporting.

---

## Digital Evidence Examined

The investigation examined several categories of forensic evidence:

- Google Chrome Web Search artifacts
- Browser Web History
- Chrome Web Cache
- Google Hangouts-related cached artifacts
- Recent Documents
- Windows Operating System metadata
- Deleted files and Recycle Bin artifacts
- Windows Shell Bag artifacts
- File paths and metadata
- File-access and deletion timestamps

---

## Investigation Process

### 1. Web Search Analysis

Autopsy's Web Search artifacts were examined to identify search activity associated with the investigation.

One of the significant recovered searches included:

`where to keep a snowy owl`

Additional owl-related search activity was identified and used to reconstruct the user's browsing behavior.

---

### 2. Web History Analysis

Browser history artifacts were examined to determine websites accessed around the same period.

An Amazon web visit was identified following the owl-related Google searches.

The browser artifacts provided useful information including timestamps, domains, URLs, and program information.

---

### 3. Web Cache and Communication Artifacts

Chrome cache artifacts associated with Google Hangouts were identified during the investigation.

Although complete chat messages were not recovered from the examined artifact, cached files demonstrated access to Hangouts-related web resources.

This demonstrated the importance of browser cache examination when investigating communication activity.

---

### 4. Recent Document Analysis

Autopsy's Recent Documents artifacts identified access to:

`Snowy_Owl.pdf`

The associated link artifact indicated that the document had been accessed from the `F:` drive.

This artifact helped correlate document-access activity with the browser activity identified during the investigation.

---

### 5. System Metadata Analysis

Operating-system information extracted during the investigation was examined to identify the system environment and user information associated with the workstation.

The recovered metadata included information relating to:

- Windows operating system
- Computer hostname
- User information
- Processor architecture
- System directories

These artifacts supported system and user attribution within the investigation scenario.

---

### 6. Deleted File Investigation

Recycle Bin artifacts were examined to identify deleted files.

A deleted image named:

`Pygmy Owl.jpg`

was identified within the forensic evidence.

The artifact preserved information including the original file location and deletion timestamp.

This demonstrated how deleted-file artifacts can remain valuable during a forensic investigation.

---

### 7. Shell Bag Analysis

Windows Shell Bag artifacts were examined to identify evidence of directory navigation.

Shell Bag information associated with the user's `Downloads` directory was identified from Windows Registry data.

These artifacts provided additional evidence of folder-access activity and helped reconstruct historical user interaction with the file system.

---

## Key Findings

The investigation identified and correlated several important digital artifacts:

- Owl-related Google search activity
- Browser history associated with the investigation timeline
- Amazon browsing following relevant searches
- Google Hangouts-related browser cache artifacts
- Access to `Snowy_Owl.pdf`
- Windows system and user metadata
- Deleted `Pygmy Owl.jpg` evidence
- Recycle Bin metadata
- Shell Bag evidence of directory access
- Timestamp relationships between multiple forensic artifacts

The combination of these artifacts provided contextual and circumstantial digital evidence that could support further investigation.

The project did not establish definitive proof of illegal wildlife trading; instead, the recovered artifacts demonstrated how digital forensic evidence can be correlated to identify behavioral patterns and investigative leads.

---

## Forensic Techniques Demonstrated

- Disk Image Examination
- Digital Evidence Triage
- Browser Forensics
- Web History Analysis
- Web Search Analysis
- Browser Cache Analysis
- Deleted File Analysis
- Recycle Bin Analysis
- Windows Artifact Analysis
- Shell Bag Analysis
- Recent Document Analysis
- Metadata Analysis
- Timestamp Correlation
- User Activity Reconstruction
- Forensic Reporting

---

## Skills Demonstrated

**Digital Forensics | Autopsy | Browser Forensics | Windows Forensics | File System Analysis | Deleted File Analysis | Metadata Analysis | Evidence Triage | Timeline Analysis | Shell Bag Analysis | Digital Evidence Analysis | Forensic Reporting**

---

## Screenshots

Screenshots from the practical Autopsy investigation are provided in the `screenshots` directory.

The screenshots demonstrate:

1. Web Search Artifact Analysis
2. Web History Analysis
3. Google Hangouts / Web Cache Artifact Analysis
4. Recent Document Analysis
5. Windows System Metadata Analysis
6. Deleted File / Recycle Bin Analysis
7. Shell Bag Analysis

---

## Project Structure

Digital-Forensics-Investigation-Using-Autopsy/
│
├── README.md
│
├── screenshots/
│   ├── 01-web-search-analysis.png
│   ├── 02-web-history-analysis.png
│   ├── 03-hangouts-cache-analysis.png
│   ├── 04-recent-document-analysis.png
│   ├── 05-system-metadata-analysis.png
│   ├── 06-deleted-file-analysis.png
│   └── 07-shellbag-analysis.png
│
└── report/
    └── Digital-Forensics-Investigation-Report.pdf

---

## Ethical Considerations

This project was conducted for academic and cybersecurity learning purposes.

Digital forensic evidence should be handled in accordance with applicable legal, privacy, evidence-preservation, and chain-of-custody requirements.

---

## Conclusion

This project demonstrates a practical digital forensic investigation using Autopsy 4.22.1.

By analyzing browser artifacts, cached web activity, recent documents, operating-system metadata, deleted files, Recycle Bin evidence, and Windows Shell Bags, the investigation reconstructed relevant user activity and correlated multiple sources of digital evidence.

The project demonstrates practical experience in digital evidence examination, Windows and browser artifact analysis, evidence correlation, timeline reconstruction, and forensic reporting.
