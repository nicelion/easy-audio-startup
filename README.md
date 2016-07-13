# easy-audio-startup

## Installation


### easy-audio-startup

    $ sudo curl -L http://www.nicelion.com/easy-audio-startup -o /usr/local/bin/easy-audio-startup
    
Then, to make it work: 
  
    $ sudo chmod +x /usr/local/bin/easy-audio/startup
  
### easy-audio Terminal Profile

    $ curl -L http://www.nicelion.com/easy-audio-startup/terminal -o /Users/yourdirectory/Desktop/easy-audio.terminal
  
You can really export this anywhere, it's just that the desktop is far easier to access than anyother directory.

- Once on the Desktop, open terminal. Go to the "Preferences" by pressing CMD+,.
- Go to the "Profiles" tab
- Click the gear/setting button on the bottom
- Click import
- Find the easy-audio.terminal file and import it
- Close your Terminal window
- Right click on the Terminal window and go to "New Window with Settings" and click easy-audio


## Configuration

easy-audio-startup will  NOT work out of the box. You will need to open the file and edit your desired directory.

Use a text editior to do so. You can use Vim, emacs or even nano if you want. For this example, I will use Vim.

    $ vim /usr/local/bin/easy-audio/startup

Press I to insert and find and change to the directory where it tells you.

Press escape and type ":wq" to save and quit.

Everything should now work.

