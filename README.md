# How to create a Twitter Developer Account

## Sign Up for a Twitter Account
- You will need your own Twitter account first. Sign up for one at [twitter.com](twitter.com). You can always delete it afterwards.
- Go to your Twitter settings https://twitter.com/settings/account. Select 'Mobile' and add your mobile phone to your account. Twitter will send you a confirmation code via text. This is required to create an application.

## Apply for a Twitter Developer Account
- Go to https://developer.twitter.com/en/apps and create an application. 
- You will need to apply for a developer account. This is a [new process that started in Summer 2018](https://blog.twitter.com/developer/en_us/topics/tools/2018/new-developer-requirements-to-protect-our-platform.html) which requires you to fill out additional forms including a detailed explanation of what you are going to use the API for. Twitter will need to approve your application. I went through the new process and I got the developer account approved within a business day (although not without pain; it took me 3 attempts to explain my use case which was highly annoying).  

Start|Finish
---|---
![start screen](img\twitter_developer_acct.png)|![confirmation](img\application_confirmation.png)

## Getting Twitter Credentials

Twitter implements OAuth 1.0 as its authentication protocol. You'll need 4 credentials in order to use OAuth and make requests to Twitter's API.

The four credentials (i.e. API key, API secret key, Access token and Access token secret) can be obtained on the Twitter developer site to access the API. The steps are as follows:

- Go to https://developer.twitter.com/en/apps and create an application. 
- Enter a name/description/website for your application. You can use https://www.google.com for the website. You also need to describe how the app will be used. Agree to the Developer Terms and create your Twitter application.
- Go to the *Keys and tokens* tab. You should be able to see your **Consumer Key** and **Consumer Secret**.
- At the bottom of the page, click the button to create your own **Access Token** and **Access Token Secret**.

**Note**: You can always revoke/regenerate your credentials or delete the application.

### You should now be ready to start using the Twitter API with your credentials. You're now ready for the workshop.
