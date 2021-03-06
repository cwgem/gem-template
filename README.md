## Introduction ##

This project was created in order to ease common tasks around EC2 instances while helping provide a learning experience for working with the AWS Ruby SDK. The following is a task list that will be updated as tasks are completed to showcase the functionality:

* Customization of instance information output through templates

Currently this is a work in progress, so the interface will be constantly changing. In other words I may rename options, remove options, and in essence break your expectations until I'm satisfied with the architecture. You have been warned!

## LICENSE ##

This software is released under the MIT License.

## Requirements ##

Ruby 1.9.3 is used for development of this project.

While providing an interace to the [AWS Ruby SDK](http://aws.amazon.com/sdkforruby/), it's not a bad idea to take a look at the underlying API to get an idea of how things work.

### External Deps ###

* RSpec 2.x series for running the specs
* Gli for command line functionality
* yard for documentation

### Standard Libary Deps ###


## Installation ##

For Rakefile building, you'll need to install at minimum the following for tasks:

    gem install rake yard rspec

The default rake task is install, so for a simple installation:

    rake
    
You can also chose to build the gem manually if you want:

    rake build

## Code Documentation ##

The main API is documented with yardoc, and can be built with a rake task:

    rake yard

from here you can use the yard server to browse the individual gem docs from the source root:

    yard server

or optionally you can run the main yard gem documentation server:

    yard server --gems
    
and docs can be viewed from `http://localhost:8808/`
    
## Tests ##

Fill once tests are written

## Example Usage ##

Fill once cli interface is working

## Project Contact ##

This project is made by Chris White( @cwgem | cwprogram@live.com ). 
