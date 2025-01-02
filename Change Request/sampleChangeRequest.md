# Sample Change Request Documentation

*Note: A few of the details are kept hidden to maintain confidentiality*

## Document Version

| Version | Date| Comments | 
| :-------- | :------- | :-------|
|Version xx|01/02/2025|Change Request document sent to Bussiness Owner|

## Business Requirements
In the ABC site, users are introduced to the unit content stored in different formats, such as PDF files.  In the current system, the users can only print the current page of the PDF file they are following. If the users want to print all the pages of the pdf file they should download the pdf file, preview it, and then print it. Furthermore, there is no consistency between the PDF file and print preview since in the preview some blank pages are added at the beginning and/or at the end. Due to this reason when the users print the pdf file, the blank pages are also printed. Following the issues mentioned above, the business solution consists of:  
- Enabling the users to print all the pages contained in the PDF file right after they have a preview of the PDF file. 
- Enabling the users to print selected pages contained in the PDF file right after they have a preview of the PDF file.
- Removing the blank pages from the preview.

## Success Metrics
Enhancing user experience by enabling users to easily print all the pdf files that they are following in the ABC site and adding consistency between the PDF file and print preview. 

## Stakeholders Impacted
- /xxxx/
- /xxxx/

## Products Impacted
- /xxxx/
- /xxxx/

## Functional Overview
Further to the implementation in the ABC site, the users will be able to preview and print PDF files conveniently. 

### XYZ Tabs: 
The output preview dialog box of PDF files should allow users to choose between printing all pages or a specific page range. The “Pages” field options- All, Odd pages only, Even pages only, and Custom should allow users to select all/even/odd/custom pages for the print. 
The changes should reflect on the preview when the user chooses an option under the “Pages” field. 
There should not be any extra blank page at the beginning or the end of the preview.  

### PDF Display Accuracy:
The system must accurately display PDF files for individual Lesson Plans when the user clicks on the PDF icon.
The content within the PDF file should be a faithful representation of the Lesson Plan.

### Print Action Consistency:
After viewing the PDF file, initiating the Print action should display a Print Preview that is consistent with the content of the PDF Lesson Plan.
The Print Preview should accurately reflect the same content and layout as presented in the PDF.

### Elimination of Blank Pages:
The system should ensure that the Print Preview and the actual printed output do not contain any blank pages.
Blank pages in the Print Preview or the printed output should be eliminated to enhance the overall printing experience.

### Content Consistency:
The content displayed in the Print Preview must align seamlessly with the content within the PDF file.
Any discrepancies between the Print Preview and the PDF Lesson Plan content should be resolved to maintain consistency.

## Business Rules 
- The Print option on PDF files is an essential feature that enhances user convenience, allowing them to easily print the required pages.
- The Print option must adhere to the user Page selection without adding blank pages.
- The Print preview should be identical to the PDF files.

## User Interactions and Design
/relevant screenshots for added details/

## Data Requirements
/field-wise data type information/

## Non-Functional Requirements
/ such as response time, compatibility, etc./

## Use Cases
|Actor|Precondition|Main flow|Postconditions|
| :-------- | :------- | :-------| :-------|
|User|has opened the print preview of PDF file|makes Page selection|is able to preview selected pages|
|xx|xx|xx|xx|

