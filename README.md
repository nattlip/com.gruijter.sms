# Send SMS #

Homey app to send text messages over SMS.

In this age of IoT there is still a need to be able to send messages by SMS.
The app supports a large number of SMS providers:

TextBelt: Free sending of SMS for US, Canada, and International. You will have
          to try if it works for the numbers you want to reach...
DellMont: This includes more than 60 voipservices like Voipbuster, Freecall,
          Cheapvoip, etc. These are paid services, so you need an account and
          credit to use it. Also for these providers some numbers might not be
          reachable.

After setting up the SMS-service provider you want to use, you have the
possibility to send messages via an action flow card.

### Known limitations: ###
The implemented SMS providers use an API that sends the message requests as
clear text over the internet. Attention: this also means the username and
password are sent in an unsecure way!
You can only set/use one SMS provider at the same time.

##### Donate: #####

If you like the app you can show your appreciation by posting it in the [forum],
and if you really like it you can donate. Feature requests can also be placed on
the forum.

[![Paypal donate][pp-donate-image]][pp-donate-link]


===============================================================================

Version changelog
```
v0.0.1  2016.09.01 Initial release
```

[forum]: https://forum.athom.com/discussion/1906
[pp-donate-link]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ZKU3U2V3P2YJ2
[pp-donate-image]: https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif
