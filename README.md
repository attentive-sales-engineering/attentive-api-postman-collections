# attentive-api-postman-collections
 
Attentive’s APIs allow you as a developer to integrate with the Attentive platform and build custom applications. Use our numerous endpoints to manage user subscriptions, trigger messages related to user actions, save subscriber attributes, and send personalized text messages.

This repo contains Attentive API Postman Collections in json format.

- Attentive Rest API
- Attentive GraphQL API

## Instructions for using in Postman

1. Download and import the Postman Collections by clicking the following links
   - [Attentive REST API](https://app.getpostman.com/run-collection/24320149-bc0db337-4f59-4c71-af0c-10cbf508bf63?action=collection%2Ffork&collection-url=entityId%3D24320149-bc0db337-4f59-4c71-af0c-10cbf508bf63%26entityType%3Dcollection%26workspaceId%3D779a6b8f-cf0f-43cd-a280-af5fcbb64f2c)
   - [Attentive GraphQL API](https://app.getpostman.com/run-collection/24320149-0f0e96d4-db01-433d-a34f-f1eb2510f63d?action=collection%2Ffork&collection-url=entityId%3D24320149-0f0e96d4-db01-433d-a34f-f1eb2510f63d%26entityType%3Dcollection%26workspaceId%3D779a6b8f-cf0f-43cd-a280-af5fcbb64f2c)
2. In Postman, click on the Environments tab in the left sidebar and create environment variables to use for testing:
   1. `phone` - Your mobile phone number in E.164 format (e.g. `+12065551212`). Required for most API calls.
   2. `email` - Your email address. Optional for most API calls.
   3. `signUpSourceId` - a required ID for using the [Subscribers API](https://docs.attentive.com/openapi/reference/tag/Subscribers/#tag/Subscribers/operation/addSubscriptions)
   4. `clientUserId` - an optional external identifier for various APIs.
