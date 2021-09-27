# Home
## Welcome

Welcome to GL513 Github Pages.

# Information
## About GL
Hello, my name is Gavin, also known as GL, and GL513 in online communitites.<br>
I've been a huge tech geek since I was 5, and I still am, helping others with their projects, such as [KeyMapper](https://play.google.com/store/apps/details?id=io.github.sds100.keymapper&hl=en_US&gl=US) by [sds100](https://github.com/sds100/).<br>
I hope that one day I can develop my own apps, like KeyMapper, or [Shortcut Maker](https://play.google.com/store/apps/details?id=rk.android.app.shortcutmaker&hl=en_US&gl=US), especially since I literally always try to make things better :)<br>
I also have an awesome community of friends, like [Jambler](https://gitlab.com/jambl3r), [Noah](https://github.com/noahtheprogrammer), A.K.A. OKprogrammer, and dreamweaver, [Trollserver](https://www.youtube.com/channel/UCljg1FH1B_ju2D_NfqAYjDw), and alot more people.<br>

Pages will be updated soon. Currently still a WIP...

# cpuminer-in-termux
## Getting Started


Running miners on computers is easy. Not so much on compact devices, like a mobile phone. If you have a high end phone, running a miner overnight might pay off, sparing you a few pennies. <br>

To mine on your android phone, you will need the application [Termux](https://f-droid.org/packages/com.termux), and a wallet address, which you can get by joining the [Raptoreum Discord](https://discord.gg/UpJx6GASCc) or by using the [official wallet appplication](https://github.com/Raptor3um/raptoreum/releases/tag/1.2.15.2) for Windows, Linux, and MacOS, developed by the Core Devs themselves.
After insuring you have a wallet, open Termux and do: <br><br>

`apt-get update && apt-get upgrade -y && apt-get install git -y && git clone https://github.com/GL513/cpuminer-in-termux && mv cpuminer-in-termux/installubuntu.sh ~/ && ls && chmod +x installubuntu.sh && ./installubuntu.sh` <br><br>

This will automatically install [ubuntu in termux](https://github.com/MFDGaming/ubuntu-in-termux). When prompted, type in `n` and press enter. After Ubuntu is done downloading, you will see a window that says "Nano".
Press "END", then navigate using the arrows and delete the part that says `[ENTER YOUR ADDRESS HERE]` and paste your own address into that section.<br><br>

Now, do `chmod +x rtmsetup.sh && ./rtmsetup.sh` and let it run. Afterward, when you see blue text, do "CTRL + c" to exit.

## Using the quick start scripts

When starting Termux, just run `./startubuntu.sh`, and then `./rtmmine.sh`, and you should now be mining to your own address.<br>
Cheers, Raptors!
