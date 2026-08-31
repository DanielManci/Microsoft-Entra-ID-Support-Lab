# Microsoft Entra ID Support Lab

A practical Microsoft Entra ID support lab demonstrating cloud user provisioning, first sign-in configuration, password management and authentication troubleshooting in a controlled test environment.

## Lab Objectives

- Create and manage a cloud user in Microsoft Entra ID
- Verify successful first sign-in
- Handle the initial password-change process
- Investigate authentication and sign-in issues
- Review Microsoft Entra sign-in activity
- Document troubleshooting steps and verification

## Environment

- Microsoft Azure
- Microsoft Entra ID
- Microsoft Entra admin centre
- Chrome / Incognito browser sessions
- Test user account: `Alex Morgan - Test User`

## User Provisioning

I created a new Microsoft Entra ID test user named `Alex Morgan - Test User` with a unique User Principal Name within the lab tenant.

![Test user created](screenshots/01-test-user-created.png)

The account was enabled and configured with an automatically generated temporary password for the initial sign-in.

## First Sign-In and Password Change

I signed in using the newly created test account in a separate browser session.

Microsoft required the temporary password to be replaced during the first sign-in. After completing the password change, the test user successfully accessed the Microsoft account portal.

![Test user first sign-in](screenshots/02-test-user-first-signin.png)

This confirmed that the cloud user had been provisioned successfully and could authenticate using the new credentials.
