## SetUp drivers
- Verify that cards are installed correctly and are recognized by the system
```lspci | grep -i mellanox
```
- Verify that the infiniband drivers are present
```lsmod | grep -i ib_
```

- Verify that the OFED software was installed correctly
Need to make sure the version is correct. Use the driver in /home/infiniband/ on dgx or the driver in /tmp/ on deepstorage.
```
modinfo mlx5_core | grep -i version | head -1
```
step to this one
sudo service openibd restart
