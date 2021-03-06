# Outline

The table of contents at the beginning of this book is available as a cursory
overview of all the chapters and sections in the book. The outline below is an
attempt to break down the topics and concepts covered within each chapter.

- **Introduction**

  - Metadata about Elixir, Elm, and functional programming.
  - Prerequisites and acknowledgements.
  - Information about the demo application.

- **Diving In**

  - Quick-paced practical introduction to the Phoenix framework.
  - Building the initial Platform demo application.
  - Configuring the PostgreSQL database, running the server, and routing.
  - Generating the HTML resources for players.

- **Elixir Introduction**

  - Create a temporary Elixir application to compare of Elixir and Phoenix
    projects.
  - Brief background on mix, folder structure, modules, functions,
    documentation, tests, and interactive environment.
  - Introduction to concepts on piping, arity, pattern matching, and guards.

- **Phoenix Testing and Deployment**

  - Running Phoenix tests.
  - Working with Git and GitHub.
  - Configuring the application and deploying to Heroku.

- **Phoenix Sign Up**

  - Extending existing resources with new fields.
  - Generating and running migrations.
  - Basic queries with IEx.
  - Updating templates and working with forms.

- **Phoenix Authentication**

  - Importing Hex dependencies.
  - Working with changesets.
  - Building an authentication plug.
  - Adding sign in and session features.

- **Phoenix API**

  - Generating a JSON API for games.
  - Routing and scopes.
  - Ecto relationships, migrations, and schemas.
  - Adding JSON API features for players.

- **Elm Introduction**

  - Brief introduction to the Elm language and tooling.
  - Covers modules, functions, types, formatting, and refactoring.

- **Elm Setup**

  - Introduction to Brunch and Phoenix assets.
  - Configuring Phoenix to work with Elm.

- **Elm Application**

  - Starting our Elm front-end application.
  - Importing and using Elm packages.
  - Working with familiar HTML as a bridge to learning Elm.
  - Breaking up code into small, pure functions.
  - Working with the concept of Maybe in Elm.
  - Iterating through lists of data.

- **Elm Architecture**

  - Structure of the Elm Architecture.
  - Working with the Record data type in Elm.
  - Adding the Model, Update, Subscriptions, and View.
  - Pulling the application together with the Main function.
  - Adding initial interactivity with Html.Events.

- **Elm API Data**

  - Reading JSON API data from Phoenix.
  - Decoding JSON and working with game data in Elm.

- **Design and Usability**

  - Viewing application routes.
  - Working with CSS and working with Bootstrap classes.
  - Authorizing actions for player account features.
  - Styling for the lists of players and games.

- **Game Setup**

  - Creating a new Elm file for our first game.
  - Configuring Phoenix to compile multiple Elm applications.
  - Adding a slug field for working with games.

- **Our First Game**

  - Working with SVG to create a small game canvas.
  - Adding a small game character and item.
  - Refactoring Elm code with let expressions and small functions.

- **Adding Interaction**

  - Working with Elm subscriptions and keyboard input.
  - Adjusting character position.
  - Spawning and collecting items.
  - Working with randomness.

- **Displaying Game Data**

  - Rendering text in the game window.
  - Displaying the player score, items collected, and time remaining.
  - Working with time.

- **Handling Game States**

  - Introducing union types for game states.
  - Rendering different elements depending on current game states.
  - Creating start, success, and game over states.

- **Phoenix Channels and Elm Ports**

  - Getting started with Phoenix channels.
  - Creating and joining a channel.
  - Introduction to Elm ports and connecting Elm to Phoenix.
  - Sending data over the socket.

- **Syncing Score Data**

  - Sending and receiving data over the socket.
  - Displaying the results on the game page.
  - Working at the intersection of Phoenix, JavaScript, and Elm.

- **Socket Authentication**

  - Working with Phoenix user tokens for socket authentication.
  - Enabling multiple players to track changes over the socket.
  - Extending gameplays with additional data.
  - Refactoring channels with pattern matching.

- **Saving Score Data**

  - Using the channel to save scores to the database.
  - Working with Elm flags to send data from JavaScript to Elm.
  - Differentiating between authenticated and anonymous players.

- **Finishing Touches**

  - Fetching saved gameplays from the database to display for our game.
  - Fetching the list of players from the database.
  - Creating helper functions to associate players and gameplays.
  - Displaying player names and scores for gameplays.

- **What's Next?**

  - Additional features and ideas that didn't make it into the book.
  - Planning for possible future versions of this book.

- **Appendix**

  - Quick installation instructions.
  - Tooling recommendations.

- **Contact**

  - Congrats and contact information.
  - Request for feedback and ideas for the future.
