# NotificationRequest

How to get notification authorization status in swift?


When getting the notification authorization status, there are actually three states it can be in, i.e.

authorized
denied
non-determined

A straightforward way to check these is with a switch-case where .authorized, .denied, and .nonDetermined are enums in UNAuthorizationStatus.

Description of UNAuthorizationStatus can be found here in Apple's docs 
https://developer.apple.com/documentation/usernotifications/unauthorizationstatus
