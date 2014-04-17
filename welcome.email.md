# Welcome to AppFog.
Just follow these steps below to get started.
##### First, you'll need to verify your email by visiting:
```
*verification URL goes here*
```
##### And input your verification token:
```
*verification token goes here*
```
Also, you can simply copy the token to your [Profile page](https://console.appfog.com/#profile).
* * *
##### Once you've verified your account, you can check out our KB to get up to speed and start using AppFog.
* [AppFog Support Documentation](https://docs.appfog.com)

Here are some things you can do to get started uploading content. First, you will need to install [Ruby](https://www.ruby-lang.org/en/installation) before you can get the AppFog Command Line Interface (AF CLI) tool installed.

```
$ sudo gem install af
```
You can then easily upload your content with our RESTful API.

```
$ af login
$ cd <app directory>
$ af push
```
Making changes to your app is easy -- pull it down, edit your code, and push it up with just these simple commands:

```
$ af pull <app name>
$ cd <app directory>
$ af update <app name>
```
Tunnel into your Postgres, MySQL or Mongo databases using [Caldecott](https://rubygems.org/gems/caldecott).

```
$ af tunnel <service name>
```
* * *
### Support
We're here to help! Our Support Desk is staffed 8am-6pm CST(GMT-6), Monday through Friday. You should submit a [ticket](support.appfog.com) using the email address associated with your account so we can quickly prioritize it based on you plan level. Our current system status and uptime report can be found at [status.appfog.com](status.appfog.com).

You can search user-moderated forums to explore how other users may have resolved similar issues.
* [AppFog Users Google Group](https://groups.google.com/forum/#!forum/appfog-users)
* [Stack Overflow](http://stackoverflow.com/search?q=appfog)

### News
Keep in touch! Visit our [blog](http://blog.appfog.com), and subscribe to [@appfog](https://twitter.com/@appfog) and [@appfogstatus](https://twitter.com/AppFogStatus) for news and plans for the future.
* * *
##### We're excited you've joined the AppFog community, and we look forward to getting to know you better. We appreciate any [feedback or suggestions](feedback.appfog.com)!

Sincerely,

David Gardiner | Senior Product Manager of AppFog
