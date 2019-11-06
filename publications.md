---
layout: page
permalink: /publications/index.html
title: Publications

pubs:

  - author: "Xudong Wang, Lijun Sun"
    title: "Detecting Spatiotemporal Traffic Anomalies with Low-rank Tensor Regression"
    month: "January"
    year: "2020"
    address: "Washington DC, United States"
    booktitle: "Transportation Research Board"
    
  - author: "Lulu Tan, Xudong Wang, Luis F. Miranda-Moreno, Aurelie Labbe, Lijun Sun"
    title: "Spatiotemporal Regularized Factorization for Traffic Data Imputation"
    month: "January"
    year: "2020"
    address: "Washington DC, United States"
    booktitle: "Transportation Research Board"
    
  - author: "Xudong Wang, Antoine Fagette, Pascal Sartelet, Lijun Sun"
    title: "A Probabilistic Tensor Factorization Approach to Detect Anomalies in Spatiotemporal Traffic Activities"
    month: "October"
    year: "2019"
    address: "Auckland, New Zealand"
    booktitle: "IEEE Intelligent Transportation Systems Conference"

  - author: "Yang Li, Xudong Wang, Shuo Sun, Xiaolei Ma, Guangquan Lu"
    title: "Forecasting short-term subway passenger flow under special events scenarios using multiscale radial basis function networks"
    month: "March"
    year: "2017"
    booktitle: "Transportation Research Part C: Emerging Technologies"
    url: https://www.researchgate.net/profile/Yang_Li128/publication/313670218_Forecasting_Short-term_Subway_Passenger_Flow_under_Special_Events_Scenarios_using_Multiscale_Radial_Basis_Function_Networks/links/59f89e000f7e9b553ec0b958/Forecasting-Short-term-Subway-Passenger-Flow-under-Special-Events-Scenarios-using-Multiscale-Radial-Basis-Function-Networks.pdf


  - author: "Yang Li, Xudong Wang, Meilin Luo"
    title: "Epileptic seizure classification of EEGs using time--frequency analysis based multiscale radial basis functions"
    month: "September"
    year: "2017"
    booktitle: "IEEE journal of biomedical and health informatics"
    url: https://ieeexplore.ieee.org/abstract/document/7875493

---

## Publications

{% for pub in page.pubs %}
{% unless pub.hidden %}
  - {% if pub.url %} [{{pub.title}}]({{pub.url}}).
    {% else %} {{pub.title}}.
    {% endif %}{% if pub.type %}({{pub.type}})
    {% endif %}<br>
    {{pub.author}}.<br>
    {% if pub.type == 'Technical Report' %}{{pub.number}}
    {% endif %}{{pub.booktitle}}{{pub.school}}{{pub.journal}}.<br>
    {% if pub.address %}{{pub.address}}.
    {% endif %} {{pub.month}}, {{pub.year}}. {% if pub.slides %}[Slides]({{pub.slides}}).
    {% endif %}{% if pub.key %}[Bibtex](http://groups.csail.mit.edu/commit/bibtex.cgi?key={{pub.key}}).
    {% endif %}{% if pub.bibtex %}[Bibtex]({{pub.bibtex}}).
    {% endif %}
{% endunless %}
{% endfor %}



