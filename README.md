## Exercise Intro

In this exercise, you'll be breaking up a class called `SurveyInviter`. This class contains two responsibilities: logic for sending invitations to each recipient, and logic for parsing a list of email addresses. Let's split the class into two in order to separate these responsibilities.

[See an example from The Weekly Iteration](https://upcase.com/videos/ruby-science-extract-class).

## Instructions

To start, you'll want to clone and run the setup script for the repo

    git clone git@github.com:thoughtbot-upcase-exercises/extract-class.git
    cd extract-class
    bin/setup

Extract a new class from `SurveyInviter` (located at `lib/survey_inviter.rb`) to split the `recipients` string into multiple email addresses. Make sure to write tests for the new class as you go.

Use the new class from `SurveyInviter`.

Make sure all tests are passing by running:

    rake
