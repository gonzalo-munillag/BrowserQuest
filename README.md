# BrowserQuest Quick Start

BrowserQuest is a multiplayer HTML5/JavaScript game.

## Requirements

- [Node.js](https://nodejs.org/) (v14+ recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Redis](https://redis.io/) (for the backend database)

## 1. Clone the repository

```sh
git clone https://github.com/YOUR_GITHUB_USERNAME/Browserquest.git
cd Browserquest
```

## 2. Install dependencies

```sh
npm install
```

## 3. Start Redis

Make sure Redis is running.

On macOS (with Homebrew):

```sh
brew install redis
brew services start redis
```

Or, simply run:

```sh
redis-server
```

## 4. Start the game server

```sh
node server/js/main.js
```

## 5. Open the game in your browser

Go to: [http://localhost:8000/](http://localhost:8000/)

---

### Notes

- The default port is `8000`. If you want to change it, edit `server/config.json` or create `server/config_local.json`.
- For more details, see the full documentation in the [wiki](https://github.com/browserquest/BrowserQuest/wiki).
- For Windows or Linux, install Redis and Node.js using your platform's package manager or from their official websites.

---

## Credits & License

- Code is licensed under MPL 2.0. Content is licensed under CC-BY-SA 3.0. See the LICENSE file for details.
- Originally created by [Little Workshop](http://www.littleworkshop.fr) and the open source community.
