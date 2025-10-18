if you use arch by the way you can download this package from AUR ( yay -S tux-colored )

compilation from source code:

step 1:
you need installed gcc and git package ( Gnu Complier Collection )

$ sudo apt install gcc git - debian-based

$ sudo pacman -S gcc git arch-based

step 2:
download the project repository

$ git clone https://github.com/Nick-cpp/tux

step 3:
compilation


$ cd tux/
$ g++ -std=c++17 "tux.cpp" -o tux
$ sudo install -Dm755 tux "$pkgdir/usr/bin/tux"

step 4:
program launch

$ tux
