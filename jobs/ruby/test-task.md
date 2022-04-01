# Description
Make a `create` action in `PostController < ApplicationController` controller that creates a post.
The action should send an email to the user notifying them that the post was created.
Also, `History` record (like a log record) should be created during the creation of the post.

## Models spec
### Post
`author` - String

`title` - String

`body` - Text

### History
`type` - String

`user`- String

`created_at` - Date

The code doesn't have to run. Feel free to create the whole Rails app from scratch and push the result to your GitHub profile, or just write code in several files and publish them as Gist, it is up to you.
Also, there are no restrictions on using libs or other 3rd party code.
Feel free to organize the code and build models and their relations as you want.

# Advanced
Cover your code with tests. This is not a mandatory requirement, but would be great plus
