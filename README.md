# OpenCore-Z390
### Z390 OpenCore bootloader for Big Sur, Catalina, Mojave

Configuration: `Z390UD + i7 8700 + RX 580 `

What's Working?
* Bluetooth
* Location Services
* AirDrop
* Airplay
* All Ports


What's not working?
* Nil

### Change this data according to your closest system configuration

`config.plist` => Use Opencore config changer / Clover Configurator to generate Serial
```xml
<key>BoardSerialNumber</key>
<string>C02936902GUKGQGUE</string>
<key>BiosVendor</key>
<string>Apple Inc.</string>
<key>ProductName</key>
<string>iMac19,2</string>
<key>SmUUID</key>
<string>63A5F24D-5798-4D37-B4DC-DB7A99AD2E5F</string>
<key>BoardType</key>
<integer>10</integer>
<key>EfiVersion</key>
<string>1554.60.15.0.0</string>
<key>SerialNumber</key>
<string>C02ZC7Z0JWDW</string>
```
