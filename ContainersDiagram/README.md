# Containers Diagram

## Primary Elements
The containers within the software system and their interactions with external software systems.

- **Application Server**: Handles business logic and interacts with external systems through the API Gateway.
- **Database**: Stores, deletes, updates, and retrieves data for the Application Server and BAnkoWeb System.
- **Notification Service**: Sends email and SMS notifications for various events, such as password changes, account settings changes, authorizations, bill payments due, statement balances, and transactional information.
- **API Gateway**: Serves as the entry point for all requests to the backend systems and integrates with external services.
- **Web Application**: Front-end interface for customers and staff, accessible via desktop, mobile, and tablet devices.
- **Mobile Application**: Native applications for iOS and Android devices, offering similar functionalities as the web application.
- **Messaging Queue**: Facilitates asynchronous communication, especially for notification services and inter-service communication.

## Supporting Elements
People and software systems directly connected to the containers.

- Customers and bank staff interact with the Application Server through the API Gateway.
- If there is a transaction with external banks, the Application Server communicates with them through the API Gateway.

## Intended Audience
Technical individuals both inside and outside of the software development team, including software architects, developers, and operations/support staff.

>
![structurizr-ContainersDiagramForBankoWeb2](structurizr-ContainersDiagramForBankoWeb2.png)
![structurizr-ContainersDiagramForBankoWeb2-key](structurizr-ContainersDiagramForBankoWeb2-key.png)


