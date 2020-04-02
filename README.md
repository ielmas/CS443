# CS443 – Cloud Computing &amp; (Mobile) Applications

## Catalog Description

Hands-on introduction to cloud computing and developing cloud-native (esp. mobile) applications. Cloud application models, services and infrastructures (virtualization, data center networking, distributed file systems), cluster computing systems (e.g. Spark), fundamental trade offs and methods (CAP theorem, NoSQL systems), architecture (modern n-tier, lambda, kappa) and applications (big data analytics, large-scale web services). Programming to develop scalable applications running on the cloud (e.g. AWS, Azure, GCP, Oracle).

Basically, this course has the following learning outcomes:

* What is cloud computing? Why we need it and in which cases we can use that paradigm (__Module-1: What is it?__).
* How to implement a cloud computing system? What is essential to build an efficient cloud solution (__Module-2: How to implement it?__)
* How to sustain a cloud application in both business and technical terms (__Module-3: How to manage it?__)

## Staff

* __Instructor:__ Dr. Orçun Dayıbaş
* __T. Assistant:__ Mousa Farshkar Azari

## Prerequisite(s)

Please refer to the web page of the course.

## Minimum Requirements to Qualify for the Final Exam

Please refer to the web page of the course.

## Assessment Methods

| Item      | Type          | Weight  |
|:--------- |:------------- | -------:|
| Attendance| N/A           | 5%      |
| Midterm   | Essay/written | 30%     |
| Project   | Implementation| 30%     |
| Final     | Essay/written | 35%     |

## Project

Each student is expected to be part of a team (size of 3 people). During the fifth or sixth week of classes the project topic will be announced and every team will be expected to implement a cloud-native mobile-first application. Grading criteria will include the operational features of the application (we will cover these features in detail throughout the semester). During the classes each team will present: reports and demo/presentation on at least but not limited to the implementation details, external services, cloud characteristics, performance analysis, etc.

