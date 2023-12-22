# magasin-scp

my high school's intended rewards system web app

## Installation

Use `docker compose up` to test the web app in a Docker container, and create a `.env` file inside the `magasinscp` package with the following variables

```
KEY=YOUR_KEY
MESSAGE_SENDER_EMAIL_ADDRESS=SENDER_EMAIL_ADDRESS
MESSAGE_SENDER_PASSWORD=SENDER_PASSWORD
STAFF_EMAIL_ADDRESS=STAFF_EMAIL_ADDRESS
```

## Usage

- Create user account with your school's email address for authentication, with the option to reset your password if needded
- Students accounts have an associated rewards points balance, while teacher's account have access to an administrative page for managing students account (e.g. distributing rewards points, modification to students credentials if needed)
- Students can access the store page for purchasing rewards, with immediate updates to their account balance
- Teachers can view students pending orders to be fufilled

