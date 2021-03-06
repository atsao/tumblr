# Lab 1 - Tumblr

**Tumblr** is an app using the [Tumblr API](https://www.tumblr.com/docs/en/api/v2).

Time spent: **11** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x] User can view a list of posts from Humans of New York blog. Posts load asynchronously
- [x] User can view post details by tapping on a cell
- [x] User can pull to refresh the main feed

The following **optional** features are implemented:

- [x] Add a section header view ~~for each post~~ 
- [x] Implement infinite scrolling
- [x] Add a zoomable photo view modal

The following **additional** features are implemented:

N/A

## Video Walkthrough

Here's a walkthrough of implemented user stories.

![Tumblr walkthrough](./Tumblr.gif "Walkthrough")

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Libraries

- CocoaPods
    - AFNetworking

## Notes

My infinite scrolling fires when you reach/drag past the last post rather than a page view before.

Challenges:

- I wasn't able to get the section headers to show up for each post

## License

    Copyright 2016 Andrew Tsao

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
