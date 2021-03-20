# ExpressJS project with Google OAuth for authentication and Gmail Smtp for Email Forwarding

## 1. How to clone and install dependencies
```
git clone https://github.com/jhonny-alberto/Oauth-Gmail-smtp.git && cd Oauth-Gmail-smtp && npm install
```
## 2. How to use
To make it work, We need following variables in __.env__ file

```
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
OAUTH_CALLBACKURL=

GMAILAPP_MAIL=
GMAILAPP_PASS=

PORT=3000
```
> To know how to generate and use __GOOGLE_CLIENT_ID__, __GOOGLE_CLIENT_SECRET__ and __OAUTH_CALLBACKURL__, refer https://developers.google.com/identity/sign-in/web/sign-in

> To know how to generate and use __GMAILAPP_MAIL__ and __GMAILAPP_PASS__ to use gmail smtp service, refer https://support.google.com/mail/answer/185833?hl=en

If you have any trouble in running the project, please contact Jhonny.

## 3. How to run
```
npm run start
```

## 4. Project Code explanation
 - Strucutre overview 
 https://i.imgur.com/PMMsZ5Y.png
