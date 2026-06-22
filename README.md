# Leveraging SmartNICs for HPC Applications

Tutorial at ISC High Performance 2026

**Held on**: Monday, June 22, 2026, 9:00 AM - 1:00 PM; Hall X11 (1st Floor)

[Event website and Program](https://isc-hpc.com/program/schedule/)

![BlueField 3 SmartNIC](fig/isc25_hamburg.jpg)

## Audience Tutorial Survey

Please fill out this short (3 question) attendee survey here in addition to the ISC survey. 

- [ISC Survey](https://ssl.linklings.net/conferences/isc_hpc/?page=SessionEval&id=sess328&new_year=ischpc2026)
- [DPU Tutorial Content Feedback Survey](https://forms.office.com/Pages/ResponsePage.aspx?id=u5ghSHuuJUuLem1_Mvqgg82dnXP1iqRHvc472TcBXahUMjk2TlhCWkFPVEpESDBVRDk2RlYzREJEQy4u)

## Presenters

* Jeffrey Young [(Georgia Institute of Technology)](https://crnch-rg.cc.gatech.edu/)
* Antonio Peña [(Barcelona Supercomputing Center)](https://www.bsc.es/)
* Elie Kfoury [(University of South Carolina)](https://sc.edu/study/colleges_schools/engineering_and_computing/faculty-staff/elie_kfoury.php)
* Richard Graham [(NVIDIA)](https://www.nvidia.com/)

**Abstract:** The past few years have witnessed an increased level of support for and deployment of programmable network adapters, known as "SmartNICs". These enhanced network devices offer standard packet processing capabilities as well as advanced "in-network" computing features built around programmable lightweight processing cores, FPGAs, and even CPU- and GPU-based platforms capable of running separate operating systems. SmartNICs have gained rapid adoption for data center tasks, including infrastructure management, packet filtering, and I/O acceleration. Increasingly these devices are also being explored for high-performance computing (HPC) and AI application acceleration.

This tutorial offers an in-depth exploration of the state-of-the-art for SmartNICs and the emerging software ecosystems supporting them. Attendees will engage in hands-on exercises to better understand how to take advantage of SmartNICs for accelerating HPC and AI applications. Specific topics include MPI and OpenMP offloading, algorithmic modifications to utilize SmartNIC processors, in-line packet processing frameworks like P4, security and containerization efforts, and I/O acceleration techniques. Participants will have the opportunity to execute these exercises using cutting-edge SmartNICs like NVIDIA's BlueField-3 Data Processing Unit (DPU) and a cloud-based Netlab environment. The tutorial presenters will discuss additional techniques for optimizing applications to harness SmartNICs as communication accelerators in HPC systems.

Please note that tutorials require a separate registration category for ISC High Performance 2026 attendees.

[Register here](https://isc-hpc.com/attendance/registration/)

## Tutorial Date/Time

Official ISC 2026 schedule slot:

* Monday, 22nd of June, 2026
* 9:00 AM - 1:00 PM
* Hall X11 (1st Floor)

Conference schedule reference: [ISC 2026 Schedule](https://isc-hpc.com/program/schedule/)

# Tutorial Agenda

| Time | Topic | Details |
|------|-------|---------|
| 9:00–9:10 | Introduction | Attendee Survey; intro to Hands-On |
| 9:10–9:25 | Communication Offloading | SmartNIC overview; DPU examples; DPU programming models |
| 9:25–9:40 | SmartNIC Use Cases | Packet processing, cyber-security, AI/HPC |
| 9:40–9:55 | Infrastructure SW – DOCA and P4 Introduction | Brief introduction to DOCA/P4 |
| 10:00–10:30 | HPC Programming – Part 1 | MPI Offload; DPA Programming |
| 10:30–11:00 | HPC Programming – Part 2 | OpenMP Offload |
| 11:00–11:30 | **BREAK** | |
| 11:30–11:45 | Hands-on DOCA/P4 | Attendees follow along in compiling and running test examples |
| 11:45–11:55 | Hands-on DPA Demo | |
| 11:55–12:15 | Hands-on HPC Demo – OpenMP/MPI Offload | |
| 12:15–12:30 | Storage Acceleration | Discussion of use case for SmartNICs with storage systems for AI |
| 12:30–12:35 | Tutorial Survey | |
| 12:35–1:00 | Continued Hands-on Activities | Time to work with the instructors on the presented demos and test cases |

## Hands-on Examples

See the "hands-on" folder for and overview of the hands on examples and pointers to specific source code. 

See the hands-on testbed login information at this [Google Doc](https://docs.google.com/document/d/1yV0nXo3pqqT7qdXVM6LqnOBwPGNvaoQ-dXFztc6gPts/edit?usp=sharing). Please note this will only be available for the week of the conference, but we will discuss options to follow on with further testing.

The following topics will be covered via selected hands-on modules using the [FABRIC testbed](https://fabric-testbed.net/) and [Netlab testbed](https://research.cec.sc.edu/cyberinfra/cybertraining).

Specific demos include the following:
- MPI and OpenMP offloading patterns for SmartNIC-enabled applications
- In-line packet processing frameworks such as P4
- BlueField-3 DPU practical exercises for DOCA and DPA programming

## Slides

Handouts/slides will be shared the day of the tutorial.
