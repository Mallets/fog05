# Copyright (c) 2014,2018 ADLINK Technology Inc.
#
# See the NOTICE file(s) distributed with this work for additional
# information regarding copyright ownership.
#
# This program and the accompanying materials are made available under the
# terms of the Eclipse Public License 2.0 which is available at
# http://www.eclipse.org/legal/epl-2.0, or the Apache License, Version 2.0
# which is available at https://www.apache.org/licenses/LICENSE-2.0.
#
# SPDX-License-Identifier: EPL-2.0 OR Apache-2.0
#
# Contributors: Gabriele Baldoni, ADLINK Technology Inc. - Windows Plugin

Windows os plugin

This plugin allow fog05 to run on top of windows

supported operation:
- execute command
- check that file exists
- save on file
- read from file
- get hw information (cp,ram,network,disks)
- get uuid from motherboard
- get hostname
- send signal
- check if a pid exists


todo:

- get detailed i/o informations
- get hw accelerators informations
- get pid from process name
- get monitoring information about network
- get gps information about node
- install packages
- remove packages

---


python dependencies:

- psutil
- netifaces

-- 

config dependencies:

- user should be able to use sudo without password asking (`echo "username  ALL=(ALL) NOPASSWD: ALL"  >> /etc/sudoers`)

