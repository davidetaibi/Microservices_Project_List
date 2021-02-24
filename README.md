#  A curated list of Open Source projects developed with a microservices architectural style

## Table of Contents
* **[Introduction](#Introduction)**
* **[How to Reference this dataset](#How-To-Reference-this-Dataset)**
* **[Demo and Toy Projects](#demotoy--projects-mainly-for-learning-purpose)**
* **[Projects not available anymore](https://github.com/davidetaibi/Microservices_Project_List#not-available-anymore)**
* **[Industrial or production-ready projects](https://github.com/davidetaibi/Microservices_Project_List#industrial-projects-created-from-scratch-with-a-microservices-architectural-style)**
* **[Acknowledgements](#Acknowledgements)**
* **[References](#References)**


## Introduction
After several questions opened in Quora[4,5,6], StackOverflow [2,3], ResearchGate [1], I decided to report the list of projects that migrated to microservices or that are implemented from scratch with a microservice architectural style.
In our previous work, we investigated several microservices issues, including migration issues[10], architectural patterns[9],  and bad smells or antipatterns[8]. The availability of a common data-set of projects implemented with a microservice architectural style, would be very useful to validate our results, but also to anyone who need to learn how to develop microservices-based applications or to researchers that want to study how these systems are architected.


The list could be useful to anyone who need to learn how to develop microservices-based applications or to researchers tha  t want to study how these systems are architected.
If you are interested to the Architecture related principles, tools and technologies, please consider this github page https://github.com/mfornos/awesome-microservices

I am still  looking for a real legacy project (5-10 years old) where I can study how it evolved from Monolithic to microservices. I think this is a common issue of most of the researchers working on microservices, and if we will manage to find at least one, it could be a very good starting point.




Feel free to contribute suggesting other projects.
You can send recommendations for new projects making a pull request to this page, or sending an email to davide [dot] taibi [at] tuni [dot] fi

## How To Reference this Dataset

Rahman, Mohammad Imranur  and Panichella, Sebastiano and  Taibi, Davide. "A curated Dataset of Microservices-Based Systems" Joint Proceedings of the Inforte Summer School on Software Maintenance and Evolution. CEUR-WS, vol. 2520, pp.1-9. Tampere, Finland. 2019

```@inProceedings{Rahman2019ACD,
  title={A curated Dataset of Microservices-Based Systems},
  author={Rahman, Mohammad Imranur  and Panichella, Sebastiano and  Taibi, Davide},
  booktitle={Joint Proceedings of the Inforte Summer School on Software Maintenance and Evolution}, 
  publisher = {CEUR-WS},
  year={2019},
  volume={Vol-2520},
}
```


## Demo/Toy  Projects, mainly for learning purpose


| Name  | Link | Languages | Framework | Number of microservices
| ------------- | ------------- | ------------- | ------------- | ------------- |
| ACME Air: | [link](https://github.com/acmeair/) | Javascript | nodejs | |
| Beer catalog (Spring Boot) | [link](https://github.com/oktadeveloper/spring-boot-microservices-example) | Java | Spring | |
| Blog post (Spring Boot) | [link](https://github.com/fernandoabcampos/spring-netflix-oss-microservices) | Java | Spring | |
| CAS Microservice (Portuguese) | [link](https://github.com/ArcanjoQueiroz/cas-microservice-architecture) | Java | Spring | |
| Cinema Administration: | [link](https://medium.com/@cramirez92/build-a-nodejs-cinema-microservice-and-deploying-it-with-docker-part-1-7e28e25bfa8b) | Javascript | nodejs | |
| CQRS microservice application: | [link](https://github.com/benwilcock/cqrs-microservice-sampler)  | Java | Spring Boot, Spring Cloud and Axon | |
| Cloud Native Strangler Example | [link](https://github.com/kbastani/cloud-native-microservice-strangler-example) | Java | Spring | 7 |
| DDD Sample Application: | [link](https://sourceforge.net/projects/dddsample)  | Java | | |
| Delivery system | [link](https://github.com/matt-slater/delivery-system) | Java, Javascript | Spring, Angular2 | |
| Digota - ecommerce microservice | [link](https://github.com/digota/digota)  | Go | | |
| E-Commerce App | [link](https://github.com/venkataravuri/e-commerce-microservices-sample) | Java | Spring | |
| Eberhard Wolff's 11 Demo Systems | [link](https://ewolff.com/microservices-demos.html) | Java | Spring | |
| EnterprisePlanner (ASP.NET) | [link](https://github.com/gfawcett22/EnterprisePlanner) | C# | .Net | |
| eShop on Containers: | [link](https://github.com/dotnet-architecture/eShopOnContainers) | C# | .Net | |
| Freddy’s bbq joint (Pivotal SSO, Spring Cloud) | [link](https://github.com/william-tran/freddys-bbq) | Java | Spring | |
| FTGO - Restaurant Management |  [link](https://github.com/microservices-patterns/ftgo-application) | Java | Spring (Saga Pattern) | 6+API-Gatweay|
| Generic Online Shop (service-based patterns experiment) (Java): | [link](https://github.com/xJREB/research-modifiability-pattern-experiment) | Java | JavaEE | |
| Graph Processing | [link](https://github.com/kbastani/spring-boot-graph-processing-example) | Java | Spring | |
| Hipster Shop | [link](https://github.com/GoogleCloudPlatform/microservices-demo) | Java, Node.js, C#, Python, GO |  | |
| Hot R.O.D. - Rides on Demand | [link](https://github.com/jaegertracing/jaeger/tree/master/examples/hotrod) | GO |  | |
| Kenzan Million Song Library | [link](https://github.com/TheDigitalNinja/million-song-library) |Java | | 7 |
| Lakeside Mutual Insurance Company (API patterns example) | [link](https://github.com/Microservice-API-Patterns/LakesideMutual) | Java, Javascript | Spring, nodejs | |
| Micro company (Spring Cloud, Axon) | [link](https://github.com/idugalic/micro-company) | Java | Spring | |
| Microblog: | [link](https://github.com/senecajs/ramanujan) | Javascript | nodejs | |
| microService | [link](https://github.com/bishion/microService) | Java | Spring | |
| Microservices book | [link](https://github.com/ewolff/microservice) | Java | Spring | |
| Microservice Kubernetes Sample | [link](https://github.com/ewolff/microservice-kubernetes) | Java | Spring | |
| Microservices Reference for Azure | [link](https://github.com/mspnp/microservices-reference-implementation) | C# | .Net | |
| Microservices with Consul and Eureka (Chinese) | [link](https://github.com/bishion/microService) | Java | Spring | |
| Movie recommendation | [link](https://github.com/mdeket/spring-cloud-movie-recommendation) | Java | Spring | |
| Music Store: | [link](https://github.com/aspnet/MusicStore) | | | |
| MusicStore (ASP.NET) | [link](https://github.com/SteeltoeOSS/Samples/tree/master/MusicStore) | C# | .Net | |
| Netflix microservices with Spring and Eureka | [link](https://github.com/yidongnan/spring-cloud-netflix-example) | Java | Spring | |
| Parts Unlimited MRP Microservices | [link](https://github.com/microsoft/PartsUnlimitedMRPmicro) | Java | Spring | |
| Photo uploader (NGINX Fabric Model) | [link](https://github.com/nginxinc/mra-ingenious) | Ruby | | |
| Piggy Metrics | [link](https://github.com/sqshq/PiggyMetrics) | Java | Spring | |
| Pitstop (DDD, CQRS, Event Sourcing) | [link](https://github.com/EdwinVW/pitstop) | C# | .Net | |
| Product Review Microservice | [link](https://github.com/callistaenterprise/blog-microservices) | Java | Spring Cloud, Netflix OSS and the ELK-stack | |
| Robot Shop | [link](https://github.com/instana/robot-shop) | Javascript, Java, Python, Golang, PHP | | |
| Service Commerce | [link](https://github.com/antonio94js/servicecommerce) | Javascript | nodejs, Studio.js | |
| Share bike (Chinese) | [link](https://github.com/JoeCao/qbike) | Java | Spring | |
| SiteWhere | [link](https://github.com/sitewhere/sitewhere) | Java | Spring | |
| Sock Shop | [link](https://github.com/microservices-demo) | Java, Javascript, Golang | Spring, nodejs, Go kit | |
| Spring Cloud Microservice Example: | [link](https://github.com/zpng/spring-cloud-microservice-examples) | Java | Spring | |
| Spring Microservice online shop: | [link](https://github.com/paulc4/microservices-demo) | Java | SpringBoot, SpringCloud | |
| Spring PetClinic | [link](https://github.com/spring-petclinic/spring-petclinic-microservices) | Java | Spring | |
| Spring Petclinic Migration to AWS | [link](https://github.com/aws-samples/amazon-ecs-java-microservices) | Java | Spring | |
| SpringBoot Microservices: | [link](https://github.com/oktadeveloper/spring-boot-microservices-example) | Java | Spring | |
| SpringBoot Microservices Blog Series: | [link](https://github.com/sivaprasadreddy/spring-boot-microservices-series) | Java | Spring | |
| Tap-And-Eat (Spring Cloud) | [link](https://github.com/jferrater/Tap-And-Eat-MicroServices) | Java | Spring | 8 |
| Task track support (Chinese) | [link](https://github.com/yun19830206/CloudShop-MicroService-Architecture) | Java | Spring | |
| Tea Store: | [link](https://github.com/DescartesResearch/TeaStore/wiki) | Java | JavaEE | |
| Vanilla-Java/Microservices | [link](https://github.com/Vanilla-Java/Microservices) | Java| | |
| Vehicle tracking | [link](https://github.com/mohamed-abdo/vehicle-tracking-microservices) | C# | .Net | |
| Warehouse microservice | [link](https://github.com/HieJulia/warehouse-microservice) | Java | Spring | |
| WeText (DDD, CQRS, C#) | [link](https://github.com/daxnet/we-text) | C# | .Net | |



## Not Available anymore
Removed from GitHub

| Name  | Link | Languages | Framework | Notes
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Movie recommendation system (Spring Cloud) | [link](https://github.com/kbastani/spring-cloud-microservice-example) | Java | Spring | |
| Airport management| [link](https://github.com/sergeivisotsky/airport-management) | Java | Spring Boot | Not OpenSource Anymore |

## "Industrial" Projects created from scratch with a microservices architectural style

* OpenEBS www.openEBS.io
* Spinnaker https://www.spinnaker.io
* Open-loyalty https://github.com/DivanteLtd/open-loyalty
* Sentry https://github.com/getsentry
* Staffjoy https://github.com/Staffjoy/v2 (abandoned)
* Gizmo (Microservice Toolkit from The New York Times) https://github.com/nytimes/gizmo
* Genie (Netflix Distributed Big Data Orchestration Service https://github.com/Netflix/genie
* Lelylan - Open Source Internet of Things https://github.com/lelylan
* SiteWhere (IoT Application Enablement Platform) https://github.com/sitewhere/sitewhere
* Magda (A platform built to power a new generation of data portals) https://github.com/magda-io/magda
* Apollo (configuration management system) https://github.com/ctripcorp/apollo

## Projects that migrated from monolithic to microservces

Still looking for... Please, contact us (davide [dot] taibi [at] tuni [dot] fi, in case you know any project. 

## Acknowledgements
This list is based on the feedbacks received in the different platforms [1][2][3][4][5][6] and on the list of microservices-based projects listed in scientific papers[7], and of several pull requests submitted buy different authors. I'd like to thank all the participants to the discussions and all the authors of the papers that contributed to populate this list.


## References
[1] https://www.researchgate.net/post/Do_you_know_any_Open_Source_project_that_migrated_form_a_monolithic_architecture_to_microservices

[2] https://stackoverflow.com/questions/48802787/open-source-projects-that-migrated-to-microservices

[3] https://stackoverflow.com/questions/37711051/example-open-source-microservices-applications

[4] https://www.quora.com/Are-there-any-examples-of-open-source-projects-which-follow-a-microservice-architecture-DevOps-model

[5] https://www.quora.com/Are-there-any-open-source-projects-on-GitHub-for-me-to-learn-building-large-scale-microservices-architecture-and-production-deployment

[6] https://www.quora.com/Can-you-provide-an-example-of-a-system-designed-with-a-microservice-architecture-Preferably-open-source-so-that-I-can-see-the-details

[7] G Márquez, H Astudillo "Actual Use of Architectural Patterns in Microservices-based Open Source Projects" 25th Asia-Pacific Software Engineering Conference (APSEC 2018). Nara, Japan

[8] D. Taibi, V. Lenarduzzi, and C. Pahl “Architectural Patterns for Microservices: A Systematic Mapping Study” in 8th International Conference on Cloud Computing and Services Science, CLOSER , 2018. [(Download)](https://www.researchgate.net/profile/Claus_Pahl/publication/323960272_Architectural_Patterns_for_Microservices_A_Systematic_Mapping_Study/links/5ab4e801a6fdcc46d3b27eb1/Architectural-Patterns-for-Microservices-A-Systematic-Mapping-Study.pdf?_sg%5B0%5D=oPIH2y43ypGIbQC8ojw7-unAVok8BYbF4VLBz74_lcDGA0ScUNMhpK5W6-McEDl9rNv05gWuphHT1XqyF_L_yg.UK0FIUQv_mOjZdgUyZpEtcGcrWy5437aARRs5MUq1XTp2y1MkVlJ4p0C9Bb9bpsxrjogCARAS1x0Qiz6jqS88w&_sg%5B1%5D=Aax2Z8__RvjCVRm6Y57N4jZFTUUIY8qodMpLj4YvC892T6gBYuU4_DubBSuk2eJiEurZAZ1kOSrW6RoKnSP07B6914M72_ylDyjqJ9d4uFIs.UK0FIUQv_mOjZdgUyZpEtcGcrWy5437aARRs5MUq1XTp2y1MkVlJ4p0C9Bb9bpsxrjogCARAS1x0Qiz6jqS88w&_iepl=)

[9] D. Taibi and V. Lenarduzzi “On the Definition of Microservice Bad Smells”, IEEE Software , vol. 35, no. 3, 2018. [(Download)](https://www.researchgate.net/publication/324007573_On_the_Definition_of_Microservice_Bad_Smells)

[10] D. Taibi, V. Lenarduzzi, and Pahl, C. “Processes, Motivations and Issues for Migrating to Microservices Architectures: An Empirical Investigation”, IEEE Cloud Computing Journal, vol. 4, no. 5, 2017. [(Download)](https://www.researchgate.net/publication/319187656_Processes_Motivations_and_Issues_for_Migrating_to_Microservices_Architectures_An_Empirical_Investigation)


