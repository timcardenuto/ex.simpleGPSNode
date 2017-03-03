## ex.simpleGPSNode ##

Example Redhawk Node that shows how to use the ex.simpleGPS Device. In this case we're using the Redhawk messaging method to broadcast GPS data over an Event Channel. You can test this by launching the Node in a Redhawk Domain and using the eventviewer command line utility. You can do all of that through a command line like this:

```
nodeBooter -D &

nodeBooter -d $SDRROOT/dev/nodes/ex/simpleGPSNode/DeviceManager.dcd.xml &

eventviewer REDHAWK_DEV GlobalGPS
```
