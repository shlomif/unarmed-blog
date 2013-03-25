all:

upload:
	rsync -a -v --progress *.xhtml "$${__HOMEPAGE_REMOTE_PATH}"/temp-publish-or-perish/

firefox:
	firefox *.xhtml
