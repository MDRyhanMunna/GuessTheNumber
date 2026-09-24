# GuessTheNumber / Number Duel

Real-time two-player number guessing game built with HTML, CSS, JavaScript, PeerJS and WebRTC.

## Main game
`gtn/number-duel.html`

## Contact form
The Developer / Contact panel uses EmailJS. The page includes the existing EmailJS service, template and public-key configuration.

For the EmailJS template, use variables such as:
- `{{from_name}}`
- `{{from_email}}`
- `{{reply_to}}`
- `{{message}}`

The game itself remains PeerJS/WebRTC-based; no Node.js, Socket.IO, FastAPI or WebSocket-chatroom code was added.
