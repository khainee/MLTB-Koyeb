## Deploying on Github Actions

**Required Variables(Add in Settings -> Secrets -> Actions -> Actions secrets -> New repository secret):**

- `Docker` : Add your Github Username.
- `GIT_EMAIL` : Add your Github Email.
- `GIT_TOKEN` : Enter your `Personal Access Github Token` and Give All Permission, it will use your account to Run the Loop Server . [Click Here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token#creating-a-token) to Generate.
- `BOT_REPO` : Put your Forked or this Repo link after removing **_https://_** from Beginning of the URL.
- `CONFIG_FILE_URL` : Gist URL contains All Required Vars for Z-Mirror, Fill it and Remove Commit ID.
