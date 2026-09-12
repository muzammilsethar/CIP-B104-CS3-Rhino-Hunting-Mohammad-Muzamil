# ICDFA CIP-B104: Computer Forensics Case Study I (Rhino Hunting)

## 📌 Candidate & Academic Profile
* **Student Name:** Mohammad Muzamil
* **REG No:** C11/26/DFIT/17289
* **Program:** DFIT (Digital Forensics and Incident Response)
* **Academy:** International Cybersecurity and Digital Forensics Academy (ICDFA)

---

## 📂 Repository Directory Structure & Evidence Mapping
- **`original/`**: Houses the pristine, untouched seized evidence (`RHINOUSB.dd`, `rhino.log`, `rhino2.log`, `rhino3.log`).
- **`working/`**: Contains intermediate analyst notes and investigative breakdown steps.
- **`recovered/`**: Contains carved unallocated space clusters (`00004`, `25604`, `51204`) recovered during forensic parsing.
- **`traffic-export/`**: Holds isolated network traffic and HTTP/proxy log streams.
- **`reports/`**: Features the comprehensive formal forensic report and cryptographic SHA256 hash manifest (`hash_manifest.txt`).
- **`screenshots/`**: Stores visual documentation and verifiable evidence output captures.

---

## 🛠️ Investigation Highlights & Tools Used
* **Provenance Control:** Manual SHA256 cryptographic hash verification via Windows CMD (`certutil`).
* **Forensic Image Parsing:** Exterro FTK Imager for FAT16 file system analysis and unallocated cluster carving.
* **Network & Traffic Intelligence:** Deep artifact correlation of legacy HTTP/proxy sessions (`MSIE 6.0`, Google 2004 timeline logs).

---

## 📬 Connect & Professional Inquiries
Feel free to connect or reach out for professional collaborations in digital forensics and cybersecurity:
* **LinkedIn:** [Mohammad Muzamil](https://www.linkedin.com/in/muzammil-sethar/)
* **Personal Email:** `muzammilsethar@gmail.com`
* **Academy Email:** `c11.dfit2617289@icdfa.edu.ng`
