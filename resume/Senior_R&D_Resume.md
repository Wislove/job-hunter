#  Senior R & D Engineer

## 📞 Personal Information
- **Email**: 975385373@qq.com
- **Date of Birth**: Sep 1992
- **GitHub**: [https://github.com/wislove](https://github.com/wislove)
- **Work Experience**: 9 years (Java full - stack development, DevOps, familiar with GO and Node.js full - stack development)
- **Job Seeking Intention**: Senior R & D Engineer
---
## 🎓 Educational Background
- **Southwest University (211)** - Bachelor of Software Engineering (Sep 2012 - Jun 2016)
- **Language Proficiency**: Proficient in reading English technical documents
---
## 🛠️ Technical Skills
### **Core Area (Java)**
- 9 - year full - time Java development experience. Familiar with JVM (used jstack and arthas to troubleshoot GC issues), concurrent programming, Spring Boot, Spring Cloud, and Spring Cloud Alibaba microservice systems and related middleware.
- Familiar with Mysql and Redis (standard for projects, familiar with relevant data consistency solutions and high - availability architectures); Have knowledge of Mongodb (mainly used for file and log storage); Have knowledge of ElasticSearch (mainly used for log storage); Have knowledge of Dameng (mainly for domestic adaptation of DM8.0 database).
- Familiar with **Redis** (mainly used for caching, also used for full - text search and distributed locks, familiar with the basic modules of Redisson), **Kafka** (mainly used for asynchronous processing of big data platform tasks), **RocketMQ** (mainly used for business system message queues, familiar with transaction message queues).
- Familiar with basic Nginx configuration, load balancing, and rate limiting. Configured the Nginx_Lua module for traffic forwarding and defense against DDoS network attacks.
- Familiar with distributed system design, distributed transactions, distributed locks, and sharding and partitioning design. Built a distributed Pass platform and is familiar with relevant components such as Nacos, Zookeeper, Sentinel, Zuul, and Mycat.
- Familiar with the integration of Jpom and Jenkins with Gitlab CI/CD, and the integration of Docker for continuous integration and continuous delivery. Familiar with build tools such as Maven and Gradle.
- Familiar with ERP and OA systems, and customizing the Activiti workflow. Have experience in Internet of Things (IoT) development, familiar with various protocols such as MQTT, Modbus, and PLC. Have experience in big data platform development, familiar with BI, data stream processing, and data visualization. Familiar with Alipay and WeChat payment processes.
### **Other Areas**
- **Front - end**: Familiar with React and Antd, functional components, Redux, and Umi. Developed management systems and portal homepages. Used Uniapp to develop tool - integrated mini - programs and APPs.
- **Golang**: Built the background of a personal project using Gin, Gorm, and Mongodb. Familiar with basic CRUD operations, exception handling, Channels, and basic container library operations such as Docker and K8s.
- **Node.js**: Wrote a game assistant using Node.js. Familiar with **ProtoBuf** and **GRPC**. Used NestJS and React for full - stack development and built a personal blog project. Familiar with async/await and Promise in Node.js.
- **Kubernetes**: Built a Kubernetes cluster on a public - network server and provided services. Familiar with Sealos for installing Kubernetes clusters, writing Yaml configuration files, and using Helm to install applications. Familiar with basic Pod commands and the configuration of PV and PVC data persistence for Redis and Mongodb. Continuously learning.
- **Lua**: Reverse - engineered a mini - game, studied the game framework Skynet, and learned the basic syntax of the Lua language and the use of LuaRocks.

## 💼 Work Experience and Key Projects

### **Sichuan Hongxin Software Co., Ltd. - Software R & D** (Dec 2018 - Present)
#### 1. Nanchong Intermediate People's Court Park Intelligent Security Project (IoT)
- **Technology Stack**: Java 11, Spring Boot, Spring Cloud, Kafka, Redis, Netty, Emqx, Mongodb
- **Business Description**: Supports data collection and unified management of over 2000 intelligent devices in the whole court, processes over 1 million device events per day on average, performs intelligent analysis and alarm, provides video security, plans intelligent patrol routes, and offers 3D map visualization and digital twin.
- **Responsibilities**: Technical leader (lead programmer, coordinating and arranging development work)
- **Achievements**:
    - Built and designed the platform from scratch, integrated intelligent devices from Hikvision, Honeywell, Hisense, etc., directly connected to devices or platforms, and realized unified data collection, display, and device control.
    - Built an intelligent out - of - band monitoring platform based on IPMI, RedFish, SNMP, etc., and an in - band application monitoring platform based on Prometheus and Grafana to comprehensively monitor computer room hardware and related application software, improving operation and maintenance efficiency and reducing the annual failure rate to less than 2 hours.
    - Built an EMQX cluster to handle MQTT - protocol devices, increasing the TPS of a 4c8g single virtual machine from 600 to 1000.
    - Used Netty to build a basic network module to uniformly access device protocols such as MQTT, Modbus TCP, Bacnet/IP, PLC, TCP, and Modbus RTU.
    - Used dynamic Jar loading and online dynamic JS scripts to realize unified mapping and conversion of device data, reducing the amount of coding for data mapping.
    - Based on Node - Red secondary development, realized a dynamically configurable rule engine, scenario linkage, and customizable functions such as choreographed processes, simplifying problems related to device differences and protocol differences and reducing hard - coding.
    - Used ffmpeg to convert different rtsp, rtmp, etc. video streams into playable streams such as hls and mp4, uniformly managed intelligent video devices from Hikvision and Dahua, built a video wall module, and used the nginx - hls - module to build a video stream service module to achieve load balancing of video services.

#### 2. Smart Community/Smart City Project
- **Technology Stack**: Java 11, Spring Boot, Spring Cloud, Kafka
- **Business Description**: Starting from the community, based on intelligent devices and grid management, constructs urban security and improves residents' self - governance.
- **Responsibilities**: Java back - end development and operation and maintenance development
- **Achievements**:
    - Designed and implemented a basic security video wall platform and a fire warning platform based on intelligent security devices, cameras, and fire - fighting equipment, improving data visualization capabilities.
    - Connected to public security data, built a special population database, and intelligent portraits. Based on cameras, drew movement trajectories on a 3D map, realizing dynamic controllability and management and reducing management costs.
    - Used Kafka as a message bus to build a device message transfer module, improving data throughput.
    - Developed with Gaode GIS maps, connected relevant maps, developed a 2.5D map, presented digital digestion and power - related platforms, and used coordinate points to intelligently plan patrol routes, improving patrol and intelligent security efficiency.

#### 3. Zhongtai Chemical Intelligent ERP System (and the incubated SaaS base)
- **Technology Stack**: Java, Spring Cloud, Spring Boot, Redis, Kafka, ShardingSphere, Neo4j
- **Business Description**: Enterprise - level management platforms such as ERP, SRM, inventory management, contract management, intelligent finance, and supply chain (multi - tenant design)
- **Responsibilities**: Back - end application development
- **Achievements**:
    - Designed and implemented a unified authentication and authorization center for core modules. Adopted Redis distributed session management. Through database index configuration and Redis caching, reduced the authentication response time from 1s to 300ms.
    - Based on Activiti 5.22, transformed the workflow module to realize functions such as process rollback, rejection to any node, jump, and countersignature, making the process more flexible.
    - Independently implemented modules such as contract similarity analysis and keyword extraction using the cosine similarity algorithm and a word segmentation tool, with a similarity analysis accuracy rate of 75%.
    - Used Mysql binlog to realize data cold - hot separation and archive data of completed processes, optimizing data query efficiency and improving query speed.
    - Used Neo4j to build a knowledge graph for personnel and finance modules, reducing the error rate and rejection rate of documents by 30%.
    - Utilized Kafka and Jpa for data auditing to realize a data auditing module, including functions such as historical change records of documents and field changes, and abstracted common modules.
    - Designed and implemented a distributed lock module based on Redis to solve the problems of interface idempotence and duplicate submissions in concurrent mode.
    - Designed and implemented a distributed transaction module based on Seata to solve the problem of strong data consistency across multiple services, and added a business compensation module to achieve final data consistency within 5s.

#### 4. China Copper Big Data Development Platform and Data Governance Project
- **Technology Stack**: Java, Redis, Kafka, Hive, Hadoop, Hbase, Spark
- **Business Description**: Full - domain indicator management and data governance, ETL, data development, and large - screen BI
- **Responsibilities**: Back - end application development and data development
- **Achievements**:
    - Participated in the development of a Web - based visual ETL function, with drag - and - drop configuration and adaptation to multiple data sources, reducing the difficulty of use.
    - Participated in building an AI question - answering module, encapsulating the details of LLM docking based on LangChain4j to simplify business call difficulty and improve development efficiency.
    - Through the analysis of Hive operation logs, adopted ORC format optimization and dynamic partitioning strategies to improve Hive data insertion efficiency, reducing the single - task execution time from 2h to 1.2h.
    - Helped a central enterprise implement data governance and big data applications, improving data governance capabilities, accurate monitoring, and reducing the abnormal data rate by 35%.
    - Used FineReport BI tools to help implement data large - screens, BI reports, and data analysis, improving operational efficiency.
---
### **Chengdu Guanxintang Technology Co., Ltd. - Java Engineer** (Aug 2016 - Dec 2018)
#### 1. Guanxintang Chronic Disease Management APP Platform
- **Technology Stack**: Java 8, Spring Boot, Jquery, MySQL
- **Responsibilities**: Java back - end development, Android development, and H5 page development
- **Achievements**:
    - Participated in building a distributed back - end architecture based on Spring, Dobbo, Mycat, ZooKeeper, ActiveMQ, and Memcached, realizing the platform from scratch.
    - Built a cache center module based on Memcached and memory to achieve a high - performance cache center.
    - Participated in the development of a distributed transaction module based on the TCC mode to ensure transaction and data consistency between the order module and the payment module.
    - Participated in the development of a distributed lock module encapsulated based on ZooKeeper. Used Jmeter for stress testing, transformed the lock method, reduced the lock granularity, and improved performance by 20%.
    - Led the development of the payment module, connected to Alipay, WeChat, UnionPay, WeChat official account development, and H5 payment functions. Used a dual - guarantee mechanism of event notification and active query to ensure the consistency of payment information.
    - Led the development of the operation module, realized the rapid launch of operation activities through dynamic modules and online page choreography, improved operation efficiency, and assisted the data analysis module for accurate operation activity placement.
---
## 🚀 Personal Projects
### **Reverse Automation Assistant for a Mini - Game** - Independent Development (Since 2024 - Present)
**Technology Stack**: NodeJS, ProtoBuf, Grpc, Golang, React, Mongodb, Redis, ElasticSearch, Docker, kubernetes

**Highlights**:
- Used Frida, Magisk, and LSPosed to reverse - engineer a mini - game APP, find so files, and capture relevant wss data.
- Built a game business assistant platform based on NodeJs from scratch to automate game business functions.
- Expanded the business modules based on NodeJs from 1 to 100, built a back - end module based on Golang and Mongodb, and a front - end platform based on React for easy business use.
- Built a distributed platform framework based on Redis, ElasticSearch, Grpc, and kubernetes from 100 to 1000, realizing dynamic horizontal scaling, load balancing, smooth business growth, unified machine management, and a 40% reduction in machine management costs.
- Managed 50 public - network servers, connected the public - network server network with WireGuard, migrated from Docker deployment to kubernetes, installed the kubernetes cluster with Sealos, installed applications with Helm, and used k8s to solve multi - machine expansion problems, achieving unified management and saving management costs.
- Used the pruning depth - first search algorithm combined with AI to implement an automatic algorithm for the intelligent 2048 mini - game and achieved a high score.
- Independently compiled the nginx - lua module, wrote lua scripts to implement custom rate limiting, and compiled them into Nginx to improve service availability.
---
## 🔥 Personal Advantages
9 - year full - stack experience, with a deep passion for technology. Have a wide range of technical knowledge and like to use technology to solve practical problems. Focus on the practicality of technology, reject fancy features, and aim for implementation, delivery, and generating benefits, doing valuable things.