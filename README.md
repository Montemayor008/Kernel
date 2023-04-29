# Kernel
Actividad M3.1: Linux "Kernel Modules"

# Change to Directory #
cd Desktop/Kernel

# Install Kernel #
sudo insmod charDev_KernelModule

# Test Kernel #
gcc gpioTest.c -o run
./run

# Uninstall Kernel #
sudo rmmod charDev_KernelModule







