Daniel Chen
============

Education
-----------

2015-2020 (expected)
:   **PhD, Genetics, Bioinformatics, and Computational Biology**; Virginia Tech

      (Blacksburg, VA)

2012-2014
:   **MPH, Epidemiology**; Mailman School of Public Health (New York City, NY)

     * Certificate: Advanced Epidemiology

2007-2012
:   **BA, Psychology**; The Macaulay Honors College at CUNY Hunter College

      (New York City, NY)

     * Concentration: Behavioral Neuroscience
	 * Minors: Biology, Computer Science

Experience
------------

**Social and Decision Analytics Laboratory**

* Build and deploy the system that houses the lab's computational infrastructure and data using Docker

* Co-instructor for the [Data Science for Public Good][dspg] Program

    * Main point of contact for code and technical issues

* Ensure the lab's workflow follow best research practices for data security, reproducibility, and replicability

**Lander Analytics**

* Teach Machine Learning and Dashboards R
* Teach Data Analysis and Programming in Python

**Columbia University School of Nursing**

* Analyzed survey data on mass causality preparedness that lead to 2 published papers

* Prepared hospital data to measure care pathways using a network approach

**Center for Injury Epidemiology and Prevention at Columbia University**

* Worked on an agent-based model written in Java looking at alcohol and violence in NYC

**NYU Langone Medical Center**

* Data manager and clinical trials coordinator

Technical Experience
--------------------

MANN
:   Multi-Agent Neural Network

    * Continuation of Master's Thesis Project.
    * Agent-based simulation model
    * Measure spread of beliefs towards a behavior in a social network

SDAL
:   Computational and data storage/management infrastructure

    * Co-maintain and develop docker containers that hold all of the software and services used in the lab

Open Source
:   [Mesa][mesa]: Agent-based modeling in Python.
                  Contributed to the documentation and
				  provided an example model based on the conference proceeding paper.
:   [EnTICE3][entice3]: Communication tool to generate tailored infographics from
                  electronic health data to improve patient literacy.
				  It is based on a [style guide][entice3_style] and has a supporting
				  [grader][entice3_grader] to help analyze the data for the
				  tool's clinical trial assessment
:   [Zika Open Data Dashboard][zika_dashboard]: Dashboard to quickly glance at all the data curated by the CDC during the Zika outbreak in 2016. The dashboard makes it easy to assemble together all the curated datasets to view and download.
Extends on a [similar project][ebola_dashboard] during the 2014 West Africa Ebola outbreak.
:   [pylens][pylens]: Python wrapper for the LENS neural network simulator used in the MANN project
:   [sdalr][bi-sdal/sdalr]: R package of commonly used functions for all members of the lab
:   * Project Templates

	    * [Computational Project Cookie Cutter][comp_cookie]: Template for analytics projects
    	* [Pweave document][pweave_example]: \LaTeX template for literate programming in Python
    	* [Knitr document][knitr_example]: `knitr` template for literate programming in R
    	* [SDAL Paper Template][sdal_paper_template] \LaTeX template for writing papers

Programming Languages
:   **R:** Primary language for data cleaning, statistical modeling, and machine learning

:   **Python:** Computer simulations, web scraping, and other general data
                collection programs.  Primarily use `pandas` for data related work.
:   Basic knowledge of **SQL**, **C++**, **Java**, **HTML/CSS**
:   System administration: **Bash**, **Docker**,  **VirtualBox**

[ref]: https://github.com/githubuser/superlongprojectname

Teaching
---------

* Data Science for the Public Good

    * Co-teach a 2.5 week long intensive [workshop][bi-sdal/workshop] on data science tools
	    * *2017*: 19 Students; *2016*: 8 Students; *2015*: 4 Students
	    * bash, SSH tunneling, git, project templates, data import/export, code repositories, R `data.table`,
		  functions and `apply`, `knitr` and `rmarkdown` reports, grouped and aggregated statistics,
		  loops, data tidying, regular expressions, plotting, command line scripts, detached processes,
		  web scraping, dashboards with `shiny`, machine learning
    * Guide research of undergraduate students and graduate fellows
		* technical and code support, data pipeline algorithms

