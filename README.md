# log-file-analyzer-bash
Bash script for fast log analysis (grep, tail)
# ⚡️ NOC Log File Analyzer (Bash CLI)

Un script Command-Line Interface (CLI) care simulează diagnoza rapidă a logurilor, esențială pentru rolurile de suport tehnic de Nivel 1 (1st Line) și Nivel 2 (2nd Line).

### Relevanță pentru Operations Technician (NOC)

Acest proiect demonstrează înțelegerea a două sarcini zilnice critice ale unui NOC Technician:
1.  **Identificare Defecte:** Folosirea eficientă a comenzilor Linux (`grep`) pentru a **identifica rapid alarmele critice** (FAULT_DETECTED) dintr-un log mare, conform procedurilor de escalare.
2.  **Competențe CLI:** Validarea cunoștințelor de **Basic proficiency in Linux** – un *must-have* pentru troubleshooting de la distanță.

### Tehnologii
* Bash Shell Scripting
* Linux Core Utilities (`grep`, `wc`, `tail`)
* Logica de Troubleshooting ITIL (Implicită)

### Cum se Rulează
1.  Asigură-te că fișierul `sample_log.txt` există.
2.  Rulează scriptul în terminal: `bash analyze.sh`

### 🔥 Next Steps (Către L2)
* Refactorizarea scriptului în **Python** pentru a permite trimiterea automată de alerte pe email sau Slack. (Acesta va fi **Proiectul #2** al nostru!)
