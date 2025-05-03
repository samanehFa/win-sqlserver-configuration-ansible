# Ansible Role: configuration of Windows MSSQL with Ansible

This Ansible role is designed to install secure files and bootstrap secret handling for a system using predefined configuration and installation assets.

## Role Structure

This role expects a `files/` directory containing any necessary installation files or scripts. You can modify this folder to include:

- Configuration files
- Installer scripts
- Secret templates
- Static binaries

## CI/CD Compatibility

This role is built with automation in mind. You can run it directly in your CI/CD pipeline (GitHub Actions, GitLab CI, Jenkins, etc.) by:

- Supplying secrets as environment variables or pipeline secrets
- Using Ansible in a non-interactive mode
