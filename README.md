# 20.3
1 
Writable
Writable in an interface in Hadoop and types in Hadoop must implement this interface. Hadoop provides these writable wrappers for almost all Java primitive types and some other types,but sometimes we need to pass custom objects and these custom objects should implement Hadoop's Writable interface.Hadoop MapReduce uses implementations of Writables for interacting with user-provided Mappers and Reducers.

WritableComparable
WritableComparable interface is just a subinterface of the Writable and java.lang.Comparable interfaces. For implementing a WritableComparable we must have compareTo method apart from readFields and write methods
