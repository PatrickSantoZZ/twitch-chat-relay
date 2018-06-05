# twitch-chat-relay
Chat relay between Twitch and TERA. This is a very basic implementation, I will add more features later. It uses the [Twitch Messaging Interface library](https://www.tmijs.org/), so you'll need to run `npm install tmi.js` to be able to use it.

## Config
Just open `config.json` and enter your details.
```json
{
  "username": "twitch_username",
  "password": "twitch_oauth_password",
  "channel": "#channel_to_join"
}
```
You can generate OAuth password [here](https://twitchapps.com/tmi/), `channel` can be your own `#username`, or if you want to chat with someone else's stream, then their `#username`.
