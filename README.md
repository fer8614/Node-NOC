# Project NOC

The objective is to create a series of tasks including a network operation center NOC, using Clean Architecture with TypeScript for sending emails and create databases with MongoDb and PostgreSQL

# dev
1. Clone .env.template file to .env
2. Configure environment variables

```
PORT=3000

MAILER_SERVICE= 
MAILER_EMAIL=
MAILER_SECRET_KEY=

PROD=false
```
3. Run the command ```npm install```

4. Enable two-factor authentication for email using the link attached below, in this case it will be used as MAILER_SERVICE=gmail
[Enable two-factor authentication](https://myaccount.google.com/security)

5. Configure the gmail email environment variable and place it in the MAILER_EMAIL= xxxxx@gmail.com variable and request the application password through the attached link, which must be placed in the MAILER_SECRET_KEY= environment variable, the password must be placed without include spaces all together.
[Google AppPasswords](https://myaccount.google.com/u/0/apppasswords) 

6. Open Docker Desktop and run the command
```
docker compose up -d
```
10. Run the command ```npm run dev```
