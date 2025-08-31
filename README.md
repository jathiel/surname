# The Surname Problem

This simple function is a first attempt to solve the surname problem of generating surnames for the offspring of two individuals while satisfying the following requirements:

* no ancestral information is lost and
* there must be a bounded number of characters in the generated surname.

Using the MD5 hash function, we propose a short and elegant solution. Namely, we hash concatenated (hashed) names.
