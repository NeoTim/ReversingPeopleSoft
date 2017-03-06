I need some sample PeopleSoft HashWithSalt() generated hashes for testing.

...

See PeopleSoft-HashWithSalt-notes.txt file for notes.

From hashcat forum,

PeopleSoft hashes supported by JtR, which are 28-character long Base64 strings,
are likely generated using the PeopleCode Hash() function. PeopleCode also has
a salted hash function, called HashWithSalt(). I do not know the specifics of
the algorithm which is used by this function, but it has the same format as
Hash(), except it begins with {1}.

{1}f+B0qgfNYGoedmHr2doZ+rN2Kso= (this is not a real hash, but shares the same
format as HashWithSalt)
