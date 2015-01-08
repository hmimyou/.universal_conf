This is my personal console config for every computer. 

Setup: 

1. git clone this dir to your home dir(~).

2. In your ~/.bash_profile file, add the following line at the bottom:

	[ -f ~/.universal_conf/.univ_bash_profile ] && source ~/.universal_conf/.univ_bash_profile

3. In your ~/.gitconfig file, add the following lines at the bottom:

	[include]
		path = ~/.universal_conf/.univ_gitconfig
