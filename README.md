# my-ddd-journey
A list of Domain-Driven Design resources that I found interesting on my journey studying DDD.

# Books
- Domain-Driven Design Distilled. Vaughn Vernon – 2016.
- Implementing Domain Driven Design - Vaughn Vernon.
- Domain-Driven Design: Tackling Complexity in the Heart of Software - Eric Evans - 2003.
- The Anatomy Of Domain-Driven Design - Booklet https://leanpub.com/theanatomyofdomain-drivendesign
- Designing Autonomous Teams and Services, Nick Tune and Scott Millett - 2017 http://www.oreilly.com/programming/free/designing-autonomous-teams-and-services.csp
- CQRS Documents, Greg Young
https://github.com/keyvanakbary/cqrs-documents
- Functional and Reactive Domain Modeling, Debasish Ghosh - 2016.
- Domain Modeling Made Functional: Tackle Software Complexity with Domain-Driven Design and F#, Scott Wlaschin - 2018.

# Online Courses
- [Domain-Driven Design Fundamentals by Julie Lerman and Steve Smith (6/2014)](https://app.pluralsight.com/library/courses/domain-driven-design-fundamentals/table-of-contents)
- [Domain-Driven Design in Practice, Vladimir Khorikov. (1/2016)](https://app.pluralsight.com/library/courses/domain-driven-design-in-practice/table-of-contents)
- [Domain-Driven Design Distilled, Vaughn Vernon. (3/2017)](https://www.safaribooksonline.com/library/view/domain-driven-design-distilled/9780134593449/)
- CQRS Tutorial http://cqrs.nu/
- [CQRS in Practice, Vladimir Khorikov (10/2018)](https://app.pluralsight.com/library/courses/cqrs-in-practice/table-of-contents) [* My notes](https://paucls.wordpress.com/2019/01/12/my-notes-on-the-video-course-cqrs-in-practice-by-vladimir-khorikov/)
- [Domain-Driven Design, Javier Ferrer and Rafa Gómez (2019)](https://pro.codely.tv/library/domain-driven-design-ddd/about/)

# Podcasts
- Interview Eric Evans, SE-Radio (09/03/2006) http://www.se-radio.net/2006/03/episode-8-interview-eric-evans/
- Eric Evans on Domain-Driven Design at 10 Years, SE-Radio (13/05/2015) http://www.se-radio.net/2015/05/se-radio-episode-226-eric-evans-on-domain-driven-design-at-10-years/
- Reactive Programming with the Actor Model, Vaughn Vernon, SE-Radio (12/02/2016) http://www.se-radio.net/2016/02/se-radio-episode-249-vaughn-vernon-on-reactive-programming-with-the-actor-model/
- Being The Worst. Audio apprenticeships for the aspiring software craftsman. Currently exploring DDD, Event Sourcing, CQRS, distributed systems, etc. http://www.beingtheworst.com/
- Domain Driven Design and Micro Services, Vaughn Vernon. (17/08/208)
https://corecursive.com/018-micro-services-and-domain-driven-design-with-vaughn-vernon/
- Domain-Driven Design & Event Storming, Jakub Pilimon (5/12/2018)
https://content.pivotal.io/podcasts/domain-driven-design-event-storming-with-jakub-pilimon

# Articles
## Aggregates
- DDD Decoded - The Aggregate and Aggregate Root Explained, Mike Mogosanu
http://blog.sapiensworks.com/post/2016/07/14/DDD-Aggregate-Decoded-1
- Identifying An Aggregate Is Not Object Oriented Design, Mike Mogosanu
http://blog.sapiensworks.com/post/2018/01/08/DDD-Aggregate-groups-behaviour-not-data
- Strengthening your domain: Aggregate Construction, Jimmy Bogard (24/02/2010)
https://lostechies.com/jimmybogard/2010/02/24/strengthening-your-domain-aggregate-construction/
- Aggregate Roots Should Look After Their Own Events, Mike Mogosanu (22/05/2014)
http://blog.sapiensworks.com/post/2014/05/22/Aggregate-Roots-Should-Look-After-Their-Own-Events.aspx.html
- DDD - Persisting Aggregate Roots In A Unit Of Work, Mike Mogosanu (01/05/2013)
http://blog.sapiensworks.com/post/2013/05/01/DDD-Persisting-Aggregate-Roots-In-A-Unit-Of-Work.aspx
- Aggregates and RFC 2119, Danil Suits (05/02/2017)
http://cascadefaliure.vocumsineratio.com/2017/02/aggregates-and-rfc-2119.html

## Entities
- How *not* to inject services in entities, Jeremie Chassaing (04/03/2009)
https://thinkbeforecoding.com/post/2009/03/04/How-not-to-inject-services-in-entities
[Explains how Double Dispatch can be the solution when an Entity needs to use a service]
- Entities should look after their own events, Mat McLoughlin
http://mat-mcloughlin.net/2014/05/22/entities-should-look-after-their-own-events/
- A Better Way to Project Domain Entities into DTOs, Nick Chamberlain
https://buildplease.com/pages/repositories-dto/ [Should the projection from Aggregate(s) to DTO be done inside your Repositories?]

## Domain Services
- Services in Domain-Driven Design, Jimmy Bogard
https://lostechies.com/jimmybogard/2008/08/21/services-in-domain-driven-design/
- Strengthening your domain: The double dispatch pattern, Jimmy Bogard
https://lostechies.com/jimmybogard/2010/03/30/strengthening-your-domain-the-double-dispatch-pattern/
- And Then This Happened, Vaughn Vernon (24/11/2018) https://kalele.io/cqrs/and-then-this-happened/ [ how using Domain Events or not using them can impact the Command Model and the projection of changes into the Query Model]

## Application Services
- Application Services - 10 common doubts answered, Robert Pankowecki (23/12/2017).
https://blog.arkency.com/application-service-ruby-rails-ddd/
- Services in Domain-Driven Design (DDD), Lev Gorodinski (14/04/2012)
http://gorodinski.com/blog/2012/04/14/services-in-domain-driven-design-ddd/
[Shows full example with: application service PurchaseOrderService, aggregate root PurchaseOrder, value object Invoice, etc.]

## Domain Events
- A better domain events pattern, Jimmy Bogard (2014/05/13).
https://lostechies.com/jimmybogard/2014/05/13/a-better-domain-events-pattern/
- Spring - Domain event publication from aggregate roots, Mark Paluch (30/01/2017).
https://spring.io/blog/2017/01/30/what-s-new-in-spring-data-release-ingalls#domain-event-publication-from-aggregate-roots
- Domain Events vs. Integration Events in Domain-Driven Design and microservices architectures, Cesar de la Torre (07/02/2017).
https://blogs.msdn.microsoft.com/cesardelatorre/2017/02/07/domain-events-vs-integration-events-in-domain-driven-design-and-microservices-architectures/
- Domain events: design and implementation. https://docs.microsoft.com/en-us/dotnet/standard/microservices-architecture/microservice-ddd-cqrs-patterns/domain-events-design-implementation
- Domain events: simple and reliable solution, Vladimir Khorikov https://paucls.wordpress.com/?p=760&amp;preview=true

## Event Sourcing
- Scalable Microservices with Event Sourcing and Redis, Tom Mooney (13/12/2017)
https://medium.com/lcom-techblog/scalable-microservices-with-event-sourcing-and-redis-6aa245574db0
- Don't Let the Internet Dupe You, Event Sourcing is Hard. Chris Kiehl. (02/03/2019)
https://chriskiehl.com/article/event-sourcing-is-hard

## Supporting Architectures
- DDD, Hexagonal, Onion, Clean, CQRS, … How I put it all together, Herberto Graça
https://herbertograca.com/2017/11/16/explicit-architecture-01-ddd-hexagonal-onion-clean-cqrs-how-i-put-it-all-together/
- Hexagonal Architecture for Rails Developers, Victor Savkin (23/07/2016)
https://medium.com/@vsavkin/hexagonal-architecture-for-rails-developers-8b1fee64a613
- Vertical Slice Architecture, Jimmy Bogard (19/04/2018)
https://jimmybogard.com/vertical-slice-architecture/
- Is Layering Worth the Mapping?, Mark Seemann (9/1/2012) http://blog.ploeh.dk/2012/02/09/IsLayeringWorththeMapping
- How CQRS Works with Spring Tools, Jakub Pilimon (16/10/2018)
https://thenewstack.io/how-cqrs-works-with-spring-tools/

## Other
- Authentication and Authorization in DDD, José Luis Martínez (8/01/2016)
https://medium.com/@martinezdelariva/authentication-and-authorization-in-ddd-671f7a5596ac
- Domain-Driven Design vs. Anemic model. How do they differ?, Kamil Berdychowski (03/01/2017) https://blog.pragmatists.com/domain-driven-design-vs-anemic-model-how-do-they-differ-ffdee9371a86 [Anemic model and bulky services vs Rich model and thin services]
- Refactoring from anemic model to DDD, Zbigniew Artemiuk (18/04/2017)
https://blog.pragmatists.com/refactoring-from-anemic-model-to-ddd-880d3dd3d45f [refactoring repository to make it independent from implementation ...]

### REST
- There is No U in CRUD, James Hood (25/07/2017) [resist the urge to follow the CRUD model for service APIs (use DDD to define your API in terms of domain objects and the business operations]
http://jlhood.com/there-is-no-u-in-crud/

# Q&A
## Aggregates
- DDD - Fictitious Aggregate Root
https://stackoverflow.com/a/46947901
- Consistency across Aggregate Root
https://groups.google.com/forum/#!topic/dddcqrs/qf0EzujnDWA
- Aggregate roots coordinating their entities in an event sourcing system [Should an AR wrap the behavior of its entities?]
https://groups.google.com/forum/#!topic/dddcqrs/T9bWd48e40I

# Entities
- DDD Injecting Services on Entity Methods Calls [Is it within best practices of DDD and OOP to inject services on entity method calls?]
https://softwareengineering.stackexchange.com/questions/357969/ddd-injecting-services-on-entity-methods-calls

# Talks
- Domain Driven Design: The Good Parts. Jimmy Bogard. (08/2016)
https://youtu.be/U6CeaA-Phqo
- A Decade of DDD, CQRS, Event Sourcing. Greg Young. DDD Europe. (29/01/2016)
https://youtu.be/LDW0QWie21s
- Eric Evans: What I've learned about DDD since the book. (2009)
https://youtu.be/lE6Hxz4yomA
- Evil by Design, Jef Claes. (01/2016) [Visualization of events on a ES system]
https://youtu.be/EmMvnB2v1GQ
- DDD Strategic Design With Spring Boot, Michael Plod. (2017) [Introduction to Bounded Context and Context Maps]
https://youtu.be/DXbmfcgOvUI
https://speakerdeck.com/mploed/ddd-strategic-design-with-spring-boot-examples
- Case Study: Practical tools and strategies for tackling legacy practices and legacy systems in a fast-growing startup, Alejandro Scandroli
https://www.slideshare.net/ascandroli/case-study-practical-tools-and-strategies-for-tackling-legacy-practices-and-legacy-systems-in-a-fastgrowing-startup
- Adopting Domain Driven Design in your organization, Aleix Morgadas. (03/11/2018) https://docs.google.com/presentation/d/1Yiw6_u0rcJVHNBjnis56HdBiVg0-aGEMQPG06XG37zA
- Case Study: tools and strategies for tackling legacy practices, Alejandro Scandroli. (2018)
https://youtu.be/i8GzkkMWGYE [DDD strategic design, Wardley Maps, ...]
- Domain Language throughout Tests, combining DDD and BDD. Kenny Baas
https://youtu.be/xSZnKnZ8EAo  [event storming, feature mapping, example mapping, ...]
- From Legacy Chaos to the Promised Land of DDD, Anita Kvamme and Ellen Lippe, 2018
https://youtu.be/bnaYU4fjGe4
[...changing software architecture and code isn't really about changing software architecture and code, it's about the people, it's about each individual and the interaction between them, it's about helping team members changing habits, to mentor and teach new skills, most of all to work all align together as a team]
- DDD Lessons, Barry O'Sullivan (2018) [Domains and SubDomains are composable. Bounded Contexts are independent (not composable).]
https://youtu.be/PMWl5X1sK70

## Functional DDD
- Functional architecture - The pits of success, Mark Seemann. (07/2016)
https://youtu.be/US8QG9I1XW0

## Supporting Architectures
- Evolutionary Software Architectures, Neal Ford [Technical Architecture vs Domain Architecture] https://youtu.be/CglSFhwbI3s
- The Actor Model, Hewitt, Meijer and Szyperski
https://channel9.msdn.com/Shows/Going+Deep/Hewitt-Meijer-and-Szyperski-The-Actor-Model-everything-you-wanted-to-know-but-were-afraid-to-ask

# Sample projects
- DDD Sample Core
https://github.com/citerus/dddsample-core
- IDDD
https://github.com/VaughnVernon/IDDD_Samples
- BookARoom is a simple project to explain CQRS, Thomas Pierrain
https://github.com/tpierrain/CQRS/blob/master/README.md
- Domain Driven Design Example C#, Zan Kavtaskin
https://github.com/zkavtaskin/Domain-Driven-Design-Example
- All Things CQRS, A bunch of ways of doing CQRS with various Spring tools, Jakub Pilimon
https://github.com/ddd-by-examples/all-things-cqrs
- Acerola: Hexagonal Architecture
https://github.com/ivanpaulovich/hexagonal-architecture-acerola
