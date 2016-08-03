# xlsxmerge.py
Merges Excell Sheets and Workbooks into one Excell Sheet

This project was designed for a specific use case, but by design it is flexible. Any other uses would require some tweaking of the code, but not much. 
## Installing 

Put the code in your `$PATH`, and change the permission of the file to make it executable. 

## Using xlsxmerge.py

To merge `file-1.xlsx file-2.xlsx` run:

    $ xlsxmerge.py file-1.xlsx file-2.xlxs [... file-n.xlsx] 

This assumes that the first row of every sheet has a heading. The first row, of the first sheet's file is the one that will be used as a "Master Heading": all the other sheets will be organized according to these headings. 

The output will be called `MergeTest.xlsx`. This could easily be adjusted in the code. 
