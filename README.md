# Web-Hacking-Tool
Tool made in C# using mcs and mono
[Visit Website](https://installlion.com/kali/kali/main/m/mono-mcs/install/index.html) to know more about mcs and mono

This tool is used to find xss and sql injection points in a given url generated from a GET request
<p> Syntax:
  
mono GET_Request_Fuzzer.exe '(the url)'
</p>
<p> Classes used 
  System
  System.IO
  System.Net(HttpWebRequest)
  
</p>

**This DOES NOT work on URL prefaced with ftp:// or file:// you will require a different library (FtpWebRequest or FileWebRequest)**
  
