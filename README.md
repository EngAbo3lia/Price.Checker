#

<h1 align="center">
  <b> Al-Anfal Price Checker Solution <p align="center">
  </p></h1><br/>
#### Project Overview

The Al-Anfal Price Checker Solution is a comprehensive application designed to streamline the process of checking product prices within the SAP Business One environment. This solution leverages .NET WinForms, SAP Business One Service Layer, and OData services to provide a seamless and efficient user experience for product information retrieval and display.

#### Key Features

- **User-Friendly Interface**: Intuitive WinForms interface for easy navigation and use.
- **Real-Time Data Retrieval**: Instant access to product information and prices from SAP Business One.
- **Splash Screen**: Professional and polished splash screen with configurable timing.
- **Barcode Scanning**: Efficient product lookup by barcode integration.
- **Extensible Controls**: Custom control extensions to enhance standard WinForms functionality.
- **Secure Credentials Management**: Robust handling of server credentials and session data.
- **Service Layer Integration**: Comprehensive utilization of SAP B1 Service Layer for data operations.

#### Technical Details

##### Price Checker (Win Form App)

- Main Entry Point
  - Program Class
    - **Description**: The primary entry point for the application.
    - **Functionality**: Initializes a new instance of `ProductService` with the required credentials and database implementation type.

##### Services

- ProductService Class
  - **Description**: Service layer responsible for product-related operations.
  - **Functionality**: Implements the `Find Product` function to fetch product details based on barcode input.

##### Forms

- ProductInfo Form

  - **Description**: Main screen of the application.

  - Functionality

    :

    - Handles splash screen timing.
    - Sends barcode data to `ProductService`.
    - Updates UI fields with product details returned from the service.

##### Helpers

- ControlExtensions Class
  - **Description**: Extends standard WinForms controls.
  - **Functionality**: Provides additional properties and methods to enhance standard controls.

##### Service Layer Helper (Helper Lib)

- Connected Services
  - ODataService / OData
    - **Description**: Enables consumption of Service Layer OData services from .NET via WCF.
    - **Functionality**: Contains connected service reference models.

##### Connection

- **Credentials Class**

  - **Description**: Stores server credentials for test and production environments.

  - Attributes

    :

    - Service Layer URI
    - Company DB
    - Username
    - Password

- **Session Class**

  - **Description**: Container for service layer session data.

##### Models

- Product Class
  - **Description**: Represents the product model.
  - **Attributes**: Includes methods and properties related to product information.

##### Services

- ServiceLayer Class

  - **Description**: Consumes SAP Business One data and services.

  - Functionality

    :

    - Connect and disconnect from the SAP B1 Service Layer.
    - Find products and retrieve their prices.
    - Prepare product data for display in the `ProductInfo` form.

##### Helpers

- ApiHelper Class
  - **Description**: Manages API requests to the SAP B1 Service Layer.
  - **Functionality**: Initializes the RestSharp client with server credentials for making GET or POST requests.

#### Tools & Technologies

- **Programming Languages**: C#, .NET
- **Frameworks**: WinForms, WCF
- **APIs**: SAP Business One Service Layer, OData
- **Libraries**: RestSharp

#### Additional Information

- **Development Duration**: 3 months

- **Team Size**: 2 developers

- **Client**: Al-Anfal Company

- **Role**: Lead Developer

- Responsibilities

  :

  - Designed the application architecture.
  - Developed the main features and functionalities.
  - Integrated SAP Business One Service Layer.
  - Implemented secure credential management.
  - Conducted testing and debugging.

This project showcases expertise in developing enterprise-level solutions with SAP Business One integration, highlighting skills in .NET development, API integration, and user interface design.


### How to Install
[![How to Install][HowToInstall1]]()

[![How to Install][HowToInstall2]]()

[![How to Install][HowToInstall3]]()

[![How to Install][HowToInstall4]]()

[![How to Install][HowToInstall5]]()

[![How to Install][HowToInstall6]]()

[![How to Install][HowToInstall7]]()

[![How to Install][HowToInstall8]]()

[![How to Install][HowToInstall9]]()

[![How to Install][HowToInstall10]]()


[HowToInstall1]: /images/1.jpg
[HowToInstall2]: /images/2.jpg
[HowToInstall3]: /images/3.jpg
[HowToInstall4]: /images/4.jpg
[HowToInstall5]: /images/5.jpg
[HowToInstall6]: /images/6.PNG
[HowToInstall7]: /images/7.jpg
[HowToInstall8]: /images/8.jpg
[HowToInstall9]: /images/9.jpg
[HowToInstall10]: /images/10.jpg
