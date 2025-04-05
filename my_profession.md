---
title: About my profession
description: A humanity
theme: minima  # You can change this to other GitHub Pages supported themes
---

Our company's products are based on Qualcomm's Snapdragon chip.

Mobile phones, computers, and other devices sometimes crash.
And my jobs is to find out the cause of the crash.
Common crash issues include:
- hungtask(some task has not been scheduled for a long time.)
- deadlock(a typical case is task t1 holds spinlock l1, and it is trying to acquire another spinlock l2 which is currently held by task t2. Meanwhile, t2 is trying to acquire l1, leading a circular dependency.)
- Address exception(including null pointer dereferencing and page faults. This issue occurs when the CPU attempts to access an unavailable address that does not belong to the current task.)

As the system consists of multiple modules, in addtion to identifying the cause of the crash, I also need to determine which module is responsible for it.