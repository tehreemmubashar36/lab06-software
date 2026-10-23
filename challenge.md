# Challenge: Install It Yourself

## 1. Install and run htop

Command: sudo apt install htop
Command: htop

Answer: The htop task was not completed. Therefore, I could not observe CPU usage, memory usage, or running processes.

## 2. Check the available apache2 version

Command: apt show apache2

Answer: Ubuntu offers Apache2 version 2.4.66-2ubuntu2.6. I checked the package information without installing Apache2.

## 3. Count installed packages

Command: apt list --installed | wc -l

Answer: The command returned 734 lines in the installed package list.

## 4. Run Alpine using Docker

Command: sudo docker run --rm alpine echo Hello from Alpine

Output: Hello from Alpine

Answer: Docker successfully ran the Alpine container and printed "Hello from Alpine". The --rm option removes the container after it finishes.

## 5. Docker key and sources file paths

Command: ls -l /etc/apt/keyrings/docker.asc

Answer: Docker's key file is located at /etc/apt/keyrings/docker.asc. The file was verified to exist.

Command: ls -l /etc/apt/sources.list.d/docker.sources

Answer: Docker's sources file is located at /etc/apt/sources.list.d/docker.sources. The file was verified to exist.

## 6. Remove htop and verify

Command: sudo apt remove htop
Command: hash -r
Command: htop

Answer: This task was not completed because htop was not removed and tested. Therefore, I cannot confirm that the command is no longer available.
