Estimated Reading Time
======================

This script estimates the amount of time it'll take to read an article.  It gives the user an ETA of how long an article will take so they can either read it now or bookmark the page and come back to it.


## How To Use
```
	print 'Estimated reading time is '.readingTime($content);
```


### Note

If you're using Wordpress, add the function to Wordpress.  Then where you're content is output in the template call the function with this...
```
	print 'Estimated reading time is '.readingTime($post->post_content);
```