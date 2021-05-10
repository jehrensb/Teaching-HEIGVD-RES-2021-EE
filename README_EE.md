# Teaching-HEIGVD-RES-2021 (en emploi)
This is the main repo for the course RES, taught at HEIG-VD in 2021. 

This is where you will find lecture notes, slides and some of the examples presented in the class. We will also keep links to the different repos used throughout the semester (for assignments).

## Upcoming deadlines

* Saturday **June 5, at 23h**: submit the Web Infrastructure lab results
  * You work in pairs
  * You will have 4 lab sections and 2 course session to work in this lab.
* **Tuesday, May 25th**, second written test. SMTP and HTTP protocols (slides, videos and lecture notes) and docker (videos). The "Web Infrastructures" slides and lecture notes are not part of the test.

## Tentative schedule

| Week              | Course                          | Lab                                         |
| ----------------- | ------------------------------- | ------------------------------------------- |
| 0                 | Introduction,                   | Chill Protocol (no grade)                   |
| 1                 | Process & tools (cont. Intro)   | Chill Protocol (cont.)                      |
| 2                 | Java IO - part 1                | Java IO                                     |
| 3                 | Java IO - part 2                | **Java IO (grade, weight 1)**               |
| 4                 | TCP programming                 | Protocol design exercise (no grade)         |
| 5                 | TCP programming                 | Protocol implementation exercise (no grade) |
| **Eastern break** |                                 |                                             |
| 6                 | **Test 1**                      | SMTP lab                                    |
| 7                 | SMTP                                           | SMTP lab                                    |
| 8                 | **Web casts**: HTTP Protocol + intro to Docker | SMTP lab                                    |
| 9                 | **Web casts**: HTTP Protocol + intro to Docker | **SMTP lab (grade, weight 1)**              |
| 10 (11/05)        | **Live**: HTTP infrastructure                  | HTTP infra lab                              |
| 11 (18/05)        | HTTP infra lab                                 | HTTP infra lab                              |
| 12 (25/05)        | **Test 2**                                     | HTTP infra lab                              |
| 13 (01/06)        | HTTP infra lab                                 | **HTTP infra lab (grade, weight 3)**        |
| 14 (08/06)        | **Live**: UDP programming                      | UDP Lab (orchestra)                         |
| 15 (15/06)        | UDP Lab (orchestra)                            | **UDP Lab (orchestra) (grade, weight 1)**   |


## Repo for the labs

| Title          | Repo (new repos need to be created for 2021)                 | Webcasts                                                     | Graded |
| -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| Chill Protocol | https://github.com/jehrensb/Teaching-HEIGVD-RES-2021-Chill-EE| https://www.youtube.com/playlist?list=PLfKkysTy70QaN-uez0K4UpSpVUbt8ETpk (12 webcasts, ~2 hours). *We need to update this, in order to use GitHub Actions instead of TravisCI.* Also see [this article](https://medium.com/software-engineering-heig-vd/network-programming-res-prelude-eab67078955a) on Medium. | no        |
| Labo Java IO   | https://github.com/jehrensb/https-github.com-SoftEng-HEIGVD-Teaching-HEIGVD-RES-2021-Labo-Java-IO | 3 webcasts have been added to the RES 2021 playlist          |        |
| Protocol design exercise | https://github.com/jehrensb/Teaching-HEIGVD-RES-2021-Exercise-Protocol-Design | 1 webcast has been added to the RES 2021 playlist.           | no     |
| SMTP                     | https://github.com/jehrensb/Teaching-HEIGVD-RES-2021-Labo-SMTP | 4 webcasts have been added to the RES 2021 labo playlist.         | yes    |
| Web Infrastructure       | https://github.com/jehrensb/Teaching-HEIGVD-RES-2021-Labo-HTTPInfra | 12 webcasts have been added to the RES 2021 playlist         | yes    |
|                          |                                                              |                                                              |        |
|                          |                                                              |                                                              |        |
|                          |                                                              |                                                              |        |

## Resources

