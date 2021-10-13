# StepZen CodeSandbox Example

An example showing how to use StepZen together with CodeSandbox for demo's.

## Forking

Before forking this example on CodeSandbox or your own device you need to create an account on [StepZen](https://stepzen.com/).

### On CodeSandbox

You can fork this CodeSandbox by clicking the fork button on the top right. You need to add two [secret keys](https://codesandbox.io/docs/secrets) to the CodeSandbox:

- `STEPZEN_USERNAME`: Your StepZen username
- `STEPZEN_ADMIN_KEY`: The admin key from your StepZen account

To try out StepZen from your own IDE You can fork this demo from its Github repository or from CodeSandbox itself.

### On your own device

From your own IDE you need to rename the file `.env.example` to `.env` and add your own credentials.

Before you're able to try out this example, you need to make sure that StepZen is installed on your local machine and that you're logged in. You can find how to do this in the [Getting Started with StepZen](https://stepzen.com/docs/quick-start) guide.

After cloning this repository you need to run the following command to start this example:

```
stepzen start
```

This will make a GraphQL API available at [http://localhost:5000/api/api/codesandbox](http://localhost:5000/api/codesandbox) with the GraphiQL Playground.

## Questions

Do you have any questions on this integration, or you want to check out other integrations you can make with [StepZen](https://stepzen.com/? Have a look at the website or join the [Discord channel](https://discord.com/channels/768229795544170506) for support.
