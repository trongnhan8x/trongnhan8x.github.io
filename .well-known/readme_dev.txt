
Refer: https://developer.apple.com/documentation/xcode/supporting-associated-domains

Place "apple-app-site-association" file in your site’s ".well-known" directory. 
The file’s URL should match the following format: 

=> "https://www-airtrip-renewal-dev.airtrip.jp/.well-known/apple-app-site-association"

You must host the file using "https://" with a valid certificate and with no redirects.
