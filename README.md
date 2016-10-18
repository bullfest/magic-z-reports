# magic-z-reports
Tool for summation of z-reports created by iZettle cashregister.

### Prerequisites
You have to have the command `pdftotext` from the package `poppler-utils` installed to be able to run the script.
During the creation of the script i used version `0.41.0` and it has thusly only been tested with said version.

## Usage
The script is used with one command.

    python zreport.py "file1.pdf" ["file2.pdf" ...]

You may specify more than one file if they are from the same date (event).
The file paths may be either the full or the relative filepath.
