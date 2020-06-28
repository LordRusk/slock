# slock
Simple X Locker
### configuration
before you compile, open up `config.def.h` and add your user name and group (usually wheel) under the correct variables, otherwise it won't work.
### patches
  - capscolor /* while locked with caps on, when you try to type the color will change from blue to purple. */
  - control-clear /* allows slock to not interact with the control key, making it easy to turn on the screen if it is asleep while lcoked. */
  - message /* allows for messages while locked */
### other
  - when locked using my sxhkd config, a script from my [dotfiles](https://www.github.com/LordRusk/dotfiles), "Suckess: software that sucks less" displays as the message using figlet and a figlet font also included in my dotfiles.
