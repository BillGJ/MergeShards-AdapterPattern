# Merge Shards - Exercise: Adapter Pattern

This is a simple exercise where the `Adapter Pattern` is used to simplify that code 
and manage the opening and closing of all the shard files.

## Compiling and Running 

    javac -cp . MergeShards.java
    java -cp . MergeShards shards/ sorted.txt