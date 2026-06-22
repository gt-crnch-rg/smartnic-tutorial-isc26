# Hands-On Information

This README covers the hands-on access and examples available for this tutorial. 

## Hands-on Access

Hands-on access changes for tutorials due to node reservations and security measures needed for public facing nodes. For this reason, we've put the latest hands-on in this [Google Doc](https://docs.google.com/document/d/1yV0nXo3pqqT7qdXVM6LqnOBwPGNvaoQ-dXFztc6gPts/edit?usp=sharing), which will remain active for a week after the tutorial. If you are interested in longer-term access, please reach out to the event organizers!

### Available Testbeds

- FABRIC testbed - used for ODOS examples
- USC Netlab - used for DOCA/DPL/P4 examples

## Hands-on Examples

### DOCA/DPL

These examples are geared towards running on the UCS Netlab infrastructure. You should be able to follow along with the provided folder on the FABRIC testbed, `USC_DOCA_Labs`, or you can work through running these examples on the Netlab Testbed. Check out the PDF in each folder and follow the instructions to run through the lab. 

### ODOS (Demo, Beta Setup)

The ODOS OpenMP and MPI Offload examples are enabled on FABRIC using a Docker container installation. This is very "beta" and is under test for this particular tutorial, so it may still have some bugs.

To run the ODOS host container, please run the following, which runs a pre-pulled container and "bind mounts" the JupyterHub home directory at /opt/user. 

```
## We have already run this first command for you!
## docker pull dfjrt321/odos-smartnic:odos-mpi-host-v1

docker run --rm -it --mount type=bind,src=/home/user,dst=/opt/user/ dfjrt321/odos-smartnic:odos-mpi-host-v1
```

### DPA Examples

We will talk about a few DPA examples using MPI with Data Path Accelerators, but these codes are not currently released for hands-on exercises.