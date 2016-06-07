---
layout: post
title:  "The K-Mer Counter"
date:   2016-06-06 20:00:00 -0500
---

Part of my shenanigans since January involved developing an application that counts K-Mers, which are specific sequences of DNA base pairs. I did this for a... programming challenge. I'd rather avoid the specific story of this challenge, however a good friend encouraged me to post my work on GitHub. Since, after all, I'm supposed to be all about this biocomputing stuff. Right?

Not going to lie, I went template crazy with this application. I've been on a template kick at work and it spilled over into this application. It definitely made a lot of sense for the basic classes (merizer, counters) that dealt with variable precisions and data representations, however the larger level integration could have done with out it. Say, maybe having these template classes derive from a non template base class.

The first version of this ran without a database and was much faster. I was later challenged to allow the application to support massive datasets on a small memory footprint. Some multithreading might help with hiding database access times, however I do feel that this additional constraint helped me gain an appreciation for how data intensive these DNA applications are.

Here it is:
[Source](https://github.com/logik1286/kmerCounter)
