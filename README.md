# CS314 Group 21 Term Project _Minstant Messenger_

By: Braulio Reyes and Max Rego

(canvas id? idk)

## Structure and Implementation

For structing our project, we devided all potential features into segments, 
using the organizational tool Jira. Braulio took project lead, volunteering
to devide the features, splitting up both the front and back end sections
to give us both time to work with each. 

Our stack is a PERN stack: PostgreSQL, Express.js, React with Tailwind CSS 
and Typescript, and Node.js.

For Authentication on our project, JSON Web Tokens manage access to the site.
By revoking and allowing tokens on logout and login, we allow accounts with matching
tokens access what is determined by their account. Logging out revokes the token, requiring
a new login and new token.

## GitHub Link
Our repository is set up with 3 repositories: The term project is a container
for both our front and back end code. The container then just has 2 submodules
for the back end and front end repositories which are independent to each other
for independent testing and maintainment. 

[Term Project](https://github.com/Braulee7/CS314-Term-Project)

## Implemented Tests

We started with test driven development for the back end routes so our
coverage for the back end is higher than the front end. All testing is
done with jest, supertest, and vitest for both the back and front end.
Unit testing makes up a majority our tests but they make sure to test for
usability, security, and resiliency. 
Our GitHub repositories are also set up for continuous integration and
automatically test our code to ensure nothing buggy or broken is pushed
into our main branch. The integration is implemented through GitHub actions
and the workflow files are in the individual repositories in the 
`.github/workflows` directory.

## Deployment Information

I think you can put info on how to deploy if we dont have a stable link

