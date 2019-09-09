# Sound Agreements App Tester Documentation

[Account Types](#account-types)

[Logging In](#logging-in)

[Sign Up](#sign-up)

[Email Verification](#email-verification)

[Using Multiple Accounts At Once](#using-multiple-accounts-at-once)

[Mediation Groups](#mediation-groups)

[Payments](#payments)

[Admin Stuff](#admin-stuff)

[Why Do I See A "Your Connection Is Not Private" Message?](#why-do-i-see-a-your-connection-is-not-private-message)

[Mobile Support](#mobile-support)

[What If I Break Something?](#what-if-i-break-something)

[Is This An App Or A Website?](#is-this-an-app-or-a-website)

[More Help](#more-help)

## Account Types
There are three types of accounts. Each has it's own dashboard, authorizations and feature set. 
* Admin - The site administrator(s)
* Mediator - A mediator
* Client - A client or end user

Each account can be of only one type. To see what type of account you are logged in with, go to the settings page and look at the badge in near the top of the page.

## Sign Up
You can sign up new accounts on using the sign up page (link next to login). This will automatically assign the new accounts to the same mediation group, but an Admin will need to assign the mediator. 


## Email Verification
Right now you might be seeing a message about email needing to be verified on many of the accounts. Since the site is still in the testing phase, the outgoing emails (needed for verification) have been limited to only a select amount of pre-approved email addresses. This is an intended security measure. 

I can add a new email to outgoing whitelist if needed so you can test verification emails.

However, there are no features of that site that are actually currently locked behind verifying an email.

## Logging In
Log in to the site by clicking the "Login" button at the top right of the site (only shown if you are not logged in). 

The password for all of the default testing accounts is ```pass```.

### [Example Accounts](https://github.com/matdombrock/SA-Testing/blob/master/Example-Accounts.md)

**All of these accounts use ```pass``` as the password unless changed!**

These are just a few of the example accounts that I've setup. You can always add new accounts by clicking the sign up button (next to login) and having an admin (me) assign a mediator to the group. I would also be more than happy to make new accounts for you as needed. 

## Using Multiple Accounts At Once
Since in normal day-to-day operations, you won't need to login to multiple accounts at the same time, this isn't something that is supported through the app itself. However, if you do need to login to multiple accounts just open a new "Incognito" or "Private Browsing" tab (depending on your browser). This prevents the "session" from being recognized by the app. You should be able to use as many accounts at once as you need to using this method. 

## Mediation Groups
"Mediation Groups" or "Mediations" are a group of 3 accounts (one mediator and two clients/users).

As a mediator, you are asked to select your active mediaton upon logging in. 

If you have already selected a mediation group in the past, the site will remember this on you next login. 

You can change your active mediation group at any time by clicking the blue ribbon at the top of page or by visiting the "overview" page.

## Payments
You can edit your payment info from the account settings page. However, since we are still in testing, **we should NEVER use real credit card info on the site under any circumstance.** This would be a really, really bad thing to do. 

What you can do is use the [pre-approved testing cards availabe here](https://stripe.com/docs/testing#cards). Any of those should work. 

## Admin Stuff
While the admin dashboard is fully functional right now, I think it's best to focus on testing the client and mediator dashboards for the time being, so if you have anything that needs the admin account just let me know.

## Why Do I See A "Your Connection Is Not Private" Message?
You also might be seeing another simmilar message depending on what browser you use.

It's hard to answer this question in a non-super nerdy way, but it's nothing to worry about. Basically we are just missing some certificates that are needed to get that message to go away. This is not something you need to worry about at all since we are only using testing accounts and testing credit cards. This message will NOT be seen the final site.

If you see this message click the button that says "Advanced" then click the link at the bottom of the page that says "Proceed to ...". 

Let me know if this causes any problems. 

## Mobile Support
While many features might already be working on mobile, right now, no part of this site has been optimized to be working on mobile phones or tablets. You will need to use a desktop or laptop for now. 

## What If I Break Something?
No problem. That's why we're testing and that's why we're doing it on a testing server. If you do break something or something just doesn't seem right let me know and I'll look into it. Worst case scenario I just have to set everything back to the way it was originally. 

## Is This An App Or A Website?
You might be wondering why I'm referring to this project as an app or website interchangeably. 

*So is it an app or a website?*

That depends on who you ask. In my opinion it's both. A website isn't always an app, but this is an app and this is also a website. Nerds debate this all the time but most of the time I will probablly say app.

## More Help
Many pages have a "help modal" that can be accessed by clicking the blue question mark (?) icon on the bottom right of the page. These modals give page & account type specific help. 

If you notice a page does not have a help modal, or the help modal is missing useful information, that would make a great issue to submit.

**Of course, feel free to reach out to me either via an issue or directly with any questions that come up!**
