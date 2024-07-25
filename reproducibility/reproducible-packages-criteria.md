---
layout: default
title: Selecting Packages/Libraries for Reproducible Software Projects
parent: Reproducible Computer Code
nav_order: 1
---

# Selecting Packages/Libraries for Reproducible Software Projects

Selecting the right software packages/libraries for reproducible software projects invovles balancing simplicity and functionality, which are important qualities for the success and sustainability of these projects. Below we provide you with some key considerations to keep in mind when choosing packages to ensure that they align with the goals of your projects and contribute to its long-term success.  

## Key Considerations for Selection

- ### Minimize Dependencies
    Select packages that come with minimal external dependencies, including the dependencies of the dependencies (the full dependency chain). By limiting the size of the technology stack the complexity the risk of dependencies becoming outdated, unsupported or unavailableover time is reduced.  

- ### Local Dependencies and Resources
    Check if all dependencies and resource can be stored locally and do not require network access. Any resources (code, data) that are stored on the network that are retrieved just in time may not be available in the future. Furthermore, networked resources will make it more challenging to preserve all dependencies and data in a way that maintains operability.  

- ### Documentation
    packages require clear instructions for installation, configuration, and usage. This documentation is necessary now and later to integrate these packages into your project. This knowledge may not be available in the future and a community of support may have ended, which makes it difficult to revive, modify or reuse a preserved product. All documentation of dependencies needs to be localized for preservation.  

- ### Community Support
    Check the availability of community support for the package. A wide and active community can greatly help in the development process by providing support, updates, and enhancements.  

- ### Open Source and Licensing
    Open source packages allow for collaboration and long-term maintenance by ensuring that everyone can access, modify, and redeploy the software. Use packages that are made freely available and may be redistributed and modified. Look for packages with public licenses that allow this free reuse. Avoid packages that require fees or have restrictions on deployment of related software. These restrictions will apply to any software that uses them, so it is best to avoid these restrictions on dependencies.  

- ### Version Control
    Check if the package uses a version control system like GitHub to track changes and manage updates. Version control helps in understanding the evolution of the package and facilitates collaboration among developers. Cloud version control systems encourage communities of support, and broad access to the source code or resource. However, a copy of the exact versions of all dependencies should be preserved with the project.  

- ### Resource Efficiency
    Choose packages that require minimal power consumption. Beyond the immediate benefits, this will allow the software to be executed in environments without access to high-end computing infrastructure. However, we appreciate that this is a difficult quality to evaluate.  
