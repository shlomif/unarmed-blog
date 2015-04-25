all:

upload:
	rsync -a -v --progress *.xhtml "$${__HOMEPAGE_REMOTE_PATH}"/inelegant-code/

firefox:
	firefox *.xhtml
