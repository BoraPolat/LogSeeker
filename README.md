# LogSeeker - Windows Event Viewer Security Log Filter

**LogSeeker** is a specialized application designed to filter and analyze Windows Security logs through Event Viewer integration. It provides users with a clear and efficient way to isolate specific security events, focusing on critical file system operations.

## 🎯 Purpose

This application filters Windows Security Logs to display only relevant events, allowing precise analysis of deleted, moved, or renamed files within a selected location and time range. LogSeeker eliminates the need to manually search through thousands of irrelevant entries in the Windows Security log.

## ✨ Key Features

### Core Filtering Capabilities
- **File/Folder Deletions** - Track and analyze deletion events
- **File/Folder Moves and Renames(As Mixed due to Limitations)** - Monitor file system changes
- **Direct Log Viewing** - View filtered results immediately within the application
- **Secondary Search Filter** - Apply additional search filters on top of initial results

### Advanced Parameters
- **Path-Based Filtering** - Specify directories or drives (e.g., C:\) to view location-specific events
- **Security Archive Logs** - Include archived Security logs for broader analysis
- **Custom Log File Import** - Load external .evtx files for offline investigation
- **Time Range Filtering** - Define precise start and end times for targeted analysis
- **CSV Export** - Export filtered results for further analysis and reporting

### Enterprise Benefits
- **Corporate Network Drive Support** - Trace activity history on shared folders
- **User Activity Tracking** - Identify who performed specific file operations
- **Fully Portable** - No installation required, run directly from executable
- **Offline Analysis** - Import and analyze external log files

## 🚀 Getting Started

### Requirements
- Windows Operating System
- Administrative privileges (recommended for full Security log access)

### Installation
**No installation required!** Simply download and run the executable file.

1. Download `LogFinder.exe`
2. Run the application as Administrator (recommended)
3. Start filtering your Security logs

## 📋 How to Use

### Step-by-Step Operation Guide

1. **Choose Operation Type**
   - Select between "Deleted" or "Moved/Renamed" logs
   - Filter events related to your selected operation only

2. **Select Target Path**
   - Choose the location (PATH) for log analysis
   - Only events within this path will be included
   - Example: Selecting C: drive filters all operations within the C: drive

3. **Configure Additional Options**
   - ✅ **Include Security Archive Logs**: Check to include archived security logs
   - 📁 **Optional Log File**: Select specific EVTX file for targeted analysis
   - ⏰ **Time Range**: Define starting and ending time for filtering

4. **Export and Review**
   - 📊 **Export**: Save filtered logs to CSV format
   - 🔍 **Open Exported CSV**: Access recently exported files instantly
   - 📋 **Review**: Analyze filtered, well-structured logs

## 🎯 Use Cases

- **System Administrators**: Monitor file system changes across corporate networks
- **Security Analysts**: Investigate suspicious file operations
- **IT Forensics**: Analyze file deletion and movement patterns
- **Compliance Auditing**: Track file access and modifications
- **Incident Response**: Quick analysis of security events

## 📊 Output

LogSeeker provides:
- **Filtered Results**: Only relevant security events
- **Structured Data**: Well-organized log entries
- **Export Options**: CSV format for further analysis
- **Time-Stamped Events**: Precise timing information
- **User Attribution**: Information about who performed operations

## 🔒 License & Distribution

- **Proprietary Software**: All rights reserved
- **Closed Source**: Source code is not publicly available
- **Usage License**: Available for use as distributed
- **Commercial Use**: Contact for licensing terms

## 📞 Contact & Support

For questions, support, or licensing inquiries:

**Email**: Bora.polat01@gmail.com

---

**Note**: LogSeeker is designed to work with Windows Security logs. Ensure you have appropriate permissions to access Security logs on your system for optimal functionality. Audit Settings are required to be configured for Event Viewer to generate file system logs.
