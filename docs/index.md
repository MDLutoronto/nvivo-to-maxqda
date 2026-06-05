---
title: "Moving from NVivo to MAXQDA"
layout: "home"
description: "To move between qualitative data analysis tools, you must put your project file into [REFI-QDA standard](https://www.qdasoftware.org/)."
permalink: "/"  #! Remove this if not the homepage
created_date: 2025-08-08
staff:
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
maintainer:
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
---

# Moving from NVivo to MAXQDA

To move between qualitative data analysis tools, you must put your project file into [REFI\-QDA standard](https://www.qdasoftware.org/).

To move an existing project from NVivo to MAXQDA:

1. Export your project to QDPX format:

    1. [NVivo for Windows instructions](https://help-nv.qsrinternational.com/15/win/Content/projects-teamwork/refi-qda%20standard.htm)  
    2. [NVivo for Mac instructions](https://help-nv.qsrinternational.com/15/mac/Content/projects-teamwork/refi-qda%20standard.htm)
2. Import your QDPX file into MAXQDA:

    1. [Follow the import instructions](https://www.maxqda.com/help-mx24/report-and-export/export-and-import-refi-qda-projects) (this page also outlines what is retained and lost when moving into MAXQDA)

Note: Not everything is retained when exporting an NVivo project to this format.  

From a sample test, here were the results:
* Files transfer over correctly (only tested Word Documents and PDFs)
* File folders don't transfer over, all files are just grouped in the main Documents folder
* Codes transfer over correctly, including hierarchies
* Coding in text files transfers over correctly
* Coding of PDF regions transfers over correctly
* **Coding of PDF text does NOT transfer over at all (this is probably the biggest limitation)**
* Memos, memo links, and annotations all transfer over, but as Free Memos, meaning that there's no link back to the associated file or associated text fragment (I would recommend that you put the file name in the memo link title to help with this association. Annotations will need to be recreated.)
* All cases transfer over as codes and no case attributes are transferred over, just attribute names with blank information underneath (if you have your attributes stored in a spreadsheet, it would be a better idea to re-import this into MAXQDA as document variables than to try to fix the imported case data)

For questions, help moving your project over, or to troubleshoot any issues, feel free to [contact us](https://mdl.library.utoronto.ca/about/contact).

**Technique:** [Qualitative Data Analysis](https://mdlutoronto.github.io/tutorials-search/?technique=Qualitative+Data+Analysis) \| **Tools:** [NVivo](https://mdlutoronto.github.io/tutorials-search/?tool=NVivo), [MAXQDA](https://mdlutoronto.github.io/tutorials-search/?tool=MAXQDA)
