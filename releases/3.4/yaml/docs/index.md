(index)=

# Charmed Apache Spark K8s Documentation

Charmed Apache Spark solution is a set of Canonical supported artefacts (including charms, rocks and snaps) that make operating Apache Spark workloads on Kubernetes seamless, secure and production-ready. This solution includes the Charmed Apache Spark bundle as well as [Client tools snap for Apache Spark](https://snapcraft.io/spark-client) and [spark8t](https://github.com/canonical/spark-k8s-toolkit-py). For more information on the contents of the Charmed Apache Spark bundle and Charmed Apache Spark solution, see the [Components explanation](/explanation/component-overview) page.

Apache Spark is a free, open-source software project by the Apache Software Foundation. Users can find out more at the [Apache Spark project page](https://spark.apache.org).

The solution helps to simplify user interaction with Apache Spark applications and the underlying Kubernetes cluster whilst retaining the traditional semantics and command line tooling that users already know. Operators benefit from straightforward, automated deployment of Apache Spark components (e.g. Spark History Server) to the Kubernetes cluster, using [Juju](https://juju.is/). 

Deploying Apache Spark applications to Kubernetes has several benefits over other cluster resource managers such as Apache YARN, as it greatly simplifies deployment, operation, authentication while allowing for flexibility and scaling. However, it requires knowledge on Kubernetes, networking and coordination between the different components of the Apache Spark ecosystem in order to provide a scalable, secure and production-ready environment. As a consequence, this can significantly increase complexity for the end user and administrators, as a number of parameters need to be configured and prerequisites must be met for the application to deploy correctly or for using the Spark CLI interface (e.g. pyspark and spark-shell). 

Charmed Apache Spark helps to address these usability concerns and provides a consistent management interface for operations engineers and cluster administrators who need to manage enablers like Spark History Server.

## In this documentation

| | |
|--|--|
|  [Tutorials](/tutorial/introduction)</br>  Get started - a hands-on introduction to using Charmed Apache Spark operator for new users </br> |  [How-to guides](/how-to/deploy/set-up-the-environment) </br> Step-by-step guides covering key operations and common tasks |
| [Reference](/reference/requirements) </br> Technical information - specifications, APIs, architecture | [Explanation](/explanation/component-overview) </br> Concepts - discussion and clarification of key topics  |

## Project and community

Charmed Apache Spark is a distribution of Apache Spark. It’s an open-source project that welcomes community contributions, suggestions, fixes and constructive feedback.

- [Read our Code of Conduct](https://ubuntu.com/community/code-of-conduct)
- [Join the Discourse forum](https://discourse.charmhub.io/tag/spark)
- [Contribute and report bugs](https://github.com/canonical/spark-client-snap)

# Navigation

[details=Navigation]

| Level | Path                           | Navlink                                                                                                                                        |
|-------|--------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | overview                       | [Overview](/index)                                                                                            | 
| 1     | tutorial                       | [Tutorial]()                                                                                                                                   |
| 2     | t-overview | [Introduction](/tutorial/introduction) |
| 2     | t-setup-environment | [1. Environment setup](/tutorial/1-environment-setup) |
| 2     | t-data-processing | [2. Distributed data processing](/tutorial/2-distributed-data-processing) |
| 2     | t-streaming | [3. Data stream processing](/tutorial/3-data-stream-processing) |
| 2     | t-history-server | [4. History Server](/tutorial/4-history-server) |
| 2     | t-cos | [5. Monitoring with COS](/tutorial/5-monitoring-with-cos) |
| 2     | t-kyuubi| [6. Apache Kyuubi ](/tutorial/6-apache-kyuubi) |
| 2     | t-wrapping-up | [7. Wrapping Up](/tutorial/7-wrapping-up) |
| 1     | how-to                         | [How To]()                                                                                                                                     |
| 2     | h-deploy                   | [Deploy]()                                               |
| 3     | h-setup-k8s                    | [Set up the environment](/)                                                 |
| 3     | h-deploy                       | [Deploy Charmed Apache Spark](/)                                                   |
| 3     | h-deploy-kyuubi                      | [Deploy Charmed Apache Kyuubi](/)                                                   |
| 2     | h-service-accounts      | [Manage service accounts]()                                               |
| 3     | h-manage-service-accounts      | [Using spark-client snap](/how-to/manage-service-accounts/using-spark-client-snap)                                               |
| 3     | h-use-spark-client-from-python | [Using Python](/how-to/manage-service-accounts/using-python)                                                            |
| 3     | h-use-integration-hub          | [Using Integration Hub](/)                     |
| 2     | h-kyuubi                  | [Apache Kyuubi]()                                               |
| 3     | h-kyuubi-encryption                   | [Encryption and passwords](/how-to/apache-kyuubi/encryption-and-passwords)                                                 |
| 3     | h-kyuubi-metastore                   | [External metastore](/how-to/apache-kyuubi/external-metastore)                                                 |
| 3     | h-kyuubi-connections                   | [External connections](/how-to/apache-kyuubi/external-connections)                                                 |
| 3     | h-kyuubi-applications                   | [Integrate with applications](/how-to/apache-kyuubi/integrate-with-applications)                                                 |
| 3     | h-kyuubi-upgrade                   | [Upgrade](/how-to/apache-kyuubi/upgrade)                                                 |
| 3     | h-kyuubi-backup                   | [Back up and restore](/how-to/apache-kyuubi/back-up-and-restore)                                                 |
| 2     | h-spark-monitoring             | [Enable monitoring](/)                                                  |
| 2     | h-history-server        | [Spark History Server]()                                   |
| 3     | h-expose-history-server        | [Expose web GUI](/)                                   |
| 3     | h-history-server-authorization | [Auth](/) |
| 2     | h-run-on-k8s-pod               | [Use K8s pods](/)                                                      |
| 2     | h-spark-streaming              | [Streaming Jobs](/how-to/streaming-jobs)                                                            |
| 2     | h-spark-gpu             | [Use GPU](/)   |
| 2     | h-spark-cert             | [Self-signed certificates](/)                                                  |
| 1     | reference                      | [Reference]()                                                                                                                                  |
| 2     | r-releases                      | [Releases]()                                                                                                                                  |
| 3     | r-rev-2                   | [Revision 2](/reference/releases/revision-2)                                                                                                                                  |
| 2     | r-requirements                 | [Requirements](/reference/requirements)                                                                               |
| 2     | r-contacts                     | [Contacts](/)                                                                        |
| 1     | explanation                    | [Explanation]()                                                                                                                                |
| 2     | e-component-overview           | [Component overview](/explanation/component-overview)                                                              |
| 2     | e-security                       | [Security](/explanation/security) |
| 2     | e-cryptography                       | [Cryptography](/explanation/cryptography) |
| 2     | e-configuration                | [Configuration](/explanation/configuration)                          |
| 2     | e-monitoring                   | [Monitoring](/explanation/monitoring)                                                        |
| 2     | e-trademarks                 | [Trademarks](/)                                                        |

[/details]

# Redirects

[details=Mapping table]
| Path | Location |
| ---- | -------- |
| t-spark-shell | t-data-processing |
| t-spark-submit | t-overview |
| t-spark-streaming | t-streaming |
| t-spark-monitoring | t-cos |
[/details]

-------------------------


```{toctree}
:titlesonly:
:maxdepth: 2
:glob:
:hidden:

Home <self>
tutorial*/index
how*/index
reference*/index
explanation*/index
*
```
