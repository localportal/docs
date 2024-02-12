---
description: Getting started with Localportal
---

Getting started with Localportal is a breeze, and one of the key concepts you'll encounter is a "Link." This simple yet powerful term refers to the connection created when you link your machine to Localportal using the localportal agent. Each Link, identified by a unique link name, represents a new pathway to accessibility. Now, let's dive into setting up and linking your machine to Localportal!

## Installation

### Mac (intel & m1/m2)
Install Localportal using Homebrew with the following command:

```bash
brew install localportal/tap/localportal
```


### Linux/Unix variants
For all other OS, run the following command:

```bash
curl -L https://localportal.io/install | sh
```

### Windows

For users on Windows, Localportal can be installed using the Windows Subsystem for Linux (WSL). 

```bash
curl -L https://localportal.io/install | sh
```

Localportal does not currently offer native support for Windows operating systems. We are committed to broadening our platform compatibility and encourage users to express their interest in Windows support by providing feedback [here](https://localportal.io/support).

### Docker

Docker support for Localportal is in our roadmap, and our development team is working diligently to bring this feature to you. Your input and feedback can guide our development priorities, so if Docker support is essential for your use case, please upvote the feature request on our [support page](https://localportal.io/support).


## Connecting Your Machine

Now that Localportal is installed, you can connect your machine to Localportal with a unique name using the following command:

```bash
localportal link <your-machine-name>
```

This will require authentication, and all you need to do is follow the instructions shown on the terminal or the browser page that opens.

Congratulations! You're now ready to explore the world of Localportal and experience accessibility like never before. Dive in and discover how Localportal adapts to your needs, effortlessly.

