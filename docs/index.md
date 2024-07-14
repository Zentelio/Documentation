<p align="center">
    <img src="assets/banner.png" width="300">
</p>

## What is Zentelio
Zentelio is a low-code framework designed for developing workflows in applications, services, and systems using a trigger-action-connector. 
Although Zentelio is written in Java, it is not necessary to know this language, as Zentelio operates based on Json, Yaml, and ZScript for constructing workflows. If required, plugins can be created in Java to incorporate new elements into Zentelio.

## Uses of Zentelio
<img src="assets/WorkflowExample.png" alt="WorkflowExample" width="300" height="275" align="left">

Zentelio can be utilized in a variety of scenarios. Below are detailed examples in different domains: 

**Order Management** 
In a company that needs to automate order management, Zentelio can establish a workflow that activates upon receiving an order, verifies available inventory, notifies the sales team, and generates a shipping order.

**IT Infrastructure Management** 
In the IT domain, Zentelio can be employed for infrastructure management, activating maintenance and monitoring actions in response to specific system events. For instance, upon detecting a potential server failure, it can execute a diagnostic script, send alerts to the support team, and schedule a maintenance task if necessary. 

**Automated Marketing**
In marketing, Zentelio can coordinate automated campaigns. A trigger such as a newsletter subscription can initiate a series of actions, including sending welcome emails, updating customer databases, and segmenting new subscribers for future personalized campaigns. 

**Data Science** 
In the field of data science, Zentelio can automate analytical and modeling processes. For example, it can receive real-time data from various sources, automatically clean and preprocess the data, train predictive models based on the received data, and generate and send reports with analysis results to stakeholders. 

**Artificial Intelligence** 
For artificial intelligence applications, Zentelio can manage the deployment and maintenance of AI models. For instance, it can detect new updates in training data, retrain AI models automatically, deploy the new models to production, and monitor model performance, adjusting parameters in real-time if necessary. 

**API Integration**
In API integration, Zentelio can facilitate communication between different systems and services. For example, it can receive data from an external API, transform the data according to internal system requirements, send the transformed data to a database or another API, and manage errors and retries automatically in case of communication failures.

## Trigger-Action-Connector Model 
The trigger-action-connector is a model used to design and execute automated workflows in applications such as Zentelio. This model is based on three fundamental components: 

**Trigger** 

The event that initiates the workflow. Triggers can be internal (within the system) or external (events originating from other applications or services).

Example: The arrival of a new email, the creation of a file in a specific folder, the reception of a message in a message queue, among others.

**Action**

The task or set of tasks executed in response to the trigger. Actions are the operations that make changes or process data.

Example: Sending an email, updating a database, calling an external API, moving a file to another location, etc.

**Connector** 

The intermediaries that enable communication between Zentelio and other services or applications. Connectors facilitate both the reception of events (triggers) and the execution of actions in different environments.

Example: Connectors for email services, databases, web services, cloud storage, social media, etc.

## ZScript Introduction
