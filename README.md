# YouLess #

Homey app to integrate YouLess LS110 and LS120 energy meters into Homey.
The app builds on the original work of Maik van Wel. His LS110 driver is still
available for legacy support.

The new drivers provides logs and adds flow cards for the following data:
- Actual power usage/production (W, 10s interval)
- Totalized power meter (kWh, 10s updates)
- All individual power meters (kWh, 10s updates)
- Recent gas usage (m3, of the previous hour)
- Gas meter (m3, 1 hour updates)
- Tariff change (off-peak, true or false)

Ledring screensaver:
- See how much energy you are using or producing just by looking at your Homey!
- Is the wash-dryer ready? Am I now producing power to the grid?

The power is totalized for consumed and produced power, during off-peak and
peak hours. Production to the powergrid is displayed as negative watts.
Only changed values are logged.

To setup go to "Devices" and enter the IP-address (preferred) or use the default
url 'youless'.

##### Donate: #####
If you like the app you can show your appreciation by posting it in the [forum],
and if you really like it you can donate. Feature requests can also be placed on
the forum.

[![Paypal donate][pp-donate-image]][pp-donate-link]

<sup>btc: 14VR1QCpqWUWiSLa1sn3Dpzq3Wrp83zFfC</sup>

<sup>eth: 0xEcF4747203Eba214c071fDAa4825cD867B410d70</sup>

<sup>ltc: LfGJu1AdnPFMoBXwHvf2qG9sCV1onyXDvd</sup>

===============================================================================

Version changelog

```
v1.0.0  2017.06.07 App transfer (LS-110) from Maik van Wel. His LS-110 driver is
				kept for legacy support. Internal speech support is removed.
				Node modules updated. Added support for YouLess LS-120 (P1).
```
[forum]: https://forum.athom.com/discussion/2779
[pp-donate-link]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=FV7VNCQ6XBY6L
[pp-donate-image]: https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif
