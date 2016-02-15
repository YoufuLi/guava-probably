Guava-Probably: TODO List 
=======================================================

=1.0

==CI
* commit/push to release SNAPSHOT, major, minor, patch :: maven central && javadocs
* simplify travis scripts

== Features
* MultiSet interface operations (count, set counts)
* CuckooFilter impl increase max capacity (separate even/odd tables? array of tables?)
* Primitive interface API (to avoid object alloc)
* Direct hash fn invocation (to avoid object alloc)
* extract filter dimensions calculation