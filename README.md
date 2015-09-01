# paper-gmail

## Overview
A material design version of gmail web app using [Polymer](https://www.polymer-project.org/1.0/). This project is using **Polymer 1.0**.

**Note**: This project originally uses Polymer 0.5. The migration work is still WIP and has not been done yet, as of Sep 1st, 2015.

**Note**: This web is still work in progress. Not all of the gmail features have been implemented. Since the app is using Google's Gmail Rest API, only features that are supported by Gmail REST API will be implemented in the future. 



## Features Supported now
* Default to show Today's emails
* Show emails list load load more emails when click on the "MORE ..." button.
* Search emails is working. It is working as the same as email searching except it excludes chats, which in the behind, it always append !is:chats to the end of search terms.
* Refresh Button is working.
* Email content is shown up. (Pure text, html based). Email view is showing all messages in the time order. It is using a reverse order of current Gmail Client. This means the latest email comes first.
* In the email view, archive, delete, move to folder buttons work as expected.
* Compose email is working. You could write simple text based email by clicking "+" button on the right bottom.

## Not working yet
* apps button next to refresh button is not working yet.
* Click on drafts will not open up a sending email window. Instead, it only shows in a email thread view for now.
* Forwarded email might not show up correctly.
* Some email's body doesn't show up correctly.
* Email attachments do not show up yet.
* Reply email is currently under developement.

## Demo
The stable version is hosted in [Google's App Engine](https://gmail-polymer.appspot.com/).

Sometimes it keeps refreshing for the first time. In this case, copy the url and paste it in a new tab will work.
The first time you access the app, you will need to sign in with your Google account. Actually, this is just to gain authorization from you to get emails and write emails as behalf of you.


## Resources 
* [Gmail REST API](https://developers.google.com/gmail/api/)
* [Polymer](https://www.polymer-project.org/1.0//)
* [Google's Material Design Colors](http://www.google.com/design/spec/style/color.html)

