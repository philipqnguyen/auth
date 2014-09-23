# Authentication from scratch

## Description

This is a project made to demonstrate authentication from scratch. It is based off of episode 250 (revised) of RailsCasts by Ryan Bates.

Users can sign up, sign in, and sign out. In addition, they must be signed in to create/edit/destroy articles.

There are two pivotal controllers, the users controller and the sessions controller. The users controller handles all the create, edit, and destruction of the user. Where as the sessions controller is what determines whether a user is logged in. No authentication engines has been installed in this app, it is all written from scratch.
