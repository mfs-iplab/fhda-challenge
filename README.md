# Forensic Handwritten Document Analysis (FHDA) Challenge 2025

<div align="center">

![Challenge Status](https://img.shields.io/badge/Challenge-Completed-brightgreen)
![Conference](https://img.shields.io/badge/IEEE-MetroXRAINE%202025-blue)
![Best Accuracy](https://img.shields.io/badge/Best%20Accuracy-64.5%25-orange)
![Teams](https://img.shields.io/badge/Teams-3%20Participated-lightgrey)

</div>

<picture>
  <img alt="Logos" src="/assets/images/headernew.jpg">
</picture>

**🏆 CHALLENGE COMPLETED - FINAL RESULTS AVAILABLE 🏆**

Welcome to the official repository for the **Forensic Handwritten Document Analysis (FHDA) Challenge 2025**, part of the [IEEE MetroXRAINE 2025](https://metroxraine.org/) conference. This challenge focused on developing innovative cross-modal methods for forensic handwritten document analysis, comparing traditional pen-and-paper documents with digitally written samples.

**📊 Winner:** Team **JNU DNSLAB** (Chonnam National University, South Korea) with 64.5% accuracy!

For complete results, rankings, and ground truth data, visit our [challenge website](https://mfs-iplab.github.io/fhda-challenge/).

## 🏆 Final Results

The FHDA Challenge 2025 has officially concluded! Here are the final rankings:

| Rank | Team Name | Institution | Accuracy | Correct Predictions |
|------|-----------|-------------|----------|-------------------|
| 🥇 **1st** | **JNU DNSLAB** | Chonnam National University, South Korea | **64.5%** | 129/200 |
| 🥈 2nd | SCLAB@CNU | Chonnam National University, South Korea | 62% | 124/200 |
| 🥉 3rd | TJZ | Keele University, United Kingdom | 55% | 110/200 |

**Challenge Statistics:**
- Total participating teams: 3 (5 registered teams)
- Test dataset size: 200 document pair comparisons
- Evaluation metric: Accuracy percentage of authorship verification
- Best performance: 64.5% accuracy achieved by JNU DNSLAB

**📊 Ground Truth Data:** Complete evaluation data is available for download on the [challenge website](https://mfs-iplab.github.io/fhda-challenge/).

## Challenge Overview

The FHDA Challenge focused on a particularly challenging **binary classification task**: determining whether pairs of handwritten documents were authored by the same individual across different writing modalities. What made this competition unique was its **cross-modal comparison** approach, requiring participants to analyze and compare traditional handwritten documents (scanned from paper) with documents written directly on digital devices like tablets or graphic tablets.

## Registered Teams

The following teams participated in the FHDA Challenge 2025:

| Team Name | Institution | Country | Team Referent |
|-----------|-------------|---------|---------------|
| **JNU DNSLAB** 🏆 | Chonnam National University | South Korea | Seyeon Jeong |
| **SCLAB@CNU** | Chonnam National University | Republic of Korea | Hyung-Jeong Yang |
| **TJZ** | Keele University | United Kingdom | Tito Osadebey |
| Richard | Zayed University, Abu Dhabi | United Arab Emirates | Richard Ikuesan |
| RichardTheGoodGuy | Zayed University, Abu Dhabi | United Arab Emirates | Richard Ikuesan |

## Dataset Information

The FHDA Challenge dataset was designed for research and educational purposes, consisting of handwritten document images from two distinct modalities:

- **Paper**: Scanned images of handwritten documents on paper
- **Tablet**: Images captured from handwritten documents written on digital tablets

**Dataset Composition:**
- **Training Set**: ~70% of the data, used for model training and validation
- **Test Set**: ~30% of the data, reserved for final evaluation (200 document pair comparisons)

**Cross-Modal Challenge:** The unique aspect of this dataset was the cross-modal comparison requirement, where participants needed to determine authorship across different writing mediums (paper vs. tablet).

### Dataset Structure

The FHDA Challenge dataset was organized as follows:
```
FHDA_Dataset/
├── Training/                        # Training set (~70% of the data)
│   ├── Paper/                       # Handwritten document images on paper
│   │   ├── id_1_paper_040.pdf
│   │   ├── id_1_paper_041.pdf
│   │   └── ...                      # Additional paper images
│   └── Tablet/                      # Handwritten document images on tablet
│       ├── id_1_Tablet_043.pdf
│       ├── id_1_Tablet_044.pdf
│       └── ...                      # Additional tablet images
└── Test/                            # Test set (~30% of the data)
    ├── 0bf90ddfb25748b291d6d528c5ca92d1.pdf
    ├── 0d801c37332d4b13aae892e91d7f3b11.pdf
    └── ...                          # Additional test images (anonymized)
```

**Key Features:**
- **Training Set**: Clearly labeled with source modality (Paper/Tablet) and participant IDs
- **Test Set**: Anonymized filenames with mixed paper and tablet documents for cross-modal evaluation
- **File Format**: PDF documents containing handwritten content
- **Naming Convention (Training)**: `[participant_ID]_[Source]_[Number].pdf`

## Timeline - COMPLETED ✅

The FHDA Challenge 2025 followed this timeline:

- ✅ **March 31, 2025**: Competition Website Launch  
- ✅ **March 31 - May 16, 2025**: Registration Period
- ✅ **April 14, 2025**: Training Set Release  
- ✅ **June 16, 2025**: Test Set Release  
- ✅ **June 20, 2025**: Final Submission Deadline  
- ✅ **June 25, 2025**: Final Rankings and Ground Truth Release
- ✅ **July 20, 2025**: Paper Submission Deadline (Winner Invited)
- ✅ **TBD**: MetroXRAINE 2025 Conference & Winners Announcement

## Publication Opportunities & Research Impact

The FHDA Challenge 2025 has significantly advanced academic research in forensic document analysis by offering the winning team, JNU DNSLAB, an exclusive opportunity to publish their innovative approach in the IEEE MetroXRAINE 2025 conference proceedings following a rigorous peer-review process. Beyond the winner's contribution, the challenge has generated broad interest in cross-modal document analysis, with the organizing committee preparing a detailed challenge description for submission to a top-tier journal. This report will outline the dataset creation, evaluation methods, and key findings from the competition. All participating teams are encouraged to further develop and publish their work, contributing to the expanding field of forensic handwriting analysis and digital document authentication.

## How to Access Challenge Resources

**📊 Final Rankings & Ground Truth Data:**
- Complete final rankings available on the [challenge website](https://mfs-iplab.github.io/fhda-challenge/)
- Ground truth data available for download (CSV format)
- Detailed performance metrics and evaluation results

**🔗 Official Links:**
- **Challenge Website**: [https://mfs-iplab.github.io/fhda-challenge/](https://mfs-iplab.github.io/fhda-challenge/)
- **IEEE MetroXRAINE 2025**: [https://metroxraine.org/](https://metroxraine.org/)
- **Registration Form**: [https://forms.gle/cxsbwfuZRJ9rVxgN8](https://forms.gle/cxsbwfuZRJ9rVxgN8) *(Closed)*

## Archive Information

**Note for Future Researchers:**
- The challenge registration period has ended (May 16, 2025)
- Dataset access was provided to registered teams only
- This repository serves as an archive of the challenge specifications and results
- For research inquiries regarding the dataset, please contact the organizing committee

## Contact Information

**Main Contact:**
- **Mirko Casu** - Ph.D. Student, University of Catania, Italy
- **Email**: [mirko.casu@phd.unict.it](mailto:mirko.casu@phd.unict.it)
- **Website**: [https://mirkocasu.github.io/](https://mirkocasu.github.io/)

**Additional Information:**
For questions about the challenge, dataset, or research opportunities, please visit our [FAQ section](https://mfs-iplab.github.io/fhda-challenge/#faq) or contact the organizing committee.

---

## Organizers

**Challenge Organizing Committee:**

| Name | Role | Affiliation | Contact |
|------|------|-------------|---------|
| **Mirko Casu** | Ph.D. Student & Lead Organizer | University of Catania, Italy | [mirko.casu@phd.unict.it](mailto:mirko.casu@phd.unict.it) |
| **Luca Guarnera** | Fellow Researcher | University of Catania, Italy | [luca.guarnera@unict.it](mailto:luca.guarnera@unict.it) |
| **Sebastiano Battiato** | Full Professor | University of Catania, Italy | [sebastiano.battiato@unict.it](mailto:sebastiano.battiato@unict.it) |

**Institutional Affiliations:**
- **University of Catania** - Department of Mathematics and Computer Science
- **Image Processing Laboratory (IPLAB)** - [https://iplab.dmi.unict.it/](https://iplab.dmi.unict.it/)
- **Multimedia Security and Forensics Group** - [https://iplab.dmi.unict.it/mfs/](https://iplab.dmi.unict.it/mfs/)

© 2025 [University of Catania](https://www.unict.it/en).  
Powered by the [Multimedia Security and Forensics](https://iplab.dmi.unict.it/mfs/) group of the [Image Processing Laboratory (IPLAB)](https://iplab.dmi.unict.it/).

---

<picture>
  <img alt="Logos" src="/assets/images/loghiunictiplab.png">
</picture>
