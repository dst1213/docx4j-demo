# docx4j-demo
Creating a docx and xlsx using docx4j, converting docx to pdf using docx4j and xlsx to pdf using both apache poi and itext

## how to

1. First run the app using Spring Boot,there is two controllers available for testing the app
2. localhost:8080/docx -> testing the creation of a docx file using docx4j and converting it to pdf using docx4
3. localhost:8080/xlsx -> testing the creation of a xlsx file using docx4j and converting it to pdf using apache poi + itext

(The created or converted files are located in the project directory)

Note : For Xlsx to word converting, currently the 1st Row is considered to be the header row and the PDF also not supports any kind of formatting as in the XLS.

Inspired From : https://github.com/mkanchwala/Utilities/tree/master/pdf-converter