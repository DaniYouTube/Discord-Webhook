<h1>DiscordWebHook</h1>
<p>An application that allows you to use Json or text only to control a Discord Webhook.</p>

<h2>Basic Mode</h2>

- Url: Your Discord Webhook Url.
- Name: Custom name for the Webhook.
- MSG: The message you want to send.

<h2>Advance Mode</h2>

- Url: Your Discord Webhook Url.
- Json: A Json that contains the properties of the Webhook.
<hr>

<h2>Json Webhook Properties</h2>

- username: The username for the Webhook.
- avatar_url: The image for the webhook.
- content: The message or you can also use it to send images through the url.
- embeds: An array of embeds.
- title: The title for the embed.
- description: The message for the embed.
- color: The color of an embed.
<center><h3>More coming soon</h3></center>

<h2>Example Json</h2>

```json
{
    "username": "DiscordWebhook",
    "avatar_url": "http://",
    "content": "This is a test!!",
    "embeds": [{
        "title": "Test",
        "description": "Discord Webhook",
        "color": "15155743"
    }]
}
```
