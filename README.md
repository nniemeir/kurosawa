# Kurosawa

To compile the module, run the following command:
```
make
```

Once compiled, the module can be loaded using the following command:
```
sudo insmod kurosawa.ko
```
The module can then be unloaded with the following command:
```
sudo rmmod kurosawa
```

This module prints a message to the kernel ring buffer when loaded/unloaded, which can be read with the following command:
```
sudo dmesg
```