| | |
|-|-|
|__Topic__ | Design, implement and operate a cloud-native URL shortener system (B2B API, Mobile client, etc.) |
|__Details__  | [Project definition](../master/project/project-definition.pdf) |
|__Examples__  | A guide about [how to use bitly](https://www.youtube.com/watch?v=oK4rRWcm3fM) |
| __Teams__ | [(Link)](../master/project/preject-teams-2020Spring.pdf) |
| __Deadlines__ | Design reports: 2020-04-03 <br /> Final reports: 2020-04-17 <br /> **Send your deliverables in an email to TA** |
| __Presentations__ | (to be announced) |

## Midterm Exam

__ATTENTION:__ The distance learning will continue until the end of the semester. The university is also in the process of developing distance assessment methods. Please follow the official announcements and remember TA is the primary point of contact to coordinate the logistics.

| | |
|-|-|
|__Date__| ~~2020-04-04~~ (to be announced) |
|__Time__| ~~14:00 - 16:00~~ (to be announced) |
|__Location__| ~~EB-202, EB-203~~ (to be announced) |

## Weekly Syllabus

| Module | Topics & Week Numbers | Notes |
|:-------|:------|:------:|
| Module-1: What is it? | [1. Introduction to cloud computing](../master/slides/chapter-1.pdf) (w#1)<br/> [2. Features of cloud](../master/slides/chapter-2.pdf) (w#2)<br/> [3. Cloud application architectures](../master/slides/chapter-3.pdf) (w#2)<br/> [4. Designing systems for scale](../master/slides/chapter-4.pdf) (w#3)<br/> [5. Microservices](../master/slides/chapter-5.pdf) (w#4) | Module content,<br/> [Project definition](../master/project/project-definition.pdf),<br/> Team formations [(Teams)](../master/project/preject-teams-2020Spring.pdf) |
| Module-2: How to implement it? | [6. Anatomy of a data center](../master/slides/chapter-6.pdf) (w#5) <br/> [7. Virtualization & containers](../master/slides/chapter-7.pdf) (w#6) <br/> [8. Resource management & coordination](../master/slides/chapter-8.pdf) (w#8)<br/> ~~9. Programming models~~ <br/> [10. Cloud-native application development](../master/slides/chapter-10.pdf) (w#9)<br/> 11. Mobile applications & case studies| Module content,<br/> [Hands-on labs](https://github.com/CemalUnal/cloud-native-application-development-workshop),<br/> Spring break (w#7),<br/> Midterm,<br/> P. report(s) |
| Module-3: How to manage it? | 12. Migration concerns (security & privacy) <br/> 13. Cloud vendors & tools <br/> 14. Governance & Case studies | Module content,<br/> Project report(s),<br/> demo & presentations |

| Hands-on Labs | Date | Week # | Prerequisites |
|:--------------|:----:|:-----:|:------|
| Docker | 2020-03-11 | 6 |[Link](https://github.com/CemalUnal/cloud-native-application-development-workshop#setting-the-environment)  |
| Prometheus | 2020-03-23 | 8 | [Link](https://github.com/CemalUnal/cloud-native-application-development-workshop#setting-the-environment) |
| Kubernetes | 2020-03-30 | 9 |[Link](https://github.com/CemalUnal/cloud-native-application-development-workshop#prerequisites-for-the-part-3)|
| Quarkus | 2020-04-01 | 9 | Maven 3.6.2+, JDK 8 or 11+ installed (with JAVA_HOME configured) |
| Flutter | 2020-04-06 | 10 | TBD |

## Weekly Schedule for 2019-2020 Spring Semester

### Regular Classes (first six weeks of the classes)

* Monday 13:40 - 15:30 (EA-Z03)
* Wednesday 15:40 - 16:30 (EA-Z03)

### Remote Instruction (the rest of the term)

* Regular time slots are also used for remote instructions.
* Official announcement: https://w3.bilkent.edu.tr/bilkent/remote-teaching-at-bilkent-university/
* Details for Zoom: https://web4.bilkent.edu.tr/zoom/
* There is no any upfront arrangement for recording the Zoom sessions. Therefore, please continue to take regular notes like you did in the physical classroom environment.

## FAQ

Below you can find the questions received during the first week of classes (hoping that will help you to decide on taking the course before add/drop week)

__Q1:__ Which mobile development frameworks (iOS/Android/etc.) will be used during the course? <br/>
__A1:__ Please do not consider that course as a "App development course". "Mobile App development" is not one of the learning outcome objectives. We will use "mobile applications" as the main theme for implementing a cloud computing solution.

__Q2:__ Which cloud service provider (vendor) will be used during the course (tutorials and/or project)? <br/>
__A2:__ Any tool/framework of a major vendor can be used (please refer to "catalog desc." part). Project deliverables (reports/presentation/demo/etc.) will include details about external services used (but it has no effect on grading). In terms of our learning objectives, we will be more into "how you use these services/tools under which conditions".

__Q3:__ Do you consider to use spare hour of the course (Wed. 16:40)? <br/>
__A3:__ Not by default. Normally, we will not use the spare slot regularly but it will be used to make up any missed class hour. A notice mail will be sent to all registered students via STARS system in any such cases (as early as possible).

__Q4:__ Are you planning to use any textbook? <br />
__A4:__ No, it is very difficult to find a book that covers the topics of that course. The main objective is to design a course that conveys the both technical and business sides of cloud systems. Therefore, following this web page for slides (I will upload slides weekly) and "Bookmarks" list (probably that list will include additional infomative content which is referred in the course but not limited to that) is the best way to cope with it.

__Q5:__ Is it possible to form a 5-person project team? <br />
__A5:__ No, it is not possible.

__Q6:__ I'm taking that course without a prior computer networking course. It may be a bit hard follow -at least- the terminology used in the course. What do you suggest? <br />
__A6:__ You can use that walk through: ["Your App Lives on a Network: Networking for Web Developers by Wim Godden"](https://www.youtube.com/watch?v=t0JdGOYuQzc) It takes around an hour and it seems the presenter covers all the basics (which is enough for this course). If you prefer more formal content, Udacity also offers a free course called ["Networking for Web Developers"](https://www.udacity.com/course/networking-for-web-developers--ud256)

## Bookmarks

That part will be used to provide external supporting content (e.g. blog posts, video tutorials) throughout the semester.

* [SRE fundamentals: SLIs, SLAs and SLOs](https://cloud.google.com/blog/products/gcp/sre-fundamentals-slis-slas-and-slos)
* [C2MS: Dynamic Monitoring and Management of Cloud Infrastructures](https://arxiv.org/abs/1310.2148)
* [Speaking Intelligently about "Java vs Node" Performance](https://rclayton.silvrback.com/speaking-intelligently-about-java-vs-node-performance)
* [Understanding the 8 fallacies of Distributed Systems](https://www.simpleorientedarchitecture.com/8-fallacies-of-distributed-systems/)
* [CAP Theorem: Revisited](https://robertgreiner.com/cap-theorem-revisited/)
* [Designing robust and predictable APIs with idempotency](https://stripe.com/blog/idempotency)
* [Zalando REST API Guidelines](https://opensource.zalando.com/restful-api-guidelines/) & [Microsoft REST API Guidelines](https://github.com/microsoft/api-guidelines/blob/vNext/Guidelines.md)
* [How to Build 12 Factor Microservices on Docker](https://hub.packtpub.com/how-to-build-12-factor-design-microservices-on-docker-part-1/)
* [Why Microsoft wants to put data centers at the bottom of the ocean](https://techcrunch.com/2018/06/08/why-microsoft-wants-to-put-data-centers-at-the-bottom-of-the-ocean/)
* [Networking for the Cloud: Challenges and Trends](https://www.researchgate.net/publication/273249689_Networking_for_the_Cloud_Challenges_and_Trends)
* [Review and Analysis of Networking Challenges in Cloud Computing](https://arxiv.org/pdf/1601.05329.pdf)
* [Containers from scratch](https://youtu.be/8fi7uSYlOdc)
* [Email crash crippled federal health offices as coronavirus was first gaining grounds in U.S.](https://www.politico.com/amp/news/2020/03/10/email-crash-coronavirus-hhs-125302)
* [Sample cloud-native application with 10 microservices showcasing Kubernetes, Istio, gRPC and OpenCensus](https://github.com/GoogleCloudPlatform/microservices-demo)
* [Resource Management in Cloud Computing: Taxonomy, Prospects and Challenges](https://www.researchgate.net/publication/280918541_Resource_Management_in_Cloud_Computing_Taxonomy_Prospects_and_Challenges)
* [Predictive CPU isolation of containers at Netflix](https://netflixtechblog.com/predictive-cpu-isolation-of-containers-at-netflix-91f014d856c7)
* [Container-based Network Function Virtualization for Software-Defined Networks](https://pdfs.semanticscholar.org/dd1c/74eccb957aba63faf0390c65229b93d5eea2.pdf)
* [Control strategies for predictable brownouts in cloud computing](https://www.sciencedirect.com/science/article/pii/S1474667016416940)
* [Consensus in the Cloud: Paxos Systems Demystified](https://cse.buffalo.edu/tech-reports/2016-02.orig.pdf)
* [Observability to Better Serverless Apps](https://www.infoq.com/presentations/serverless-observability-2018/)
* [The Single Most Important Internal Email in the History of Amazon](https://apievangelist.com/2012/01/12/the-secret-to-amazons-success-internal-apis/)
* [Introducing Quarkus: a next-generation Kubernetes native Java framework](https://developers.redhat.com/blog/2019/03/07/quarkus-next-generation-kubernetes-native-java-framework/)
* [Lightweight cloud-native Java applications](https://medium.com/graalvm/lightweight-cloud-native-java-applications-35d56bc45673)
* [Top 10 Things To Do With GraalVM](https://medium.com/graalvm/graalvm-ten-things-12d9111f307d)

## References

* https://link.springer.com/book/10.1007/978-1-4419-6524-0
* https://samnewman.io/books/building_microservices/
* https://landing.google.com/sre/books/
* https://conferences.oreilly.com/software-architecture/sa-eu-2016/public/schedule/detail/52350
* https://speakerdeck.com/thockin/kubernetes-understanding-pods-vs-containers
* https://www.slideshare.net/YifanXing/consensus-algorithmspaperswelove2018sep
* https://muratbuffalo.blogspot.com/2015/10/consensus-in-wild.html
* https://www.usenix.org/system/files/conference/atc14/atc14-paper-ongaro.pdf
* https://agenda.infn.it/event/19049/contributions/98119/attachments/66836/81864/FaaS-Serverless-SOSC19.pdf
* https://martinfowler.com/articles/serverless.html