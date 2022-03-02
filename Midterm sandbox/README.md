# Midterm roadmap

Basic idea: Whta factors make afirm more exposed/protected from pandemic?

Need: A dataset that looks like this:

Firm | return over pandemic start | size
--- | --- | --- 
A | 10% | -1
B | 1% | 0
C | -5% | 1

Project steps:

- download_text_files.py
    - get sample firms 
    - download 10-Ks
- measure_risk.py
    - read "prase" 10-Ks
- analysis_report.py
    - combine sample with return data, and risk measures
    - (more things)
    - results