* Software Carpentry / Data Carpentry

    * Co-[maintainer][swc_r_lesson] of the R [Lesson][swc_lesson]
	* 15+ Workshops taught around the country

Teaching Materials
----------------------

* [Git Essentials][git_essentials]: Online video course through [Safari Books Online][safari] on the basics of git.
* [Cleaning Data in Python][dc_data]: [DataCamp][datacamp] course on diagnosing and cleaning data in Python
* [Pandas for Everyone][pandas_book] (Expected end of 2017): Book published though Pearson's Addison-Wesley Data & Analytics Series about the Python data analyics library, `pandas`

Publications
--------------

ORCID: [http://orcid.org/0000-0003-3857-1741][orcid]

* Mass fatality preparedness among medical examiners/coroners in the United States: a cross-sectional study. 2014.
  Robyn RM GershonEmail author, Mark G Orr, Qi Zhi, Jacqueline A Merrill, Daniel Y Chen, Halley EM Riley and Martin F Sherman.
  BMC Public Health201414:1275.
  DOI: 10.1186/1471-2458-14-1275

* Are We Ready for Mass Fatality Incidents? Preparedness of the US Mass Fatality Infrastructure. 2015.
  Jacqueline A. Merrill, Mark Orr), Daniel Y. Chen, Qi Zhi, and Robyn R. Gershon.
  Disaster Medicine and Public Health Preparedness.
  DOI: https://doi.org/10.1017/dmp.2015.135

* Systems Science and Population Health.
  Systems of Behavior and Population Health.
  Mark Orr, Kathryn Ziemer, Daniel Chen. 2017.
  Book Chapter.
  ISBN: 9780190492397

* Software Carpentry: Programming with R. 2016.
  DOI: 10.5281/zenodo.57541.
  URL: https://doi.org/10.5281/zenodo.57541

* Software Carpentry: The Unix Shell. 2016.
  DOI: 10.5281/zenodo.57544.
  URL: https://doi.org/10.5281/zenodo.57544

* Software Carpentry: Using Databases and SQL. 2016.
  DOI: 10.5281/zenodo.57551.
  URL: https://doi.org/10.5281/zenodo.57551

* Software Carpentry: Version Control with Git. 2016.
  DOI: 10.5281/zenodo.57467.
  URL: https://doi.org/10.5281/zenodo.57467


----

> <chend@vt.edu> • +1 (917) 880 9254 • https://chendaniely.github.io

[orcid]: http://orcid.org/0000-0003-3857-1741
[dspg]: https://www.bi.vt.edu/sdal/projects/data-science-for-the-public-good-program
[mesa]: https://github.com/projectmesa/mesa
[entice3]: https://github.com/chendaniely/wicer-entice3
[entice3_style]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4371489/
[entice3_grader]: https://github.com/chendaniely/wicer-entice3-grader
[zika_dashboard]: https://chendaniely.shinyapps.io/zika_cdc_dashboard/
[ebola_dashboard]: https://chendaniely.shinyapps.io/shinyCountryTimeseries/
[stan]: http://mc-stan.org/
[bi-sdal/workshop]: https://github.com/bi-sdal/workshop
[swc_lesson]: https://software-carpentry.org/lessons/
[swc_r_lesson]: http://swcarpentry.github.io/r-novice-inflammation/
[git_essentials]: https://www.safaribooksonline.com/library/view/git-essentials-livelessons/9780134655284/
[safari]: https://www.safaribooksonline.com/
[datacamp]: https://www.datacamp.com/
[dc_data]: https://www.datacamp.com/courses/cleaning-data-in-python
[pandas_book]: https://www.amazon.com/Pandas-Everyone-Analysis-Addison-Wesley-Analytics/dp/0134546938
[bi-sdal/sdalr]: https://github.com/bi-sdal/sdalr
[pylens]: https://github.com/chendaniely/pylens
[sdal_paper_template]: https://github.com/bi-sdal/paper_template_LaTeX
[knitr_example]: https://github.com/chendaniely/knitr-child-document-example
[comp_cookie]: https://github.com/chendaniely/computational-project-cookie-cutter
[pweave_example]: https://github.com/chendaniely/pweave-child-document-example
