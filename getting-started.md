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
# NoatCards getting started

## Noat.Cards telegram bot

Accessing to the [noat.cards telegram bot](https://telegram.me/noat_cards_bot) here.

Trigger the bot and register by command `/start`

## Start General Review Session

- Navigate to `📘`(Learn)
- Click on `General Review` to start review session
- Click `Start/Continues` to review

## Start Review Session based on specific Repository

- Navigate `📘`(Learn)
- Select Review Session based on specific repository
- Click `Start/Continues` to start review session on the specified repository

## Configure daily knowledge review time

`noat.cards` will send you a remind message about daily knowledge review

- Go to setting `⚙`
- Sync up TimeZone by select `✍ Time Zone`
- Using `⬆` and `⬇` to configure your TimeZone (base on GTM)
- Configure your daily knowledge review time by selecting `✍ Review Time`
- Using `⬆` and `⬇` to configure your daily review time (base on configured TimeZone)

## What is review heatmap ? 

Review heatmap is simple tracking chart which records your daily review activity. 

## What is repo shelf 🗃

repo shelf would be like your bookshelf. It is the place to store all of your knowledge repositories. You can add more knowledge repo to the repo shelf

You can go there to browse about your knowledge repositories like you go to your bookshelf to get a book for reading

## Import knowledge repository to repo shelf by Git url

- From `📘`(Learn) navigate to `🗃` (Repo Shelf)
- Select `Import Repo 📥` (Import Repository with git url)
- Input your repo git url. For example: `https://github.com/noatcards/og-aws`

Note:

- noat.cards only support `https` public repository git url

## Browse existed public knowledge repo in platform and clone it

- From `📘`(Learn) navigate to `🗃` (Repo Shelf)
- Select `Repo Browse` (Browse public repositories in platform)
- Select `Repo` you are interested on
- Explore the repo by Chat UI or open Web View by clicking `Open` button
- Click on `🧬 Clone` Button to clone the repo to your repo shelf


## Delete a repo from repo shelf

- Navigate to repo shelf `🗃`
- Select repo want to delete
- Click on `🔥🗑️` to delete repo
- Click `Okay` to confirm

## Sync up a repo with its remote Git

- Navigate to `🗃`(repo shelf)
- Select repo want to open
- Click on `Sync Up 🔃` to sync up repo. The process will take sometime
- Return on success message like bellow:

For repository already sync (latest version)

```
Your repository linkedin-skill-assessments-quizzes already sync up
```

Or for repository have new update
```
Repository: linkedin-skill-assessments-quizzes updated
From:  079f (old)
To 023f (new)
```
## Browse deck in specific repository

With Repo Shelf, you can simple navigate to a specific deck in a repo which you interested on. and start a learning session.

- Navigate to `🗃`(Repo Shelf)
- Select the repo you want
- Select the Deck you want
- All cards content on the deck will show, click on a Card you are interested. Using button `>>` or `<<` to navigate between cards

## Learn by decks

With Repo Shelf, you can simple navigate to a specific deck in a repo which you interested on. and start a learning
session.

- Navigate to `🗃`(Repo Shelf)
- Select the repo you want
- Select the Deck you interested
- Select `Learn It` to start study/review session. All cards belong the deck file will push to study/review session

## Share a deck

Instead of share the whole repo with other people, you can select a single `Deck` to share

- Navigate to `🗃` Repo Shelf
- Select the repo you want
- Select the Deck you want to share
- Select `Share` button
- Select who you want to share the deck with 

## Share a card by browse card

- Navigate to `🗃` Repo Shelf
- Select the repo you want
- Select the Deck which content the card you want to share
- Select the card you want to share
- Select `Share` button
- Select who you want to share the card with

## Share a card by search it (full text search)

`Noat.Cards` support full text search, then you can easy get the card you want by searching it

- In the chat bar, input `@noat_cards_bot <your search string here`
- Select the card from search result
- Click `Share` button 
- Select who you want to share the card with

Another way to make card searching here

- From `📘`(Learn) navigate to `Explore`
- The search feature is enabled by default, input your search string in chat bar
- Select the card from search result
- Click `Share` button
- Select who you want to share the card with

## Share Card

By embedding knowledge to a single note/flash card. Then you can document your knowledge. Simple way to search the card, and easy to share the card with others

- Search a card by search string (full text search)
- Select the card from search result to preview
- If it is the card want to share, click on `Share button`
- Select who you want to share the card with


## What is Quiz Competition ?

Quiz Competition`🏆` is a game which lets participants compete against each other to bring out a competitive spirit and create a fun experience!

You can have several quiz questions and define correct answers to aggregate the total score and reveal a final winner at the end

## Create Quiz Competition 

- Navigate to `🏆`Quiz Competition button
- Select create new Quiz Competition
- Select Quiz Question you want to add to your quiz competition.
- Select `Set Name` button to set the name for the quiz competition 
- Select `Preview` button to preview the Quiz Competition
- Click `Publish` to publish the quiz competition.

The Quiz Competition Dashboard is show up. At the time, you can edit some setting for the new quiz competition.
or Share the quiz competition to your friend or group to start a quiz competition game.

Using `filter` button to select deck or repo which are allowed to shown up


## Browse quiz competition 

- Navigate to `🏆`Quiz Competition button
- UI will show all your quiz competition
- Click button `Filter` to select what quiz competition allowed to show up

## Delete Quiz contest

- Navigate to `🏆` Quiz Competition Browse
- Select Quiz Competition want to delete
- Select `❌ Delete`Delete button
- Select Okay to confirm delete operation
