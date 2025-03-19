### Beta 5 (2024-02-20) - 14 tickets

- Allow the chat textarea to expand to multiple rows
- Show view button button in the chat messages
- Fix bug with the Agent is typing message dissapearing after viewing another thread
- Show average wait time for the AI Developer in the chat
- Create a page for domains and API endpoints
- Show special tool messages in the chat
- Add functionality to revert to a previous version of a site
- Add Sentry to the workers
- Create a run after the first message is added to the chat
- Prepare getsite9000 for the OpenAI GPT store launch
- Fix issues with Auth0 login and signup not working properly
- Add Google Auth to Auth0
- Preview a particular version of the site
- Fix a bug with login not working on Safari

### Beta 4 (2024-02-15) - 20 tickets

- Create infrastructure for scheduled workers using Rancher
- Fix a bug with the site not shown when generated for the first time
- Fix a bug with roasts not being shown in the chat
- Fix a bug with threads not updating messages properly after a new thread is started
- Fix a bug that changed the subdomain between deployments
- Create a run after a message is added to the chat
- Call the runs endpoint instead of waiting for the result of message post
- Implement the runs endpoints
- Create services for all third party integrations in the API
- Remove OpenAI calls from the controllers
- Create a forked process worker when a new run is create
- Replace draft UUID with site id
- Functionality to delete a site
- Show run duration in the chat window
- Show multiple versions in the chat window top bar
- Refresh JWT token when expired
- Send all the code (HTML, CSS, and JS) in a single call to the API
- Option to create multiple threads of a site
- Update version when site is updated
- Reload the preview iframe when a new version is created

### Beta 3 (2024-02-10) - 5 tickets

- Refactor the frontend to use ReactJS instead of jQuery
- Create an onboarding spage for creating a new site
- Try to use GPT-3 Turbo for the first few messages then switch to GPT-4 Turbo
- Add a cursor to the messages endpoint for pagination
- Inject code in the iframe for version preview or multiple choice

### Beta 2 (2024-02-05) - 10 tickets

- Fix thread files
- Autoexpand chat textarea
- Show a timer on the chat send button
- Use all the messages from the conversation when generating a completion
- Add images limitation to the pricing page
- Limit images generation
- Add user to request object in the API controllers
- Store the users in the database
- Add more restrictions to anon users
- Implement a chat completion alternative as a fallback to the assistant API

### Beta 1 (2024-02-01) - 14 tickets

- Show better error message when rate limit of the API
- Configure Sentry for the API and the chat app
- Show directory with microsites on getsite.online
- Only allow to upload files when the agent is not working
- Implement try/catch for the API controllers
- Fix issues with failed requests and runs getting stuck
- Update the instructions and tools for the assistant each time the server starts
- Create privacy policy and terms of service for the site
- Store the name of the site in the database
- Show the not found page if an html file is requests, otherwise send a 404 header
- Add a short timeout for the transcribing and completion API calls
- Create a metadata file in the R2 bucket
- Add feature to speak with the agent (TTS)
- Implement user roles

## Navigation

- [Back to Changelog](../changelog.md)
