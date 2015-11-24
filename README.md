
# snsrv

__attempt to create a [Simplenote](http://simplenote.com/) server clone (at least the api part)__

## features

- aims to be 100% compatible with the simplenote api (this means you should be able to point your simplenote client to the address of this server and it will work out of the box)
- multiuser, secure, etc...
- scalable with mongodb, and flask structure

## dependencies 

The following software and libraries are used:

- python3
- mongodb
- python-pymongo
- python-flask
- python-urllib
- python-bcrypt

## TODO

- sanitize data on update and create
- more testing!
- find more info on api to fix any potential issues (be more compatible)

## running

Currently tested like this:

- clone the repository
- edit config.py to your liking
- `$ python app.py` for the development server 

## contributing

At the moment the server needs to be thoroughly tested for compatibility, stability, and security, so contributions of any kind are welcome!
Feel free to submit a pull request or raise an issue. :)


## License

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.


Copyright © 2015 Samuel Walladge
