# Xdgts




                    DISCLAIMER!
"This software is intended for educational and didactic purposes only 
such as testing the security of your own systems. 
It is not intended to be used for any illegal activities, 
such as unauthorized access to systems and/or others. 
The user assumes all responsibility for any actions taken using this script as raw code or precompiled software. 
We encourage users to use this software responsibly and to respect the privacy and security of others. 

 
                    Description :
This script generates a list of all possible combinations of a given number of digits
	(that NUMBER must be an integer). 
The combinations are written to a text file on the user's desktop.
    That should work on Windows, Mac Os and Linux,but still needs testing, please report any error to the author.
The user can choose to include various commands such as :
    "ENTER" wich simulate the press of the enter button
    "DELAY" wich needs a value in milliseconds and writes it after every attempt
        (this is the time the script it's going to wait before trying another pin)
    "SDELAY" as a second delay with different values than the first one
    "TDELAY" as a time delay with given values that you can set to be repeated a given amount of times
    "WAIT_FOR_BUTTON_PRESS" that obviously waits for a button press by the user, that also can be repeated a given amount of times


  

                    Usage:

Run the script.
Enter the desired file name.
Enter the number of digits for the PIN.
Enter the delay values (DELAY, SDELAY and TDELAY if any).
Enter the order of commands to be included after each PIN.
  There's a really useful option called "c" where you can manually enter the keystrokes in DuckyScript and the script its going to use them after every loop.
The script will generate the file on the user's desktop.


                    Attention

The script will overwrite any existing file with the same name if you agree, if not its gonna bre
The script will only work on MacOS, needs testing on other platforms.
The script uses the Os and platform modules, which are part of the Python Standard Library.


                    Contributors

This script was created by:

https://github.com/KiddCalu
https://www.instagram.com/kiddcalu

If you have any questions ,issues or ideas to add something, please contact the author!


                    Credits/Thanks to :

https://Github.com/egosinenomine for helping during the development of the idea and pattern scheme of the script.
https://Github.com/LolloPig for fixing the whole c option in custominorder
https://www.instagram.com/corona.lorenzo_ for helping during the testing on windows and compatibility porting for linux

Thanks for checking out!!!
