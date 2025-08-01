# Steps to work with Git and GitHub

## Create a GitHub Account

1. Go to [GitHub](https://github.com).
2. Click on "Sign up" in the top right corner.
3. Follow the prompts to create your account.
4. Verify your email address.
5. Set up your profile with a username, bio, and profile picture.

## Install Git

1. Download Git and install with default settings.
2. Verify installation by opening a terminal and typing:

```bash
   git --version
```
3. Configure your Git username and email for working with GitHub:

```bash
   git config --global user.name "your_username"
   git config --global user.email "your_email"
```

## Install GitHub CLI

1. Download the GitHub CLI from [GitHub CLI](https://cli.github.com/).
2. Install it following the instructions for your operating system.
3. Verify installation by opening a terminal and typing:

```bash
   gh --version
```

4. Authenticate with GitHub:

```bash
   gh auth login
```

5. Follow the prompts to authenticate via web or token.
6. Verify authentication by typing:

```bash
   gh auth status
```