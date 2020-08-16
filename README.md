# React & Node Project

A full stack project with React and Node. It has been deployed here: [https://thawing-scrubland-15537.herokuapp.com](https://thawing-scrubland-15537.herokuapp.com).

## App Overview

Emaily is a feedback collection application for users who would like to get feedback from their customers to make their app/service better.

## User Flow

Here is the app user flow:

1. User signs up via Google OAuth
2. User pays for email credits (survey credits) via Stripe API
3. User creates a new "campaign"
4. User enters a list of receivers for the surveys
5. Emaily will send email to the list of surveyees
6. Surveyees click on link in email to provide feedback
7. Then we will Tabulate feedback
8. User can see report of all survey responses

## Tech Stack

1. **User Signup:** Express + MongoDB + PassportJS
2. **User Payment:** Stripe + MongoDB
3. **User Create Survey:** React + Redux
4. **User Enter Emails:** React + Redux + Redux Form
5. **Send Emails:** Email Provider (SendGrid)
6. **Surveyees Click Links:** SendGrid + Express + MongoDB
