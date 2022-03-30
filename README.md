<p align="center"><a href="https://github.com/pratyakshm/WinRice"><img src="files/banner.png" width="470" height="250"></a></p> 
<h2 align ="center">Set up your Windows device using automation</h2>
<p align="center">
<a href="https://github.com/pratyakshm/WinRice#running-WinRice"><img src="https://img.shields.io/static/v1?label=pratyakshm&message=WinRice&color=blue&logo=github" alt="pratyakshm - WinRice"></a>
<a href="https://github.com/pratyakshm/WinRice"><img alt="GitHub all releases" src="https://img.shields.io/github/downloads/pratyakshm/WinRice/total?color=blue"></a>
<a href="https://github.com/pratyakshm/WinRice"><img src="https://img.shields.io/github/stars/pratyakshm/WinRice?style=social" alt="stars - WinRice"></a>
<a href="https://github.com/pratyakshm/WinRice"><img src="https://img.shields.io/github/forks/pratyakshm/WinRice?style=social" alt="forks - WinRice"></a>
<a href="#license"><img src="https://img.shields.io/badge/License-GPL_v3-blue" alt="License"></a>
</p>

<p align="center"><a href="doc/Main-brief.md">A brief on WinRice</a> &bull; <a href="doc">Documentation</a> &bull; <a href="#running-winrice">Usage</a>

<p align="center"><a href="doc/Frequently-answered-questions.md">FAQ</a>   &bull; <a href="LICENSE">License</a> &bull; <a href="#contributing">Contribution</a>

## Description

WinRice uses PowerShell automation to setup a Windows device. It currently supports only the latest retail builds of Windows 11 and 10.
  
WinRice, amongst a host of other things, improves privacy, de-clutters the Windows user interface and removes non-essential apps from Windows while still retaining OS functionality.

## Documentation

The documentation for WinRice is available below. 

If you're a beginner, Main brief is all you need. It describes the modifications that WinRice generally performs: [`Main-brief.md`](https://github.com/pratyakshm/WinRice/blob/main/doc/Main-brief.md).

The directory that contains all documents is available [here](https://github.com/pratyakshm/WinRice/tree/main/doc).  
 
**Known issues**: See [Known issues](https://github.com/pratyakshm/WinRice/issues?q=is%3Aopen+is%3Aissue+label%3A%22Bug+report%22) before running WinRice.

## Requirements

WinRice, when run, checks if all of the following requirements are met:
- Device is connected to the Internet.
- Device is powered by a Windows build that's currently in service. [See more](https://github.com/pratyakshm/WinRice/blob/main/doc/Supported-winver.md).
- There are no pending device restarts.

If any one of the above criteria are not met, WinRice terminates itself.

## Running WinRice

Download and run [WinRice.exe](https://github.com/pratyakshm/WinRice/releases/download/v0.5.04112021/WinRice.exe).

### Other method(s)

Alternatively, you may use this command in PowerShell (Admin)

```
Invoke-Expression ((New-Object System.Net.WebClient).DownloadString('https://bit.ly/WinRice'))
```

## Contributing

Read [CONTRIBUTING.MD](https://github.com/pratyakshm/WinRice/blob/main/doc/CONTRIBUTING.md).
