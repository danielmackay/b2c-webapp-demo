# b2c-webapp-demo
Demo using Azure AD B2C to secure a Razor Pages Web App.

## Overview
Azure AD B2C can be thought of as "Identity for the Internet" as opposed to "Identity for Organisations".  It can be a great replacement where previously you might have had a local user database you managed directly.  Besides off loading the risk of leaking user passwords, Azure AD B2C can speed up implementing Identity for your application, and enable additional functionality like social logins, that would have previously been more difficult.

## Tech Stack
- Azure AD B2C
- ASP.NET Core Razor Pages
- .NET 5

The project was scaffolded using the following commands:

```
mkdir b2c-webapp-demo
cd .\b2c-webapp-demo\
dotnet new webapp --auth IndividualB2C
```

## User Flows
This solution uses Azure AD B2C to 3 user flows.  These flows are provided OOTB by identiy including the UI.

### Sign Up and Sign In
![Sign Up and Sign In](https://danielmackay.github.io/b2c-webapp-demo/images/susi.png)

### Edit Profile
![Edit Profile](https://danielmackay.github.io/b2c-webapp-demo/images/edit-profile.png)

### Reset Password
![Reset Password](https://danielmackay.github.io/b2c-webapp-demo/images/reset-password.png)

## Resources
- https://www.youtube.com/watch?v=oG9GcYIuYQM