# DevOps Internship – Task 10
## Docker Volumes & Networking (WSL)

## Objective
To understand Docker volumes for data persistence and Docker networking for container communication using WSL.

---

## Tools Used
- Docker Desktop
- WSL (Ubuntu)
- Docker CLI

---

## Docker Volumes
- Created a Docker volume using CLI
- Attached volume to a container
- Stored data inside the volume
- Deleted the container
- Recreated container and verified data persistence

Result: Data was not lost after container deletion.

---

## Docker Networking
- Created a custom Docker bridge network
- Connected multiple containers to the same network
- Installed ping inside container
- Verified container-to-container communication using ping

Result: Containers successfully communicated using container names.

---

## Conclusion
This task helped me understand how Docker manages persistent data using volumes and enables communication between containers using networks.
