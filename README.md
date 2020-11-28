# hdrs

hdrs stands for header-search.
It can be used to recursively list all included headers starting from the input header path, or try to
check whether such header includes the target header or not.

# General

It accepts setting up search list of include header paths in which it will be basing the search on.
It will do BFS to list all included header for a header file in a higher level first before going
deeper.

# License

Wasin, MIT
