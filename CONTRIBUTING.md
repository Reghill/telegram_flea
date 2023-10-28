Contributing Guidelines by GPT

# How to Contribute 🛠️

## Step 1: Find an Issue

Browse the open issues in the main repository and pick one you want to work on.
Or create one if you have found a bug or have a feature request.

## Step 2: Fork the Project 🍴

Click the "Fork" button on the main page of the repository to make a copy in your own account.

## Step 3: Install dependencies

Dependencies:

- python
- pip
- git
- poetry

## Step 4: Create a Branch 🌿

```bash
git switch -c Branch_Name
```

## Step 5:

- Create a virtual environment with poetry
  For more information see: (https://python-poetry.org/docs/basic-usage/)
- Copy .env.example `cp .env.example .env`
- Open the file
- Edit .env variables 
  - `TELEGRAM_BOT_TOKEN` - your bot's token. Open https://telegram.me/BotFather and follow instraction how to create a new bot. In the end you will recei
  - `CHANNEL_USERNAME` - the channel tag to which messages will be sent. Create a new file 
- Add your bot to the channel and give it admin rights

## Step 6: Work on the Task 👨‍💻👩‍💻

Make the necessary changes in the code or documentation.

## Step 7: Test your code

Make sure that the changes you've made work locally before creating a Pull Request

❕ IMPORTANT. Make sure to refactor your code using "Black" formatter before creating a Pull Request

To install Black formatter run:

```bash
pip install black
```

To format your code run:

```bash
black .
```

## Step 8: Commit ✅

Add your changes through Git and create a commit with a descriptive message.

```bash
git add .
```

Create a Commit

```bash
git commit -m 'Your descriptive message'
```

NOTE: Each pull request (PR) should contain only one commit. If you have multiple commits, they need to be squashed.

## Step 9: Work Remotely 🌍

When your work is ready and complies with project conventions, upload your changes to your fork:

```bash
# Push your work to your remote repository
git push -u origin Branch_Name
```

## Step 10: Create a Pull Request ➡️

Go to the page of your fork on GitHub and click "New Pull Request". Verify that the changes are displayed correctly, and then submit your pull request.
