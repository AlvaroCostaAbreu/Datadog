# Datadog Service Catalog Integration Sample

**This is a json sample based on v2 Datadog Service Catalog Integration [Oficial Documentation](https://github.com/DataDog/schema).**

## Integrated Features 
- Contacts
  - Slack
  - E-mail
  - Microsoft Teams
- Documentation
- Source Code
- Runbooks
- Dashboards
  - Using template variables
- Tags

## Using
To apply this json you need to submit a post request in Datadog API, to test this you can use this curl request:

` 
  curl -X POST "https://api.datadoghq.com/api/v2/services/definitions" -H "Content-Type: application/json" -H "DD-API-KEY: <YOUR-API-KEY>" -H "DD-APPLICATION-KEY: <YOUR-APLICATION-KEY>" -d @- << EOF
  {json element}
  EOF
`


![ServiceCatalogExample](./ServiceCatalogSample.png)


# Documentation 
* [Product Overview](https://docs.datadoghq.com/tracing/faq/service_catalog/)
* Setting up Service Catalog as an APM customer [Setting up Service Catalog as an APM * customer
* Setting up Service Catalog as a non-APM customer [Setting up Service Catalog as a non-APM customer
* Service Catalog API : Registering Services through the Datadog Service Definition API
* Integrations 
* JSON Schema Store 
* Troubleshooting 
* Guides
