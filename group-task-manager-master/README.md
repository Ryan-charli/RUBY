# group-task-manager
Group task manager assignment on rails
## Running the code
First, install [group-task-manager-master](https://github.com/Ryan-charli/RUBY/edit/master/group-task-manager-master):

    git clone git://github.com:Ryan-charli/RUBY.git
    cd group-task-manager-master
    git submodule init
    git submodule update
    make && sudo make install
    
To deploy this code to a local CouchDB instance:

    push http://localhost:3000/

## Structure

* __data__ - some old data I needed to migrate, _you can ignore this_
* __deps__ - vendor files used by my code in the lib directory
* __files__ - a dumping ground for my files on the web, _you can ignore this_
* __lib__ - the main application code, see app.js for how it fits together
* __static__ - static attachments: css, js, images etc
* __templates__ - dust templates used by the app


