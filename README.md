## Integrating real time surveillance and dynamic modelling of COVID-19 in Grampian to inform an adaptive healthcare response

The aim of this project was to provide timely information on the local progression of COVID-19 to NHS Grampian to enable the optimal provision of additional resources to deal with changing clinical demand. 

We have developed a variety of monitoring and modelling tools:

* [A tool for visualising clusters of positive cases and their contacts](https://github.com/JessButler/covid_networks) provides the ability to track local outbreaks. A version of this has been modified and is used internally within NHS Grampian to monitor local clusters on a weekly basis. The code has been shared directly with other NHS boards.
* [A novel social distancing score](https://jessbutler.github.io/social_distancing/#social-distancing-score) to identify areas that might be at greater risk of transmitting COVID-19. The score combines three measures: percent of people with essential jobs; percent of people living in overcrowded homes; local population density. It is used by NHS Grampian to inform COVID-19 testing provision.
* [An epidemiological model] using the same compartments as Public Health Scotland, but estimating the local parameters directly from Grampian data. This model is in daily use by NHS Grampian to estimate future demand for hospital beds.

Using the tools we have developed, we hope to continue providing essential information to NHS Grampian for the duration of the pandemic.
This project is a collaboration between the Aberdeen Centre for Health Data Science and the NHS Grampian Health Intelligence team. It was funded by [NHS Grampian Endowments](https://www.nhsgcharities.com/). 
