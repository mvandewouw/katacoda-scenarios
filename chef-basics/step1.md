Here we are gonna install chef server

## Task

We want the ubuntu server version **wget ...**

`wget https://packages.chef.io/files/stable/chef-server/12.17.33/ubuntu/16.04/chef-server-core_12.17.33-1_amd64.deb`{{execute}}

No we install this debian package **dpkg -i ...**

`dpkg -i ~/chef-server-core_12.17.33-1_amd64.deb`

After installing we need to configure it **chef-server-ctl ...***

`chef-server-ctl reconfigure`