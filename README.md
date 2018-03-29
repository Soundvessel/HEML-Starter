# HEML Email Build Tools

An NPM powered starter kit to create a HTML email template using [HEML](https://heml.io/).

##Instructions

1. In base directory commandline `npm i` to install requirements.
2. To develop `npm run hemlDev`. This will open a browser window and recompile whenever you make changes to `email.heml`. Note this DOES NOT build the html file. For that you need to run `npm run hemlBuild` to get `email.html` as output when you have everything done.
3. Read all comments carefully and ensure ones prefixed with `@todo` are completed if applicable.
4. Use HEML tags documented here: [https://heml.io/docs/getting-started/overview](https://heml.io/docs/getting-started/overview)

For more information check out [HEML.io](https://heml.io/).

## Important Notes
Output current creates an extra empty `<head>` tag that needs to be removed from the generated html file. You can track the issue [here](https://docs.npmjs.com/cli/ls).

MailChimp has a great reference on media queries for email: [https://blog.mailchimp.com/mailchimp-and-media-queries/](https://blog.mailchimp.com/mailchimp-and-media-queries/)

##Questions?

[https://github.com/Soundvessel/HEML-Starter](https://github.com/Soundvessel/HEML-Starter)