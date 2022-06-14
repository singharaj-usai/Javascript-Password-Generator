# Singharaj's Password Generator

## Index
1. [Overview](#overview)
    - [Summary](#summary)
    - [Links](#links)
    - [User Story](#user-story)
    - [Acceptance Criteria](#acceptance-criteria)
    - [Screenshots](#screenshots)
    - [Made with](#made-with)

# Overview

Modify an existing Javascript and add on to it in order to finish a password generator. 

## Summary

The purpose of this is to demonstrate a password generator when a user clicks on the red "Generate Password" button,
and a prompt is shown to the user to generate a password with the following:
The length of the password.
Choosing between 8 to 128 characters.
Do they want to include lowercase, uppercase, numbers, and special characters.
And after they have made their decisions, the password will be generated by Javascript's "Math.random() and Math.random()" functions, and finally their
generated password will be shown in the text box.

As an added bonus, there will also be a "Copy Password" button for user convenience. 

## Links

Live Site URL: https://indieun.github.io/Javascript-Password-Generator/

Repository URL: https://github.com/indieun/Javascript-Password-Generator

## User Story

AS AN employee with access to sensitive data
I WANT to randomly generate a password that meets certain criteria
SO THAT I can create a strong password that provides greater security

## Acceptance Criteria

GIVEN I need a new, secure password
WHEN I click the button to generate a password
THEN I am presented with a series of prompts for password criteria
WHEN prompted for password criteria
THEN I select which criteria to include in the password
WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters
WHEN asked for character types to include in the password
THEN I confirm whether or not to include lowercase, uppercase, numeric, and/or special characters
WHEN I answer each prompt
THEN my input should be validated and at least one character type should be selected
WHEN all prompts are answered
THEN a password is generated that matches the selected criteria
WHEN the password is generated
THEN the password is either displayed in an alert or written to the page

## Screenshots
* Generate Password Button
    * You are shown the Generate Password button which creates randomly generated strings of characters.
![](./assets/Images/1.png)

* Prompts
    * A list of prompts are given after clicking "Generate Passwords" as options for your choice of items you want in your generated password.
![](./assets/Images/2.png)

* Error message
    * If you don't select valid options, you will be shown an error message saying that you must select a valid option.
![](./assets/Images/3.png)

* Password generated
    * When all prompts are successfully chosen, your password is generated.
![](./assets/Images/4.png)

* Copy Password Button
    *A  convenient copy password button is present to copy the generated key into your clipboard.
![](./assets/Images/5.png)

## Made With

* HTML5
* JavaScript
* CSS
