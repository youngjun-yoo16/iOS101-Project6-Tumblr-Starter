# Project 6 - *Tumblr Detail*

Submitted by: **Youngjun Yoo**

**Tumblr Detail** is an app that displays a list of Tumblr blog posts in a scrolling list. It demonstrates creating and configuring a table view and a custom table view cell, along with fetching data from an API. The project emphasizes UI setup, including table views and custom cells, and dynamically loading images and text from the Tumblr API into the app. It's a practical exercise in applying API data fetching and UI elements in iOS development.

Time spent: **2** hours spent in total

## Required Features

The following **required** functionality is completed:

- ✅ Setup navigation to the Detail Screen
- ✅ Created the Detail View UI
- ✅ Add the ability to pass data to the Detail View Controller
- ✅ Made personal finishing touches to the UI

## Video Walkthrough

<div>
    <a href="https://www.loom.com/share/c26ab99eb7a8404bbd6243b788e63ea7">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/c26ab99eb7a8404bbd6243b788e63ea7-1712035127369-with-play.gif">
    </a>
</div>

## Notes

Realizing that we have to set the 'post' property in advance (i.e. within the prepare for segue method) was something unexpected and caused me initial challenges. Since post is an implicitly unwrapped optional, if it gets referenced before a value is set (i.e. it's nil) we'll get a crash.

## License

    Copyright [2024] [Youngjun Yoo]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
