## Brief

### Preparation

Self Study Check In

Q1: What will you choose Agile Methodology or Waterfall?

Q2: What software do you know that is part of CICD?


### Lesson Overview

IT software deployment is a necessity in any organization’s IT environment. Software deployment can either make or break the transitions between software, which significantly affect business operations. That is why it’s essential to have a solid software deployment process in place.

---

## Part 1 - Software Deployment

![image](https://user-images.githubusercontent.com/106639884/196575951-1401e0c1-443d-4c18-83b4-e89a992ce08d.png)


Software deployment involves all the activities required to get a software system or application ready for use on a device or a server. Software deployment is also commonly known as application deployment. Using software deployment software will help to ensure that all applications in your organization’s environment operate smoothly.

The Software Development Life Cycle (SDLC) refers to a methodology with clearly defined processes for creating high-quality software. in detail, the SDLC methodology focuses on the following phases of software development:

### Main 6 stages of SDLC

**1. Identify the Current Problems**

“What are the current problems?” This stage of the SDLC means getting input from all stakeholders, including customers, salespeople, industry experts, and programmers. Learn the strengths and weaknesses of the current system with improvement as the goal.

**2. Plan**

“What do we want?” In this stage of the SDLC, the team determines the cost and resources required for implementing the analyzed requirements. It also details the risks involved and provides sub-plans for softening those risks.

**3. Design**

“How will we get what we want?” This phase of the SDLC starts by turning the software specifications into a design plan called the Design Specification.

**4. Build**

“Let’s create what we want.” At this stage, the actual development starts. It’s important that every developer sticks to the agreed blueprint.

**5. Code Test**

“Did we get what we want?” In this stage, we test for defects and deficiencies. We fix those issues until the product meets the original specifications.

**6.Deployment & Maintenance**

“Let’s start using what we got.”At this stage, the goal is to deploy the software to the production environment so users can start using the product. The plan rarely turns out perfect when it meets reality. Further, as conditions in the real world change, we need to update and advance the software to match.

SDLC is a process followed for a software project, within a software organization. It consists of a detailed plan describing how to develop, maintain, replace, and alter or enhance specific software. The life cycle defines a methodology for improving the quality of software and the overall development process.


### Deployment Methodologies

Selecting a methodology to establish a framework in which the steps of software development are applied. It describes an overall work process or roadmap for the project. Methodologies can include Agile development, DevOps, Rapid Application Development (RAD), Scaled Agile Framework (SAFe), Waterfall and others.

- Agile Methodology
- Waterfall Methodology

### Types of software deployment

**Basic Deployment**

Basic deployment is the simplest type of software deployment. This type updates all the target environments simultaneously without any process or strategy. Because it doesn’t deploy software in a slow and controlled manner, it is the riskiest.

**Blue-Green Deployment**

Blue-green deployment starts by having the original environment plus a duplicate environment. This enables you to preserve the old environment while deploying the new application simultaneously.

Once the new application is deployed, make sure that everything runs properly. If any issues crop up, traffic can be redirected to the old environment so that it continues to run seamlessly. When you’ve determined that the new environment is free of issues, you can switch back to the new environment and then end the old environment.

---

## Part 2 - CI/CD Concepts

CI and CD stand for continuous integration and continuous delivery/continuous deployment. In very simple terms, CI is a modern software development practice in which incremental code changes are made frequently and reliably. Automated build-and-test steps triggered by CI ensure that code changes being merged into the repository are reliable. The code is then delivered quickly and seamlessly as a part of the CD process. In the software world, the CI/CD pipeline refers to the automation that enables incremental code changes from developers’ desktops to be delivered quickly and reliably to production.

CI/CD allows organizations to ship software quickly and efficiently. CI/CD facilitates an effective process for getting products to market faster than ever before, continuously delivering code into production, and ensuring an ongoing flow of new features and bug fixes via the most efficient delivery method. 

![image](https://user-images.githubusercontent.com/106639884/196317207-2181407b-83a8-4c47-990d-4d2d1703c9d6.png)


![image](https://user-images.githubusercontent.com/106639884/196323086-5186d386-c140-47c9-96e7-d5d04b09a38a.png)


### CICD Tools
![image](https://user-images.githubusercontent.com/106639884/196317255-28111830-170b-48d1-929f-229fac39b2f1.png)


**CICD will be sharpen on Module 3**

---

## Part 3 - Containerization Concepts

Containerization is a form of virtualization where applications run in isolated user spaces, called containers, while using the same shared operating system (OS). One of the benefits of containerization is that a container is essentially a fully packaged and portable computing environment.

Everything an application needs to run—its binaries, libraries, configuration files, and dependencies—is encapsulated and isolated in its container. The container itself is abstracted away from the host OS, with only limited access to underlying resources—much like a lightweight virtual machine (VM). As a result, the containerized application can be run on various types of infrastructure—on bare metal, within VMs, and in the cloud—without needing to refactor it for each environment.

With containerization technology, there’s less overhead during startup and no need to set up a separate guest OS for each application since they all share the same OS kernel. Because of this high efficiency, containerization is commonly used for packaging up the many individual microservices that make up modern apps.

![image](https://user-images.githubusercontent.com/106639884/196323476-2f099a1f-da3e-4f1b-858c-809b3efbd741.png)


**Containerization will be sharpen on Module 3**
