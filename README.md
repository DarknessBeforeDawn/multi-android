
#Multi-Android


Double Android system solutions：
================================

To enhance the security and customizability of Android system, a method based on the container technique on the Android system is proposed through analyzing the current virtualization technology. By sharing a Linux kernel, it can run multiple Android systems on one device simultaneously. 

First of all, we create multiple isolated operation space in the Linux kernel by using container and virtualization technology. we also implement the display device, Binder driver GPU WIFI and SIM virtualization for running an Android subsystem independently in each separated space, in order to achieve multiplexing equipment.

We also studied and implemented quickly switch technology between Android subsystem, it allows for fast switching within 1 second, diverse switching mode, which can be switched by the program can also be switched by physical buttons.

Due to each container isolates from each other, this approach can effectively protect security of user’s data. Even if there is a running fault or malicious attacks in one of the Android subsystems, the other subsystems can still working correctly. So it can improve the security for whole system. And, the Applications and functions of each subsystem can be particularly customized to meet different requirements of users.


Statement:
==========

(C) Copyright 2015  Xia Yang

Design by University of Electronic Science and Technology of China of Embedded Real Time Computing Laboratory.

Contact Info:xyang@uestc.edu.cn

See file License to project for more details. (http://www.gnu.org/licenses/gpl-2.0.html)

See file Video Demo: Double Android operating system of video.


Version information:
====================

Platform: LG nexus 4

Kernel: 3.4

Android: Android 4.3


Video Show：
===========

Video：http://v.youku.com/v_show/id_XMTMwMzUyMTgyOA==.html?firsttime=0&from=y1.4-2

Video File: https://github.com/multi-android/multi-android/blob/master/Video%20Demo/Multi-android.mp4



