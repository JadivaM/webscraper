# Hacker News Web Scraper

-This is a Web scraper app using Puppeteer and React that retrieves information from the Hacker News website. It filters and retrieves only articles that have upvotes higher than 100 so that users only get the highest rated articles. Users are able to view the title of the article, number of votes, and can click on the link to access the article.

## Setup

- `git clone` this repo
- `cd` into it.
- `yarn install`
- `cd client && yarn install`

## Available build commands

- `yarn dev`: Runs BOTH your Express.JS and React developer environment locally at the same time. Any logs coming from Express will be prefaced with `[0]`, any logs from `create-react-app` will be prefaced with `[1]`.
- `yarn server`: Runs JUST your Express.JS server.
- `yarn client`: Runs JUST your front-end React app.

Open [http://localhost:3000](http://localhost:3000) to view your local React app in the browser. The page will reload if you make edits.
