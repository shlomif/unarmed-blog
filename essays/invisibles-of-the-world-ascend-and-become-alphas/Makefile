all:

upload:
	rsync -a -v --progress *.xhtml "$${HOMEPAGE_SSH_PATH}"/those-who-teach-can/

firefox:
	firefox *.xhtml
