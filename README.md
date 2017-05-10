# SASL plugin for ChatZilla.

ChatZilla is a clean, easy to use and highly extensible Internet Relay Chat (IRC) client

Get it here: https://addons.mozilla.org/addon/16

# How do I install scripts?
http://chatzilla.hacksrus.com/faq/#install-script

# How to use chatzilla
https://wirelesspt.net/wiki/Chatzilla

*****************************************************************************************

# Plugin usage.

/plugin-pref cz_sasl
/plugin-pref cz_sasl sasl.username YOUR_USERNAME
/plugin-pref cz_sasl sasl.password YOUR_PASSWORD
/plugin-pref cz_sasl sasl.proceed_on_fail (true|false)

*****************************************************************************************

# How to enable debug mode.

- Set ``browser.dom.window.dump.enabled'' to true in ``about:config''.
- Run ``/pref debugMode cdt'' in ChatZilla.
- Start ChatZilla from console, like ``seamonkey -chat'' or ``firefox.exe -chat -console''.

