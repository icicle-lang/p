p
=
[![Build Status](https://api.travis-ci.com/icicle-lang/p.svg?branch=master)](https://travis-ci.com/icicle-lang/p)

```
The Icicle Language Prelude. Short and sweet.
```

General rules.

 - Safety first.
 - Consistency of functionality.
 - Attempt at completeness of functionality across core structures.

Guidance - "Should it go in `p`"

 - Is something that is very general & useful, with an obvious semantic and can be implemented from `base` - YES.
 - If it is unsafe - NO.
 - Is there a more general version - NO.
 - Is it something available in base in only _some_ GHC versions - YES.
 - It has a lot of dependencies - Probably Not - Maybe case for splitting into p-*.
 - It introduces name clashes - Probably Not - Consider a standalone module designed to be import qualified in `P`, i.e. `P.Text as T`.
