# OVLS aka Optitrack Vicon LCM Stub

The purpose of this piece of software is to provide a STUB (aka adapter) for LCM
(Lightweight Communication and Masrhalling) that acquire from an Optitrack MOCAP system
and publish vicon_t data.

## Copyright

All parts of NatNetLinux are Copyright 2015,
Roberto Marino - <formica@member.fsf.org>

Optitrack-Vicon-Lcm-Stub (OVLS) is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 3 of the License, or
(at your option) any later version.
    
OVLS is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.
    
You should have received a copy of the GNU General Public License
along with NatNetLinux;if not, write to the Free Software Foundation,
Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301 USA, or visit
http://www.gnu.org/copyleft/gpl.html

### Required

* `cmake` - version 2.8 or later
* `boost` - with `system` and `thread` components
*  `lcm`

## Installation

* Put the cmake files in cmake/Modules inside the cmake-your-version/Modules dir of your system.

* compile it
```
  mkdir build
  cd build
  cmake ..
  make
```

