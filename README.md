### Announcement:

Due to high usage, the heroku limits have been exceeded! I'll work on getting the API up again as soon as possible, while also implementing rate limiting, so that the service is usable by all.
Thank you!

I've created a new heroku instance in the meantime. But I plan to create a more long-term solution with rate limiting on AWS. Stay tuned!

## Endpoints:

### Grab a random joke!
[https://official-joke-api.herokuapp.com/random_joke](https://official-joke-api.herokuapp.com/random_joke)

### Grab ten random jokes!
[https://official-joke-api.herokuapp.com/random_ten](https://official-joke-api.herokuapp.com/random_ten)

## How these jokes were collected

Full disclosure: I did a lot of googling...
But since this repo went open source, many of them were contributed by joke-loving coders around the world!

### Make a contribution!

Submit a Pull Request, with your joke added to the jokes/index.json file. Make sure the joke is in this format:

```javascript
{
  "id": "<last joke id + 1>",
  "type": "your joke's type",
  "setup": "your joke's setup line",
  "punchline": "your joke's punchline"
}
```

### Run Locally
* Clone the repo
* `npm install && npm start`
* Visit `localhost:3000/random_joke` or `localhost:3000/random_ten` on your browser!
