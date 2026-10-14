# Quick Reference: Document Types in Skybook Flight Service

## Document Inventory

```
FlightService_Detailed_Documents_Agnibha_Chandra/
├── Sequence/Flow Diagrams (5 pairs)
│   ├── Add_Flight.drawio / .pdf
│   ├── Delete_Flight.drawio / .pdf
│   ├── Schedule_Flight.drawio / .pdf
│   ├── Search_Flight.drawio / .pdf
│   └── Update_Flight.drawio / .pdf
│
├── Data Model
│   ├── Flight_ER_Diagram.drawio / .pdf
│
├── Object Design (2 pairs)
│   ├── flightServices_ClassDiagram.drawio / .pdf
│   └── Flight_User_Service.drawio / Flight_User_Service_CD.pdf
│
├── Requirements
│   ├── FlightService_USE_CASE.draw.io / .pdf
│
├── UI/UX Design
│   ├── UI-Wireframe-Flight-Service.docx / .pdf
│
└── Architecture
    └── Project Architecture.pptx
```

## Document Type Matrix

| Type | Count | Format | Purpose | Audience |
|------|-------|--------|---------|----------|
| **Sequence Diagrams** | 5 | draw.io + PDF | Process flows & workflows | Developers, Architects |
| **ER Diagrams** | 1 | draw.io + PDF | Database schema | DBAs, Developers |
| **Class Diagrams** | 2 | draw.io + PDF | OOP design | Developers, Architects |
| **Use Case Diagrams** | 1 | draw.io + PDF | System functionality | All stakeholders |
| **UI Wireframes** | 1 | DOCX + PDF | Interface design | UI/UX, Product |
| **Architecture** | 1 | PPTX | System overview | Architects, Managers |

## File Format Breakdown

```
Draw.io Files:     11 (editable source diagrams)
PDF Files:         10 (distribution/viewing)
PowerPoint:         1 (presentation)
Word Document:      1 (wireframes)
─────────────────────────────────
Total:             23 files
```

## Key Characteristics

### ✅ Strengths
- **Dual-format pattern:** Source (draw.io) + Export (PDF)
- **Comprehensive coverage:** All system aspects documented
- **Professional quality:** Industry-standard tools and notation
- **Accessibility:** Multiple formats for different audiences
- **Maintainability:** Editable source files for updates

### 📋 Coverage Areas
- ✓ Data modeling (ER diagrams)
- ✓ Object-oriented design (Class diagrams)
- ✓ Functional requirements (Use cases)
- ✓ Process flows (Sequence diagrams)
- ✓ User interface (Wireframes)
- ✓ System architecture (Presentations)
- ✓ CRUD operations (Add, Update, Delete, Search, Schedule)

### 🎯 Audience Mapping
| Audience | Documents |
|----------|-----------|
| **Developers** | Class diagrams, ER diagrams, Sequence diagrams |
| **Architects** | Architecture presentation, Use cases, Class diagrams |
| **Business Analysts** | Use cases, Wireframes, Sequence diagrams |
| **DBAs** | ER diagrams |
| **UI/UX Designers** | Wireframes, Use cases |
| **Project Managers** | Architecture, Use cases |

## Documentation Best Practices Observed

1. **Clear Naming:** Descriptive file names indicating type and subject
2. **Consistent Organization:** All files in single directory
3. **Version Control:** Metadata preserved in files
4. **Completeness:** No gaps in documentation coverage
5. **Accessibility:** Multiple export formats
6. **Editability:** Source files maintained for updates

## Recommended Usage Pattern

```
For Creating New Documentation:
1. Create diagram in draw.io (editable source)
2. Export to PDF (for distribution)
3. Store both versions in repository
4. Use consistent naming: [ComponentName]_[DiagramType]
5. Include metadata (dates, versions)
6. Organize by component/service
```

## Tools Used

| Tool | Purpose | Files |
|------|---------|-------|
| **draw.io** | Diagram creation | 11 .drawio files |
| **Chromium/Skia** | PDF export | 10 .pdf files |
| **Microsoft Word** | Wireframes | 1 .docx file |
| **Microsoft PowerPoint** | Presentations | 1 .pptx file |

## Metadata Summary

- **Created:** January 2020
- **Tool Version:** draw.io v12.5.8
- **Creator:** Agnibha Chandra
- **Project:** Skybook E-flight Booking System
- **Component:** Flight Service

---

**Note:** This documentation serves as an excellent template for creating similar comprehensive documentation for other system components or services.
