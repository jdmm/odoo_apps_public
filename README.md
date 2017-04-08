Account Standard report
=======================
This module can generate a accounting report in PDF and Excel, with the new implementation of the accounting from Odoo V9.
In this new implementation there are not openning entries, it is a continously  accounting. And in some case in repport
the matching have no sense, because some moves are matched with the next year (or after the end date).

Features
========
Report
------
* Export in PDF
* Export Excel Files (xlsx), build to use pivot table
* General Ledger
* Partner Ledger
* Journal Ledger
* Open Ledger

Initial balance
---------------
* Initial Balance with detail on unmatching moves from payable/receivable account
* With ou without reduced balance (credit or debit egual zero) on payable/receivable account
* Use the fiscal date of company to generate the initial balance

Matching Number
---------------
* Management of macthing after the end date. (replace by * if one move is dated after the end date)
* The partner ledger unreconciled don't change over time, because the unreconciled entries stay unreconciled even if there are reconcilied with an entrie after the end date.

Installation
============
Just install the module

Usage
=====
* Go to Accounting/Report/Standard
* Choose your options

Known issues / Roadmap
======================
If some options are selected this can generate a report that does not make sense.

Bug Tracker
===========

Contributors
------------
* Florent de Labarre

Maintainer
----------
