Change Log
==========

0.1.2 (2015-03-16)
------------------

Doc
~~~

 - APIs relevant to send mails, see :ref:`sendmail_guide`.


New
~~~

- Sections in changelog are now in the order given in ``git-
  changelog.rc`` in the ``section_regexps`` option. [Valentin Lab]

- Added ``body_split_regexp`` option to attempts to format correctly
  body of commit. [Valentin Lab]

- Use a list of tuple instead of a dict for ``section_regexps`` to be
  able to manage order between section on find match. [Valentin Lab]

- New ``unreleased_version_label`` option in ``gitchangelog.rc`` to
  change label of not yet released code. [Valentin Lab]

- Use ``gitchangelog`` section in ``git config`` world appropriately.
  [Valentin Lab]

Changes
~~~~~~~

- Commented code to toggle doctest mode. [Valentin Lab]

- Cosmetic removal of trailing whitespaces. [Valentin Lab]

Fix
~~~

- Doctests were failing on this. [Valentin Lab]

- Bad sorting of tags (alphanumerical). Changed to commit date sort.
  [Valentin Lab]

- Support of empty commit message. [Valentin Lab]

- ``git`` in later versions seems to fail on ``git config <key>`` with
  errlvl 255, that was not supported. [Valentin Lab]

- Removed Traceback when there were no tags at all in the current git
  repository. [Valentin Lab]