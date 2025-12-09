Here is a clean, professional **README.md** ready to paste directly into your new repo:

---

# StudyASAP Global Data

Centralized datasets powering the **American Study Abroad Program (StudyASAP)**—including FAFSA-eligible institutions, Post-9/11 GI Bill foreign institutions, tuition benchmarks, visa requirements, and international study analytics.

This repository serves as the **public data backbone** for tools, dashboards, and advisory services supporting American students studying overseas.

---

## 📊 Purpose

To provide a **single, authoritative, transparent source of global education data** used across:

* StudyASAP university matching tools
* GI Bill & FAFSA eligibility checkers
* Tuition comparison systems
* Visa & residency requirement guides
* Power BI analytics
* Americans Abroad Network integrations

---

## 📁 Repository Structure

```
/datasets
    /fa_fsa_foreign_schools.csv
    /gi_bill_approved_schools.csv
    /tuition_estimates_by_country.csv
    /visa_requirements_summary.csv
    /cost_of_living_index.csv

/scripts
    /update_fafsa_data.py
    /update_gibill_data.py
    /tuition_scraper.py

/docs
    /data_dictionary.md
    /methodology.md
```

---

## 🧭 What This Data Covers

### ✔ FAFSA Foreign School Eligibility

List of non-U.S. institutions approved to accept Title IV funding.

### ✔ Post-9/11 GI Bill (Chapter 33) Overseas Schools

Institutions approved by the U.S. Department of Veterans Affairs.

### ✔ Tuition Benchmarks (International Students)

Aggregated annual tuition ranges for bachelor's and master's programs.

### ✔ Visa Requirements Summaries

High-level requirements for U.S. citizens studying abroad (EU/EEA, UK, Switzerland, etc.).

### ✔ Cost of Living Index

Indicative data comparing affordability across major student destinations.

---

## 🔄 Update Frequency

| Dataset               | Update Cycle |
| --------------------- | ------------ |
| FAFSA Foreign Schools | Monthly      |
| GI Bill Schools       | Monthly      |
| Tuition Data          | Quarterly    |
| Visa Requirements     | Quarterly    |
| Cost of Living        | Quarterly    |

Automated scripts may update certain datasets directly via `/scripts`.

---

## 📜 License

This repository is licensed under the **MIT License**, allowing public use, modification, and distribution with attribution.

---

## 🤝 Contributing

Pull requests are welcome for:

* Data corrections
* Updated visa rules
* Additional universities
* New dataset proposals

All contributions must adhere to data accuracy and sourcing standards (see `/docs/methodology.md`).

---

## 🌐 About StudyASAP

**American Study Abroad Program (StudyASAP)** helps U.S. students access affordable, accredited degree programs overseas—supporting FAFSA, Post-9/11 GI Bill pathways, visas, relocation, and academic guidance.

Learn more:
[https://www.amabroad.net](https://www.amabroad.net)

---

If you want, I can also create the **data dictionary**, folder structure, or the first CSV templates for you to upload.
