# Clinical-Audit-Automation
### Python-based tool for Medicare billing compliance and clinical data integrity.

## 🏥 Project Overview
This project was inspired by my four-year tenure as a Clinical Coordinator and Supervisor at **Specsavers**. During my time there, I managed complex Medicare billing cycles and health fund audits. I developed this script to demonstrate how automation can replace manual record-checking to ensure 100% data accuracy in a clinical setting.

## 🧬 Why This Matters for Biomedical Informatics
Informatics is the bridge between clinical domain expertise and computational efficiency. This tool reflects that bridge by:
- **Ensuring Data Integrity:** Identifying missing or incorrect billing codes.
- **Scaling Clinical Oversight:** Moving from manual "spot-checks" to automated full-dataset validation.
- **Operational Optimization:** Reducing human error in high-volume healthcare environments.

## 🚀 How It Works
The script uses the `pandas` library to process a mock clinical dataset. It executes a validation engine that:
1. Cross-references patient eligibility status against submitted billing codes.
2. Flags discrepancies where required information is missing.
3. Outputs a clean "Audit Report" for administrative review.

## 🛠️ Technical Stack
- **Language:** Python 3.x
- **Libraries:** Pandas (Data manipulation)

## 📁 Repository Structure
- `audit_tool.py`: The core Python script containing the audit logic.
- `mock_data.csv`: Sample data representing patient appointments and billing statuses.
- `About_The_Code.pdf`: A detailed explanation of the project's logic and clinical context.

## 📬 Contact
[Your Name]  
[Link to your LinkedIn Profile]
