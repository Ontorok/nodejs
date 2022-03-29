## Notes

<ul>
    <li>fs.readFile() accept 3 parameters. first is which file has read, second is config such as encoding, and third is callback function. If there is any exception to read this file the first parameter of callback function hold this error. second parameter of callback function holds the data in as Buffer. To convert Buffer to actual data, there are two ways. First, use toString method. second, use encoding in second parameter of fs.readFile()</li>
    <li>readFile,writeFile,appendFile etc ect are async operation</li>
    <li>To avoid callback hell in readFile, writeFile etc ect, use <strong>const fsPromisses = require('fs').promises;</strong></li>
</ul>
