# GRAF
# Geographic Information Software to conduct file transformation in the objective of Geoid compatibility within GNSS Receiver

## 1. Overview of the Application

GRAF is a file transformation application developed as part of ITB's Geodesy and Geomatics Capstone Project with the listed Contributors below. The application aims to conduct file transformation of common final product of Geoid Undulation [N] in .xyz files and then parsing it to be transformed into file format supported by GNSS Receiver such as .ggf files. It aims to chase interoperability/compatibility between various GNSS Receiver and Geoid model, especially those locally developed for regional/national purposes in an intuitive and simple procedure.

## 2. Project Goals

The objective GRAF intends to accomplish these goals:
1. To identify and address incompatibility between various geoid files and its GNSS Receiver.
2. To develop an application that provides the transformation of common Geoid Undulation files.
3. To provide users with a simple and intuitive application to parse and transform Geoid Undulation files into Geoid Files.

## 3. Key Features

The application is expected to include these following features:

1. **File Upload:** The ability to accept user input raw Geoid Undulation files abd its various supported format (e.g., .xyz, .csv, and other supported formats).
2. **Parsing Geoid Undulation Files:** The process of reading and interpreting raw Geoid Undulation files and extract their underlying data, identify their structure, and prepare them for subsequent transformation into the target .ggf format.
3. **File Transformation:** Transforming the identified raw Geoid Undulation files data structure uploaded by the user and transform them into .ggf files
4. **File Export:** The ability to export the targeted transformation file for download and user's intended usage within a GNSS Receiver.
5. **Access to Capstone's Geoid Model:** User that have access to the GRAF application will have access to a regional Geoid Model for the entire Java Island both for usage and reference.

## 4. Application Pipeline

```
GRAF
├── File input
├── Reading & Parsing
├── Data Normalization
├── Targeted Transformation
├── Data Validation
└── Output
```

## 5. Stack and Computing Languange

The currently planned framework of the GRAF application will include:

|Category | Technology|
|---|---|
|Frontend | [To be determined]|
|Backend | [To be determined]|
|Programming Languange | [To be determined]|
|Geospatial Processing | [To be determined]|
|File Parsing | [To be determined]|
|File Transformation | [To be determined]|
|Database | [To be determined]|
|API/Communication | [To be determined]|
|Version Control | Git & GitHub|
|Development Environment | [To be determined]|
|Testing & Validation | [To be determined]|

## 6. Project Structure

The repository is organised into the following directories:

```
project-name/
├── README.md
├── docs/
├── frontend/
├── backend/
└── assets/
```

*Note: The directory structure may evolve as development progresses.*

## 7. Development Team

| Name | Role / Responsibility |
|---|---|
| Reksa Okta Ramadhani| [TBD] |
| Firzatullah Al-Ghifari| [TBD] |
| Mustika Gangga Nirmala | [TBD] |
| Anugrah Arya Muhajir | [TBD] |
| Nurachman Alwy Sumintardja | [TBD] |

## 8. Development Guidelines

To maintain consistency and collaboration throughout development:

- All members should work through their own Git branches.
- Changes should be submitted through Pull Requests.
- The main branch should contain the stable version of the application.
- Tasks and development progress should be documented through GitHub Issues.

## 9. Project Status

**Current Status:** Planning / Initial Development

This section will be updated as the project progresses.