- YouTube [playlist cours](https://www.youtube.com/playlist?list=PLP7INXz-ovzWxIIar7Lmp9tK2mmc7taEJ)
- YouTube [playlist labos](https://www.youtube.com/playlist?list=PLfKkysTy70QY_C0t9avTuEsLVVObxOtTM)

## Week 0

* Slow introduction: objectives, semester planning
* Compared to the full-time class, we will spend 2 weeks for the first course / labo
* EE will therefore be 1 week behind PT. 

## Week 1

* Course introduction: objectives, semester planning, intro to first lab
* The "Chill Protocol" lab
  * Get familiar with the GitHub workflow
  * Get familiar with toolset and practices that will be used during the semester (maven, lombok, JUnit)
  * See a first example of a "communication" protocol 
* [Slides](./slides/00-Introduction-JER.pptx)

## Week 2

* Java IO, part 1
* [Slides part 1](./slides/01-JavaIOs-p1-JER.pdf)
* The Java IO Lab (file operations)


## Week 3

* Java IO, part 2
* [Slides part 2](./slides/01-JavaIOs-p2-JER.pdf)
* The Java IO Lab (file operations)

## Week 4

* Webcast for the lab: https://www.youtube.com/watch?v=95GwsyiSMXI (added to the RES 2021 playlist)
* TCP programming, part 1
* [Slides](./slides/02-TcpProgramming-p1-JER.pdf) and [extra slides](./slides/02-TcpProgramming-example.pdf).
* Recommended activities for the lab:
  * Start by reading the guidelines in the lab repo (https://github.com/jehrensb/Teaching-HEIGVD-RES-2021-Exercise-Protocol-Design)
  * Do the exercise in a pair
  * Watch my solution (Webcast)
  * Redo the exercise (make sure that you are able to reapply the process for another protocol)
  * Read and run the TCP examples

## Week 5

* TCP programming, part 2
* [Slides](./slides/02-TcpProgramming-p2-JER.pdf) and [extra slides](./slides/02-TcpProgramming-example.pdf).
* Recommended activities for the lab:
  * Work in pairs
  * One student implements the client
  * One student implement the server
  * Try to make the client and the server work together, troubleshoot and review each other code

## Easter Break


## Week 6

Written test

## Week 7

* The Simple Mail Transfer Protocol (SMTP)
* Theory and demos on Thursday, lab on Friday
* [Slides](./slides/03-SMTP-JER.pdf)


## Week 8

* HTTP Protocol and Docker
* [Lecture notes](./lectures/04-Lecture4-HTTP.md) 
* [Slides](./slides/04-HTTPProtocol-p1-JER.pdf) 
* The Docker Playlist: https://www.youtube.com/playlist?list=PLfKkysTy70QbseGZcVbpTXhas2xrXKk61
* The HTTP Playlist: https://www.youtube.com/playlist?list=PLfKkysTy70QZG5eUH6nyLrUZLn8Hnlf86


## Week 9

* HTTP Protocol and Docker
* [Lecture notes](./lectures/04-Lecture4-HTTP.md) 
* [Slides](./slides/04-HTTPProtocol-p2-JER.pdf) 
* The Docker Playlist: https://www.youtube.com/playlist?list=PLfKkysTy70QbseGZcVbpTXhas2xrXKk61
* The HTTP Playlist: https://www.youtube.com/playlist?list=PLfKkysTy70QZG5eUH6nyLrUZLn8Hnlf86

## Week 10

* HTTP infrastructure
* [Lecture notes](./lectures/05-Lecture5-WebInfrastructure.md) 
* [Slides](./slides/05-WebInfrastructures-p3-JER.pdf) 
* The work on the HTTP infrastructure is not hard, but time consuming. You will be working in pairs, but be careful that each student does the work and understands the procedure. Otherwise, you will have a hard time at the exam.

## Week 11

## Week 12

* Test 2
* This test will focus on the SMTP and HTTP protocols, as well as on Docker.
* The content of the "HTTP infrastructure" lecture is NOT part of this test. We will keep it for the exam.
* There will very probably be a practical part, like for the first test. So make sure that you have a running Docker installation on your machine, that you have the toolset presented in the videos (e.g. curl, postman) ready to be used. 

## Week 13

## Week 14

## Week 15


