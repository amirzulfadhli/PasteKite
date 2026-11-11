# PasteKite

A context-aware clipboard manager built for developers

PasteKite is a window application designed to make, copying, organizing and reusing programming related content easier

## About the Project

Programmers frequently copy and paste different types of content while working on projects, including code snippets, urls, json, file paths and terminal commands.

However, regular clipboard tools mainly focus on storing copied text. They dont provide tools to understand, organize or transform developer specific content.

PastKite aims to solve this problem by combining clipboard history with content recognition and useful text transformations in one desktop application.

The goal is to reduce repetitive formatting and make frequently copied information easier to find and reuse.

## Planned Features

### Clipboard Management

1. Automatically capture copied text
2. Display recent clipboard entries
3. Search through clipboard history
4. Reuse previously copied content
5. Delete individual entries or clear history

### Context Aware Recognition

1. Detect JSON content
2. Recognize URLs
3. Identify file paths
4. Recognize basic programming code snippets
5. Suggest relevant actions based on the detected content

### Developer Utilities

1. Format and minify JSON
2. Clean unnecessary white/blank space
3. Convert between compatible file path formats
4. Apply common text transformations
5. Preview transformed text before copying it

### Privacy and Control

1. Store clipboard history locally
2. Pause or resume clipboard monitoring
3. Clear stored clipboard data
4. Operate without user accounts or cloud synchronization

//All features are currently planned and have not yet been implemented

### Tech Stack

| Technology | Purpose |
| --- | --- |
| JavaScript | Application logic and clipboard processing |
| HTML | Application interface |
| CSS| Interface styling |
| Electron | Windows desktop applicaiton framewrok |
| JSON | Local clipboard history storage |
| Git & GitHub | Version control and project documentation |

//Tech stack may change as developement progresses

## How it Works

1. The user copires text from another application
2. PasteKite detects the clipboard change
3. The copied text is saved to local clipboard history
4. PasteKite analyzes the content to identify its type
5. Relevant transformation options are displayed
6. The user selects an action and previews the result
7. The transformed content can be copied back to the clipboard

## Installation and Running the Project

Status: not yet available

## Planned requirements

- Windows 10/11
- Node.js and npm
- Git

## Planned Developement Setup

1. Clone the PasteKite repository
2. Open the project directory
3. Install the required npm dependencies
4. Run the application using the configured developement command

//The exact terminal commands and tested installation guide will be added after complete developement of MVP

## Developement Journey 

### Planned Developement Milestones

| Phase | Developement Work |Estimated Hours |
| --- | --- | --- |
| 1 | Planning, README, requirements | 1h |
| 2 | Project setup and basic interface | 2h |
| 3 | Clipboard monitoring | 3h |
| 4 | Clipboard history and lcoal storage | 4h |
| 5 | Content recognition | 3h |
| 6 | Search and filtering | 2h |
| 7 | Smart transformations | 4h | 
| 8 | Transformation preview | 2h |
| 9 | Interface improvements | 2h |
| 10 | Testing, documentation, release | 2h |


//There are estimated planning target, not actual developement time

## Challenges and lessongs learned

This section will document real problems encountered during developement, including debugging, technical decisions, unsuccessul approaches and improvements

## Screenshots and Demo

Screenshots and GIFs demonstrating the applicaiton will be added once the interface and core features have been developed

## Project Scope

The initial version focuses on providing a working, locallt operated clipboard manager with developer focused utilities

Features outside the initial scope:

- Cloud synchronization
- Multi device clipboard sharing
- User account management
- Ai generated clipboard suggestions
- Online clipboard storage

## Future improvements

Possible improvements after initial developement:

- Keyboard shortcuts for faster access
- Pinne/favourite clipboard entries
- Support for additional content formats
- Custom user defined transformations
- Improved content detection accuracy

//These are potential additions rather than actual features

## AI Disclosure 

AI assistance was used to help organize project structure, suggest scope&tech

Developement, implementation debugginf and testing will be made by myself

This disclosure will be updated to accurately descrive any additional AI assistance during the project developement/implementation.

## Project Goal 

Create functional clipboard manager that improves how developers manage frequently copied information, while learning deskstop application developement, event handling, local data storage, content processing and software testing