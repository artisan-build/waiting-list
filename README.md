# Laravel Waiting List (Work In Progress)

Manage a waiting list of users who have expressed interest in joining your Laravel-powered site. We are building this to manage the pre-launch process for our websites.

### How To Use

Don't. Because it doesn't actually do anything yet. But when it's ready, you'll start with this:

`composer require artisan-build/waiting-list`

### What We Are Building

This package will provide the following features to a Laravel site:

1. A table of prospective users who have expressed interest in using the site (the waiting list) `waiting_users` with model `WaitingUser`.

2. A route (POST) `waiting_list__join` that you can attach to your signup form. It will record the waiting list user. It can either redirect the browser or send a json object back with the newly created waiting list user so you can do whatever you like.

3. A command that you can run to invite a particular user by email address or invite the oldest x users on your list.

4. A signed url pointing at your site's registration page, allowing invited users to register as long as they click on the valid signed link.

5. A component that you can place on your register page that will redirect any uninvited users to the waiting list signup form. `x-invitation-only`

### What We Need From You

1. Ideas for improving the roadmap above.

2. Pull requests adding features or fixing issues.

3. Reviews of pull requests.

### Let's build!