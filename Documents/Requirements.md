# Requirements Document
FIFA MATCH TOOL

## 1 Introduction
The Fifa Match Tool is an Android Application that will accept user input and determine what Fifa team is appropriate for them. The logic is primarily based on the Fifa Team Flow Chart.

### 1.1 Definitions and Acronyms
List any project definitions and acronyms introduced to the project by this plan. Be sure and define all acronyms before their use.  If no acronyms or terms requiring special definition are used, this section can be left out.

## 2 User Requirements

### 2.1 Software Interfaces

List all the external systems with which the software product interacts. These are external systems/libraries that you have to interact with.

### 2.2 User Interfaces
The user will be asked a series of questions related to Fifa world cup teams. The user will have to provide an answer to an question and based on the response, it will generate a subsequence question to narrow down the proper fifa team. The user will have an option to go back to previous question and change their answer. 

Specify the logical characteristics of each interface between the software product and its users. This is a description of how the system will interact with its users.  Note that this should *not* be a description of the UI (that belongs in the design document), but rather a high level discussion of how the user will interact with the product.

### 2.3 User Characteristics
Describe the general characteristics of the intended users of the product, including educational level, experience, and technical expertise.

## 3 System Requirements
These subsections contain all the software requirements at a level of detail sufficient to enable 
designers/developers to design/develop a system that satisfies those requirements, and testers to test 
that the system satisfies those requirements. This part of the document should provide a numbered 
(possibly hierarchical) list of simple, complete, and consistent functional and non-functional 
requirements.

### 3.1 Functional Requirements
The application shall go to the start page when the user open the apps
The application shall have a restart button that will take the user to the main page
The application shall have a back button that goes to the previous question page
The application shall display the new question when the user select one of the answer

### 3.2 Non-Functional Requirements
The application shall go to the start page if the system crashes
The application shall give the same final country for the same sets of answers
The application shall take no longer than 1 sec to display the answer or go to the subsequence question
The application shall prevent the user from changing the questions
List the quality attributes that are important for your system (e.g., reliability, security) and explain why they are important for your system and how they will be measured.
