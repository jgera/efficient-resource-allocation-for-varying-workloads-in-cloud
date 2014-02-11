efficient-resource-allocation-for-varying-workloads-in-cloud
============================================================

Efficient Resource allocation can by achieved by avoiding overloading of Physical Machines (PM). Once the overload is detected one of the Virtual Machines(VM) is migrated from the current PM to other PM (the target is chosen in such a way that the load is distributed evenly among the PM’s) . Hence the first step in overload avoidance is predicting the future load. We proposed a Feed forward Neural network for predicting the future load. This is achieved by the use of Back propagation algorithm. We predict the future load based on the window of past load values and then migrate if required
