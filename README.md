# Digital Forensics Report: Investigation into Illegal Animal Sales

## Overview

This repository contains documentation and analysis related to the digital forensic investigation of the USB evidence file `Animal.E01`. The objective of the investigation was to determine whether the suspect, **James Jones**, known online as **“Animalman”**, has been involved in the **illegal selling of exotic and restricted animals**.

---

## Objectives

- To follow digital forensic procedures for acquisition, preservation, examination, and analysis.
- To determine whether the suspect is involved in criminal activities concerning the illegal trade of animals.

---

## Deliverables

- A forensic analysis report based on the `Animal.E01` image file.
- Documentation linking the USB image to an illegal animal trading website.
- Email communications to and from **animalman@lotmail.com**.
- Metadata and timestamps proving the origin and timeline of the activity.

---

## Methodology

This investigation follows the **NIST SP 800-86** digital forensic process model, which includes:

1. **Collection**: Acquiring a forensically sound copy of the evidence using FTK Imager and calculating hash values for integrity.
2. **Examination**: Extracting relevant data using tools like Autopsy and identifying artifacts such as emails, websites, and image files.
3. **Analysis**: Interpreting findings to uncover illegal activities and establishing timelines.
4. **Reporting**: Presenting results with supporting figures, conclusions, and recommendations for legal action.

---

## Tools Used

- **FTK Imager** – Evidence acquisition
- **Autopsy** – Forensic examination
- **HashCalc** – Hash integrity verification
- **Microsoft OneDrive** – Secure cloud preservation
- **Microsoft Word & Snipping Tool** – Report documentation and figures

---

## Key Findings

- Email evidence shows communication between **Animalman** and a buyer named **Bob**, discussing a secret section of a website where animals were sold.
- Metadata from the USB image reveals:
  - Hidden `private.html` page containing listings of caged, exotic animals.
  - Emails showing account creation and illegal activity coordination.
- The email **animalman@lotmail.com** was created on **Feb 23, 2009** by a system admin, linking James Jones to the account.
- Images and site pages confirm the sale of unlicensed exotic animals.

---

## Legal Implications

Based on the investigation, James Jones (aka "Animalman") is in violation of:

- **Animal Welfare Act 2006**:
  - Section 4: Causing unnecessary suffering
  - Section 13: Engaging in unlicensed animal trading
- **Animal Welfare (Licensing of Activities Involving Animals) Regulations 2018**

He may face penalties including **up to 6 months imprisonment, a fine, or both**.

---

## Recommendations

- Initiate a **follow-up investigation** to explore the full extent of the criminal network.
- Ensure **continuous monitoring** of James Jones.
- Recommend legal proceedings under relevant UK animal welfare legislation.

---

## References

- [Animal Welfare Act 2006](https://www.legislation.gov.uk/ukpga/2006/45/contents)
- [Licensing of Activities Involving Animals (2018)](https://www.legislation.gov.uk/ukdsi/2018/9780111165485)
- Kent, K., Chevalier, S., Grance, T., & Dang, H. (2006). *Guide to Integrating Forensic Techniques into Incident Response* (NIST SP 800-86)

---

## Appendix

- **Chain of Custody Documentation**
  - Verified and recorded during the collection phase.
- **Figures**
  - Includes screenshots of emails, website pages, metadata, and forensic tools used during the investigation.

---

> This repository is intended for educational and investigatory purposes only. All digital evidence has been handled according to forensic best practices to ensure admissibility and integrity.
