# Domain-driven design \(DDD\) learning resources

## **Introduction**

Domain-driven design \(DDD\) is an approach to software development for complex needs by connecting the implementation to an evolving model. The premise of domain-driven design is the following

* placing the project's primary focus on the core domain and domain logic;
* basing complex designs on a model of the domain;
* initiating a creative collaboration between technical and domain experts to iteratively refine a conceptual model that addresses particular domain problems.

[https://en.wikipedia.org/wiki/Domain-driven\_design](https://en.wikipedia.org/wiki/Domain-driven_design)

DDD for everyone [https://docs.google.com/presentation/d/1HOqF3vvvckDu05CgHwj7afZfbxrZrS62Mn3VpB0-T0w/edit\#slide=id.p](https://docs.google.com/presentation/d/1HOqF3vvvckDu05CgHwj7afZfbxrZrS62Mn3VpB0-T0w/edit#slide=id.p)

## Benefits

DDD Value And Benefits \(A.K.A. How To Sell Ddd To Your Management, Domain Experts, And Technical Team Members\)

* Organization gains a useful model of its domain
* Develop a refined, precise definition and understanding of your business
* Domain experts contribute to software design
* Gain a better user experience
* Place clean boundaries around pure models
* Better organize elements of your enterprise architecture
* Use agile, iterative, continuous modeling
* Employ new tools, both strategic and tactical, to your code

[http://www.informit.com/articles/article.aspx?p=1944876&seqNum=4](http://www.informit.com/articles/article.aspx?p=1944876&seqNum=4)

The following are the main benefits of the Domain Driven Design style:

* **Communication**. All parties within a development team can use the domain model and the entities it defines to communicate business knowledge and requirements using a common business domain language, without requiring technical jargon.
* **Extensible**. The domain model is often modular and flexible, making it easy to update and extend as conditions and requirements change.
* **Testable**. The domain model objects are loosely coupled and cohesive, allowing them to be more easily tested.

  Consider DDD if you have a complex domain and you wish to improve communication and understanding within your development team, or where you must express the design of an application in a common language that all stakeholders can understand. 

  DDD can also be an ideal approach if you have large and complex enterprise data scenarios that are difficult to manage using other techniques.

[https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ee658117\(v=pandp.10](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ee658117%28v=pandp.10)\)

In **Microservices**, we build each service to serve only one thing and do one thing well. Each service is also isolated from the others. On this matter, DDD principles can help us to keep the scope of the service small through what it calls **"bounded context."**

Subsequently, DDD is going to help you **investigate and know your domain and all subdomains** well through the communication you build with the domain experts. By knowing your domain andsubdomains well, you will know the map contexts and how all subdomains interact with each other, which will help you in designing and choosing the type of your microservices architecture and what kind of approaches you use to implement them, whether a reactive approach, orchestration approach, or hybrid... it will depend on your knowledge about the domain you're working on. There are pros and cons for each approach that need to be evaluated based on the project and your domain knowledge. DDD will help you make a decision on this matter. [https://dzone.com/articles/ddd-part-iv-ddd-amp-microservices](https://dzone.com/articles/ddd-part-iv-ddd-amp-microservices)

## Glossary

* [http://uniknow.github.io/AgileDev/site/0.1.8-SNAPSHOT/parent/ddd/core/glossary.html](http://uniknow.github.io/AgileDev/site/0.1.8-SNAPSHOT/parent/ddd/core/glossary.html)
* [https://gist.github.com/bobthemighty/b241a4fccadbd7591024](https://gist.github.com/bobthemighty/b241a4fccadbd7591024)
* [http://dddcommunity.org/resources/ddd\_terms](http://dddcommunity.org/resources/ddd_terms)
* [https://en.wikipedia.org/wiki/Domain-driven\_design\#Building\_blocks](https://en.wikipedia.org/wiki/Domain-driven_design#Building_blocks)

## Books

* [https://amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215](https://amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215)
* [https://amazon.com/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577](https://amazon.com/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577)
* [http://dddcommunity.org/books](http://dddcommunity.org/books)
* [http://domainlanguage.com/ddd/](http://domainlanguage.com/ddd/)
* [https://amazon.com/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164](https://amazon.com/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164)
* [http://carfield.com.hk/document/software%2Bdesign/dddquickly.pdf](http://carfield.com.hk/document/software%2Bdesign/dddquickly.pdf)
* [http://eventstorming.com](http://eventstorming.com)
* [https://www.amazon.com/Patterns-Principles-Practices-Domain-Driven-Design/dp/1118714709](https://www.amazon.com/Patterns-Principles-Practices-Domain-Driven-Design/dp/1118714709)

## Presentations

* Greg Young — A Decade of DDD, CQRS, Event Sourcing [https://youtube.com/watch?v=LDW0QWie21s](https://youtube.com/watch?v=LDW0QWie21s)
* Eric Evans — Tackling Complexity in the Heart of Software [https://youtube.com/watch?v=dnUFEg68ESM](https://youtube.com/watch?v=dnUFEg68ESM)
* GOTO 2014 • Event Sourcing • Greg Young [https://youtube.com/watch?v=8JKjvY4etTY](https://youtube.com/watch?v=8JKjvY4etTY)
* Eric Evans - DDD and Microservices: At Last, Some Boundaries! [https://youtu.be/sFCgXH7DwxM](https://youtu.be/sFCgXH7DwxM)
* JDD 2017: Keep IT clean: mid-sized building blocks and hexagonal architecture \(Jakub Nabrdalik\) [https://youtu.be/KrLFs6f2bOA](https://youtu.be/KrLFs6f2bOA)
* Mariusz Gil: Discovering unknown with Event Storming [https://youtube.com/watch?v=Pl5HD8Ae3PU](https://youtube.com/watch?v=Pl5HD8Ae3PU)
* Boiling Frogs 2018 - Mariusz Gil - Discovering unknown domain with Event Storming [https://youtu.be/dhoXYRqghws?t=15s\(polish](https://youtu.be/dhoXYRqghws?t=15s%28polish)\)
* WJUG \#204 - Marcin Haręza: Event Sourcing - co to, po co to, jak to? [https://youtube.com/watch?v=dEA6uv0FPpE](https://youtube.com/watch?v=dEA6uv0FPpE) \(polish\)
* Domain Driven Design - A place for everything and everything in its place [https://youtube.com/watch?v=jraV7xSTYVs](https://youtube.com/watch?v=jraV7xSTYVs) \(polish\)
* Boiling Frogs 2018 - Jarosław Pałka - Sagi, strumienie, reaktywność i inne buzzwordy [https://youtu.be/27S0G9bE3Bg?t=0s\(polish](https://youtu.be/27S0G9bE3Bg?t=0s%28polish)\)
* Sławomir Sobótka - DDD: Q&A - czyli co gryzie świadomego programistę/programistkę [https://youtu.be/FkylT96at4g](https://youtu.be/FkylT96at4g) \(polish\)
* Sławomir Sobótka - DDD Q&A - wersja rozszerzona [https://youtu.be/do-xqIbKZ\_8](https://youtu.be/do-xqIbKZ_8) \(polish\)
* [https://devstyle.pl/2014/12/01/devtalk04-o-domain-driven-design-ze-slawomirem-sobotka/](https://devstyle.pl/2014/12/01/devtalk04-o-domain-driven-design-ze-slawomirem-sobotka/) \(polish\)
* Event-Driven Rails from scratch [https://youtube.com/watch?v=C3P3yGQyDQ4](https://youtube.com/watch?v=C3P3yGQyDQ4) 
* DDD europe [https://www.youtube.com/channel/UC3PGn-hQdbtRiqxZK9XBGqQ/playlists](https://www.youtube.com/channel/UC3PGn-hQdbtRiqxZK9XBGqQ/playlists) 

## References

* [https://github.com/heynickc/awesome-ddd](https://github.com/heynickc/awesome-ddd)
* [http://alistair.cockburn.us/Hexagonal+architecture/v/slim](http://alistair.cockburn.us/Hexagonal+architecture/v/slim)
* [http://mkuthan.github.io/blog/2014/09/22/ddd-how-to-learn/](http://mkuthan.github.io/blog/2014/09/22/ddd-how-to-learn/)
* [http://dddweekly.com](http://dddweekly.com)
* [https://docs.microsoft.com/en-gb/dotnet/standard/microservices-architecture/microservice-ddd-cqrs-patterns/ddd-oriented-microservice](https://docs.microsoft.com/en-gb/dotnet/standard/microservices-architecture/microservice-ddd-cqrs-patterns/ddd-oriented-microservice)
* [https://martinfowler.com/bliki/AnemicDomainModel.html](https://martinfowler.com/bliki/AnemicDomainModel.html)
* [https://martinfowler.com/tags/domain driven design.html](https://martinfowler.com/tags/domain%20driven%20design.html)
* [https://github.com/dzfweb/microsoft-microservices-book/blob/master/microservice-ddd-cqrs-patterns/ddd-oriented-microservice.md](https://github.com/dzfweb/microsoft-microservices-book/blob/master/microservice-ddd-cqrs-patterns/ddd-oriented-microservice.md)
* [https://www.ibm.com/developerworks/cloud/library/cl-domain-driven-design-event-sourcing/index.html](https://www.ibm.com/developerworks/cloud/library/cl-domain-driven-design-event-sourcing/index.html)
* [https://content.pivotal.io/blog/getting-started-with-domain-driven-design-top-3-concepts](https://content.pivotal.io/blog/getting-started-with-domain-driven-design-top-3-concepts)
* [https://www.linkedin.com/pulse/code-better-ddd-what-why-balazs-hideghety/](https://www.linkedin.com/pulse/code-better-ddd-what-why-balazs-hideghety/)
* [https://gist.github.com/somebox/21c7c9ca3a62de9ac65a366fbb8c3250](https://gist.github.com/somebox/21c7c9ca3a62de9ac65a366fbb8c3250)
* [http://mkuthan.github.io/presentations/micro-services.html\#/](http://mkuthan.github.io/presentations/micro-services.html#/)
* [https://github.com/mariuszgil/awesome-eventstorming](https://github.com/mariuszgil/awesome-eventstorming)

### Java

* [https://bottega.com.pl/materialy.xhtm?cat=DDD](https://bottega.com.pl/materialy.xhtm?cat=DDD) \(polish\)
* [https://bottega.com.pl/pdf/materialy/sdj-ddd.pdf](https://bottega.com.pl/pdf/materialy/sdj-ddd.pdf) \(polish\)
* [https://bottega.com.pl/pdf/materialy/ddd/ddd1.pdf](https://bottega.com.pl/pdf/materialy/ddd/ddd1.pdf) \(polish\)
* [https://bottega.com.pl/pdf/materialy/ddd/ddd2.pdf](https://bottega.com.pl/pdf/materialy/ddd/ddd2.pdf) \(polish\)
* [http://jakubn.gitlab.io/keepitclean/\#1](http://jakubn.gitlab.io/keepitclean/#1)
* [http://tswiackiewicz.github.io/inside-the-source-code/architecture/ddd-layered-architecture](http://tswiackiewicz.github.io/inside-the-source-code/architecture/ddd-layered-architecture) \(polish\)
* [https://devstyle.pl/2016/11/23/esencja-cqrs-to-bardzo-proste/](https://devstyle.pl/2016/11/23/esencja-cqrs-to-bardzo-proste/) \(polish\)
* [http://piotrgankiewicz.com/2016/08/01/handling-domain-events](http://piotrgankiewicz.com/2016/08/01/handling-domain-events)
* [http://tidyjava.com/hexagonal-architecture-powerful](http://tidyjava.com/hexagonal-architecture-powerful)
* [https://geek.justjoin.it/architektura-kodu-mikrouslugi-oparta-o-domain-driven-design/](https://geek.justjoin.it/architektura-kodu-mikrouslugi-oparta-o-domain-driven-design/) \(polish\)

### Ruby

* [https://blog.arkency.com/domain-driven-rails/](https://blog.arkency.com/domain-driven-rails/)
* [https://ddd-ruby.github.io/](https://ddd-ruby.github.io/)
* [https://www.developer.com/open/domain-driven-design-aggregates-with-ruby.html](https://www.developer.com/open/domain-driven-design-aggregates-with-ruby.html)
* [https://mensfeld.pl/2017/08/domain-driven-rails-mediocrity-driven-book/](https://mensfeld.pl/2017/08/domain-driven-rails-mediocrity-driven-book/)
* [https://medium.com/@poilon/domain-driven-design-with-graphql-on-ruby-on-rails-api-3f0f2a090b4f](https://medium.com/@poilon/domain-driven-design-with-graphql-on-ruby-on-rails-api-3f0f2a090b4f)
* [https://github.com/envato/event\_sourcery](https://github.com/envato/event_sourcery)
* [https://theplainprogrammer.com/applying-clean-architecture-to-ruby-on-rails-first-impressions-3746ed0c9668](https://theplainprogrammer.com/applying-clean-architecture-to-ruby-on-rails-first-impressions-3746ed0c9668)
* [https://github.com/valignatev/ddd-dynamic](https://github.com/valignatev/ddd-dynamic)

### Go

* [https://gist.github.com/eduncan911/c1614e684e4802d626ae](https://gist.github.com/eduncan911/c1614e684e4802d626ae)
* [https://threedots.tech/post/microservices-or-monolith-its-detail](https://threedots.tech/post/microservices-or-monolith-its-detail)
* [https://hackernoon.com/golang-clean-archithecture-efd6d7c43047](https://hackernoon.com/golang-clean-archithecture-efd6d7c43047)
* [https://medium.com/@eminetto/clean-architecture-using-golang-b63587aa5e3f](https://medium.com/@eminetto/clean-architecture-using-golang-b63587aa5e3f)
* [https://juicemia.com/post/go-ddd/](https://juicemia.com/post/go-ddd/)
* [https://www.citerus.se/go-ddd/](https://www.citerus.se/go-ddd/)
* [https://outcrawl.com/go-microservices-cqrs-docker/](https://outcrawl.com/go-microservices-cqrs-docker/)

## Samples

### Java

* [https://github.com/ddd-by-examples/factory](https://github.com/ddd-by-examples/factory)
* [https://github.com/BottegaIT/ddd-leaven-v2](https://github.com/BottegaIT/ddd-leaven-v2)
* [https://github.com/eventuate-examples/eventuate-examples-java-spring-todo-list](https://github.com/eventuate-examples/eventuate-examples-java-spring-todo-list)
* [https://github.com/avthart/spring-boot-axon-sample](https://github.com/avthart/spring-boot-axon-sample)
* [https://github.com/jakubnabrdalik/hentai-cloudy-rental](https://github.com/jakubnabrdalik/hentai-cloudy-rental)
* [https://github.com/jakubnabrdalik/hentai](https://github.com/jakubnabrdalik/hentai)
* [https://ordina-jworks.github.io/conference/2016/07/10/SpringIO16-DDD-Rest.html](https://ordina-jworks.github.io/conference/2016/07/10/SpringIO16-DDD-Rest.html)
* [https://github.com/olivergierke/spring-restbucks](https://github.com/olivergierke/spring-restbucks)

### Ruby

* [https://github.com/paulrayner/ddd\_sample\_app\_ruby](https://github.com/paulrayner/ddd_sample_app_ruby)
* [https://github.com/lcrodriguez/rails-ddd-todolist](https://github.com/lcrodriguez/rails-ddd-todolist)
* [https://railseventstore.org/docs/install/](https://railseventstore.org/docs/install/) \(event sourcing lib\)

### Go

* [https://github.com/bxcodec/go-clean-arch](https://github.com/bxcodec/go-clean-arch)
* [https://github.com/marcusolsson/goddd](https://github.com/marcusolsson/goddd)

## Frameworks

\(Actually "framework" is not important\)

### Java

* [https://github.com/RBMHTechnology/eventuate](https://github.com/RBMHTechnology/eventuate)
* [https://github.com/eventuate-local/eventuate-local](https://github.com/eventuate-local/eventuate-local)
* [https://github.com/RBMHTechnology/eventuate/wiki/Thoughts-on-Eventuate’s-future](https://github.com/RBMHTechnology/eventuate/wiki/Thoughts-on-Eventuate’s-future)
* [https://github.com/AxonFramework](https://github.com/AxonFramework)
* [https://blog.eventuate.io/2016/04/05/the-eventuate-todo-list-application-microservices-springboot-eventsourcing-cqrs/](https://blog.eventuate.io/2016/04/05/the-eventuate-todo-list-application-microservices-springboot-eventsourcing-cqrs/)
* [https://github.com/AxonFramework/AxonFramework](https://github.com/AxonFramework/AxonFramework)
* [https://github.com/binkley/axon-spring-boot-starter](https://github.com/binkley/axon-spring-boot-starter)

### Ruby

* [https://github.com/envato/event\_sourcery](https://github.com/envato/event_sourcery)

