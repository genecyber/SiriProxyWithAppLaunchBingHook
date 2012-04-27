SiriProxyWithAppLaunchBingHook
==============================

How to run:
Install all prereq's from official SiriProxy

run:
RVM use 1.9.3
./rebuild.sh

how to use:
say Bing open netflix

How it works
bing's website is redirected via dns to the server running within siriproxy (\lib\siriproxy\connection\bing.rb)

list of commands
    "open about settings" => " prefs:root=General&path=About",
    "open accessibility settings" => "prefs:root=General&path=ACCESSIBILITY",
    "open airplane mode settings" => "prefs:root=AIRPLANE_MODE",
    "open autolock settings" => "prefs:root=General&path=AUTOLOCK",
    "open brightness settings" => " prefs:root=Brightness",
    "open bluetooth settings" => " prefs:root=General&path=Bluetooth",
    "open date settings" => " prefs:root=General&path=DATE_AND_TIME",
    "open time settings" => " prefs:root=General&path=DATE_AND_TIME",
    "open facetime settings" => " prefs:root=FACETIME",
    "open general settings" => " prefs:root=General",
    "open keyboard settings" => " prefs:root=General&path=Keyboard",
    "open icloud settings" => " prefs:root=CASTLE",
    "open icloud storage settings" => " prefs:root=CASTLE&path=STORAGE_AND_BACKUP",
    "open international settings" => " prefs:root=General&path=INTERNATIONAL",
    "open location services settings" => " prefs:root=LOCATION_SERVICES",
    "open music settings" => " prefs:root=MUSIC",
    "open music equalizer settings" => " prefs:root=MUSIC&path=EQ",
    "open music volume settings" => " prefs:root=MUSIC&path=VolumeLimit",
    "open network settings" => " prefs:root=General&path=Network",
    "open nike settings" => " prefs:root=NIKE_PLUS_IPOD",
    "open notes settings" => " prefs:root=NOTES",
    "open notification settings" => " prefs:root=NOTIFICATIONS_ID",
      "open notification weather settings" => " prefs:root=NOTIFICATIONS_ID&path=Weather_Widget",
      "open notification phone settings" => " prefs:root=NOTIFICATIONS_ID&path=Phone",
      "open notification mail settings" => " prefs:root=NOTIFICATIONS_ID&path=Mail",
      "open notification messages settings" => " prefs:root=NOTIFICATIONS_ID&path=messages",
      "open notification reminders settings" => " prefs:root=NOTIFICATIONS_ID&path=Reminders",
      "open notification calendar settings" => " prefs:root=NOTIFICATIONS_ID&path=Calendar",
      "open notification skype settings" => " prefs:root=NOTIFICATIONS_ID&path=Skype",
    "open password lock settings" => "prefs:root=General&path=Passcode_Lock",
    "open phone settings" => " prefs:root=Phone",
    "open photos settings" => " prefs:root=Photos",
    "open profile settings" => " prefs:root=General&path=ManagedConfigurationList",
    "open reset settings" => " prefs:root=General&path=Reset",
    "open safari settings" => " prefs:root=Safari",
    "open siri settings" => " prefs:root=General&path=Assistant",
    "open sounds settings" => " prefs:root=Sounds",
    "open software update settings" => " prefs:root=General&path=SOFTWARE_UPDATE_LINK",
    "open store settings" => " prefs:root=STORE",
    "open twitter settings" => " prefs:root=TWITTER",
    "open usage settings" => " prefs:root=General&path=USAGE",
    "open vpn settings" => " prefs:root=General&path=Network/VPN",
    "open wallpaper settings" => " prefs:root=Wallpaper",
    "open wi-fi settings" => " prefs:root=WIFI",

    #apps
    "open netflix" => "nflx://",
    "open youtube" => "youtube://",
    "open skype" => "skype://",
    "open ibooks" => "itms-books://",
    "open mail" => "mailto:"