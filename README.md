Estimation of Work

Before we can use the functionality in our project, we must first license it. The three licenses that must be acquired are basic, part operations, and solid modeling. It usually takes three days to add the licenses to the project. Our to-do list also includes FlexLM implementation, licensing library, checkout license, check back in, initialize, and shut down licensing. The full API, as well as the automated API, will undergo changes. We'd like to be able to uncheck licenses we don't require. The most common licenses are those that we utilize regularly in scenarios.

Requirements

The major goals of our project are to create a fictitious FlexLM system that reads a text file of available licenses and to create a licensing library that sits on top of Flex LM Libraries. Cloud apps and desktop apps are among the requirements. To use the JSON API in cloud apps, we need some kind of authentication. We require a license toolkit that we can develop as a desktop application on our own. Flexera's FLEXLM toolkit is a paid toolkit that we employ. The team must create a local licensing file or a network license server. When the license server reads the license file, it validates the list of entitlements. The difficult aspect is dividing the code into sections that can only be accessible using the license features we desire. These are the most important considerations for the project.
Design Document

For Design Document (https://github.com/nikhithachaluvadi/SA_Final_Application/blob/01893a78b0666aeda2066b03fe60c5fcd834a644/DesignDocument)

Conclusions

  Requirements: The application's requirements are added. As we all know, requirements are divided into three categories: mandatory, desirable, and optional. The items that are marked as needed are included in our project. As part of our application, we include cloud and desktop apps.
  
  Design Document: The project also includes a design document in the read.md file, which provides all of the APIs. App component ops, automation binding and fake automation, journaling, and UI library are all included in the Journaling Layer APIs. Journaling part, partOps, dll main, and journaling session are all included in app part ops. Wirebuilder, feature collection, rooted collection, extrude, and block builder are all examples of automation binding.
  
  Unit Tests: In the project's core unit tests folder, unit tests are added. The test files for our application are the test.cpp and pch.cpp files, which contain unit tests.

Implementation: For our project, we created a fake FlexLM that reads the test files of available licenses. We used a licensing framework that was already in place.

Finally, we've incorporated the licensing capability to our project. Basic, component operations, and solid modeling are the three licenses that have been added to our software. The employed licensing toolkit is abstracted away. We made the API distinguish between UI and automation API requests to the functionality.
