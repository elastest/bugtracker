[![License badge](https://img.shields.io/badge/license-Apache2-orange.svg)](http://www.apache.org/licenses/LICENSE-2.0)

Copyright © 2017 [ElasTest]. Licensed under [Apache 2.0 License].

ElasTest Bugtracker
==========

Reporting bugs
--------------

Ok, you’ve run into something unexpected. Some kind of weird error that makes
everything crumble. How should you proceed? This document represents the
guidelines for reporting bugs found in [ElasTest], and hosted in the [official
github repository].

If you're new to reporting bugs, you may want to try getting help from the more
experienced contributor. You can also ask for support on how to report in our
[ElasTest Public Mailing list].

We would like all users to please observe these reporting guidelines, as they
will help us all save time, and acquire the clarity needed to diagnose the
problem quickly.

TL;DR
-----

* Be precise: don’t wander around and go straight to the point, describing as
  precisely as possible what’s happening

* Be clear: explain how to reproduce the problem, step by step, so others can
  reproduce the bug

* Be economic: provide the minimum amount of information needed to understand
  what’s happening

* Be clean: report only one problem per issue so we can track individual
  issues

* Be curious: has it been asked before? is it really a bug? Google is your
  friend!

* Be provactive: Check with other versions, speacially with the latest 
  develeopment version. We can't emphasize this enough: it's the
  first thing that we are going to ask

How to report a bug
-------------------

### Is it really a bug?

The first thing before reporting a bug, is to really make sure it is a bug. Many
of the messages from the list are not bugs: coding issues, configuration
problems... In order to make sure there is indeed a bug, you can follow this
checklist:

* Read the documentation: If the answer is in the documentation, the answer
  will be “Read the documentation”... one mail round wasted

* Check with the latest development version. It is possible that a bug in 
  the last release is fixed in development.

* Read the logs, they are normally quite interesting. Sometimes building tools
  are just not configured correctly or others have reported the same error.
  Client logs, server logs, build tool logs… For all of those, Google is your
  friend!

### Ok, it’s a bug. What now?

First of all, don’t panic! There is still a small work to be done before reporting
the bug.

* If it’s an installation issue, don’t touch anything! Normally when this
  happens, we tend to do random things that could only make things worse

* Choose a bug header that fits the problem

  * Bad: “Nothing works. Help!”

  * Good: “ElasTest 0.5-dev is not executing a test”
 
* Provide a good description of the problem, with the minimum relevant amount of
  information to reproduce and diagnose the bug

  * What steps will reproduce the problem?

  * What is the expected output?

  * What happens instead?

  * What are the specific versions of ElasTest components?
  
  * Have you checked the development version?

* If you can provide the test you are trying to execute with ElasTest, please do so. 
  A pointer to a github
  repo is very welcome, as it will put us both in the same path. This doesn’t
  mean that we are going to debug your code

* Provide the logs if they are relevant (i.e. 99% of the time)

For some specific type of bugs, there is some more information that you can provide

* If the bug was recently introduced, finding a regression window can help
  identify the cause of the bug.

### So, how should a bug report look like?

* Summary: How would you describe the bug in less than 60 characters?

* Version: select the earliest Version with what the problem can be reproduced

* OS: On which operating system (OS) did you find it?

* Description: The details of your problem report, including:

	* Overview

	* Build Id

* Steps to Reproduce

* Actual Results

* Expected Results

[ElasTest public mailing list]: https://groups.google.com/forum/#!forum/elastest-users
[GitHub ElasTest bugtracker]: https://github.com/elastest/bugtracker/issues
[GitHub ElasTest Group]: https://github.com/elastest
[ElasTest]: http://elastest.io
[ElasTest Blog]: http://www.kurento.org/blog
[Apache 2.0 License]: http://www.apache.org/licenses/LICENSE-2.0
[official github repository]: https://github.com/elastest/
