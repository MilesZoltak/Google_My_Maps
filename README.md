# Google_My_Maps

## Miles Zoltak

**Google_My_Maps** displays a list of maps, each of which show user-defined markers with a title, description, and location. The user can also create a new map. 

Time spent: **12** hours spent in total

## Functionality 

The following **required** functionality is completed:

* [x] The list of map titles is displayed.
* [x] After tapping on a map title, the associated markers in the map are shown.
* [x] The user is able to create a new map.

The following **extensions** are implemented:

* [x] The user can delete a map from the RecyclerView

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<blockquote class="imgur-embed-pub" lang="en" data-id="a/WpBjLde" data-context="false" ><a href="//imgur.com/a/WpBjLde"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>
<img src='https://imgur.com/a/WpBjLde.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

I really wanted to build in SQLite database functionality using Room but it was such a nightmare I sunk a lot of time into it and
scrapped it for a more attainable goal.  Afterall, this setup works, and it seems like deleting maps is actually a pretty useful
functionality that wasn't yet included!  I had some trouble passing around the right information and it was initially hard to
remove items from the RecyclerView, but I got it eventually!
## License

    Copyright [2020] [Miles Zoltak]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
