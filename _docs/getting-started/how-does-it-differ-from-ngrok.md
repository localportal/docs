---
description: How does it differ from Ngrok?
---

At first glance, some people might confuse Localportal as a clone of Ngrok, a popular reverse tunneling service. While both platforms offer the capability to expose local machines to the internet, Localportal goes far beyond simple tunneling. The purpose of this documentation page is to clarify the similarities and differences between Localportal and Ngrok, highlighting the unique features and advantages that Localportal brings to the table.

While ngrok is a useful tool for exposing local services and recently added support for production ingress, it primarily focuses on tunneling and does not offer the full range of features and functionality provided by Localportal's pseudo operating system and built-in apps. Localportal is a powerful and versatile SaaS platform that enables users to create a [pseudo operating system](/docs/core-concepts/pseudo-os/) on their local machines or cloud computers. With Localportal, users can access a remote desktop environment through a web browser, complete with a range of [built-in apps and tools](/docs/getting-started/features/). It is designed to provide a comprehensive remote access solution. Whether you need to access a [remote terminal](/features/get-secure-terminal-access-to-any-machine-instantly/), [manage files](/features/remote-filesystem-that-looks-like-your-local-one/) on a remote machine, work with [Jupyter notebooks](/features/get-jupyter-notebook-on-any-machine-in-one-click/), or [expose specific ports](/features/a-unique-method-to-expose-localhost-to-internet-step-by-step-guide/), Localportal has you covered. It also includes features like [local network mode](/docs/core-concepts/local-only/), and the ability to [share your entire desktop](/docs/sharing-and-collaboration/desktop-sharing/) with others. One of the key features of Localportal is its ability to provide public URLs for users' machines, allowing easy access from anywhere and that is what is causing some people to confuse Localportal with Ngrok.

## Ngrok

Ngrok is a popular tunneling service that allows developers to expose their local development environments to the internet securely. It provides a simple way to create public URLs for locally running web services and applications.

#### Key features of ngrok include:

- Secure tunneling: Ngrok establishes encrypted tunnels between the local machine and the ngrok server, ensuring secure access to local services from the public internet.
- Instant domains: Developers can quickly generate public URLs that point to their local services, making it easy to share and access them remotely.
- Traffic inspection: Ngrok provides a web interface and API for monitoring and debugging traffic flowing through the tunnels.
- Production Ingress


## Similarities and Differences

Localportal is a platform that enables users to create a pseudo operating system on their local machines or cloud computers. With Localportal, users can access a remote desktop environment through a web browser, complete with a range of built-in apps and tools. One of the key features of Localportal is its ability to provide public URLs for users' machines, allowing easy access from anywhere and that is what is causing the ambiguity between Localportal and Ngrok.

| Feature                            | Localportal                                                      | Ngrok                                                                               |
|------------------------------------|------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| **Core Functionality**             | Creates a pseudo operating system on local or cloud machines.    | Provides secure tunneling to expose local services to the internet.                 |
| **Remote Desktop**                 | Yes, a range of built-in apps accessible via a web browser.      | With RDP                                                                            |
| **Public URLs for Machines**       | Yes, allows easy access from anywhere.                           | No                                       |
| **Public URLs for Exposed Ports**  | Yes                                                              | Yes                                       |
| **Built-in Apps**                  | Yes, including terminal, filesystem, Jupyter notebooks, and more.| No                                                                    |
| **Local Network Mode**             | Yes, uses mDNS to get local-only URLs.                           | No                                                                          |
| **Desktop Sharing**                | Yes, allows sharing the entire (pseudo) desktop with others.     | With RDP                                                       |
| **Secure Tunneling**               | Yes                                                              | Yes                                    |
| **Instant Domains**                | Yes                                                              | Yes                         |
| **Traffic Inspection**             | Coming soon as an App                                            | Yes, includes a web interface and API for monitoring traffic.   |
| **Production Ingress**             | No                                                               | Yes                   |



