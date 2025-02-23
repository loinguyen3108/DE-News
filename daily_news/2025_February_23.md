# Summary Data Engineer news at February 23rd 2025, 9:00:15 am
## Summary content
This summary covers several key areas in data engineering. It starts with implementing graph databases for managing complex data relationships, emphasizing node, relationship, and property organization and database selection (Neo4j, ArangoDB, Amazon Neptune). The second post discusses streaming SQL functionality using Stateful DataFlow and Fluvio, highlighting its advantages and use cases. Then, implementing MLOps within data engineering workflows is explored, covering the setup of development environments, model deployment, monitoring, and governance. Also, the issue of "ghost models" in dbt projects is examined. It stresses how non-materialized models can disrupt deferral processes in CI/CD pipelines and suggests disabling such models as a solution. Lastly, it delves into advanced data governance in hybrid and multi-cloud environments, focusing on establishing governance frameworks, data cataloging, quality management, compliance, security, and data integration. The last post show complement a certain average value to ensure that the total sum remains unchanged from SQL to SPL.

## Posts main ideas
[Set up Graph Databases in Large-Scale Applications for Complex Data Management](https://dev.to/flnzba/set-up-graph-databases-in-large-scale-applications-for-complex-data-management-1000)
*   Graph databases are suitable for handling complex, interconnected data through nodes, relationships, and properties.
*   Proper data modeling and the selection of the right graph database (e.g., Neo4j, ArangoDB, Amazon Neptune) are crucial for maximizing performance.

[Streaming SQL in Stateful DataFlows](https://dev.to/debadyuti/streaming-sql-in-stateful-dataflows-3jng)
*   SQL Streaming Queries and Stream Processing Operations is released in Stateful DataFlow Beta 7 running on Fluvio 0.15.2
*   You can Run ad-hoc queries on saved state objects and materialized views based live event streams, also use SQL queries to run stream processing operations in data flows.

[Implementing MLOps within Data Engineering Workflows for Efficient Machine Learning Model Deployment](https://dev.to/flnzba/implementing-mlops-within-data-engineering-workflows-for-efficient-machine-learning-model-deployment-10e1)
*   MLOps streamlines ML model deployment through version control, package management, and experiment tracking.
*   Automated CI/CD pipelines, model monitoring, and regular retraining are essential for maintaining model performance and compliance.

[Ghost models and spooky manifests in dbt](https://dev.to/panasenco/ghost-models-and-spooky-manifests-in-dbt-o78)
*   "Ghost models" (non-materialized models in dbt) can break deferral and slim CI processes, leading to increased CI runtime and costs.
*   Disabling ghost models is recommended to prevent issues with deferral and ensure the proper functioning of CI/CD pipelines.

[Implementing Advanced Data Governance in Hybrid and Multi-Cloud Environments](https://dev.to/flnzba/implementing-advanced-data-governance-in-hybrid-and-multi-cloud-environments-10nk)
*   Establishing a clear data governance framework with defined policies and data stewards is essential for managing data across hybrid and multi-cloud environments.
*   Implementing data cataloging, quality management, security, and compliance measures are critical for ensuring data integrity and regulatory adherence.

[Complement a certain average value to ensure that the total sum remains unchanged — From SQL to SPL #3](https://dev.to/judith677/complement-a-certain-average-value-to-ensure-that-the-total-sum-remains-unchanged-from-sql-to-spl-4mn)
*   SQL code requires indirect implementation using nested subqueries and window functions, and the sequence numbers also need to be extra generated using window functions.
*   With grouped subsets, SPL code can be more natural for data processing.
