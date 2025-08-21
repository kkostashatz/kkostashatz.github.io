---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education

- **Ph.D. Candidate in Computational Science**  
  *University of Amsterdam* (Oct. 2024 – Present)  
  *Research Focus*: Stochastic Modelling and Quantitative Finance for Renewable Energy Markets.  
  *Supervisors*: Sven Karbach.

- **M.Sc. in Stochastics and Financial Mathematics**  
  *University of Amsterdam* (Sept. 2022 – Sept. 2024)  
  *Specialization*: Financial Mathematics (Current Grade: 8.5/10).  
  **Coursework**:  
  - Stochastic Integration, Measure Theoretic Probability, Computational Finance.  
  - Interest Rate Models, Portfolio Theory, Advanced Topics in Stochastic Analysis, and Rough Volatility Models.  

- **M.Eng. in Applied Mathematics and Physics**  
  *National Technical University of Athens (NTUA)* (Sept. 2017 – July 2022)  
  - **Thesis**: *"Probabilistic forecasting of solar power generation using SDEs and applications on optimal trading strategies for RES Aggregators"* (Grade: 10/10).  
  - Supervisor: Prof. Antonis Papapantoleon.

---

# Employment

- **Researcher / Ph.D. Candidate**  
  *University of Amsterdam* (Oct. 2024 – Present)
  
- **Research Intern**  
  *Statkraft Trading, Düsseldorf* (March 2024 – August 2024)  
  - **Thesis Title**: *Optimal trade execution in intraday markets under Marked-Hawkes processes*.

- **Algorithmic Trading Intern**  
  *Statkraft Trading, Düsseldorf* (April 2023 – Oct. 2023)  
  - Analyzed EPEX LOB dynamics for intraday markets in Germany and the UK.  
  - Developed trading strategies for day-ahead/intraday power markets.  
  - Created forecasting models for rare meteorological events (e.g., icing).  
  - Reported risk metrics for algorithmic trading.

- **Energy Trader Intern**  
  *Wootis S.A* (April 2022 – August 2022)  
	-  Worked with the quantitative analytics department, building and refining strategies for solar and wind energy intraday trading.
  -  Developed a probabilistic forecasting model for the aggregated Solar power production using SDEs and evaluated it using risk-averse trading strategies for the company's energy portfolio.

<!-- - **Data Scientist Intern**  
  *ELVAL - Hellenic Aluminum Industry* (June 2021 – August 2021)  
  - Developed ML regression models to predict aluminum coil waste.  
  - Performed PCA for temporal data analysis in quality control. -->

---

# Skills

- **Languages**:  
  - Greek (Native), English (Proficient), German (Fluent).

- **Programming**:  
  - Python, R, MATLAB, SQL, LaTeX.

---

# Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

---

# Talks

<ul>
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

---

# Teaching

<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

---
