#ERP for Schools, Colleges & Educational Institutes
[![Build Status](https://travis-ci.org/frappe/schools.png)](https://travis-ci.org/frappe/schools) [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/frappe/erpnext?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
---
ERPNext Schools is built on the [Frappé](https://github.com/frappe/frappe) Framework, a full-stack web app framework in Python & JavaScript.

Requires [EPRNext](https://github.com/frappe/erpnext), 

Read the User and Developer Documentation at https://frappe.github.io/schools

![Student](schools/public/student.png)

### Full Install

The Easy Way: our install script for bench will install all dependencies (e.g. MariaDB). See https://github.com/frappe/bench for more details.

New passwords will be created for the ERPNext "Administrator" user, the MariaDB root user, and the frappe user (the script displays the passwords and saves them to ~/frappe_passwords.txt).

Once you install ERPNext run -

```
$ bench get-app schools https://github.com/frappe/schools
$ bench install-app schools
```

#### License
GNU General Public License v3

The ERPNext Schools code is licensed as GNU General Public License (v3) and the Documentation is licensed as Creative Commons (CC-BY-SA-3.0) and the copyright is owned by Frappe Technologies 
<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">
  <h3 align="center">Streamlining Educational Administration</h3>
  <p align="center">
    Comprehensive open-source management solution for schools, colleges, and other educational institutions.
    <br />
    <a href="https://grow.empress.eco/"><strong>Explore the Docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/empress-eco/schools/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/schools/issues">Request Feature</a>
  </p>
</div>

## About The Project

Empress Education Management System is an open-source solution designed specifically to streamline and automate administrative tasks for educational institutions such as schools and colleges. Its user-centric design focuses on simplifying operations, saving time and resources. 

## Key Features

- Comprehensive Student Information System: Maintain detailed student profiles and records.
- Efficient Course and Batch Management: Effectively manage course batches, schedules, and assignments.
- Streamlined Fee, Attendance, and Assessment Management: Automate and organize fee collection, attendance tracking, and grading.

## Target Audience

Our solution is designed for administrators, educators, and staff within schools, colleges, and other educational institutions seeking to automate and streamline their administrative tasks.

## Technical Stack and Setup Instructions

This project leverages the power of Python and JavaScript, built on the robust [Empress](https://github.com/Empress/Empress) platform.

### Prerequisites

The project requires [Empress](https://github.com/Empress/Empress) to be installed.

### Installation

Follow these steps to set up your development environment:

```sh
# Clone the repository
$ git clone https://github.com/empress-eco/schools.git

# Navigate to the project directory
$ cd schools

# Install the application
$ bench get-app schools
$ bench install-app schools
```

For detailed instructions and dependencies, visit the [documentation](https://grow.empress.eco/).

## Usage

After installation, you can start using Empress Education Management System for managing various aspects of your educational institution. For a comprehensive guide and detailed instructions, visit our [documentation](https://grow.empress.eco/).

## Contribution Guidelines

We encourage community contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements

This project is licensed under the MIT License. All your contributions will also be licensed under the MIT License.

Special thanks to the Empress Community for providing the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.