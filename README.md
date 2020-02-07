# _¡Railz!_

#### _This is an application that creates, stores, rates & reviews user created skate spot data_

#### By _**Josh Forman, Pete Wells, Dylan Manly & Nate Powers**_

## Description

_This application stores data on skate spots. It allows the user to view, create, read & update the database_

_https://github.com/JPForman/railz_demo.git_

##Specs

* _The application allows the user to locate, create, rate, review & update skate spots anywhere in the world_



## Setup/Installation Requirements

* _Clone repository from git hub_

* _Email one of the authors for the master.key file and security permissions_

* _delete config/credentials.yml_

* _delete Gemlock_

* _comment out rails version in Gemfile_

* _insert master key into config/master.key file_

* _$ bundle install_

* _$ EDITOR=“atom —wait” rails credentials:edit_

* _edit credentials with secret_key_base: # given by admin, google_maps_api_key: key you must obtain through your google api account,  and weather_api_key: key you must obtain through weather.com api_

* _From terminal run "rake db:setup"_

* _$ rake db:drop_

* _$ rake db:create_

* _$ rake db:migrate_

* _$ rake db:seed_

* _$ rails s_

* _Open your web browser to Localhost:3000_

## Known Bugs

_Needs styling_

_Sometimes quirky image links_

## Support and contact details

_Any questions, comments or contributions please contact Dylan Manly (dylan.manley@gmail.com ), Nate Powers (Russellsproutz@Gmail.com), Josh Forman (cyborgforman@gmail.com), Pete Wells (petethebeatwells@gmail.com)_

## Technologies Used

_Ruby, Rails, Bcrypt, ActiveStorage_

### License

*The MIT License


Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.*

Copyright (c) 2020 **_Pete Wells, Nate Powers, Josh Forman, Dylan Manly_**
