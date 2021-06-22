# XSeed Cloud
All of the code and configs I used to setup a cloud gaming service.

## Components
- controlServer: manage user accounts and computers joining, leaving, allocation to users
- guest-agent: runs on the guest operating system (Windows), allows for automations that is vital to a seamless UX.
- android-client: gaming client for end user on android.
- flutter_app: gaming client - cross platform (to be built with Flutter)
- vmconfigs: Configs needed to create performant gaming VMs, specifically tested on my server (Dual CPU: Xeon E5 2678 v3, GPU RTX 2070)