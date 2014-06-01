FBLikeOnly v0.1b
==========

Facebook Like-only Button.
Can be used not to loose FB subscribers and 'likers'.
It uses HTML5, CSS, jQuery.


Use as iframe with set:
* Facebook App Id,
* URL to like
* Button Text
* Locale

__Send data to iframe via URL #hash__

Hash variables are:
* 'text' for Button Text
* 'locale' to set FB locale (en_US by default)
* 'appID' to set FB App ID associated with the url the button is loading from
* 'urltolike' is urldecoded component to set URL to like

Example:
```html5
<iframe src="fb.like.only.btn.html#appID={appID}&locale={locale}&text={like button text}&urltolike={encoded URL to like}"></iframe>
```
