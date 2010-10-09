Rails 3, RSpec, Factory Girl, Haml, and jQuery
==============================================

Easily generate a Rails 3 RC application with RSpec, Factory Girl, Haml, and
jQuery in one line:

    % rails new <my_app> -J -T -m http://github.com/bendyworks/rails3-app/raw/master/app.rb

## Need Cucumber?

Use this generator file instead:

    % rails new <my_app> -J -T -m http://github.com/bendyworks/rails3-app/raw/master/cuke.rb

rvm
---

We love `rvm`, so the application has an `.rvmrc` generated to specify a gemset.

Generators
----------

This also gives you the Factory Girl and Haml Rails 3 generators &mdash; the
generators for RSpec are in the RSpec gem &mdash; so that your factories and
views are generated using Factory Girl and Haml, and that all your generated
tests are specs. These generators are from the [ haml-rails
](http://github.com/indirect/haml-rails) and [factory_girl_generator](http://github.com/leshill/factory_girl_generator) gems.

JavaScript Includes
-------------------

Since the Rails helper `javascript_include_tag :defaults` is looking for
Prototype, we change the default JavaScript includes to be jQuery.

git
---

We love `git`, so the application has a git repo initialized with all the initial changes staged.

Wrap Up
-------

After the application has been generated, there are a few final command to finish the install, check the output!

Note on Patches/Pull Requests
-----------------------------

* Fork the project.
* Make your feature addition or bug fix.
* Commit
* Send me a pull request. Bonus points for topic branches.
