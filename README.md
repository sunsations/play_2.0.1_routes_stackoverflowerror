play_2.0.1_routes_stackoverflowerror
====================================
The following simple project creates an StackOverflowError on my MacBook Air.
In my project I would like to have clean URLs. Thus I creates entries in conf/routes like:
GET   /switzerland  controllers.Application.country(countryCode = "CH")
GET   /germany      controllers.Application.country(countryCode = "DE")
...
GET   /:countryCode  controllers.Application.country(countryCode: String)


Any help on how to prevent the error is highly appriciated.
Maybe there is also a much more elegant solution to this propblem.

Thank you for your help.
