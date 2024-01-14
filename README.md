**Project Overview: B5 - Application Development (B-DEV-500)**


**Action REAction - Automation Platform for Digital Life** 


> AREA Project Overview

Language: react(js), flutter, nodejs

**Summary:**
To construct a sophisticated automation platform, like IFTTT or Zapier, facilitating interactions between various digital services. 

**Key Components:**
1. **Application Server:** Core of business logic, orchestrating the interaction of various digital services.
2. **Web Client:** A browser-based interface for user interaction with the application server.
3. **Mobile Client:** Similar to the web client, but designed for mobile platforms.

**Functionality:**
- User Registration and Authentication
- Configuration of Actions and REActions (event-based triggers)
- Synchronization between web and mobile clients

**Technical Aspects:**
- Docker Compose for project construction
- Detailed API documentation
- Incremental development: from a proof of concept to a minimum viable product, and at the end in a fully-featured final product


## Contents

- [Installation](#installation)
- [Prerequisites](#prerequisites)
- [Documentation](#documentation)
- [Usage](#usage)
- [Commit-standard](#commit-standard)
- [Credits](#credits)


## Prerequisites
  - docker


## Documentation
Tutorial and documentation to implement new functions and services are here : [documentation](https://app.gitbook.com/o/tlBey3v2OgvQ70gwBrbP/s/39k5jNhW2EXTlTbB90lZ/docker/page-1)

## Installation


## Usage

#### :secret: <ins>.env</ins> 

- Make sure to have a .env with these datas in the server folder : 

```
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
REDIRECT_GOOGLE_URL=
CLIENT_URL=
TOKEN_SECRET=
ATLAS_URI=
```

- Make sure to have a .env with these datas in the client_web folder : 

```
REACT_APP_SERVER_URL =
```

#### :rocket: <ins>launching</ins> 

- In the client_web folder 

```shell
npm install
npm start
```
- In the server folder

```shell
npm install
npm start
```


## Commit Standard
By adhering to these standards, we aim to keep our codebase organized and our development process streamlined. 
We believe that a well-maintained commit history is a reflection of the team's dedication and professionalism.

Commit standard : [Website](https://www.conventionalcommits.org/en/v1.0.0/)


## Credits

* **Louis DE-CAUMONT**
* **Antoine DUFOUR**
* **Matthis BROCHETON**
* **Guillaume LE COZ**
* **Victor M. SMITH**