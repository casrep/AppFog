# Welcome to AppFog!
Please follow the steps below to get started:

##### First, verify your account:
```
*verification URL goes here*
```
##### (Or enter the verification token directly on your [Profile page](https://console.appfog.com/#profile))
```
*verification token goes here*
```
* * *
After your account is verified, please read our [Support docs](https://docs.appfog.com) to learn how to start using AppFog. If you don't want to read any documentation, at least read the rest of this email :-)

You will need to install [Ruby](https://www.ruby-lang.org/en/installation) to get the Command Line Interface (CLI) tool installed. Use the CLI to upload your source code (via our RESTful API)...

```
$ sudo gem install af
$ af login
$ cd <app directory>
$ af push
```
Making changes to your app is easy -- pull it down, edit your code, and push your updates live!

```
$ af pull <app name>
$ cd <app directory>
$ af update <app name>
```
Tunnel into your MySQL, Postgres, or Mongo databases using [Caldecott](https://rubygems.org/gems/caldecott).

```
$ af tunnel <service name>
```
* * *
### Support
Our [Support Desk](http://support.appfog.com) is staffed Mon-Fri, 8am-6pm CST (GMT-6). You should [Submit a ticket](http://support.appfog.com) using the email address associated with your account so we can quickly prioritize your ticket based on your Plan level. Our current system status and uptime report is at [status.appfog.com](http://status.appfog.com). 

We also recommend you subscribe to our [Twitter @appfogstatus](https://twitter.com/@appfogstatus) handle for system status notifications. 

You can also search through these user-moderated forums to explore how other users may have resolved similar issues:
* [AppFog Users Google Group](https://groups.google.com/forum/#!forum/appfog-users)
* [AppFog-related questions on Stackoverflow](http://stackoverflow.com/search?q=appfog)

### News
For updates on what's happening at AppFog, visit our [blog](http://blog.appfog.com) and subscribe to our [@appfog](https://twitter.com/@appfog).
* * *
##### We're glad you've chosen us as your application hosting provider, and appreciate any constructive [feedback or suggestions](http://feedback.appfog.com/). 

Sincerely,

David Gardner | AppFog Product Manager
