# File Analysis
[BACK TO UACTF](/UACTF)<br>

File analysis and understanding is one aspect of the larger field of Digital Forensics. Digital Forensics encompasses the investigation of data found on digital devices and involves preserving, identifying, extracting, documenting and interpreting this data. <br>

One of the more common activities in digital forensics is the recovery of deleted files. Though a user may have “deleted” or “moved a file to the trash bin” those files are not always deleted. A very nice set of intuitive tools for use in digital forensics is The Sleuth Kit tool set (http://www.sleuthkit.org/index.php). <br>

Below is a screenshot of the output of the Sleuth Kit file listing tool (fls) which shows two files that have been “deleted” by the user but are still recoverable. The ability to recover and save what was previously thought to be deleted files can be very valuable in an investigation. <br>

<p align="center">
<img width="650px" height="550px" src="/00_Archive/images/fileanalysis.png" alt="FileAnalysis"/>
</p>

Specifically, when looking at the analysis of files, an investigator needs to start with the file header. File headers are information about a file that the computer stores so that it knows what type of file it is. Typically, file headers are stored in the first 4 or 5 bytes of a file. By using the hexdump tool, the hexadecimal version of a file can be viewed. Hexdump is available on most Linux distributions and there are many Windows interfaces to Hexdump (ex. https://sourceforge.net/projects/hexdump/). <br>

One of the more interesting items that occur during an investigation is when a suspect tries to disguise a file by changing an incriminating file’s signature. Having a good understanding of file signatures is important. Below is an exert from a larger list of file signatures of the more common files seen during investigations. A larger list can be seen at the following location: https://en.wikipedia.org/wiki/List_of_file_signatures <br>

<p align="center">
<img width="550px" height="450px" src="/00_Archive/images/filesignatures.png" alt="FileSignatures"/>
</p>

[BACK TO UACTF](/UACTF)<br>
