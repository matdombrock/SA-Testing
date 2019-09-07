# Sound Agreements App Tester Documentation

[Account Types](#account-types)

[Logging In](#logging-in)

[Sign Up](#sign-up)

[Email Verification](#email-verification)

[Using Multiple Accounts At Once](#using-multiple-accounts-at-once)

[Mediation Groups](#mediation-groups)

[Mobile Support](#mobile-support)

[What If I Break Something?](#what-if-i-break-something)

[Is This An App Or A Website?](#is-this-an-app-or-a-website)

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

### Example accounts you can use by group
Example Guide:
```
Mediator Login
-------
User A Login
User B Login
```
Group 1:
```
gannon.mediator@example.com
-------
alice.testa@example.com
bob.testa@example.com
```
Group 2:
```
gannon.mediator@example.com
-------
charlie.testa@example.com
dan.testa@example.com
```
Group 3:
```
gannon.mediator@example.com
-------
greg.testa@example.com
homer.testa@example.com
```
**All of these accounts use ```pass``` as the password unless changed!**

These are just a few of the example accounts that I've setup. You can always add new accounts by clicking the sign up button (next to login) and having an admin (me) assign a mediator to the group. I would also be more than happy to make new accounts for you as needed. 

## Using Multiple Accounts At Once
Since in normal day-to-day operations, you won't need to login to multiple accounts at the same time, this isn't something that is supported through the app itself. However, if you do need to login to multiple accounts just open a new "Incognito" or "Private Browsing" tab (depending on your browser). This prevents the "session" from being recognized by the app. You should be able to use as many accounts at once as you need to using this method. 

## Mediation Groups
"Mediation Groups" or "Mediations" are a group of 3 accounts (one mediator and two clients/users).

As a mediator, you are asked to select your active mediaton upon logging in. 

If you have already selected a mediation group in the past, the site will remember this on you next login. 

You can change your active mediation group at any time by clicking the blue ribbon at the top of page or by visiting the "overview" page.

## Mobile Support
While many features might already be working on mobile, right now, no part of this site has been optimized to be working on mobile phones or tablets. You will need to use a desktop or laptop for now. 

## What If I Break Something?
No problem. That's why we're testing and that's why we're doing it on a testing server. If you do break something or something just doesn't seem right let me know and I'll look into it. Worst case scenario I just have to set everything back to the way it was originally. 

## Is This An App Or A Website?
You might be wondering why I'm referring to this project as an app or website interchangeably. 

*So is it an app or a website?*

That depends on who you ask. In my opinion it's both. A website isn't always an app, but this is an app this is also a website.
