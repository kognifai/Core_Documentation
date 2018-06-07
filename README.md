
[<img src="./.attachments/Kognifai_H.png" width="200" hight="200">]()
# About Kognifai

Welcome to the Kognifai Software Developer Kit. Kognifai is an industrial platform for accessing data, applying advanced analytics, running applications and accelerating digitalization initiatives in your industrial world.

Kognifai is available both as an edge installable on-premise installation and as a cloud service, offering secure connectivity and application serving to your global assets.

![](https://github.com/kognifai/Kognifai/blob/master/.attachments/Kognifai.png)
 
The Kognifai ecosystem consist an IoT Platform, a sensor database, analytic services, web application framework, network infrastructure, identity management, container and hosting services, Machine Learning platform, APIs, storage and self-service management portals.

In this SDK you will find documentation and examples on how to get started developing Kognifai App, Services and Connectors. 

## [Poseidon Next – Framework](https://github.com/kognifai/PoseidonNext-Framework/blob/master/README.md)

Poseidon is the Kognifai web application framework, built on Angular, using the Kognifai Design System. It provides a fast way of developing and deploying new applications to both Kognifai Edge and Kognifai Cloud installations scenarios.

The framework takes responsibility for a range of basic features and is built in a modular way which opens up for different adaption levels.

![](https://github.com/kognifai/Kognifai/blob/master/.attachments/Posedion.jpg)
 
* Identity Management – Embedded ThinkTecture Identity Server for authentication integration to a range of ID
*	Responsive Web Design – Support for all screen sizes
*	Design System – The framework is built on the Kognifai Design System
*	Edge and Cloud support

In this SDK you will find documentation on how to write your own Poseidon applications, starting with the Poseidon Developer Edition available from https://npmjs.org and the sample application provided.

-  [Poseidon Next – Framework](https://github.com/kognifai/PoseidonNext-Framework/blob/master/README.md) 
    - [Attributions](https://github.com/kognifai/PoseidonNext-Framework/blob/master/KognifaiPoseidonNext-Attribution.pdf)
    - [Authentication Service](https://github.com/kognifai/PoseidonNext-Framework/blob/master/SDK-documentation/Authentication-Service.md)
    - [Authorization Service](https://github.com/kognifai/PoseidonNext-Framework/blob/master/SDK-documentation/Authorization-Service.md) 
    - [Common Data Service](https://github.com/kognifai/PoseidonNext-Framework/blob/master/SDK-documentation/Common-Data-Service.md)
    - [Configuration Service](https://github.com/kognifai/PoseidonNext-Framework/blob/master/SDK-documentation/Configuration-Service.md)
    - [Creating a widget](https://github.com/kognifai/PoseidonNext-Framework/blob/master/SDK-documentation/Dashboards/Creating-a-widget.md)
    - [Creating a widgets package](https://github.com/kognifai/PoseidonNext-Framework/blob/master/SDK-documentation/Dashboards/Creating-a-widgets-package.md)
    - [Developers Getting Started page](https://github.com/kognifai/PoseidonNext-Framework/blob/master/Developers-Getting-Started.md)
    - [Home and Favorites Service](https://github.com/kognifai/PoseidonNext-Framework/blob/master/SDK-documentation/Home-and-Favorites-Service.md) 
    - [Logging Service](https://github.com/kognifai/PoseidonNext-Framework/blob/master/SDK-documentation/Logging-Service.md) 
    - [Message Service](https://github.com/kognifai/PoseidonNext-Framework/blob/master/SDK-documentation/Message-Service.md)
    - [Settings Service](https://github.com/kognifai/PoseidonNext-Framework/blob/master/SDK-documentation/Settings-Service.md)
    - [Statistics Service](https://github.com/kognifai/PoseidonNext-Framework/blob/master/SDK-documentation/Statistics-Service.md) 
    - [Tools Menu Service](https://github.com/kognifai/PoseidonNext-Framework/blob/master/SDK-documentation/Tools-Menu-Service.md)
    - [Unit Of Measurement Service](https://github.com/kognifai/PoseidonNext-Framework/blob/master/SDK-documentation/Unit-Of-Measurement-Service.md)
    
    





 ## [Galore](https://github.com/kognifai/Galore/blob/master/README.md)
 
Galore is the Kognifai timeseries and streaming database available both as an on-premise installable database and as a service delivered from the Kognifai cloud. The database is highly scalable and can be installed on everything from a small edge PC to large clusters, supporting the smallest edge analytic scenarios as well as fleet wide global data collection and analytic scenarios.

This industrial quality database supports storage, analytics and distribution of most sensor like streaming data types:

*	Timeseries data – Single values, vectors or matrixs
*	Alarm & Event data – Indexed, searchable and related text values
*	Dataset – Larger dataset from high frequency analytic sensors and subsystems
*	Asset Structures – Mapping of physical industrial plants into structures, supporting templating and advanced graphs

 ![](https://github.com/kognifai/Kognifai/blob/master/.attachments/Posedion_Graph.jpg)

The Galore database is built upon the concept of streams where all data is quarriable either through the built in advanced Timeseries Query Language (TQL) or through the APIs.

In the SDK you will find detailed information on how to access and start using Galore, how to get starting using the TQL language and how to use the APIs.

## [Kognifai IoT](https://github.com/kognifai/IoT)
The Kognifai IoT Platform is an industrial solution for securely connecting, managing and integrating remote devices and systems. Targeting everything from embedded sensors to energy production facilities, the platform is capable of scaling to thousands of globally distributed on and offshore installations.

Kognifai provides self-service portals for roll out and management of customer solutions, as well as a wide range of industrial connectors ensuring safe and reliable connectivity with data sources on the edge. Common connectors available on Kognifai are OPC UA, OPC DA / HDA, ModBus among others.

This SDK will provide you with documentation and samples on how to build your own custom connector if you need to integrate with a system which does not support these standard industrial interfaces.

 ![](https://github.com/kognifai/Kognifai/blob/master/.attachments/IoT.png)

The Connectors feeds the Kognifai Edge Gateway which is responsible for buffering of data in the case of connectivity loss, for compression and for securely authentication and transport encryption to the Kognifai cloud endpoints:

-	Secure and reliable transfer of data from the edge to the cloud using AMQP, MQTT or HTTPS over TLS
-	Authentication towards the Kognifai cloud services using certificates or shared secrets
-	Buffering of data to disk supporting offline scenarios
-	Reliable transfer of data over unreliable communication channels
-	Logging, health and security data reporting

 
### [Infrastructure](https://github.com/kognifai/Infrastructure/blob/master/README.md#infrastructure_documentation)

The Kognifai platform provides infrastructure both for Edge and Cloud, as well as the secure connectivity needed between sites, edges, cloud and other platforms.

![](https://github.com/kognifai/Kognifai/blob/master/.attachments/Infrastructure.jpg)

