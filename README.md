# java-Tasks
# Password-Generator

This project is a Java Console Application to generate random passwords and perform password strength checks.

## Introduction

I decided to build this project during the Winter Break of my second year after taking the Object-Oriented Effective Java Programming course. I wanted to build something interesting with Java to practice and see what I could do on my own. However, I still wasn't sure what I wanted to do. Then one night, while explaining to my father the importance of having a strong password for his social media accounts, I got the idea of creating a random password generator. A week later, it was done. 

While working on it, I decided to include a password strength checker feature that checks the overall strength of the entered password. I was pretty happy with how it turned out, but I realized that it was not very straightforward to use for someone who does not know how it is supposed to work. So, I decided to create a GUI for the application for the next step, which is available in the Password-Services repository.

## Functionalities

### 1. Generating a Password:

- The user answers with "Yes" or "No" to questions about using uppercase letters, lowercase letters, numbers, or symbols.
- The user then enters the desired length of the password.
- A password alphabet is generated based on the user's answers, which is a string containing the chosen characters.
- Random characters from the password alphabet are selected and combined to form a completely random string according to the user's preferences.
- The randomly generated password is then displayed on the console.

