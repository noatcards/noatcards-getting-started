+++
noatcards = true
isdraft = false
fragment = "content"
weight = 110

title = "Noat.Cards How to use"

noatcards = true
draft = false

[sidebar]
    sticky = true 
+++
# NoatCards Getting Started

## Noat.Cards Telegram Bot

The Noat.Cards Telegram bot can be accessed [here](https://telegram.me/noat_cards_bot).

Trigger the bot and register with the command `/start`.

## Start General Review Session

In order to start a general review session you have to:

- Navigate to `📘`(Learn)
- Click on `General Review` to start review session
- Click `Start/Continue` to review

## Start Review Session based on a specific Repository

- Navigate to `📘`(Learn)
- Select Review Session based on a specific repository
- Click `Start/Continue` to start the review session on the specified repository

## Configure daily knowledge review time

`noat.cards` will send you a reminder message for a daily knowledge review session. In order to configure this you have to:

- Go to settingS `⚙`
- Sync up TimeZone by select `✍ Time Zone`
- Use `⬆` and `⬇` to configure your TimeZone (base on GTM)
- Configure your daily knowledge review time by selecting `✍ Review Time`
- Use `⬆` and `⬇` to configure your daily review time (base on configured TimeZone)

## What is the Review Heatmap ? 

The Review heatmap is a simple tracking chart which records your daily review activity. 

## What is the Repo Shelf 🗃

The Repo Shelf is similar to your bookshelf. It is the place to store all your knowledge repositories. You can add more knowledge repositories to your Repo Shelf.

You can go there to browse your knowledge repositories like you go to your bookshelf to get a book for reading.

## Importing a Knowledge Repository to your Repo Shelf by Git url

- From `📘`(Learn) navigate to `🗃` (Repo Shelf)
- Select `Import Repo 📥` (Import Repository with git url)
- Input the repo Git url. For example: `https://github.com/noatcards/og-aws`

Note:

- Noat.Cards only supports `https` public repository Git urls.

## Browse existing Public Knowledge Repositories in the platform and clone it

- From `📘`(Learn) navigate to `🗃` (Repo Shelf)
- Select `Repo Browse` (Browse public repositories in platform)
- Select the `Repo` you are interested on
- Explore the repository by Chat UI or open Web View by clicking `Open` button
- Click on `🧬 Clone` Button to clone the repo to your repo shelf

## Delete a Repository from your Repo Shelf

- Navigate to repo shelf `🗃`
- Select the repository your want to delete
- Click on `🔥🗑️` to delete the repo
- Click `Okay` to confirm

## Sync up a repo with its remote Git

- Navigate to `🗃`(repo shelf)
- Select the repository want to open
- Click on `Sync Up 🔃` to sync up the repository. The process will take some time.
- Return on success message like bellow:

For repository already in sync (latest version)

```
Your repository linkedin-skill-assessments-quizzes already sync up
```

Or for repository with updates

```
Repository: linkedin-skill-assessments-quizzes updated
From:  079f (old)
To 023f (new)
```

## Browse a Deck from a specific repository

With Repo Shelf, you can simple navigate to a specific deck in a repo which you're interested in and browse the deck of cards.

- Navigate to `🗃`(Repo Shelf)
- Select the repo you want
- Select the Deck you want
- All card contents on the deck will show, click on a Card you are interested in. Using button `>>` or `<<` to navigate between cards

## Learn a full Deck

With Repo Shelf, you can navigate to a specific deck in a repo which you're interested in and start a learning session.

- Navigate to `🗃`(Repo Shelf)
- Select the repo you want
- Select the Deck you interested
- Select `Learn It` to start a study/review session. All cards belongin to the deck file will be pushed to the study/review session.

## Share a Deck

Instead of sharing the whole repo with other people, you can select a single `Deck` to share.

- Navigate to `🗃` Repo Shelf
- Select the repo you want
- Select the Deck you want to share
- Select the `Share` button
- Select who you want to share the deck with 

## Share a Card by Browsing

- Navigate to `🗃` Repo Shelf
- Select the repo you want
- Select the Deck which content the card you want to share
- Select the card you want to share
- Select the `Share` button
- Select who you want to share the card with

## Share a Card by Searching (full text search)

`Noat.Cards` support full text search, so you can find the card you want by searching for it.

- In the chat bar, input `@noat_cards_bot <your search string here`
- Select the card from search result
- Click `Share` button 
- Select who you want to share the card with

Another way to search for a card:

- From `📘`(Learn) navigate to `Explore`
- The search feature is enabled by default, input your search string in chat bar
- Select the card in the search results
- Click the `Share` button
- Select who you want to share the card with

## What is Quiz Competition ?

Quiz Competition`🏆` is a game which lets participants compete against each other to bring out a competitive spirit and create a fun experience!

You can have several quiz questions and define correct answers to aggregate the total score and reveal a final winner at the end.

## Create a Quiz Competition 

- Navigate to `🏆`Quiz Competition button
- Select create new Quiz Competition
- Select Quiz Question you want to add to your quiz competition.
- Select `Set Name` button to set the name for the quiz competition 
- Select `Preview` button to preview the Quiz Competition
- Click `Publish` to publish the quiz competition.

The Quiz Competition Dashboard shows up where you can edit some settings for the new quiz competition.
Or share the quiz competition to your friend or group to start a quiz competition game.

Use the `filter` button to select the decks or repos which are allowed to show up.

## Browse Quiz Competitions 

- Navigate to `🏆`Quiz Competition button
- UI will show all your quiz competitions
- Click button `Filter` to filter this list

## Remove a Quiz Competition

- Navigate to `🏆` Quiz Competition Browse
- Select the Quiz Competition want to delete
- Select the `❌ Delete`Delete button
- Select Okay to confirm the delete operation
