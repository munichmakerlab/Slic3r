# Building a .deb package

1. Build slic3r the regular way, see the instructions in the main README for that
2. Copy "slic3r-gui" from build/src into debbuild/slic3r-ME_x.x.x/usr/local/etc/bin/
3. Copy the whole resources folder from project root to debbuild/slic3r-ME_x.x.x/usr/local/etc/
4. cd into debbuild and run dpkg --build slic3r-Me_x.x.x
