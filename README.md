Name: ......
NIM : ......
# Instructions
1. Edit your identity above
2. Rename config-6.13.7-x64v3-xanmod1 --> .config, copy the .config to the .config of your linux source
3. In case your cpu was in production before 2020. YOu are allowed to use minimal config
4. Execute time make -j$(nproc --ignore=2) > default\_kernel\_build\_time.txt
5. Execute time make -j$(nproc --ignore=2) > modules\_build\_time.txt
6. Execute sudo make install, then reboot to boot loader. Capture the boot loader screenshot with your phone, store as bootloader.jpg
7. While in the linux source, git clone https://github.com/FlorentRevest/linux-kernel-vscode/. 
8. Run .vscode/tasks.sh update
9. Open .vscore/tasks.sh, state how many commands are available. Store the identified commands as tasks\_command.txt
10. Complete before due time
