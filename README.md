NAME
    Postcop - Defends against Postfix unauthorized mass mailers.

VERSION
    This documentation refers to Postcop version 1.20140123

SYNOPSIS
    postcop

OPTIONS
    Postcop takes an optional configuration file argument. The default
    configuration option is /etc/postcop/postcopd.conf

DESCRIPTION
    Postcop is an daemon that monitors Postfix logs and blocks unauthorized
    mass mailers in a Postfix fashion via postmap and postsuper.

CONFIGURATION
    Postcop's default config file is /etc/postcop/postcopd.conf and is in
    standard INI format. See comments in the default configuration file -
    postcopd.conf - for details.

DEPENDENCIES
    DBM::Deep, Config::Std, Sys::Syslog, Email::Sender::Simple,
    List::MoreUtils

SOURCE CODE
    The source code repository is at
    https://github.com/shawnsustaita/postcop.

BUGS AND LIMITATIONS
    There are no known bugs in this app. Please report problems to Shawn
    Sustaita <shawn.sustaita@gmail.com> Patches are welcome.

AUTHOR
    Shawn Sustaita <shawn.sustaita@gmail.com>

LICENSE AND COPYRIGHT
    Copyright (C) 2014 Shawn Sustaita <shawn.sustaita@gmail.com>. All rights
    reserved.

    This program is free software: you can redistribute it and/or modify it
    under the terms of the GNU Affero General Public License as published by
    the Free Software Foundation, either version 3 of the License, or (at
    your option) any later version.

    This program is distributed in the hope that it will be useful, but
    WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero
    General Public License for more details.

    You should have received a copy of the GNU Affero General Public License
    along with this program. If not, see <http://www.gnu.org/licenses/>.

