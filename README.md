When first starting up your local network, or when you restart your computer, local network, and/or ADB server, All active "adb reverse" port-forwarding rules are cleared.

!!!!!!!!!Make sure the program/server is running (with the emulator, or while your device is connected) before running the command!!!!!!!!!!!


Run this command in WINDOWS POWERSHELL

""""""""""""""

& "C:\Users\(yourusername)\AppData\Local\Android\Sdk\platform-tools\adb.exe" reverse tcp:8080 tcp:8080

""""""""""""""

You may find your AppData folder by pressing Windows+R, type "appdata" to look for the right folder directory.
Or press the windows key, and type %appdata% on the Windows search bar.

