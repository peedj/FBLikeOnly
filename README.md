Like Only Buttons v0.2
==========

Social Like-only Button Collection.
Can be used not to loose FB subscribers and 'likers'.
It uses HTML5, CSS, jQuery.


Buttons:
* fb.like.only.btn.html - Facebook like-only btn
  
  __Send data to iframe via URL #hash__
  Hash variables are:

  * 'text' for Button Text
  * 'locale' to set FB locale (en_US by default)
  * 'appID' to set FB App ID associated with the url the button is loading from
  * 'urltolike' is urldecoded component to set URL to like
  * fb.like.only.btn.html - Facebook like-only btn
  
  Use as iframe with set:

  * Facebook App Id,
  * URL to like
  * Button Text
  * Locale
  
  Example:
  ```html5
  <iframe src="fb.like.only.btn.html#appID={appID}&locale={locale}&text={like button text}&urltolike={encoded URL to      like}"></iframe>
  ```


Resent Changes:
* v0.1: Just Facebook Like-only Button
