# Summary Data Engineer news at February 22nd 2025, 9:00:15 am
## Summary content

This summary covers a range of data engineering topics. It starts with implementing MLOps within data engineering workflows, emphasizing version control, experiment tracking, CI/CD pipelines, model monitoring, and governance. It also discusses how "ghost models" in dbt projects can break deferral and slow down CI jobs, advising users to disable these unused models. Next, it addresses advanced data governance in hybrid and multi-cloud environments, highlighting the importance of clear policies, data cataloging, quality management, privacy, security, and seamless data integration. The summary continues by comparing SQL and SPL for a specific data processing task, demonstrating SPL's simpler approach with grouped subsets. Furthermore, it introduces Envio, a tool for streamlining indexer setup with a no-code solution for blockchain developers. Finally, it provides resources for Azure Data Engineering and offers strategies for extracting data from Cloudflare-protected websites, including bypassing CAPTCHAs.

## Posts main ideas
[Implementing MLOps within Data Engineering Workflows for Efficient Machine
Learning Model Deployment](https://dev.to/flnzba/implementing-mlops-within-data-engineering-workflows-for-efficient-machine-learning-model-deployment-10e1)
*   MLOps streamlines ML model deployment through version control, experiment tracking, and automated CI/CD pipelines.
*   Model monitoring, retraining, and governance ensure models remain effective and compliant.

[Ghost models and spooky manifests in dbt](https://dev.to/panasenco/ghost-models-and-spooky-manifests-in-dbt-o78)
*   Ghost models (models that exist but are not materialized) can break deferral in dbt and slow down CI jobs.
*   The solution is to disable these ghost models to ensure slim CI works correctly.

[Implementing Advanced Data Governance in Hybrid and Multi-Cloud Environments](https://dev.to/flnzba/implementing-advanced-data-governance-in-hybrid-and-multi-cloud-environments-10nk)
*   A robust data governance framework is crucial for managing data across hybrid and multi-cloud environments, including defining policies, assigning data stewards, and implementing data cataloging.
*   Effective data integration, security, privacy, and quality management are essential for compliance and operational efficiency.

[Complement a certain average value to ensure that the total sum remains
unchanged — From SQL to SPL #3](https://dev.to/judith677/complement-a-certain-average-value-to-ensure-that-the-total-sum-remains-unchanged-from-sql-to-spl-4mn)
*   SPL provides a simpler and more natural approach compared to SQL for tasks involving grouped subsets and rule-based field additions.

[Streamline Your Indexer Setup with Envio](https://dev.to/envio/streamline-your-indexer-setup-with-envio-465p)
*   Envio offers a no-code solution for quickly setting up blockchain indexers with guaranteed type safety.

[Azure Data Engineering Books from #Techtter YT Channel](https://dev.to/techtter/azure-data-engineering-books-from-techtter-yt-channel-2j9b)
*   Techtter YouTube Channel provide Data Engineering books that across web, youtube and social media platforms.

[How to Extract Data from a Cloudflare-Protected Website](https://dev.to/luisgustvo/how-to-extract-data-from-a-cloudflare-protected-website-3g49)
*   Bypassing Cloudflare's protections requires a combination of proxies, browser automation, and CAPTCHA-solving tools.
*   Emulating human-like interactions, rotating IP addresses, and utilizing AI-powered CAPTCHA solutions like CapSolver are key strategies for successful data extraction.
