VBA function to replace all occurrence of "VLOOKUP" and "HLOOKUP" with new "XLOOKUP" formula in Excel.

Handles absolute/relative/named ranges, references on other sheets, both match types and even incorporates wrapped "IFERROR" inside XLOOKUP.

xlookup_replace.bas contains all necessary functions

test.xlsb contains examples and unit test

Script will intentionally ignore V/HLOOKUPs with 4th argument = TRUE if the indexing array is not sorted, that is to ensure that behavior stays the same
 
