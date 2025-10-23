# NOC Log Analyzer (Bash CLI)

A Command-Line Interface (CLI) script designed for **fast log analysis and immediate defect identification** within a Network Operations Center (NOC) environment.

### Project Relevance for Operations Technician

This project validates proficiency in core NOC functions:
1.  **Fault Identification & Escalation:** Demonstrates efficient use of Linux utilities to quickly locate and isolate critical alarms (`CRITICAL_FAULT`), adhering to escalation procedures.
2.  **Basic Linux Proficiency:** Confirms hands-on experience with Bash scripting and essential Linux commands (`grep`, `tail`, `wc`), a foundational requirement for remote network troubleshooting.

### Technologies
* Bash Shell Scripting
* Linux Core Utilities (`grep`, `head`, `wc`)
* CLI Troubleshooting Logic

### Usage
1.  Ensure `sample_network_log.txt` is populated.
2.  Grant execution rights: `chmod +x analyze.sh`
3.  Run the script: `bash analyze.sh`

### Next Steps (L2 Automation Potential)
* Integrate Python to automatically parse JSON or XML log structures.
* Implement automatic alerting (e.g., sending email notifications) upon detecting a critical threshold.
