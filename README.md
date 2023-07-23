<h1 align="center">Welcome to Next Api Router 👋</h1>

> A tiny api router for your next.js project. It turns your api routes to express route like syntax


## Install

```sh
npm install nxr
```

## Usage

In your `pages/api` folder create a file called `[...all].js` or `[...all].ts` if using typescript and copy below to the file.

```javascript
import router from "nxr";

router.get("/", (req, res) => {
  res.send({ ok: 1 });
});

export default router.handler;
```

## How it works?

It takes advantage of next.js catch all routes and parse and bind function to the route.

