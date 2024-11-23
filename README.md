# I'm not the original developer

And as such I have no idea how to fix the issues you're facing with the application itself. So please direct your questions to the OG
devs here: [wireguard-apple](https://github.com/WireGuard/wireguard-apple). And no, I have no idea why they've disabled the ability to create issues in their repo.

# Why does this repo exist?

The MacOS version of the official Wireguard GUI app is only available to download from [App Store](https://apps.apple.com/us/app/wireguard/id1441195209). That requires sign-in into the Apple account, which some people don't have or intentionally don't want to use due to privacy concerns. 

I haven't found any other places on the internet where you could get that applications other than the Apple store. Not in the official repo of [wireguard-apple](https://github.com/WireGuard/wireguard-apple), not on the [official website](https://www.wireguard.com/install/). 

But the good thing is Mac applications are sort of like Linux's Appimage apps. They are self contained and can simply be copied from one machine to another. So I took the blow, signed into the Apple store, downloaded the application and re-uploaded it here. So now you can continue avoiding the Apple ecosystem.

This repo also has an older version [v1.0.15](https://github.com/vaardan/wireguard-macos-app/releases/tag/v1.0.15) that is intended to be used by MacOS version 10.14 to 12.0. You won't be able to get that version on the App Store, because Apple doesn't let users download previous versions of the software.


# Security

The uploaded application files are unchanged and retain their original crypto signature. Here's the VirusTotal scan reports:
- v1.0.16 [report](https://www.virustotal.com/gui/file/df84eab7d5b991164d508c1a4c8596d428a4cf6a20cc201716adc0cf0f6bed75/details)
- v1.0.15 [report](https://www.virustotal.com/gui/file/d31ea7a0441c695db234e4684901acbc8126c05b56e8e19d7ffa4a0305322066/details)

Still, I encourage you not to download random apps from the Net without re-checking that they're not a blatantly obvious virus.

# Installation

Firstly, download the application from the "Releases" section:
- If you have the OS version 12.0+, get [v1.0.16](https://github.com/vaardan/wireguard-macos-app/releases/tag/v1.0.16)
- If you have an older version (10.14 to 12.0), get [v1.0.15](https://github.com/vaardan/wireguard-macos-app/releases/tag/v1.0.15)

After the download, extract the application, and put it into global or local `Applications` directory on your system. 
