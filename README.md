##Thanks… for taking our test.

Please keep in mind that there is going to be more todo than what I expect you to accomplish in an hour.  Please do not rush. It is better to do one thing well, then attempt all of them and get nothing done.

ok.. so here is the test

We are making a backend API for a classic blog.

##Tasks

Please fork the repo at .

Please make a small change, perhaps adding a space and make a commit. This will serve as the start time as your test.  Please  make sure you make your final commit no latter than 1 hour and 10 minutes latter.  A second latter will be an automatic fail.

Please create a migration and models for typical blog tables.  Please include a posts, and tags functionality.  Please create a roles table and tie it to the users table. Set up the models for these tables and eloquent relationships.  Put in a “user” role and a “admin” role.

Please create an artisan command, that takes a email and password. It should ask for the email and password and whether the user is an admin.

Please create an endpoint that takes a username + password and issues an api token.

Please create another endpoint to create a post.  It should send a bearer token returned in step 5 to authorize.

Please create another endpoint to edit existing post. It should disallow editing if the person didn’t author the post. Unless.. the user is an admin then they can edit any post.



Please remember to commit when you are done.  I don’t expect that you can do everything in an hour.

After you commit please create a PR to the base repo. 
