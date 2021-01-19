# **Switching from Bash to Zsh**

In the terminal run:

<kbd>brew update && brew install rbenv ruby-build</kbd>

&nbsp;

Open <mark style="background:lightblue">`.zshenv`</mark> using `nano` or `vim` and put the following in the file.

<kbd>`export PATH="$HOME/.rbenv/bin:$PATH"`</kbd>

&nbsp;

Afterwords add the following lines to <mark style="background:lightgreen">`.zshrc`</mark>.

<kbd>`source $HOME/.zshenv`</kbd>

<kbd>`eval "$(rbenv init - zsh)"`</kbd>

&nbsp;

This is so the previous file is sourced correctly when a new session is started and
rbenv is initialized for Zsh. 

&nbsp;

Now source <kbd>.zshrc</kbd> or restart the terminal.

<kbd>source ~/.zshrc</kbd>

&nbsp;

Add all <kbd>`$PATH`</kbd> statements from <kbd>`~/.bash_profile`</kbd> to your 
<mark style="background:lightblue">~/.zshenv</mark> file.

&nbsp;

Add all alias, functions, key bindings and more from <kbd>`~./bash_profile`</kbd> and 
put them in your <mark style="background:lightgreen">~./zshrc</mark> file.

&nbsp;

Make sure to update <kbd>Xcode</kbd> by opening up the App Store and looking in the top right
for updates. Find <kbd>Xcode</kbd> and click update.

![alt text](./assets/Screen%20Shot%202021-01-18%20at%2010.22.21%20PM.jpg "xcode")

&nbsp;

Finally install <kbd>rbenv</kbd> editions that you want. You can find any latest stable
versions by running <kbd>rbenv install -l</kbd>

&nbsp;

Run the following:

<kbd>rbenv install 2.7.2</kbd>

<kbd>rbenv global 2.7.2</kbd>

&nbsp;

Check to make sure everything is up and running properly by running:

<kbd>ruby -v</kbd>

<kbd>ruby -e "puts (1..100).reduce(:+)"</kbd> 

You should get the following output: `5050`

&nbsp;

## **Congratulations! You are now coding like a BOSS 😎🔥**

# **Go ahead and install your 💎 gems**