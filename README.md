log-parser-plugin
=================

[![Build Status](https://ci.jenkins.io/buildStatus/icon?job=Plugins%2Flog-parser-plugin%2Fmaster)](https://ci.jenkins.io/blue/organizations/jenkins/Plugins%2Flog-parser-plugin/branches/)

Parses the console output and highlights error/warning/info lines.

http://wiki.jenkins-ci.org/display/JENKINS/Log+Parser+Plugin


### *This fork is for the purpose of adding additional functionality to the existing log-parser-plugin.*

#### Recommendations
  * The Build Log will be scanned, using a list of Regex Patterns. When a pattern is found, an associated
  recommendation (in HTML format) will be inserted into the existing Log-Parser output. The purpose is to provide
  users with recommendations, Knowledgebase articles, etc. that will assist them in fixing routine issues without
  needing to submit a support ticket to their DevOps Support team.
