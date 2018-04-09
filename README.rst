PQI Air Card sync utility for Windows
------------------------

How to install ?
^^^^^

1.  Download and install forceBindIP to bind PQI Air Card IP to a specific Wifi network adapter :

    ::

        https://r1ch.net/projects/forcebindip       
        
2.  Download and install wget for Windows from :

    ::

        http://gnuwin32.sourceforge.net/packages/wget.htm

3. Create a new shorcut and copy-paste next string into path input

    ::

        "C:\Program Files (x86)\ForceBindIP\ForceBindIP64.exe" 192.168.1.1 "C:\Users\User\Downloads\wget.exe"  -c --reject html -m http://192.168.1.1/sd/DCIM/ -o wget.log -P "C:\Users\User\Desktop\PQI Air Card.wget"
