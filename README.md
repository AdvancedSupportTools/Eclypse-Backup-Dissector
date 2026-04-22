Eclypse Backup Dissector
⚠️ IMPORTANT: COMMUNITY TOOL – NOT AN OFFICIAL DISTECH CONTROLS PRODUCT
This application is a special project developed by the Distech Controls Advanced Support Team and is NOT a sanctioned or official product release by Distech Controls Inc.
Please read DISCLAIMER.txt in full before using this tool.
Advanced inspection, extraction, and analysis of ECLYPSE controller backup files
Platform: Windows
Technology: PowerShell + WPF
Distribution: Community Tool
________________________________________
⚠️ Important Notice
THIS IS A COMMUNITY TOOL – READ BEFORE USE
This application is:
✅ Freely available for use and redistribution
✅ Designed for offline analysis of ECLYPSE backup ZIP files
✅ Uses only standard ZIP, JSON, and file based processing
✅ Supported by Advanced Support at their discretion, primarily for Distech:
•	System Integrators (SIs)
•	Authorized Distributors
•	OEM Partners
•	Internal engineering and support teams
❌ NOT an official Distech Controls product
❌ NOT covered by Distech Controls warranties
❌ NOT covered by Distech Controls support agreements
❌ NOT subject to standard Distech Controls QA or release procedures
📋 READ THE FULL DISCLAIMER – Contains important legal information regarding warranty, liability, and support.
By using this tool, you acknowledge and accept these terms.
________________________________________
🎯 What Is This?
Eclypse Backup Dissector is a forensic-style inspection and extraction utility for ECLYPSE controller backup files (.zip).
It is designed to help support engineers and system integrators quickly understand what a backup contains, verify required artifacts, and safely extract or repackage data for troubleshooting.
Built for:
•	System Integrators
•	Advanced Support & Field Service Engineers
•	QA and Engineering teams
•	IT professionals supporting BAS environments
Developed by:
Distech Controls Advanced Support Team (community project)
Primary Use Cases:
•	Backup validation (“Is everything here?”)
•	Offline configuration inspection
•	Rich visualization of JSON configuration files
•	Designer project and dashboard recovery
•	Safer troubleshooting without touching live controllers
________________________________________
✨ Key Features
📦 ZIP Backup Analysis
•	Open ECLYPSE backup ZIP files without extracting
•	Scan and verify expected components: 
o	bacnet.json
o	network.json
o	modbus.json
o	security.json
o	iot.json
o	Designer projects
o	Dashboards
•	Clear Present / Missing status indicators
•	Tree aware detection of designer and dashboard content
________________________________________
🖼️ Rich Embedded JSON Reports
The following JSON files are rendered as interactive, tabbed HTML reports directly inside the application:
•	✅ BACnet Configuration
•	✅ Network Configuration
•	✅ Modbus Configuration
•	✅ Security Configuration
•	✅ IoT Configuration
Features include:
•	Tabbed navigation (sections + raw JSON)
•	Human readable tables and badges
•	Inline formatting (monospace, color coding)
•	No external browser required
•	Raw JSON view preserved and readable
________________________________________
🔍 Inline Preview Pane
•	HTML and text previews rendered inside the application
•	Monospace formatting for logs and text files
•	Automatic size limits to avoid memory issues
•	Safe handling of binary vs text content
________________________________________
📂 Safe Extraction Engine
•	Zip Slip protection (path traversal defense)
•	Stream based extraction (no temp explosions)
•	Preserves timestamps where possible
•	Full extraction to a structured workspace: 
•	Workspace/
•	├─ ExtractedFiles/
•	├─ DesignerProjects/
•	├─ Dashboards/
•	├─ Zips/
•	└─ Logs/
________________________________________
🧱 Designer & Dashboard Re Packaging
•	Rebuild DesignerProjects.zip from extracted content
•	Rebuild Dashboard.zip from extracted content
•	Automatically selects the correct source tree
•	Output ZIPs tracked as artifacts in the UI
________________________________________
🪵 Comprehensive Diagnostic Logging
•	Built in diagnostic log viewer
•	Save logs to file at any time
•	Optional PowerShell transcript support
•	Console logging (optional)
•	Automatic log trimming to prevent UI slowdown
________________________________________
🖥️ Modern WPF User Interface
•	Resizable layout with splitter
•	DataGrid with sorting and selection
•	Embedded WebBrowser preview pane
•	Busy indicators for long operations
•	Designed for large backups and large screens
________________________________________
🔄 Versioning
Semantic Versioning (MAJOR.MINOR.PATCH)
•	MAJOR – Breaking changes or workflow changes
•	MINOR – New features, backward compatible
•	PATCH – Bug fixes and stability improvements
Current Version: v1.3.3
________________________________________
🧪 What This Tool Is Not
Eclypse Backup Dissector is NOT:
❌ A controller commissioning tool
❌ A live controller management utility
❌ A firmware upgrade or configuration editor
❌ A replacement for official Distech Controls software
❌ A tool that communicates with controllers
❌ A supported production system component
This tool operates entirely on backup files and the local file system.
________________________________________
🧰 Typical Workflows
1️⃣ Inspect a Backup
•	Open ZIP
•	Scan contents
•	Verify required artifacts are present
•	Preview configuration JSON inline
2️⃣ Troubleshoot Offline
•	Inspect network, BACnet, Modbus, or security configuration
•	Review user accounts, policies, and settings safely
•	No controller connection required
3️⃣ Recover Assets
•	Extract everything
•	Rebuild designer projects
•	Rebuild dashboards
•	Package and return ZIPs to customer or SI
4️⃣ Support Escalation
•	Export logs
•	Provide extracted reports
•	Share findings without exposing live systems
________________________________________
🔐 Security Notes
•	No network access required
•	No telemetry
•	No data exfiltration
•	All processing is local
•	Sensitive data remains in extracted files under user control
⚠️ Backups may contain credentials or sensitive information.
Handle extracted data according to your organization’s security policies.
________________________________________
📥 Installation & Usage
•	Runs on Windows
•	Requires PowerShell (STA mode enforced automatically)
•	No installer required (script or packaged executable)
Recommended: Create a dedicated workspace per case or customer.
________________________________________
📚 Documentation
•	README.md – This document
•	DISCLAIMER.txt – Legal disclaimer and limitation of liability
•	Inline tips and warnings in the UI
________________________________________
🤝 Support & Community
This is a community tool.
Support is provided at the discretion of the Distech Controls Advanced Support Team and may include:
•	Best effort assistance
•	Bug triage
•	Limited enhancements
There are:
•	❌ No guaranteed response times
•	❌ No SLAs
•	❌ No warranty obligations
________________________________________
📊 Project Information
•	Application Name: Eclypse Backup Dissector
•	Current Version: v1.3.3
•	Release Type: Community Tool
•	Status: Stable
•	Platform: Windows
•	Language: PowerShell (WPF UI)
________________________________________
🏆 Acknowledgments
This tool relies on:
•	.NET Framework / WPF
•	PowerShell
•	Built in ZIP and JSON processing libraries
No proprietary Distech Controls tooling is used.
________________________________________
⚠️ Final Reminder
This is a community utility.
Please read DISCLAIMER.txt before use.
Built with ⚡ by the Distech Controls Advanced Support Team

