# Learning VIVO Development Workshop

Welcome to the open repository, documentation and materials for the Learning VIVO Development workshop at the VIVO 2018 Conference!

* When: Wednesday, June 6th, 2018, 8:30 AM - 11:30 AM
* Where: [**Meeting Room C**](http://vivoconference.org/schedule/#session-1)
* Workshop Materials: [github.com/j2blake/2018_dev_Workshop](https://github.com/j2blake/2018_dev_Workshop)
* Workshop Code: [Vitro](https://github.com/j2blake/2018_dev_Vitro) and [VIVO](https://github.com/j2blake/2018_dev_VIVO) 
* Workshop Slides: [in this Repository](slides/)

## About the Workshop

The goal of this workshop is to provide developers with a practical, hands-on introduction to selected VIVO development approaches and debugging methods. We also hope to highlight the process for contributing back to the VIVO core code. The workshop is intended to encourage further developer engagement in the VIVO community and to help begin training developers and build a broader base of VIVO committers. 
We ask that all participants come to the workshop ready to dive in by reviewing the information in this document. If you want a sneak peak of the workshop's contents, feel free to also watch this repository (you'll be notified of updates). To watch this repository, sign into GitHub, go this repository's home URL, and click the "Watch" button on the top right of the page.


## Workshop Schedule

Time               | Topic                                                          | Leader(s)
------------------ | -------------------------------------------------------------- | ------------------------------------------
**8:30-8:40 AM**   | Overview and Introductions (10 minutes)                        | Whole Group
**8:40-9:10 AM**   | Set up your development environment (20 minutes)               | [Don](mailto:elsborg@colorado.edu)
**9:10-9:20 AM**   | VIVO Architecture (10 minutes)                                 | [Jim](mailto:jeb228@cornell.edu)
**9:20-9:45 AM**   | Deep dive: VIVO starts up (25 minutes)                         | [Jim](mailto:jeb228@cornell.edu)
**9:45-10:05 AM**  | Developing: Debugging VIVO in Eclipse (20 minutes)             | [Huda](mailto:hjk54@cornell.edu)
**10:05-10:15 AM** | Break (10 minutes)                                             | n/a
**10:15-10:25 AM** | Deep dive: Unit tests in VIVO (15 minutes)                     | [Jim](mailto:jeb228@cornell.edu)
**10:25-10:35 AM** | Developing: The Developer Panel (10 minutes)                   | [Jim](mailto:jeb228@cornell.edu)
**10:35-10:45 AM** | Deep dive: Search Index Configuration (10 minutes)             | [Jim](mailto:jeb228@cornell.edu)
**10:45-11:05 AM** | Developing: Search Index Configuration  (20 minutes)           | [Huda](mailto:hjk54@cornell.edu)
**11:05-11:30 AM** | Developing: Pull Request process and interaction (25 minutes)  | [Andrew](mailto:awoods@duraspace.org)


## Contact Before, During, After the Workshop

If you have questions or concerns leading up to or after the workshop, please open an issue on this GitHub repository, particularly with any questions dealing with workshop preparation or any installation issues. This allows multiple workshop leaders to respond as able, and other participants can also learn (since we're sure the same questions will come up multiple times): https://github.com/j2blake/2018_dev_Workshop/issues (this will require that you login or create a free account with GitHub).

During the workshop, we will indicate the best ways to get help or communicate a question/comment - however, this workshop is intended to be informal, so feel free to speak up or indicate you have a question at any time.

## Our Expectations of You

To keep this workshop a safe and inclusive space, we ask that you review and follow the [Duraspace Code of Conduct](http://www.duraspace.org/about/policies/code-of-conduct/) and [the Recurse Center Social Rules (aka Hacker School Rules)](https://www.recurse.com/manual#sub-sec-social-rules).

## Participant Requirements

We request that all participants:
- You should bring a laptop with a modern web browser and at least 4Gb memory (at we strongly recommend, if you want to play with more than intro data, at least 6Gb);
- Please have Vagrant and Virtual Machine downloaded per these instructions: [installation instructions](installation/README.pdf)

If you have any issues with the above, please contact us ASAP using the [communication methods detailed above](#contact-before-during-after-the-workshop).

### Running Virtual Machine and Vagrant

- [Virtual machine and Vagrant installation instructions](installation/README.pdf)
- [Virtual machine/Vagrant on Mac OS](https://docs.google.com/document/d/1JeU_PnLOPIFbtgLPJdE8uaZ_BKoKwE3Y7an2d89OkvU/edit?usp=sharing) or [in this repo](installation/Vagrant%20on%20Mac%20OS.pdf)

### Backup Option (full environment without a virtual machine or vagrant)
- [Installation  on Mac](https://docs.google.com/document/d/10s2WjPp0u7jwrx8qVqG1qn8tM_EgHwIlNkciolrMNT0/edit?usp=sharing) or [in this repo](installation/Installation%20Notes_%20Mac%20using%20Homebrew.pdf)
- [Installation on Windows](https://docs.google.com/document/d/1hDUJq0kxRGRkMLDUMu_k4Q0Yhmn0r5Qq79GnKW432R0/edit?usp=sharing) or [in this repo](installation/Installation%20Notes_%20The%20old%20fashioned%20way.pdf)

### Workshop code
- We will be working with our copies of the Vitro and VIVO code using [Vitro](https://github.com/j2blake/2018_dev_Vitro) and [VIVO](https://github.com/j2blake/2018_dev_VIVO) respectively.  For VIVO, checkout the branch "workshopBranch" as this will be the code we will walk through and debug together . The "functioningBranch" branch has the working version of the code that does not require any fixes and you can use that as a reference.

#### Copied liberally from the README for https://github.com/spark4lib/code4lib2018