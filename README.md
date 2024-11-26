## Overview

- Nexalyze is an application that extracts data from the search engine results page, in this case we will use Google Search.
- Store the search result and display it to users as soon as possible after each keyword is processed.
- Users must be authenticated to use the application.

## Application Requirements

1. Authenticated users can upload a CSV file of keywords. This upload file can be in any size from 1 to 1000 keywords.
2. The uploaded file contains keywords. Each of these keywords will be used to search on [https://www.google.com](https://www.google.com/) and will start running as soon as they are uploaded.
3. For each search result/keyword result page on Google, store the following information on the first results page:
    - The total number of Google Ads advertisers on the page.
    - The total number of links (all of them) on the page.
    - HTML code of the page/cache of the page.
4. Allow users to view the list of their uploaded keywords. For each keyword, users can also view the search result information stored in the database.

## Principles

While working on this challenge, you must follow these principles:

- Clarity: write clear code that any developer can read and understand in one go.
- Simplicity: write straightforward code with no ambiguities.
- Defensiveness: cover all test cases and treat user inputs with care.
- UI/UX: you are free to drive it your way, but let's keep it usable and user-friendly enough.

---

All features must have a Web user interface. If you feel like going the extra mile, you can also add APIs to the application (optional). Refer to the below sections for a detailed description.

### Web UI

The following screens must be implemented:

- Sign in.
- Sign up.
- Upload a keyword file.
- View the list of keywords.
- View the search result information for each keyword.
- Search across all reports.

### API (Optional)

The following endpoints must be implemented:

- Sign in.
- Get the list of keywords.
- Upload a keyword file.
- Get the search result information for each keyword.

Users would need to sign up via the Web UI (in-browser) to use the API.

### Technical Requirements

- Use Git during the development process.
  - **Make regular commits and merge code using Pull Requests**.
  - Fork this repository to a **private GitHub repository**.
  - Invite the reviewers with **Read** access when done. You can reach out to us to retrieve the list of the reviewers.
- Continue the implementation from this codebase, follow its convention as much as you can.
- Write tests.
- Have CI and CD workflows.
- A document on how to run your application will be appreciated as well.
- Optional: Deploy the application to a cloud provider e.g. AWS, Google Cloud, Digital Ocean or Heroku.
