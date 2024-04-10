---
description: Connecting Your Machine
---

Now that Localportal is installed, you can connect your machine to Localportal with a name for your machine. You can connect in two ways: using the "local only" mode for accessing your machine from local network and the default mode for public access.

# Local Only

For users who prefer not to connect through the internet or do not require public access, Localportal offers a **free** local network mode that doesn't even require user to login. This mode uses multicast DNS to provide a .local URL, accessible only within your local network. To learn more, read [local network mode](/docs/core-concepts/local-only/).

### Activating Local Network Mode

Run the following command to start Localportal in local network mode:

```bash
localportal link <your-machine-name> --local
```

Replace <your-machine-name> with a name you choose for your machine. This name helps you easily identify your machine in the Localportal environment. Note that this mode does not require signing in or an API key. It provides an immediate, secure way to access your machine locally.

### Accessing Your Machine

- Local URL: After running the command in local network mode, you'll receive a .local URL. This URL can be used on any device within the same local network to access your Localportal desktop.
- Security: Access is secured within your local network, ensuring that only devices connected to the same network can reach your Localportal desktop. But your local desktop is also sit behind a basic password authentication that you setup during the first connection over local URL


# Public Access

To connect your machine for public access and get a unique and secure public URL, use the same command without the `--local` flag:

```bash
localportal link <your-machine-name>
```

Replace <your-machine-name> with a name you choose for your machine. This name helps you easily identify your machine in the Localportal environment.

### Authentication

After running the above command, Localportal will prompt you for authentication. Follow the instructions on the screen go create an account if you don't have one. If you do have an account,
the instructions on the terminal will guide you to get the API key that you need to copy and paste for once. Once authenticated, your machine will be linked to Localportal, and you'll receive a unique public URL for accessing your pseudo desktop remotely. This is a secure URL and by default only you'll be able to access the machine. Refer to [desktop sharing](/docs/desktop-sharing/desktop-sharing/) to learn how to share your desktop with others.

Congratulations! You're now ready to explore the world of Localportal and experience accessibility like never before. Dive in and discover how Localportal adapts to your needs, effortlessly.


