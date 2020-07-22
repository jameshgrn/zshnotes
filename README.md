# zshnotes
# oh-my-zsh-reminder
A small, simple OhMyZsh plugin which creates a daily notes file in your homefolder ($HOME/zshnotes) and timestamps any entries, accessed by using "note" and "cnote" in the terminal

Start by adding a note :

    $ note I need to get tomatoes
 
    $

Then see your added note (with timestamp) :

    $ cnote
    ##########################################################
    ############### DAILY NOTES FOR 07-22-20 ################
    ##########################################################

    06:13:06 PM:  I need to get tomatoes

    $

You can always add another :

    $ note I had a great conversation with my colleague today

    $

It will have an accurate timestamp :

    $ ##########################################################
      ############### DAILY NOTES FOR 07-22-20 ################
      ##########################################################

      06:13:06 PM:  I need to get tomatoes
      --
      06:15:20 PM:  I had a great conversation with my colleague today

    $

Thats it! 

# Installation

To install, clone the repo into `~/.oh-my-zsh/custom/plugins` (ZSH plugins don't allow dashes, so make sure you clone it into a single-word folder):
``` bash
git clone https://github.com/jameshgrn/zshnotes/ ~/.oh-my-zsh/custom/plugins/reminder
```

Then add it to your list of plugins in `~/.zshrc` (e.g `plugins=(zshnotes)`).

I took much of this README from github user AlexisBRENON: check out their project here [https://github.com/AlexisBRENON/oh-my-zsh-reminder]
