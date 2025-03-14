# Linux Administration & Automation Challenge

## Overview
This mini-project challenges you to demonstrate your skills in Linux administration, Git, Bash scripting, and basic networking. You'll create a set of automation tools to manage a small Linux server environment, track changes with Git, and monitor system performance.

## Project Requirements

### Part 1: Git Repository Setup
1. Create a Git repository with the following structure:
   - `scripts/` - Contains your automation scripts
   - `config/` - Contains configuration files
   - `monitoring/` - Contains monitoring scripts
   - `documentation/` - Contains your documentation

2. Implement Git best practices:
   - Create a proper `.gitignore` file
   - Use meaningful commit messages
   - Create a pre-commit hook that performs syntax checking on your scripts
   - Create a branch for each feature/script and merge them properly

### Part 2: Linux Server Administration
1. Set up at least two Linux virtual machines:
   - Create a user and configure SSH for the user with key-based authentication
   - One as your admin server
   - One as your target server to be managed

2. For each server, demonstrate:
   - User management (create users with appropriate permissions)
   - Package management (install and configure necessary packages)
   - Service management (configure and enable system services)
   - File system management (partition, mount, and manage storage)
   - Process management (monitor and control processes)

### Part 3: Networking Configuration
1. Configure basic networking between your servers:
   - Set up static IP addressing
   - Configure SSH with key-based authentication
   - Implement basic firewall rules using iptables or ufw
   - Set up a private network between your servers
   - Configure and test DNS resolution

2. Create a network documentation file that includes:
   - Network topology diagram
   - IP addressing scheme
   - Firewall rule explanations
   - Service ports in use

### Part 4: Bash Automation Scripts
Create Bash scripts that accomplish the following:

1. `system_inventory.sh`:
   - Collects hardware information (CPU, memory, disk)
   - Lists installed packages
   - Identifies running services
   - Outputs a formatted report

2. `user_manager.sh`:
   - Creates, modifies, and removes users
   - Sets up SSH keys for users
   - Implements password policies
   - Manages user groups

3. `system_hardening.sh`:
   - Configures SSH securely
   - Disables unnecessary services
   - Updates system packages
   - Implements basic security policies

4. `network_monitor.sh`:
   - Monitors network connections
   - Logs unusual network activity
   - Tests connectivity between servers
   - Reports bandwidth usage

5. `backup_manager.sh`:
   - Creates timestamped backups of important directories
   - Implements rotation policy (keeps X most recent backups)
   - Verifies backup integrity
   - Logs backup operations

### Part 5: Cron Jobs & Logging
1. Set up appropriate cron jobs to:
   - Run system inventory weekly
   - Run network monitoring hourly
   - Run backups daily
   - Check for system updates daily

2. Implement proper logging:
   - Centralized logging for all scripts
   - Log rotation configuration
   - Timestamps and appropriate log levels
   - Email notifications for critical events

### Part 6: Documentation & Reporting
1. Create a comprehensive README.md in your Git repository
2. Document each script with proper comments and usage instructions
3. Create a script that generates a daily report including:
   - System uptime
   - Disk usage
   - Memory usage
   - Failed login attempts
   - Package update status

## Technical Challenges

Complete at least three of the following advanced challenges:

1. **Security Auditing**: Create a script that performs basic security auditing and reports vulnerabilities.

2. **Performance Monitoring**: Set up performance monitoring that tracks CPU, memory, and disk usage over time and generates reports.

3. **Log Analysis**: Create a script that analyzes system logs and identifies potential security issues.

4. **Automated Testing**: Implement a framework to test your scripts and ensure they work as expected.

5. **Self-healing**: Create a script that can detect and fix common system issues automatically.

6. **Version Control Automation**: Create a script that automates Git operations for your team workflow.

## Evaluation Criteria

Your solution will be evaluated based on:

1. **Linux Administration**: How well you've configured and managed the Linux systems.
2. **Git Usage**: How effectively you've used Git for version control.
3. **Bash Scripting**: Quality, efficiency, and robustness of your scripts.
4. **Networking**: Proper configuration and security of network services.
5. **Automation**: Level of automation achieved across the system.
6. **Error Handling**: How your scripts handle and recover from errors.
7. **Documentation**: Clarity and completeness of your documentation.
8. **Security**: Implementation of security best practices.

## Technical Questions to Answer

During your demonstration, be prepared to answer the following questions:

1. Explain your Git branching strategy and how you managed changes across multiple scripts.

2. What Linux kernel parameters did you tune and why?

3. How do your scripts handle unexpected errors or edge cases?

4. Explain the security measures you implemented on your servers.

5. How would you scale your solution to manage dozens of servers?

6. Demonstrate how your backup and recovery process works.

7. Explain how you tested your scripts to ensure they work correctly.

8. What was the most challenging Linux administration task you encountered?

9. How did you ensure that your networking configuration is secure?

10. Which Bash scripting techniques did you find most useful for this project?

## Submission Guidelines

1. Push your complete solution to your Git repository
2. Provide access to your Linux servers for evaluation
3. Prepare a 30-minute demonstration of your system
4. Be ready to deliberately break something and fix it during the demonstration

**Note:** You may use any open-source tools you find appropriate, but you must understand how they work and be able to explain your choices.
