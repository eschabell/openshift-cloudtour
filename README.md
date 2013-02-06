Cloud Tour mobile app on OpenShift
==================================

This is the kitchensink html5/mboile JBoss Quickstart app.

Running on OpenShift
--------------------

Create an account at http://openshift.redhat.com/

Create a jbossas-7 application

    rhc app create -a cloudtour -t jbossas-7 --from-code git://github.com/eschabell/openshift-cloudtour.git

That's it, you can now checkout your application at:

    http://cloudtour-$namespace.rhcloud.com
