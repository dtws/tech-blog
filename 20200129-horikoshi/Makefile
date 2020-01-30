blog.html: blog.md
	markdown $< > $@

blog.md: blog.ipynb
	ipython nbconvert --to markdown $<
