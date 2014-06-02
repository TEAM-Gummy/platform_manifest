TEAM Gummy
==============

Gummy AOSP 4.4.2

Sync and Build:
---------------

In terminal enter:

    {x}   repo init -u git://github.com/TEAM-Gummy/platform_manifest.git -b kk4.4
    {x}   repo sync
    {x}   prebuilts/misc/linux-x86/ccache/ccache -M 50G
    {x}   . build/envsetup.sh && brunch "device" -j8

Devices Currently Supported:
----------------------------

This list is always subject to change:

    {x}   Asus Nexus 7 2012
    {x}   Asus Nexus 7 2013
    {x}   HTC One (All Variants besides Sprint)
    {x}   LG G2 ( All Variants besides Sprint)
    {x}   LG Nexus 4
    {x}   LG Nexus 5
    {x}   LG Optimus G Pro
    {x}   Motorola Droid 4
    {x}   Motorola Droid Bionic
    {x}   Motorola Droid Razr
    {x}   Motorola Droid Razr HD
    {x}   Motorola Droid Razr M
    {x}   Oppo Find7a (All Variants)
    {x}   Samsung Galaxy Nexus (Toro and Maguro)
    {x}   Samsung Galaxy Note 2 (All Variants)
    {x}   Samsung Galaxy Note 3 (T-Mobile)
    {x}   Samsung Galaxy S3 (All Variants)
    {x}   Samsung Galaxy S4 (All Variants)
