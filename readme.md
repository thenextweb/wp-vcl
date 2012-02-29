Default Wordpress VCL
=====================

Makes Varnish 3 play nice with wordpress 


Features
--------

* normalizes url for higher hit rate
* supports cookies for logged in users
* servers cached pages for non-loggedin users
* servers static content

* restarts when backend is slow
* can handle multiple back-end machines
* direct traffic to main machine for wp-admin and static content

