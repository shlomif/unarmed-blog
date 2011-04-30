all:

upload:
	rsync -a -v --progress *.xhtml "$${HOMEPAGE_SSH_PATH}"/criminal-mind/

firefox:
	firefox *.xhtml
