<!--
This file is auto-generated and will be re-generated every time the docs are updated.
To modify it, go to its source at https://github.com/fastlane/fastlane/blob/master/fastlane/lib/fastlane/actions/chatwork.rb
-->

# chatwork


Send a success/error message to [ChatWork](https://go.chatwork.com/)




> Information on how to obtain an API token: [http://developer.chatwork.com/ja/authenticate.html](http://developer.chatwork.com/ja/authenticate.html)


chatwork ||
---|---
Supported platforms | ios, android, mac
Author | @astronaughts



## 1 Example

```ruby
chatwork(
  message: "App successfully released!",
  roomid: 12345,
  success: true,
  api_token: "Your Token"
)
```





## Parameters

Key | Description | Default
----|-------------|--------
  `api_token` | ChatWork API Token | 
  `message` | The message to post on ChatWork | 
  `roomid` | The room ID | 
  `success` | Was this build successful? (true/false) | `true`

<em id="parameters-legend-dynamic">* = default value is dependent on the user's system</em>


<hr />
To show the documentation in your terminal, run
```no-highlight
fastlane action chatwork
```

<a href="https://github.com/fastlane/fastlane/blob/master/fastlane/lib/fastlane/actions/chatwork.rb" target="_blank">View source code</a>

<hr />

<a href="/actions/"><b>Back to actions</b></a>
