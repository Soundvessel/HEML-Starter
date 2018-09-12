# HEML Email Build Tools

An NPM powered starter kit to create a HTML email template using [HEML](https://heml.io/).

## Instructions

1. In base directory commandline `npm i` to install requirements.
2. To develop `npm run hemlDev`. This will open a browser window and recompile whenever you make changes to `email.heml`. Note this DOES NOT build the html file. For that you need to run `npm run hemlBuild` to get `email.html` as output when you have everything done.
3. If you need to create multiple templates simply modify the scripts in `package.json` to create file name HEML/HTML pairs for each template. I recommend creating a master template that can be duplicated to create new variations.
4. Read all comments carefully and ensure ones prefixed with `@todo` are completed if applicable.
5. Use HEML tags documented here: [https://heml.io/docs/getting-started/overview](https://heml.io/docs/getting-started/overview)
6. Output purposely creates an extra empty `<head>` tag in the outputted file to [solve an issue with Yahoo mail](https://mosaico.io/email-client-tricks/double-head-trick-yahoo-app-android/).

For more information check out [HEML.io](https://heml.io/).

## Additional Reading

MailChimp has a great reference on media queries for email: [https://blog.mailchimp.com/mailchimp-and-media-queries/](https://blog.mailchimp.com/mailchimp-and-media-queries/)

## Questions?

Post an issue or question via the repo on Github: [https://github.com/Soundvessel/HEML-Starter/issues](https://github.com/Soundvessel/HEML-Starter/issues)