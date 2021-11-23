# Slack Enriched Message Tag

This tag allows you to send complex messages to slack. It leverages the [chat.postMessage](https://api.slack.com/methods/chat.postMessage) API.

To use this tag, you must have a Slack Application, and you can do so here: https://api.slack.com/apps. (Slack provides a tutorial available for getting a token here: https://api.slack.com/tutorials/tracks/getting-a-token).

Then, you can create your complex message by using the Block Kit Builder: https://app.slack.com/block-kit-builder/.

As you're on GTM, you can use GTM Variable to render your message dynamically (in the tag, set `{{VariableName}}` that will be replaced by the variable).

## Example

Here's an example you can send to slack when using the default Block Kit Builder Example:

![Slack Message Example](./slack_example.png)
