# alpha-os-arc-theme

As of this writing (November 2017) the original maintainer of the Arc GTK theme has been completely MIA for several months.  

Though new maintainers have forked the original repo to fix the backlog of issues, the larger problem is that the GPG key used to sign the OBS repo for Ubuntu 16.04 has expired.  That key has been insecure since June of this year, which forces 16.04 users to either compile Arc for themselves, or disable apt's key checking.  Neither of which are ideal.

This repo simply mirrors the stable releases made by @NicoHood, but does so with a currently maintained reprepro repository.  The Arc deb and its packaging files are shared here for auditing, and for those who don't want to enable the Alpha repository (here are the instructions for those who do: https://alpha.store/forums/topic/alpha-software-repo-now-available/).
