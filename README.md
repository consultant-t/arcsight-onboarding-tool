# ArcSight Log Source Onboarding & FlexConnector Generator

A lightweight, browser-based tool that simplifies **ArcSight log source onboarding** by generating **SmartConnector integration guides** for supported log sources and **FlexConnector parser templates** for unsupported ones.

> 🚀 No installation required. Runs completely offline. Your log data never leaves your browser.

---

## 🌐 Live Demo

**Try it here:**

https://consultant-t.github.io/arcsight-onboarding-tool/

---

## ✨ Features

### Supported Log Sources
Generate a complete SmartConnector onboarding guide including:

- SmartConnector selection
- Device-side configuration
- Collection method
- Connector configuration
- Destination setup
- Validation steps

### Unsupported Log Sources
Automatically generate:

- FlexConnector regex parser (.properties)
- CEF field mapping
- Parser deployment instructions
- Ready-to-edit configuration template

---

## 📂 Input Options

- Paste raw log samples
- Upload **.log**
- Upload **.txt**
- Upload **.csv**

Supported log formats include:

- Key=Value
- CSV
- Syslog
- Generic CEF
- Free-form text logs

---

## 📦 Supported Log Sources

- Cisco ASA
- Palo Alto Networks
- Fortinet
- Check Point
- Windows Event Logs
- Sysmon
- Linux Syslog
- Apache HTTP Server
- Microsoft IIS
- Generic CEF
- Squid Proxy
- F5 BIG-IP

Custom log formats are also supported through automatic parser generation.

---

## 🛠️ How It Works

1. Enter the log source type.
2. Paste a raw log sample or upload a log file.
3. Click **Generate Onboarding Guide**.

The tool automatically determines whether the log source is supported.

### If Supported

A complete SmartConnector onboarding guide is generated.

### If Unsupported

The tool:

- Detects the log format
- Extracts fields
- Maps fields to CEF
- Generates a FlexConnector parser
- Provides deployment instructions

---

## 🔒 Privacy

All processing is performed locally inside your browser.

- ✅ No cloud processing
- ✅ No external APIs
- ✅ No data uploads
- ✅ Completely offline

Your logs remain on your machine.

---

## 💡 Why I Built This

Creating FlexConnector parsers for unsupported log sources is one of the most repetitive and time-consuming tasks during ArcSight deployments.

This tool helps reduce the initial onboarding effort from hours to minutes by providing a structured starting point for parser creation while still allowing engineers to review and customize the generated output.

---

## ⚠️ Disclaimer

The generated FlexConnector parser is intended as a starting point.

Engineers should always review, test, and validate the generated parser before deploying it in a production environment.

---

## 🚀 Roadmap

Planned enhancements include:

- JSON log support
- LEEF support
- Regex validation
- Interactive parser testing
- Downloadable parser packages
- Additional SmartConnector templates
- Expanded log source catalog

---

## 🤝 Contributions

Suggestions, feature requests, and improvements are welcome.

Feel free to open an Issue or submit a Pull Request.

---

## ⭐ If you find this useful...

Please consider giving the repository a ⭐ on GitHub.

Feedback from the ArcSight community is always appreciated.

---

## 📄 License

This project is released under the MIT License.
