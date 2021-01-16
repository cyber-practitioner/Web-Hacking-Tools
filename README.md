# Web-Hacking-Tools
Tool made in C# using mcs and mono

This tool is used to find xss and sql injection points in a given url generated from a GET request
<p> Syntax
  
  
mono GET_Request_Fuzzer.exe '(the url)'
</p>
<p> Classes used 
  System
  System.IO
  System.Net(HttpWebRequest)
  
</p>
<p> This **DOES** not work on URL prefaced with ftp:// or file:// you will require a different library (FtpWebRequest or FileWebRequest)
  </p>
