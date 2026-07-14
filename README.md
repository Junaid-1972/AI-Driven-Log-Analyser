# AI-Driven-Log-Analyser
This project showcase how deep security operation centre (SOC) automation has truly become. This is an AI-powered cybersecurity log analysis agent that automates anomaly detection and generates professional SOC reports. Built to support NIST CSF Detect/Respond and ISO 27001 Annex A.5 & A.8, this tool helps security teams transform raw logs into actionable intelligence efficiently.


# Development of AI Agent for Cybersecurity Log Analysis

**Project Report**
 
**Prepared by:** Junaid

---

## Executive Summary

A functional AI-powered cybersecurity log analysis agent built with Python was successfully developed and demonstrated. The application enables users to upload log files (CSV format), perform automated analysis for anomalies and threats, and generate professional SOC-style reports.

The demo showcases end-to-end functionality despite initial setup challenges with library installations and environment configuration. The agent leverages LLM capabilities (via OpenRouter) to deliver actionable insights on suspicious user activity, denied actions, unusual protocols and potential threats.

---

## Project Objectives

- Build a user-friendly web interface for uploading and analyzing cybersecurity logs.
- Integrate AI/LLM for intelligent detection of anomalies, suspicious behavior, and potential threats.
- Generate structured SOC (Security Operations Center) reports summarizing key findings.
- Support common cybersecurity use cases: log analysis, threat detection, IP investigation, and activity summarization.

**[Screenshot: Executive Summary & Objectives]**

---

## Technical Implementation

- **Frontend:** Streamlit
- **Backend:** Python 3.12 with key libraries including pandas, streamlit, crewai, and LLM integration via OpenRouter API.
- **Data Handling:** CSV log files containing network traffic, IP addresses, ports, protocols, actions, and user details.
- **AI Layer:** OpenRouter API for LLM-based analysis and report generation.

**[Screenshot: Full Python Script in VS Code Editor]**

---

## Development Process & Challenges

1. **Initial Setup**
   - Script written and reviewed.
   - Multiple Python environment issues encountered (Python 3.14 compatibility problems, resolved by using Python 3.12).

2. **Library Installation**
   - Required packages installed via terminal.
   - Some packages needed additional dependencies.

3. **API Configuration**
   - OpenRouter API key configuration (loaded via `.env` file).
   - Initial import and command errors resolved through path and spelling corrections.

4. **Application Launch**
   - Command: `streamlit run Buildings.py`
   - Local server started successfully at `http://localhost:8501`.

**[Screenshot: Terminal Output Showing Streamlit Server Startup]**

---

## Demo Walkthrough & Results

### Step 1: Application Interface
- Clean UI titled **“JUNAID AI Agent for Cybersecurity Use Cases”**.
- File upload section for logs.

**[Screenshot: Full View of Junaid AI Agent Web Interface]**

### Step 2: Log Upload
- Sample log file (`company_h_logs.csv`) uploaded successfully.

**[Screenshot: Log File Upload Success Screen]**

### Step 3: Analysis Execution
- Analysis prompt submitted.
- AI agent processed the data and generated a comprehensive report.

**[Screenshot: Analysis Execution and Agent Findings]**

### Key Findings from Sample Report (June 24, 2026)

**[Screenshot: Generated SOC Report – Key Findings & Overview]**

**[Screenshot: Generated SOC Report – Threats & Recommendations]**

---

## Achievements & Impact

- **Fully Functional Prototype:** Successfully moves from code to interactive web app to actionable security report.
- **Practical Value:** Automates tedious log analysis, helping SOC analysts focus on high-priority threats.
- **Extensibility:** Framework supports additional use cases (threat detection, IP investigation, activity summarization).

---

## Lessons Learned

- Environment consistency (Python version, virtual environments) is critical for dependency management.
- Proper `.env` handling for API keys prevents runtime errors.

---

## Conclusion

This AI Agent project represents a strong foundation for an intelligent cybersecurity assistant. The successful demonstration, from overcoming setup hurdles to delivering a polished SOC-style report, highlights both technical competence and practical problem-solving skills.

This project effectively bridges traditional log analysis with modern AI capabilities, offering significant potential for real-world security operations.

**[Screenshot: Final Report Conclusion or Application Overview]**

---

**End of Report**
