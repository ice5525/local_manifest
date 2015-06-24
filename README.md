# local_manifest
This is local_manifest.xml for Euphoria OS w/ 3.4.0 CAF Kernel for OnePlus One (bacon)

CAF features:


ROM features:

Vanilla CAF LA.BF.1.1.1_rb1.24 display HAL (improved display performance)

Vanilla CAF LA.BF.1.1.1_rb1.24 media HAL (improved video performance)

Vanilla CAF LA.BF.1.1.1_rb1.24 audio HAL (improved audio performance)

OxygenOS camera libraries (improved camera performance)

No 4K video recording (due to OxygenOS camera libraries; see why I did this in the FAQ)

Disabled Qualcomm performance daemon (CPU boosting is now handled completely by the driver I wrote)

2 CPU cores are not forced online all the time (saves power this way)

Many other misc. optimizations


Kernel features:

Based off latest CAF LA.BF.1.1.1_rb1.24 kernel source from Qualcomm

Most similar to Oxygen kernel (but there are many big differences in major Qualcomm driver subsystems)

Almost 100% pure CAF (very clean, shouldn't be any crazy stability or performance issues)

Removed lots of excessive debugging

Latest CAF LA.BF.1.1.1_rb1.24 prima (WiFi) drivers

Rewrote half of the Synaptics touchscreen driver (over 2500 lines of code modified; your touchscreen might work better)


Newest available Synaptics touchscreen firmware (the per-panel firmware, no battery drain: http://review.cyanogenmod.org/#/c/99607/)

Dynamic CPU input boost driver I wrote myself (makes the phone feel smooooth)

CPU underclocked to 1958MHz by default\

Improved notification LED color (white doesn't have a blue tint)

No BS patches or features or compiler optimizations

Many other misc. optimizations
