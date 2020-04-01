# rosrect
Develop a standardized communication protocol and stack for remote intervention and resolution to increase uptime and avoid critical failure conditions of robotic solutions.

**NOTE: This project is under active development. Documentation will be added as and when features will become available. Until that first commit, this README will host general information such as objectives and timelines about the project.**

This project adheres to the Contributor Covenant [code of conduct](/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report any unacceptable behavior to [info@cognicept.systems](mailto:info@cognicept.systems). If you are interested in contributing, please refer to the guidelines [here](/CONTRIBUTING.md).

Table of Contents:
- [Problem Statement](#problem-statement)
- [Scope](#scope)
- [Deliverables](#deliverables)
- [Project Timeline](#project-timeline)

## Problem Statement

The best robots face downtime in any industry, not just because of robot based errors, but also operational errors stimulated by the environment of third party sensors and other processes. A higher number of errors are reported when the robots are deployed in new facilities or new scope of work, and thus significantly affecting the mass deployment of these robots. Robot companies with >10K deployments starts building their own standards, but a blind spot exists when the client works with multiple robot vendors for its operations. Moreover, there are certain applications that require a manual/supervised mode of operation, and a remote intervention tool becomes critical to support day-to-day operations.

Proposed are tools and services that will provide a generalised Error Classification Stack for the existing and future robot companies to monitor, manage and analyse the robot errors, assist the companies to reduce their downtime, and help them deploy robots at a new workplace with a complete insight of all the site based errors. Also proposed are remote intervention tools, that will allow remote site to intervene at the point of error or an operational call.
 
## Scope

- Define and Standardize a list of commonplace actions, activities and critical error classifications of robotic systems (mobile robots, collaborative robots, industrial robots) used in various commercial and industrial applications (services sector, warehousing, manufacturing and assembly/production lines, logistics/fulfillment centers etc).
- Design, develop, test and release a software solution that enables robotic edge devices to propagate its states and error conditions to a remote central system, for the purpose of getting remote assistance and directives on the next course of action that would enable it to revert back to a non-erroneous state (normal operating condition).
- Design and build a basic Remote Intervention tool, to allow robot companies to engage with their robots deployed on premises or at a remote site. 

## Deliverables

- Software architecture and design specification 
- Communication protocol specification - including standardized error messages, actions and types
- Software code modules (as ROS 2.0 packages) 
- Edge device communication stack implementation 
- Server side communication stack implementation 
- Readme file - describing clearly and in a structured and simple flow how to: o Install the package o Configure it for a target system and specific use case 
- Example code files and/or tutorials – at least two that describe different use cases 
- Test report that include: 

    * Compilation results 
    * Static analysis results 
    * Unit test results 
    * Functional/manual test results 
    * Performance/stress test results
    * System/integration test results

## Project Timeline

![alt text][timeline]

[timeline]: /docs/rosrect_project_timeline.png "Detailed Project Timeline"
