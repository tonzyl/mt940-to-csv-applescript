This script takes a MT940 export from the Dutch bank Knab, and turns it into a CSV (with semicolons as separator).
The structure of the CSV follows what I need for my own bookkeeping only. 
It also assumes a specific location and filename to start with. It's a rough hack, in other words.
But it might be useful as a starting point to build your own MT940 parsing script.

Input: a MT940 file of the Knab bank
Output: CSV with : full date, month, description, amount debit, amount credit.
