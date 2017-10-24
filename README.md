# Digital Platform- Example Architectural Epics

## Channel

- For developers who need to implement solutions that work over many different technical channels (e.g. web, mobile) the platform offers them services (which are frameworks and shared services) that provide support for developing user interfaces that can work on each channel. Unlike the standard approach of developers finding and installing the required frameworks and tools, the platform provides a standardized and easy to access service for this.
- For developers of systems that require user interaction (e.g. from customer) the platform provides an identity service that maintains a unique identity for the user (independent of the process and application) and controls access to the services individual for the user. Unlike a standard IAM solution, the platform also maintains a list of which digital services the user has the right to access that can be dynamically changed based on user interaction (for instance, a customer has signed up for a service).
- For developers who have to develop systems that maintain long term processes, the platform offers services that allows users to start processes, rejoin processes at a later date., allow different users to join and progress the processes (e.g. customer support staff). Unlike typical BPM solutions the processes can be started and rejoined from any channel and are customer centric.

## Experience

- For developers developing applications that use sensor data, the platform provides the means to manage the sensors, receive data from the sensors, and process the data.
- For developers developing applications that use sensor data, the platform  provides the means to connect to external platforms that manage and receive the data from the sensors.
- For developers that require the use of augmented reality, the platform offers services that can combine real time video feeds with information from other sources and also provides means to detect features in the video stream.
- For developers who wish to improve the user experience, the platform provides services that allow features to be switched in and out for different user groups and thus enable A/B testing.
- For developers that need to develop applications that require knowledge of the spatial position of the user, the platform provides services to receive location and direction information and map this to information stored in other systems.

## Empowerment

- For Internal staff, partners and customers who need to collaborate the platform provide services that allow them to have shared repositories of rich documents, collaborate in real time on rich documents, structure and find rich documents, group users together and allow them to communicate using voice and video.
- For partners who form part of extended processes the platform offers managed APIs that can be accessed securely by them. Unlike a simple interface (e.g. over file transfer), the APIs allow the user the extend processes and as such be part of the ecosystem.
- For partners who wish to develop systems that extend processes and applications, the platform offers APIs that allow them to access internal data and functionality and offer value added services to customers. Unlike a fixed contract with the partner the platform should allow more flexible contractual  forms (such as payment based on usage) with the intent to foster the development of an ecosystem.
- Provide the functionality and information required for a task closer to where the task is performed.

## Information and Insight

- For data scientists who implement applications to do data analysis of the data provided by source systems the platform stores the data that originates from source systems during the execution of processes and provides means to process the ingested data to other forms that are more amenable to analysis (e.g. extract summaries, change the form of the data, generate meta-data). Unlike a simple BI solution the platform provides this functionality as a service that can be used on a on-demand basis.
- For compliance officers who need to ensure that the data has not been changed the platform provides immutable data stores as a service that ensures that regulatory requirements are met.
- For data scientists who need to work with the data the platform provides ingestion pipes from applications and external data sources that can be connected to from data analysis tools.
- For data scientists and compliance officers who analyze the data from various sources (including personal and confidential data) the platform provides services to encrypt data, both at-rest and in-motion so that data classification and security requirements are fulfilled.
- For developers who design and implement systems the platform provides facilities for them to be able to expose data services that can be subscribed to in a secure way.
- For developers implemented advance systems with AI capabilities, the platform provides means to configure, train and run neural networks.

## Agility
- For developers who have to implemnt new product ideas the platform offers a set of tools to support an agile dvelopment, including agile project tracking, epic and use case tracking, source control management, testing, version and configuration  control, service design, build management, continuous integration.
- For developers who need to use standard services the platform can provide these on a self-service basis over APIs. These services are _(to be done)._
- For developers who need standard technology stacks for development, the platform is a central point for obtaining these on a self service basis so that they can be quickly used. Unlike a typical installation of these, the platform provides and runs the complete run time environment for the technology stacks. The technology stacks provided are _(to be done)_.
- For development managers who have teams using the platform and for the operators of the platform, the platform provides change-back / show-back mechanisms based on the usage of the services.
- For staff who operate the platform, facilities are provided to automatically scale up with increased demand and to scale down when the demand decreases.
- For platform operators, who need to offer services that are not yet available on the platform (or it is not cost effective to have them), the platform offers breakage to third-party providers of that service.
- For developers implementing systems using highly componentized architectures (e.g. with microservices) the platform provides facilities to deploy, manage, run and scale those components.
- For operators of the platform, facilities are provided for automation of the operations.
- For users of service which use the platform, the platform provides controlled access to the services from anywhere over the internet.
