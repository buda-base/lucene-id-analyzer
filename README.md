# Lucene analyzer for identifiers

This is a very small analyzer aimed at easing the search of identifier values. The main features are:
- lowercasing
- removing padded 0: `T0001` becomes `T1`
- removing everything but alphanumerical characters plus dash (`-`)
- if the id can be interpreted as an isbn, normalize it