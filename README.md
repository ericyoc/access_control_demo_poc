# Access Control Concepts

This project demonstrates six key access control concepts using Python. It aims to provide a clear understanding of these fundamental cybersecurity principles through code implementation and graphical representation.

## Motivating Article
Yocam, E., Alomari, A., Gawanmeh, A., Mansoor, W. (2023). A privacy-preserving system design for digital presence protection. Computers, Materials & Continua, 75(2), 3091-3110. https://doi.org/10.32604/cmc.2023.032826
https://www.techscience.com/cmc/v75n2/52026

## Overview

This Python script implements and visualizes the following access control concepts:

1. Access Control Matrix
2. Linux Access Control
3. Principle of Least Privilege
4. Sandboxing
5. Role-Based Access Control (RBAC)
6. Attribute-Based Access Control (ABAC)

For each concept, the script provides a textual demonstration and a graphical visualization to enhance understanding.

## Results

### Access Control Table
![](https://github.com/ericyoc/access_control_demo_poc/blob/main/Access_Control_Table.jpg)

### 1. Access Control Matrix
![](https://github.com/ericyoc/access_control_demo_poc/blob/main/access_control_matrix.png)

### 2. Linux Access Control
![](https://github.com/ericyoc/access_control_demo_poc/blob/main/linux_access_control.png)

### 3. Principle of Least Privilege
![](https://github.com/ericyoc/access_control_demo_poc/blob/main/principle_of_least_privilege.png)

### 4. Sandboxing
![](https://github.com/ericyoc/access_control_demo_poc/blob/main/sandboxing.png)

### 5. RRAC
![](https://github.com/ericyoc/access_control_demo_poc/blob/main/rbac.png)

### 6. ABAC
![](https://github.com/ericyoc/access_control_demo_poc/blob/main/abac.png)

## Concepts Covered

1. **Access Control Matrix**: Defines access rights for subjects (users) to objects (files).
2. **Linux Access Control**: Uses file permissions to control read/write/execute access.
3. **Principle of Least Privilege**: Users are given minimum levels of access needed for their tasks.
4. **Sandboxing**: Restricts the environment in which certain code can run.
5. **Role-Based Access Control (RBAC)**: Access decisions are based on roles that users have.
6. **Attribute-Based Access Control (ABAC)**: Access decisions based on attributes of users, resources, and environment.


## Concepts Explained

### 1. Access Control Matrix

- **Principle**: Separation of privilege
- **Explanation**: A table that defines the access rights of each subject (user) to each object (file) in the system.

### 2. Linux Access Control

- **Principle**: Simplicity and uniformity
- **Explanation**: Uses a combination of user, group, and others permissions (read, write, execute) to control access to files and directories.

### 3. Principle of Least Privilege

- **Principle**: Minimize potential damage
- **Explanation**: Users are given the minimum levels of access – or permissions – needed to perform their job functions.

### 4. Sandboxing

- **Principle**: Isolation and containment
- **Explanation**: A security mechanism for separating running programs, usually in an effort to mitigate system failures or software vulnerabilities from spreading.

### 5. Role-Based Access Control (RBAC)

- **Principle**: Simplify administration
- **Explanation**: Access decisions are based on the roles that individual users have as part of an organization.

### 6. Attribute-Based Access Control (ABAC)

- **Principle**: Fine-grained access control
- **Explanation**: Access rights are granted to users through the use of policies which combine attributes together.

## Importance in Cybersecurity

These access control concepts are crucial in cybersecurity for several reasons:

1. **Data Protection**: They help ensure that sensitive data is only accessible to authorized individuals.
2. **Compliance**: Many regulatory standards require implementation of proper access controls.
3. **Minimizing Attack Surface**: By limiting access, they reduce the potential damage from compromised accounts or systems.
4. **Scalability**: Concepts like RBAC allow for easier management of access rights in large organizations.
5. **Flexibility**: ABAC allows for more dynamic and context-aware access control decisions.
6. **Defense in Depth**: Implementing multiple access control methods provides layered security.

Understanding and implementing these concepts is fundamental to creating a robust cybersecurity posture in any organization.

## Contributing

Contributions to improve the code, visualizations, or documentation are welcome. Please feel free to submit a pull request or open an issue.

## Disclaimer
The reponsitory contents are for research and academic purposes only.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
