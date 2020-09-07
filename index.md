---
layout: page
schemadotorg:
  "@context": http://schema.org/
  "@type": CreativeWork
  "genre": TrainingMaterial

  # Course details
       # "name" -> The acronym and extended name of the course, separated by " - "
       # "description" -> Short description of the course
  name: "R4HDA - R for Health Data Analysis"
  description: "R for Health Data Analysis"


  # Keywords -> Consult EDAM:Topic
  keywords:  "r, data analytics, health data research"

  # Audience -> Following Elixir-Tess input
  audience: ["Academia/ Research Institution", "Industry", "Non-Profit Organisation", "Healthcare"]

  # Author info
  author:
    - "@type": Organization
      name: "Health Data Research Organization"
      alternateName: "HDRO"
      sameAs: "gtpb.igc.gulbenkian.pt/bicourses/index.html"

  # predominant type of learning resources
  "learningResourceType": ["presentation", "exercise", "scripts", "handout"]

  # Contributor info
  contributor:
    - "@type": Person
      name: "CO-AUTHOR_1"
    - "@type": Person
      name: "CO-AUTHOR_2"
    - "@type": Person
      name: "CO-AUTHOR_3"

  # License & Language & url
  license: https://creativecommons.org/licenses/by/4.0/
  inLanguage: "en-us"
  url: "https://gtpb.github.io/Web_course_template/"
---

### Course Description
R is a programming language and environment commonly used in statistical computing, data analytics and scientific research.It is one of the most popular languages used by statisticians, data analysts, researchers and marketers to retrieve, clean, analyze, visualize and present data.After the training, participants will be able to critically interpret results, troubleshoot analyses, and will be ready to successfully attend more specialized training e.g. in genomics, mutaional pattern analysis, phylogenetics, biological network analysis and more.

### Target Audience
* Undergrad students
* Who are interested in data research

---

### Learning objectives
* Familiarize participants with R syntax
* Understand the concepts of objects and assignment
* Understand the concepts of vector and data types
* Data management
* Data visualization
* To understand and analyze data
* Analytics report writing

### Training Materials
* [Introduction to R](/pages/notes/introduction.html)
* [Variables in R](/pages/notes/variables.html)
* [Data Types in R](/pages/notes/datatypes.html)
* [Control Flow in R](#)
* [R Data Structure](#)
* [R Functions](#)
* [Data Manipulation using dplyr](#)
* [Data Visualization using ggplot2](#)
* [Interactive Data Visualization using Plotly](#)
* [url](/pages/page_name.md)
### Reference Books
* [R for Data Science by Roger D.Peng ](https://bookdown.org/rdpeng/rprogdatascience/)
* [Introduction to Data Science by Rafael Irizarry](https://rafalab.github.io/dsbook/)
* [Data Analysis for the Life Sciences by Rafael Irizarry](https://rafalab.github.io/pagesharvardx.html)


### Instructor
[Jubayer Hossain](https://jhossain.me/)

---

The source for this course webpage is [in github](https://github.com/hdro/R4HDA).

<br/>

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">This Course</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">HDRO</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

<br>
Template is taken from [GTPB](https://github.com/GTPB/Web_course_template)
