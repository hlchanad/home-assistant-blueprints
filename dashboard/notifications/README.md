# Notifications Section

## Description
It creates a notifications section on the dashboard. The notifications are 
shown only when certain condition is fulfilled. If there is no any 
notifications, the 'Notification' title will be hidden as well!

This is achieved by css hack only. No extra virtual sensor needed to be 
created. It would be extremely easy for supporting new notifications in
the future.

## Showcases

### When there is notifications:
![has-notifications.png](has-notifications.png)

### When there is no notifications 
![has-no-notifications.png](has-no-notifications.png)

## Dependencies
- [lovelace-card-mode](https://github.com/thomasloven/lovelace-card-mod)
- [lovelace-mushroom](https://github.com/piitaya/lovelace-mushroom)

## Notes
Since the pseudo-class `:has()` is used, please confirm your usage on 
[can-i-use](https://caniuse.com/css-has) beforehand.
