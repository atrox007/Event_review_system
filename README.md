# Event_review_system

## GitHub Repo Link:

```bash
  https://github.com/atrox007/Event_review_system
```

## Description and Features

- Backend REST APIs of review and rating system for the events.
- User Login and SignUp functionality with full validation, passsword encryption, JWT token for secure user authentication.
- Organizer Login and SignUp functionality with full validation, passsword encryption, JWT token for secure user authentication.
- Implemented middlewares for both user authorization and organizer authorization for secure APIs access.
- Organizer can create/schedule events, display all the events, update/reschedule events and delete events.
- User after SignUp/logIn, can view all reviews of an event, submit review, like review, report review, give rating for different criteria like registrationExperience,     eventExperience, breakFastExperience and overall ratings.
- If report of a review is greater than or equal to 5 then that review will be flagged.
- Organizer can respond to a particular review.
- Implemented pagination features for browsing through rating/reviews, ensuring efficient handling of large datasets.

## Tech Stack

**Backend:** Node.js, Express.js.

**Database:** MongoDB.

**Backend APIs Testing Tool:** Postman.

## Run Locally

Create .env file and write following environment variables

```bash
  PORT =
  MONGO_URL =
  SALT_ROUNDS =
  JWT_EXPIRES_IN =
  JWT_SECRETE_KEY =
```

Install dependencies by 

```bash
  cd Backend/
  npm install
```

Start the Backend server / app (app.js)

```bash
  npm run dev
```
