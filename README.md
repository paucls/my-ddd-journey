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
- [Domain-Driven Design Distilled, Vaughn Vernon. (4h)](https://www.safaribooksonline.com/library/view/domain-driven-design-distilled/9780134593449/)
- [Domain-Driven Design in Practice, Vladimir Khorikov.](https://app.pluralsight.com/library/courses/domain-driven-design-in-practice/table-of-contents)
- CQRS Tutorial http://cqrs.nu/

# Podcasts
- Being The Worst. Audio apprenticeships for the aspiring software craftsman. Currently exploring DDD, Event Sourcing, CQRS, distributed systems, etc. http://www.beingtheworst.com/

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

## Domain Services
- Services in Domain-Driven Design, Jimmy Bogard
https://lostechies.com/jimmybogard/2008/08/21/services-in-domain-driven-design/
- Strengthening your domain: The double dispatch pattern, Jimmy Bogard
https://lostechies.com/jimmybogard/2010/03/30/strengthening-your-domain-the-double-dispatch-pattern/

## Application Services
- Application Services - 10 common doubts answered, Robert Pankowecki (23/12/2017).
https://blog.arkency.com/application-service-ruby-rails-ddd/
- Services in Domain-Driven Design (DDD), Lev Gorodinski (14/04/2012)
http://gorodinski.com/blog/2012/04/14/services-in-domain-driven-design-ddd/
[Shows full example with: application service PurchaseOrderService, aggregate root PurchaseOrder, value object Invoice, etc.]

## Domain Events
- Spring - Domain event publication from aggregate roots, Mark Paluch (30/01/2017).
https://spring.io/blog/2017/01/30/what-s-new-in-spring-data-release-ingalls#domain-event-publication-from-aggregate-roots
- Domain Events vs. Integration Events in Domain-Driven Design and microservices architectures, Cesar de la Torre (07/02/2017).
https://blogs.msdn.microsoft.com/cesardelatorre/2017/02/07/domain-events-vs-integration-events-in-domain-driven-design-and-microservices-architectures/

## Event Sourcing
- Scalable Microservices with Event Sourcing and Redis, Tom Mooney (13/12/2017)
https://medium.com/lcom-techblog/scalable-microservices-with-event-sourcing-and-redis-6aa245574db0

## Supporting Architectures
- DDD, Hexagonal, Onion, Clean, CQRS, … How I put it all together, Herberto Graça
https://herbertograca.com/2017/11/16/explicit-architecture-01-ddd-hexagonal-onion-clean-cqrs-how-i-put-it-all-together/
- Hexagonal Architecture for Rails Developers, Victor Savkin (23/07/2016)
https://medium.com/@vsavkin/hexagonal-architecture-for-rails-developers-8b1fee64a613
- Vertical Slice Architecture, Jimmy Bogard (19/04/2018)
https://jimmybogard.com/vertical-slice-architecture/

## Other
- Authentication and Authorization in DDD, José Luis Martínez (8/01/2016)
https://medium.com/@martinezdelariva/authentication-and-authorization-in-ddd-671f7a5596ac

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

# Sample projects
- DDD Sample Core
https://github.com/citerus/dddsample-core
- IDDD
https://github.com/VaughnVernon/IDDD_Samples
- Domain Driven Design Example C#, Zan Kavtaskin
https://github.com/zkavtaskin/Domain-Driven-Design-Example
