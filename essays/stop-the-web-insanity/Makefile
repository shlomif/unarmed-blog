all:

upload:
	rsync -a -v --progress *.xhtml "$${HOMEPAGE_SSH_PATH}"/stop-the-web-insanity/

firefox:
	firefox *.xhtml
