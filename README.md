🚀 Introduction
Ever wondered how different software components talk to each other? They use APIs! Just completed my Postman certification and I'm super excited to share what I've learned. Here's a snapshot of how APIs bridge different applications:
•	Hardware API for apps to talk to your camera 📸
•	Software library API for image processing 🎨
•	Web API for sending images to servers for all those likes 👍
________________________________________
🔍 Architecture Types
APIs come in various flavors, each with its unique strengths:
•	REST (Representational State Transfer): A set of constraints that ensures stateless operations, making it easy to scale and reliable.
•	GraphQL: A query language for your API, it allows clients to request only the data they need.
•	WebSockets: Provides full-duplex communication channels over a single TCP connection, allowing real-time data transfer.
•	webhooks: User-defined HTTP callbacks that react to specific events.
•	SOAP (Simple Object Access Protocol): A protocol with predefined rules for structuring messages, typically used in enterprise settings.
•	gRPC (Google Remote Procedure Call): Uses HTTP/2 for transport, Protocol Buffers as the serialization format.
•	MQTT (MQ Telemetry Transport): A lightweight messaging protocol for small sensors and mobile devices.
________________________________________
🌐 API Accessibility
APIs can be categorized based on their accessibility:
•	Public APIs: Open for the world, they can be discovered and consumed by any developer out there.
•	Private APIs: These are the internal workhorses, consumed within an organization and shielded from external access.
•	Partner APIs: A bridge between organizations in a partnership, facilitating collaboration.
For instance, Instagram's API that fetches user photos is a RESTful public API!
In the course we will be using Public, REST, Web API 👀
________________________________________
✍️ Postman in Action
Here's how to make the most of Postman's features:
1.	Create a Workspace: Think of it as your personal playground to test and develop APIs.
2.	Create a Collection: Organize related requests together. It's like a folder for your API calls.
3.	Add Request: Specify the kind of operation you want, be it GET, POST, PUT, or DELETE. Remember, PUT generally replaces an entire resource, whereas PATCH typically updates parts of a resource.
________________________________________
💡 Supercharging with Variables
Tired of typing the base URL repeatedly? Use variables in Postman!
•	Replace values, especially sensitive ones.
•	Access them with curly braces: {{variableName}}
________________________________________
🔗 Query Parameters and Path Variables
•	Query Parameters: These are the extra knobs and dials for your API calls. They fine-tune the request based on key-value pairs and are appended to the URL after a ?, separated by &.
•	Path Variables: They pinpoint specific resources in your API calls. For instance, /users/{id} might target a user with a specific ID.
________________________________________
📃 HTTP Request Methods
Beyond just fetching or sending data, HTTP methods dictate the kind of operations:
•	POST: Create a new resource.
•	GET: Retrieve existing data.
•	PUT: Update or replace an existing resource.
•	DELETE: Remove a resource.
Think of these methods as the "address" on your envelope, guiding how the data inside should be treated.
________________________________________
🎭 Variables and Scripting
Unlock the power of automation in Postman:
•	Variable Scopes: Local, global, environment, data, local-specific.
 
•	Scripting in Postman: Supercharge your API calls by adding dynamic behaviorPre-request scripts: Executed before a request is sent.Test scripts: Run immediately after receiving a response.
Harness the pm object in Postman to access, set, or modify variables dynamically
________________________________________
🔐 Authorization: Ensuring Secure API Interactions
In the realm of APIs, 'Authorization' is paramount. Here's a brief on the methods I explored with Postman:
•	Basic Auth: Uses a username and password combination. 
•	OAuth: Offers delegated authorization. 
•	API Keys: Secret strings given to a developer from an API portal.These methods ensure that our API interactions are not just efficient but also secure.
________________________________________
📜 Postman's Codegen Feature
Ever wanted to integrate your API calls directly into your app? Postman's codegen feature translates your API requests into code snippets in various languages, easing integration.
