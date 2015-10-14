# custom-libvirt.xml

In order to use a custom libvirt.xml, it's necessary to change the file:

`/usr/lib/python2.7/dist-packages/nova/virt/libvirt/driver.py`

and restart the `nova-compute` service.

The version provided is for the version `1:2014.1.5-0ubuntu1.3` of `python-nova` package.

