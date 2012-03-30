all:

upload:
	rsync -a -v --progress *.xhtml "$${HOMEPAGE_SSH_PATH}"/stpoic-road/

firefox:
	firefox *.xhtml
