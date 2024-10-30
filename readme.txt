=== Jfa Social Media Post ===
Contributors: @jfadev
Donate link: https://jordifernandes.com/donate/
Tags: Instagram,Social Media
Requires at least: 5.8
Tested up to: 5.8
Stable tag: 1.0.0
Requires PHP: 7.0
License: MIT License
License URI: https://github.com/jfadev/jfa-social-media-post/blob/main/LICENSE

This WordPress plugin allows you to retrieve a specific Instagram post and consume it via the REST API.

== Description ==

This WordPress plugin allows you to retrieve a specific Instagram post and consume it via the REST API.
Homepage: [https://jordifernandes.com/jfa-social-media-post/](https://jordifernandes.com/jfa-social-media-post/)

## Config

Enter https://instant-tokens.com and create the `API URL` of your instagram account.

For example:
`https://ig.instant-tokens.com/users/XXXXXX/instagram/XXXXXX/token?userSecret=XXXXX`

## Endpoint

Access the post's JSON at the following endpoint:
`GET /wp-json/api/v2/social_media_post/post/`

##### Return
`
{
  "permalink": "https://www.instagram.com/p/XXXXXXXXXXXX/",
  "caption": "Caption text",
  "media_url": "https://scontent-ams4-1.cdninstagram.com/v/XXX/XXX.jpg?_nc_cat=X&ccb=1-5&_nc_sid=XX&_nc_ohc=XXX&_nc_ht=scontent-ams4-1.cdninstagram.com&edm=XXX",
  "url_token": "https://ig.instant-tokens.com/users/XXXXXX/instagram/XXXX/token.js?userSecret=XXXX",
  "username": "XXXXXXXX",
  "timestamp": "2020-12-14T20:12:36+0000"
}
`

== Frequently Asked Questions ==

== Screenshots ==

1. Admin page.

== Changelog ==

= 1.0.0 =
This is the first version.

== Upgrade Notice ==