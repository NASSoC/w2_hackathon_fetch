# w2_hackathon_fetch

Authors: Nicholas, Ahammed, Sahara

[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6453956&assignment_repo_type=AssignmentRepo)

# Fetch Hackathon

Today, we will be using our newfound skills to make apps that request data from a server.

## Step 1 - Getting data and brainstorming (20 - 30 mins)

Here are some APIs that we can use for free. All but the dad jokes one simply need the url. Each API has documentation on how to ask for different data by changing the url. We have included an example fetch for each one to help you get started.

👉 Visit the documentation for the APIs, and use JS to request some data to see what you get back. From there, brainstorm what you could make with your knowledge of JavaScript, the DOM and the data you have received.

### Pokemon API

- [Pokemon API](https://pokeapi.co/)

```js
// fetch the first pokemon
fetch("https://pokeapi.co/api/v2/pokemon/1/");
```

### Trivia API

- [Trivia API](https://opentdb.com/api_config.php)

```js
// fetch 10 random questions
fetch("https://opentdb.com/api.php?amount=10");
```

### Dad Jokes API

- [Dad Jokes API](https://icanhazdadjoke.com/api)

```js
// fetch a dad joke
fetch("https://icanhazdadjoke.com/", {
  headers: { accept: "application/json" },
});
```

### Dictionary API

- [Dictionary API](https://dictionaryapi.dev/)

```js
// fetch the definition of the word "hello" in British English (other languages available in the docs)
fetch(`https://api.dictionaryapi.dev/api/v2/entries/en_GB/hello`);
```

## Step 2 - Break down the problem (20 - 30 mins)

Now that you have an understanding of what data you're working with and have come up with an idea of what you could achieve, break down the problem into smaller chunks. Keep breaking the problem down until you can translate your plan into code. You should dream big, break it down, and start small. If your plan turns out to be overly ambitious, then be smart and reign it in. If you've been too conservative, try and push yourself.

## Step 3 - Build (The rest of the day!)

Translate your plan into code, and turn your ideas into reality. Enjoy!

### Section 2

# Practice: Working with Data, Fetching, and the DOM

Use this time to get more familiar with what we've covered so far using the activities below. You'll have all afternoon. If by the end of the afternoon you don't finish every task, that's alright. You can keep working on these on your own time.

Use the time this afternoon to collaborate and work together to pair program your way through the tasks and help reinforce each other's learning. Keep working together throughout!

## 👉 More about fetch - can you escape the earth? 🚀

- Use our short videos [here](https://vimeopro.com/schoolofcode/fetch-videos/) (password: bootcamp), the [docs](https://developer.mozilla.org/en-US/docs/Web/API/fetch), and other online resources to explore more about the second argument of fetch.
- [Click here](https://documenter.getpostman.com/view/2090159/TzRLkAk8) and follow the instructions and documentation. Make requests with `fetch` to the API endpoint to figure out the solution to the escape room. Can you escape the earth in time?

### Resources

- [JavaScript Info: Fetch](https://javascript.info/fetch)
- [FreeCodeCamp: JavaScript Fetch API Tutorial with JS Fetch Post and Header Examples](https://www.freecodecamp.org/news/javascript-fetch-api-tutorial-with-js-fetch-post-and-header-examples/)
- [Video: Using Async/Await with the Fetch API](https://www.youtube.com/watch?v=Yp9KIcSKTNo)
- [Video: Callbacks, Promises, Async Await | JavaScript Fetch API Explained](https://www.youtube.com/watch?v=VmQ6dHvnKIM)
- ... and more! Google anything you're still unsure about.

Note: Resources you find online will often use the .then syntax, a way to deal with promises that came before async/await was introduced to JavaScript. If you encounter this, see if you can use your docs-reading muscles to translate the code into async/await!

## 👉 Putting it all together - RPS in the DOM 🪨📄✂️

Once you've figured out your way through the escape room above, click [the classroom link here](https://classroom.github.com/a/8ybqonfb) for your next activity, taking rock paper scissors from the console to the DOM.
