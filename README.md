# Data Science Platform Resources

<br>

<p align="center">
  <img src="./img/platform.png">

  <br>

  A starter kit for a data science platform.

</p>

<br>

This is a collection of links and descriptions for popular and interesting tools, services and resources that every world-class data organization needs in order to manage their data and make data driven apps and services.

## Data Management

Establishing good data practices early in the organizational transformation is key.

The most important part of your data science platform will be the data and the way you manage it will make the difference between a useful data science platform and a frustrating one. FAIR data are data which meet principles of findability, accessibility, interoperability, and re-usability. For more information about FAIR data, please visit the following links:

FAIR data are data which meet principles of **findability**, **accessibility**, **interoperability**, and **reusability**. A March 2016 publication by a consortium of scientists and organizations specified the "FAIR Guiding Principles for scientific data management and stewardship" in Scientific Data, using FAIR as an acronym and making the concept easier to discuss. From [Wikipedia](https://en.wikipedia.org/wiki/FAIR_data).

In 2016, the ‘FAIR Guiding Principles for scientific data management and stewardship’ were published in Scientific Data. The authors intended to provide guidelines to improve the Findability, Accessibility, Interoperability, and Reuse of digital assets. The principles emphasise machine-actionability (i.e., the capacity of computational systems to find, access, interoperate, and reuse data with none or minimal human intervention) because humans increasingly rely on computational support to deal with data as a result of the increase in volume, complexity, and creation speed of data. From [Go FAIR](https://www.go-fair.org/fair-principles/).

1. [CKAN](https://ckan.org/) is a powerful data management system that makes data accessible by providing tools to streamline publishing, sharing, finding and using data. You can see a [demo of CKAN](https://demo.ckan.org/).

    More links:
    
    - [CKAN and The Government of Canada](https://ckan.org/team/government-of-canada/)
    - [Install CKAN with Docker Compose](https://docs.ckan.org/en/2.9/maintaining/installing/install-from-docker-compose.html)
    - [How to use Frictionless Data with CKAN](https://frictionlessdata.io/how-to/how-to-use-data-packages-with-ckan/)
    - [Docker Container](https://github.com/keitaroinc/docker-ckan)
    - [CKAN and Government of Canada](https://ckan.org/team/government-of-canada/)
    - [CKAN Government of Canada Extension on Github](https://github.com/open-data/ckanext-canada)
    - [CKAN API Documentation](https://docs.ckan.org/en/2.9/api/)
    - [CKAN Documentation](https://docs.ckan.org/en/latest/contents.html#)

2. [Frictionless](https://frictionlessdata.io/) is a progressive, incrementally adoptable open-source toolkit that brings simplicity and gracefulness to the data experience - whether you're wrangling a CSV or engineering complex pipelines with gigabytes.

    More links:
    
    - [Github](https://github.com/frictionlessdata) 
        - [Python Module](https://github.com/frictionlessdata/frictionless-py)
        - [How to use.](https://github.com/frictionlessdata/frictionless-py/blob/master/docs/target/getting-started/README.md)
    - [Lecture on Frictionless Data](https://www.youtube.com/watch?v=EFQmudQP4io)
    - [Lecture Slides](https://www.google.com/url?q=http://bit.ly/fdATO&sa=D&ust=1604076235975000&usg=AOvVaw3f7NIudeVlmUsxyZQKl9xv)
    - [Good Tables](https://goodtables.io/)
    - [Frictionless Data Creator](https://create.frictionlessdata.io/) 
    - [Guide to Frictionless](https://frictionlessdata.io/guide/)

## Data Platform Engineering

The data science platform will rest on some kind of compute platform. I'm not an expert at this level but here are some promising projects on which you can host your platform.

1. [K3ai](https://docs.k3ai.in/) is a lightweight “infrastructure in a box” designed specifically to install and configure AI tools and platforms on portable hardware, such as laptops and edge devices. This enables users to perform quick experimentations with Kubeflow on a local cluster.

1. [MLflow](https://mlflow.org/) is an open source platform to manage the ML lifecycle, including experimentation, reproducibility, deployment, and a central model registry. MLflow currently offers four components:

    - [MLflow Tracking](https://mlflow.org/docs/latest/tracking.html): Record and query experiments: code, data, config, and results.
    - [MLflow Projects](https://mlflow.org/docs/latest/projects.html): Package data science code in a format to reproduce runs on any platform.
    - [MLflow Models](https://mlflow.org/docs/latest/models.html): Deploy machine learning models in diverse serving environments.
    - [Model Registry](https://mlflow.org/docs/latest/model-registry.html): Store, annotate, discover, and manage models in a central repository.

1. [Ansible](https://www.ansible.com/) is an open-source software provisioning, configuration management, and
application-deployment tool enabling infrastructure as code. It runs on many
Unix-like systems, and can configure both Unix-like systems as well as Microsoft
Windows. It includes its own declarative language to describe system
configuration.
  
    I've found some example Ansible roles for data science:

    - [Ansible Role for Data Science](https://github.com/govcloud/ansible-role-data-science)
    - [Ansible Role for Data Science](https://github.com/remigius42-ai/ansible-role-data_science_base)
    - [Ansible Data Science Toolkit](https://github.com/riethmayer/data-science-toolkit)

1. [Open Data Hub](https://opendatahub.io/) is a blueprint for building an AI as a service platform on Red Hat's Kubernetes-based OpenShift Container Platform and Ceph Object Storage. It inherits from upstream efforts such as Kafka/Strimzi and Kubeflow, and is the foundation for Red Hat's internal data science and AI platform. Data scientists can create models using Jupyter notebooks, and select from popular tools such as TensorFlow, scikit-learn, Apache Spark and more for developing models. Teams can spend more time solving critical business needs and less on installing and maintaining infrastructure with the Open Data Hub. 

## Data Science and Machine Learning

### NLP

1. [spaCy](https://spacy.io/) is designed to help you do real work — to build real products, or gather
real insights. The library respects your time, and tries to avoid wasting it.
It's easy to install, and its API is simple and productive. We like to think of
spaCy as the Ruby on Rails of Natural Language Processing. 

1. [Doccano](https://doccano.herokuapp.com/) is an open source text annotation tool for humans. It provides annotation features for text classification, sequence labeling and sequence to sequence tasks. So, you can create labeled data for sentiment analysis, named entity recognition, text summarization and so on. Just create a project, upload data and start annotating. **You can build a dataset in hours.**

## Data Analysis and Business Intelligence

1. [jamovi](https://www.jamovi.org/) is a new “3rd generation” statistical spreadsheet. designed from the ground up to be easy to use, jamovi is a compelling alternative to costly statistical products such as SPSS and SAS. **jamovi is built on top of the R statistical language, giving you access to the best the statistics community has to offer.** Try jamovi in the [cloud](https://cloud.jamovi.org/).

1. [nteract](https://nteract.io/) is an interactive computing experiences that allow people to collaborate with ease. The nteract ecosystem provides a wide variety of notebook-based applications for your scenario. Whether you want to edit notebooks in a desktop app or in your favorite editor, nteract provides you the tools you need to leverage the full power of interactive notebooks. 
   

## Data Science and ML Development Environments

### Jupyter

- [GPU Powered Docker Containers](https://hub.docker.com/r/cschranz/gpu-jupyter)
- [Jupyter Notebooks from StatCan](https://github.com/govcloud/jupyter-notebooks)
- [Docker Containers for Jupyter Notebooks](https://github.com/jupyter/docker-stacks)



### Datasette

https://github.com/simonw/datasette

## DevOps

DevOps is a set of practices that combines software development (Dev) and IT
operations (Ops). It aims to shorten the systems development life cycle and
provide continuous delivery with high software quality. DevOps is complementary
with Agile software development; several DevOps aspects came from Agile
methodology.



### Data Management and Search

#### Elastic Stack

Elasticsearch is the distributed search and analytics engine at the heart of the
Elastic Stack. Logstash and Beats facilitate collecting, aggregating, and
enriching your data and storing it in Elasticsearch. Kibana enables you to
interactively explore, visualize, and share insights into your data and manage
and monitor the stack. Elasticsearch is where the indexing, search, and analysis
magic happens.

- [What is Elastic Stack?](https://www.elastic.co/guide/en/elasticsearch/reference/current/elasticsearch-intro.html)
- [Installing Elastic Stack with Docker](https://www.elastic.co/guide/en/elastic-stack-get-started/current/get-started-docker.html)

### Data Visualization

### Streamlit

The fastest way to build and share data apps. Turn data scripts into shareable
web apps in minutes. All in Python. All for free. No front-end experience
required.

- [Homepage](https://www.streamlit.io/)

#### Vega

Vega is a visualization grammar, a declarative language for creating, saving,
and sharing interactive visualization designs. With Vega, you can describe the
visual appearance and interactive behavior of a visualization in a JSON format,
and generate web-based views using Canvas or SVG.

- [Homepage](https://vega.github.io/)
- [Demo of Vega](https://vega.github.io/editor/#/)
- [Example Gallery](https://vega.github.io/vega/examples/)

### Apache Preset

*An enterprise-ready analytics platform where data novices can learn and data
professionals will thrive.*

Superset is fast, lightweight, intuitive, and loaded with options that make it
easy for users of all skill sets to explore and visualize their data, from
simple line charts to highly detailed geospatial charts.

- [Homepage](https://preset.io/)
- [Homepage](https://superset.apache.org/)
- [Install Apache Preset](https://preset.io/blog/2020-05-11-getting-started-installing-superset/)
- [Github Page](https://github.com/apache/incubator-superset)
- [Article](https://medium.com/airbnb-engineering/superset-scaling-data-access-and-visual-insights-at-airbnb-3ce3e9b88a7f)

### Metabase

- [Homepage](https://www.metabase.com/start/oss/)


### Open Knowledge Foundation

https://okfn.org/what-we-do/training/



# Project/Organization Management

https://www.tuleap.org/

Tuleap is the tool to turn your digital transformation plans into reality.

Tuleap helps your teams better collaborate adopting the Agile and DevOps
practices. Accelerate the delivery of quality, customer-focused solutions. Bring
everyone on the same page, at the same time.

### Closed Source Solutions

https://www.knime.com/

https://www.tableau.com/

#### Retool

Stop wrestling with UI libraries, hacking together data sources, and figuring
out access controls. Start shipping apps that move your business forward.

- [https://retool.com/](Homepage)

### No Code Solutions

https://capiche.com/e/software-lockin

https://medium.com/@rrhoover/the-rise-of-no-code-e733d7c0944d

https://lobe.ai/  (Currently only supports image classification)

https://www.freshpaint.io/product/visual-editor


### Luna Lang / Enso

An interesting hybrid code/visual programming language. The development team switched from
Luna to Enso. Enso is currently pre-1.0, but Luna is in beta. There is no more development on luna, 
but you can try it to see how Enso would look in the future. 

https://github.com/enso-org/enso
https://luna-lang.org/


# Decision Process Automation

http://learn-dmn-in-15-minutes.com/
https://en.wikipedia.org/wiki/Decision_Model_and_Notation
https://en.wikipedia.org/wiki/Predictive_Model_Markup_Language
https://www.slideshare.net/MarlonDumas/ai-for-business-process-management?from_action=save
https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=32592
https://www.redhat.com/en/technologies/jboss-middleware/process-automation-manager
https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=32603
http://kie.org/
https://kogito.kie.org/

https://www.research.ibm.com/artificial-intelligence/trusted-ai/


https://www.odoo.com/
