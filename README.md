# PDFtotext
Converts PDFs to text files

Updated the code to solve problems of blank text files or ones with junk text which where usually under 1 KB, furthermore, using slate was more accurate in getting all text (however, this means special characters and inutile spaces were gathered also), whenever slate failed to get text I put the older version using PyPDF2 and wordninja in use to at least get text.
