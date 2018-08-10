# dVideo Embed Player

This is the main video player for dVideo. It is hosted directly on GitHub pages for simplicity. You can pass options to the player through the url hash fragment:

The syntax is as follow `/#!/author/permlink/autoplay/branding`

* Author: the Steem username of the account associated with the content
* Permlink: the permlink of the Steem content, or 'live' for the user livestream
* Autoplay: true/false, default to false. If true, the video will start playing without click
* Branding: true/false, default to false. If true, the dVideo logo will be hidden

Example:

`https://get.dvideo.io/#!/jaredricesr/s3k3cjji/true/true` -> will autoplay and remove dVideo logo
