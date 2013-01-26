all:

upload:
	rsync -a -v --progress *.xhtml "$${__HOMEPAGE_REMOTE_PATH}"/stoic-road/

firefox:
	firefox *.xhtml
