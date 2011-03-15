all:

upload:
	rsync -a -v --progress *.xhtml "$${HOMEPAGE_SSH_PATH}"/they-who-teach-can/

firefox:
	firefox *.xhtml
