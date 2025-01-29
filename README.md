# hello-world-
this app is developed using the ionic framework 


Steps for Creating and Configuring the Preprod Environment in Unqork
1. Creating the Preprod Environment in Unqork
1.1 Access the Admin Console:
  - Log in to Unqork and navigate to the Admin Console.
1.2 Add a New Environment:
  - Go to the Environments section and select Add Environment.
  - Name the environment as Preprod.
  - Specify the environment type (e.g., Performance Testing/Preprod).
1.3 Set the Base URL:
  - Assign the URL for the Preprod environment (e.g., https://preprod.unqork.companyname.com).
2. Configuring Required Connections in Preprod
2.1 Google Analytics
- Obtain the tracking ID for Google Analytics for the Preprod environment.
- Add the tracking ID to the relevant application configuration in Unqork.
- Verify event tracking works as expected in Preprod.
2.2 SendGrid
- Obtain the API key for the Preprod SendGrid instance.
- Go to Services > Integrations in Unqork and configure the SendGrid service with the key.
- Test email notifications from the Preprod environment.
2.3 Glia
- Update the endpoint to the Preprod Glia environment URL.
- Ensure chat and customer interaction workflows are functional.
2.4 Okta
- Set up the Preprod Okta integration with the appropriate authentication credentials.
- Update the SAML/SSO settings in the Preprod environment.
- Validate user login and session management.
2.5 Dynatrace
- Configure Dynatrace monitoring for the Preprod environment.
- Add the Dynatrace monitoring script or API to your Unqork configuration.
- Verify that application performance metrics are captured in Preprod.
2.6 TD and Canada Post
- Configure the APIs for TD and Canada Post.
- Update the credentials and endpoints for Preprod usage.
- Test the integration with mock data or staging resources provided by the respective services.
2.7 Enterprise Docustore
- Connect the Enterprise Docustore to the Preprod environment.
- Verify file uploads, storage, and retrieval functionality.
2.8 Duo Salesforce (SF EEPPerf)
- Use the EEPPerf Salesforce environment URL and API keys.
- Add integration details to Preprod using API Services in Unqork.
- Confirm data exchange between Unqork and Salesforce Preprod.
2.9 Guidewire
- Using SIT4C temporarily, configure Guidewire with the SIT4C environment for now.
- Plan to switch to GW Perf1C after March 10 as specified.
- Validate insurance-related workflows with Guidewire SIT4C.
3. Validation and Testing
After configuring all integrations:
- Perform end-to-end testing in the Preprod environment.
- Validate each integration’s functionality, ensuring seamless communication between systems.
- Fix any issues or errors identified during the testing phase.














