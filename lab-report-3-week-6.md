# Lab Report 3 - Week 6

## Streamlining `ssh` Configuration

In this week's report, I go through the process of logging in to the remote connection in a faster and more convenient method. The method of streamling the `ssh` configuration will allow me to interact with the server with a shorter "nickname" compared to the long login username, `cs15lwi22***@ieng6.ucsd.edu`.

## Part 1: Setting up config file

To start, I added a config file into the `.ssh` folder that we added our ssh keys into. In the config file I added the following lines:

```
Host ieng6
    Hostname ieng6.ucsd.edu
    User cs15lwi22*** (use username)
```

