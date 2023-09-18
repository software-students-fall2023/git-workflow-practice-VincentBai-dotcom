# README
[Migrating millions of lines of code to TypeScript](https://stripe.com/blog/migrating-to-typescript)

Here is the link to an article published on Slack's engineering blog, which recounts the the process of migrating from Flow, an optional type system for javascript developed by Meta, to Typescript, the most popular trend in the industry. What I think is interesting about this article is how the company chooses the right migration strategy. Since a clear transition from Flow to Typescript is required, i.e. two are not allowed to exist in the codebase at the same time, it's much wiser to use automated language conversion tools to achieve desired outcome, as the man power required to manually convert is enourmous. 

(Andrew Huang): I think it's very interesting that Stripe has a team solely "focused on elevating the experience of writing JS at Stripe". While it's seemingly unconventional for a tech company to have a specialized team like this, the results have clearly paid off with this team's work of migrating from Flow to TypeScript. 