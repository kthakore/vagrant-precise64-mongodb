vagrant-precise64-mongodb
============================

Vagrant files for a mongodb server based on Ubuntu Precise 64.

How to Use?
-----------

You can use this as a database server for any project.

1. Install [vagrant](http://vagrantup.com/)
2. Install [VirtualBox](http://www.virtualbox.org/)
3. Install this box on vagrant

        vagrant box add precise64-mongodb [ADD_URL]

4. Init it on your project directory

        vagrant init precise64-mongodb

5. Run it!

        vagrant up

6. Mongodb will be available to connect on port 27017.

How to Hack?
-----------

1. Install [vagrant](http://vagrantup.com/)
2. Install [VirtualBox](http://www.virtualbox.org/)
3. Clone this repo
4. Bundle it

        cd vagrant-precise64-mongodb
        bundle

5. Customize the mongodb config files
6. Test it

        vagrant up

7. Package and distribute it like on [documentation](http://docs.vagrantup.com/v1/docs/getting-started/packaging.html)

        vagrant package --vagrantfile Vagrantfile.pkg

Maintainer
----------

* Ramon Bispo (http://ramonpage.com)

License
-------

(The MIT License)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
