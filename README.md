# avatar-image (get gravatar by email)
Get the gravatar image by email address with specefic size.

## Usages
Install the latest version:

```npm i avatar-image```

Require the module in your code & start using:

```const avatar = require('avatar-image');```

# Documentation
#### How to use on your template:

It's very easy to use, It will give you generated link from your email address with a default size of 80 px. 

`avatar(email, size)` this function allows you to use two pass email and size.

after import just use anywhere from your file like this:
##### example (For specefic image size like 128 px):
`var imgLink = avatar('youremail@example.com', 128)`

`<img src='imgLink'`/>

##### example(by default it will give you 80 px image src link):
`var imgLink = avatar('youremail@example.com')`

`<img src='imgLink'`/>

#support & suggestion:

If you face any issue with this package please let us know about it by creating an issue on Github.
Any kind of suggestion will be appreciated.



