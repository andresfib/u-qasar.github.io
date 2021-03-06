---
type: description
---
Configuring Automatic Metrics
-----------------------------
As mentioned before the quality of one Project is measured by aggregations of its children elements. Quality Objectives are aggregations of Quality Indicators and those are aggregations of Metrics. The last element in Project's hierarchy is the metric. Metrics are used to retrieve measurements and they can be configured to get the data from external tools. Those tools should have been previously set up in the "Adapter Settings" option.
To configure automatic Metrics the user has to select the data source in the "Metric Source" field. It should be different from "Manual", for instance "Static Analysis". Then, in the "Metric Type" field the specific metric to be retrieved should be selected (see Figure: Configuring automatic metrics): 


<img src="adpt_auto.png " width="760" alt="Adapter: Configuring Automatic Metrics" />


Inputting the measurement data manually
---------------------------------------
There are plenty of situations where a desired measurement value is not available, the measured value is false, no longer valid, not in a suitable format etc. This leads that the value has to be added/updated manually later. The Quality Project view enables editing of metric values. The metric type and source are set to manual. After this, the metric value can be set and the changes can be saved.


<img src="adpt_manual.png " width="760" alt="Adapter: Inputting the measurement data manually" />


Retrieving the data automatically from the connected tools (JIRA, SonarQube, TestLink, Cubes, Jenkins, Gitlab)
-------------------------------------------------------------------------------------------------------------- 
For the Integrated Platform, adapters for the JIRA bug tracking system ([JIRA Website](https://www.atlassian.com/software/jira "https://www.atlassian.com/software/jira")), the SonarQube code analysis software tool ([SonarQube Website](http://www.sonarqube.org/ "http://www.sonarqube.org/")), the TestLink test management software ([TestLink Website](http://testlink.org/ "http://testlink.org/")), the Cubes OLAP Framework ([Cubes Website](http://cubes.databrewery.org/ "http://cubes.databrewery.org/")), Jenkins continuous integration server ([Jenkins Website](https://jenkins-ci-org "https://jenkins-ci-org")), and the Gitlab version management server ([Gitlab Website](https://gitlab.com "https://gitlab.com")) were implemented. The adapters are used in the Integrated Platform to obtain quality metric data for the platform. The data is parsed, stored internally and may be further viewed, analysed and visualized on the platform etc. Further Data Retrieval and Usage related functionalities on U-QASAR are how to retrieve Data from JIRA, SonarQube, TestLink, Cubes, Jenkins and Gitlab Adapters.
