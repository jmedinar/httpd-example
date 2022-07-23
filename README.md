# Apache HTTP Server (httpd) S2I Sample Application

This is a very basic simple application repository that can be built and deployed on [OpenShift](https://www.openshift.com) using the [Apache HTTP Server builder image](https://github.com/sclorg/httpd-container).

The application serves a single static html page via httpd.

To build and run the application and deploy on OpenShift, assuming you have a
working `oc` command line environment connected to your cluster already:

`$ oc new-app centos/httpd-24-centos7~https://github.com/sclorg/httpd-ex`

odo create httpd --git https://github.com/openshift/httpd-ex.git
