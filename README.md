HDBC
====

Welcome to HDBC, Haskell Database Connectivity.

HDBC is modeled loosely on Perl's DBI interface, though it has also
been influenced by Python's DB-API v2, JDBC in Java, and HSQL in
Haskell.

Please see the HDBC [wiki](https://github.com/hdbc/hdbc/wiki) for an
introduction to HDBC and its various features.

Installation
------------

You'll need either GHC 6.4.1 or above, or Hugs 2005xx or above.

The steps to install are:

    ghc --make -o setup Setup.lhs
    ./setup configure
    ./setup build
    sudo ./setup install

If you're on Windows, you can omit the leading "./".

Usage
-----

To use with hugs, you'll want to use hugs -98.

To use with GHC, you'll want to use -package HDBC in your programs.
Or, with Cabal, use Build-Depends: HDBC.
