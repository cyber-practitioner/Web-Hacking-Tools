Here's a revised version of your README for the "Web-Hacking-Tool" that is structured to provide a clear and informative overview of the tool, its usage, and important notices:

---

# Web Hacking Tool

A comprehensive tool developed in C# designed to identify potential XSS (Cross-Site Scripting) and SQL Injection vulnerabilities in websites through GET requests. Built using `mcs` (Mono C# compiler) and `mono` runtime, it streamlines the process of web vulnerability assessment.

## About MCS and Mono

Mono is an open-source implementation of Microsoft's .NET Framework, enabling developers to build cross-platform applications. MCS is the Mono C# compiler that compiles C# code for the Mono environment. For more information about `mcs` and `mono`, [visit the official website](https://installlion.com/kali/kali/main/m/mono-mcs/install/index.html).

## Features

- Identifies XSS and SQL Injection vulnerabilities via GET requests.
- Simple and easy-to-use syntax for web assessments.
- Utilizes the `System`, `System.IO`, and `System.Net (HttpWebRequest)` classes for robust network operations.

## Usage

To use this tool, ensure Mono is installed on your system. Then, use the following syntax to run the tool against a target URL:

```sh
mono GET_Request_Fuzzer.exe 'the_url'
```

Replace `'the_url'` with the actual URL you wish to test. 

**Note**: This tool is designed for URLs using the HTTP or HTTPS protocols and does not support `ftp://` or `file://` URLs. For those, you would need to use `FtpWebRequest` or `FileWebRequest` respectively.

## Prerequisites

- Mono runtime and MCS installed on your system.
- Basic understanding of web vulnerabilities such as XSS and SQL Injection.

## Important Notice

- This tool does NOT support URLs prefaced with `ftp://` or `file://`. You will require a different library (`FtpWebRequest` or `FileWebRequest`) for those protocols.
- Use this tool responsibly and ethically. Ensure you have permission to test the target websites to avoid unauthorized assessment activities.
