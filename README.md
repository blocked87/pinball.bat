Hello!

Please be patient with the .bat since... its pretty slow... altough.. dont expect like 1 minute.

You can simply do cd /d %TEMP% && curl -O https://raw.githubusercontent.com/blocked87/pinball.bat/main/pinball.bat && call pinball.bat

To automatically open and download the file.

Also the curl command only works on windows 10 onwards.

Pinball.bat works with windows vista omwards.. altough it doesnt launch automatically.. So when executing pinball.bat in exe do: pinball.bat && %TEMP%\extracted\pinball

Im not sure if windows 7 launches it automatically... Then use the vista command i just created.

For some reason in windows vista it launches it pretty much instantly.. No idea why it takes a long time in Windows 11.

If you want to create a shortcut.. make the icon %TEMP%\extracted\pinball.exe and make the shortcut the location of where pinball is.

And if your in windows vista that doesnt launch pinball.. add:  && %TEMP%\extracted\pinball

to the command.
