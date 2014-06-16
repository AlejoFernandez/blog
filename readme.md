This is a clone of the qraftlabs blog at [http://blog.qraftlabs.com](http://blog.qraftlabs.com).

This blog uses [Jekyll](https://github.com/mojombo/jekyll).


## Create a new blog post

	rake new_post["title of the new blog post"]

## Run

1.  Make sure you have [RVM](http://rvm.io/) or other ruby version manager installed.
2.	You must also have [npm](http://npmjs.org) installed.
3.  Enter the blog directory and make sure with ruby --version that you are running the right ruby version (.ruby-version file).
4.  Install dependencies with `bundle install`
5.  `bundle exec jekyll serve --watch`
6.  Open [http://localhost:4000/blog/](http://localhost:4000/blog/). Make sure you don't leave out the trailing slash (/), otherwise you will get:
![error](https://i.cloudup.com/FWLX_cUhXb.png)


## License

All the infrastracture to run this blog is open sourced under the [MIT license](http://www.opensource.org/licenses/mit-license.php).

The exact content of the articles (the _posts folder) is Qraftlabs Copyright.
