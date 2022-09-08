# This repository has been ARCHIVED
The example has moved into the [Post Login Action Template Repository](https://github.com/Auth0-Marketplace/TEMPLATE-action-post-login/tree/main/examples)

# Risk Score Example Action Integration

This repo contains an example for an Action that sends Auth0 profile data to a risk score API and makes decisions based on the response. The code in this repo is meant to be used as a starting point for an Action integration with a similar purpose and should not be used as-is in production. 

**Please Note:** The code in this repository should be used as an example to help write an Action integration, not used directly in production.

## Getting started

The code in the `integration/integration.action.js` file needs to saved to an Auth0 tenant ([sign up for free](https://auth0.com/signup)) in order to test how the Action is working. You can do this one of two ways:

### Manual deployment

The example Action code provided can be copied and pasted into the Auth0 Dashboard using the steps below. 

1. [Create a new custom Action](https://auth0.com/docs/customize/actions/write-your-first-action) using the code from the `integration.action.js` file
1. Change all instances of `event.configuration` to `event.secrets` in the Action code
1. Add all secret values and dependencies being used
1. Deploy and test the Action to make sure it's working properly

### Integration template deployment

The example Action can also be tested, linted, and deployed using the partner development tools provided by the [Action integration template](https://github.com/Auth0-Marketplace/TEMPLATE-action-post-login).

1. Clone or download the repo linked above
1. Copy the files from the `integration` directory in this example to the `integration` directory in the template
1. Follow the instructions in the template README to deploy the Action to your tenant

## Submitting your integration to Auth0

Follow the [submission instructions in the template](https://github.com/Auth0-Marketplace/TEMPLATE-action-post-login#submit-for-review) to prepare your integration for submission. 

## What is Auth0?

Auth0 helps you to:

* Add authentication with [multiple authentication sources](https://auth0.com/docs/identityproviders), either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, among others**, or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory, ADFS or any SAML Identity Provider**.
* Add authentication through more traditional [username/password databases](https://auth0.com/docs/connections/database/custom-db).
* Add support for [linking different user accounts](https://auth0.com/docs/link-accounts) with the same user.
* Support for generating signed [JSON Web Tokens](https://auth0.com/docs/jwt) to call your APIs and **flow the user identity** securely.
* Analytics of how, when, and where users are logging in.
* Pull data from other sources and add it to the user profile, through [JavaScript rules](https://auth0.com/docs/rules/current).

## Issue Reporting

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author

[Auth0](https://auth0.com)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file in this repo for more info.
