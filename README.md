# pixelpost: upload and post images to pixelfed/mastodon

simple bash script, uses curl and jq

`usage: ./pixelpost file[s]`

 - uses image description from exif data (UserComment) (probably doesn't work with newlines yet)

 - almost no error checking, handle with care

## setup

copy pixelpost.conf to ~/.config
edit it to supply server information and access token from your profile
