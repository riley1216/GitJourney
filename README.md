#  ![png](https://user-images.githubusercontent.com/6971421/27861136-5f791fa2-6134-11e7-85f5-97c00a39b84a.png ) GitJourney 


[![Codacy Badge](https://api.codacy.com/project/badge/Grade/d6fabe013081423eaedcf07056f48b15)](https://www.codacy.com/app/OlgaKuklina/GitJourney?utm_source=github.com&utm_medium=referral&utm_content=OlgaKuklina/GitHubJourney&utm_campaign=badger) [![Build Status](https://travis-ci.org/OlgaKuklina/GitJourney.svg?branch=master)](https://travis-ci.org/OlgaKuklina/GitJourney)


![gjimg7](https://user-images.githubusercontent.com/6971421/27860742-ba54135c-6132-11e7-9a72-929bd922e88a.png)


Overview
======

A non-official GitHub mobile app helps users work with their github content, monitor
github activity, check for news and updates.
The application implements secure login with OAuth to access user data.
In the main screen user is able to monitor daily contributions activity placed in chronological
order. 
The application allows user to monitor profile data such as feed list, repositories,
followers/followings list, and starring / watching activity.

The app widget provides a list of today’s feeds and invitations to start journey: by clicking on a
list item, the app opens on the feed list tab.

Explore and search
======

 - Explore your daily contributions activity.
 - Explore public repositories, analyze source code
 - See number stars and clones of your repositories.
 - See list of followers of current user.
 - Navigate to your GitHub map
 - See list of users followed by current user.
 - Monitor feed list with different types of user activity.
 - See number of starred repositories with number of stars, clones and watchers.

Getting Started
======
- The app uses GitHub API. Get your API keys in order to run the app.
- Create a new resource file using the following path: app/src/main/res/values/client_credentials.xml.
- Put "client_id" and "client_secret" key values in it.

Application min API Level: 22, Android 5.1 ( LOLLIPOP_MR1 ).

Used libraries
======
- Picasso for loading and rendering images.
- CommonsIO/CommonsHttpClient for accessing GitHub REST api.
- A number of standard Android libraries.
- A text-to-html conversion tool MarkdownJ
- Softwee:codeview-android:1.2.0 for syntax highlighting

License
======

Copyright 2017 Olga Kuklina

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.


