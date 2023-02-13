## February 2023

### Updates

- [Developing Azure Functions using the v2 programming model for Python | Azure Friday](https://youtu.be/KARieaWBxuk)[19]
    > Gavin Aguiar and Shreya Batra join Scott Hanselman to discuss the v2 programming model for Azure Functions using Python.
    - Comprehensive overview over the simplified v2 programming model and how quick deployments can be done through Visual Studio Code.

- Announcements of [the latest beta release of the Azure Text Analytics client libraries for Python](https://devblogs.microsoft.com/azure-sdk/announcing-the-new-beta-release-of-azure-text-analytics-libraries/) [18]. The blog post highlights Python samples for these features:
    - Abstractive summarization
    - Named entity recognition (NER) resolutions
    - Dynamic classification
    - Healthcare FHIR bundles with document type
    - Automatic language and script detection

    
    > **Note**
    >
    > If you follow the example along:
    > - you may need to create the cognitive services account in the right region, otherwise you might be seein errors like this when attempting to run the code: `{'code': 'InvalidRequest', 'message': "Job task: 'AbstractiveSummarization-0' failed with validation error: Document abstractive summarization is not supported in the region {Your-Region}. The supported regions are North Europe, East US, UK South."}`
    > - you may need to request access at https://aka.ms/applyforgatedsummarizationfeatures if the service is part of a gated public preview feature.


- Azure Developer CLI (azd) includes [new templates for Python](https://devblogs.microsoft.com/azure-sdk/azure-developer-cli-azd-february-2023-release/#python) [14].
    - [Deploy a Python (Flask) web app with PostgreSQL in Azure](https://github.com/Azure-Samples/msdocs-flask-postgresql-sample-app) [15]
    - [Deploy a Python (Django) web app with PostgreSQL in Azure](https://github.com/Azure-Samples/msdocs-django-postgresql-sample-app) [16]
    - [HTTP API powered by FastAPI with Azure Functions and APIM](https://github.com/pamelafox/fastapi-azure-function-apim) [17]

- Not really a February update but a reminder:
    > On 31 March 2023, [Microsoft] will be retiring support for Azure SDK libraries which do not conform to [their] current Azure SDK guidelines.
    <br>&mdash; <cite>[Azure Updates](https://azure.microsoft.com/en-us/updates/support-for-azure-sdk-libraries-that-do-not-conform-to-our-current-azure-sdk-guidelines-will-be-retired-as-of-31-march-2023/)</cite>[12]
    - Here is the [list of deprecated Python libraries](https://azure.github.io/azure-sdk/releases/deprecated/index.html#python) [13]

- [February 2023 release of the Python and Jupyter extensions](https://devblogs.microsoft.com/python/python-in-visual-studio-code-february-2023-release/) for Visual Studio Code are now available [11].

### References

| # | Title | URL | Accessed-On |
| --- | --- | --- | --- | 
| 11 | Python in Visual Studio Code – February 2023 Release | https://devblogs.microsoft.com/python/python-in-visual-studio-code-february-2023-release/ | 2023-02-03 |
| 12 | Update your Azure SDK libraries by 31 March 2023 | https://azure.microsoft.com/en-us/updates/support-for-azure-sdk-libraries-that-do-not-conform-to-our-current-azure-sdk-guidelines-will-be-retired-as-of-31-march-2023/ | 2023-02-06 |
| 13 | Python - Deprecated Libraries | https://azure.github.io/azure-sdk/releases/deprecated/index.html#python | 2023-02-06 |
| 14 | Azure Developer CLI (azd) – February 2023 Release - Python Templates | https://devblogs.microsoft.com/azure-sdk/azure-developer-cli-azd-february-2023-release/#python | 2023-02-09 |
| 15 | Azure Samples - Deploy a Python (Flask) web app with PostgreSQL in Azure | https://github.com/Azure-Samples/msdocs-flask-postgresql-sample-app | 2023-02-09 |
| 16 | Azure Samples - Deploy a Python (Django) web app with PostgreSQL in Azure | https://github.com/Azure-Samples/msdocs-django-postgresql-sample-app | 2023-02-09 |
| 17 | HTTP API powered by FastAPI with Azure Functions and APIM | https://github.com/pamelafox/fastapi-azure-function-apim | 2023-02-09 |
| 18 | Announcing the new beta release of Azure Text Analytics libraries | https://devblogs.microsoft.com/azure-sdk/announcing-the-new-beta-release-of-azure-text-analytics-libraries/ | 2023-02-10 |
| 19 | Developing Azure Functions using the v2 programming model for Python - Azure Friday | https://www.youtube.com/watch?v=KARieaWBxuk | 2023-02-11 |

## History

- [Updates from January 2023](2023-01.md)
