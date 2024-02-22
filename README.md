# Twitch Stream Viewer

This simple HTML file allows users to watch a Twitch stream without registration or the need for app installation. It's a lightweight solution for quickly accessing Twitch content directly from a web browser.

## Features

- **No Registration Required**: Users can watch Twitch streams without needing to create an account.
- **No App Installation Needed**: The stream can be viewed directly in any modern web browser.
- **Responsive Design**: The viewer adapts to different screen sizes, ensuring a good viewing experience across devices.

## How to Use

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in any modern web browser.
3. Enjoy watching the Twitch stream without any additional steps!

## Customization

If you want to embed a different Twitch stream, you can do so by modifying the `channel` property in the JavaScript code:

```javascript
new Twitch.Player("twitch-embed", {
    channel: "YOUR_CHANNEL_NAME"
});
