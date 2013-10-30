
bookmarklet.js: timefiller.js
	echo -n 'javascript:(function(){' > $@
	cat $< | tr '\n' ' ' >> $@
	echo '})()' >> $@

clean:
	rm -f bookmarklet.js
