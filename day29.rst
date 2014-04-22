===============================
Day 29: Tuesday, April 22, 2014
===============================

0. Read `How the Bitcoin protocol actually works <http://www.michaelnielsen.org/ddi/how-the-bitcoin-protocol-actually-works/>`__.

   Additional reading: `The future of the blockchain <http://www.businessinsider.com/the-future-of-the-blockchain-2014-4>`__; `Bitcoin tutorial <https://docs.google.com/presentation/d/1PDv5emVtrkTQgUg7yjQUNEeK972Bh40nT0BI0kLSWzc/edit#slide=id.p>`__

1. Quiz.

.. https://docs.google.com/forms/d/11iF_g0ALq0P8VMV2NkOkX8-LjvPgYfGOjNnEmQKHoy8/viewform

2. Bitcoin discussion points

   - tries to work well in an imperfect world: attackers, latency
   - notice how synchronization is a hard problem?
   - asymmetry in computing: used for validation, verification
   - random algorithms used to break ties (blockchain): look up `skip lists <http://en.wikipedia.org/wiki/Skip_list>`__, my `PyCon talk last year <https://us.pycon.org/2013/schedule/presentation/53/>`__ `(video) <https://www.youtube.com/watch?v=jKBwGlYb13w>`__

   `Is Bitcoin a plot by the NSA? <http://realcurrencies.wordpress.com/2013/06/21/is-the-national-security-agency-behind-bitcoin/>`__

   My theory: is Bitcoin about testing the reliability of certain cryptographic
   operations?

3. Contention, locking, and ACID.

   See: `Atomicity, Consistency, Isolation, Durability (ACID) <http://en.wikipedia.org/wiki/ACID>`__.  Note, locking is *expensive*.

   a. read `Transactions <http://www.postgresql.org/docs/8.3/static/tutorial-transactions.html>`__, through the 5th paragraph ("Another important property...")

   b. read `Transaction isolation <http://www.postgresql.org/docs/9.1/static/transaction-iso.html>`__, up to 13.2.1 (through "To set the transaction isolation level...")

   c. for each transaction isolation level, list out one or more
      applications for which those guarantees are either probably or
      certainly sufficient for reliable performance (think worst case
      for "certainly"!)

      In table-sized groups of 4-8, please list out 1 or more
      applications for each isolation level, annotated as "probably"
      or "certainly" sufficient.  `(List them out here) <https://docs.google.com/document/d/1asH8g_iD0kH_Axtg_5oU1tKGwBFA6mPNirROYqc9kEQ/edit#>`__

4. SIRS forms.

.. stickies
.. sirs forms
.. pencils? from cse?

.. diagram: serial locks; concurrent transaction locks; etc; connect to
      version control!
