# Webbit

A _nearly_ full-feature Reddit clone build with Ruby on Rails. The app is the result of a course called Hello Rails at [hellorails.io](https://hellorails.io). This branch is part of the **master** course which contains source code for the additional bonus modules.

## Modeling

Each model will be responsible for different data throughout the app.

- User - focused on the user.
- Submission - The user authors this. Has different media (text, image/video, link)
- Community - Category based on submissions
- Comments - A responsive given to the submission from another user to a given user.
- Subscription - Not to be confused with billing. A user can subscribed and unsubscribe to a community.
