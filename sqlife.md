# SQLife - a new Oracle/PostgreSQL client

## Brief Description
SQLife is a lightweight and user-friendly SQL client designed for Oracle and PostgreSQL databases. Unlike many SQL clients, SQLife is optimized for MacOS while also providing robust support for Windows and Linux. It enables users to connect to databases, execute queries, and manage data efficiently.

![SQLife Banner](https://bitifyware.com/images/banner02.png)

## Supported Platforms
* Windows (x86-64)
* Linux (x86-64): Debian, Ubuntu, Fedora, CentOS
* MacOS (x86-64, ARM64 - Apple Silicon)

## Features
* Comprehensive Connection Properties for Oracle and PostgreSQL
* Object Management (tables, views, procedures, functions, triggers, etc.)
* Support for Multiple Connections
* Intelligent Auto-Completion
* SQL Syntax Highlighting and Formatting
* Data Export/Import (SQL, CSV, Excel)
* Data Viewing and Inline Editing
* SQL History Tracking

## Managing Connections
Connections are organized into customizable groups, allowing users to separate development, production, personal, or work-related connections. Temporary connections can be created without a name, and passwords are optional for user convenience, though using passwords is recommended for better security.

## User Interface
SQLife features a tab-based interface for managing multiple connections and SQL editors. Key highlights include:
* **Object and Script Management**: The left panel provides tools for managing database objects and scripts. Users can switch schemas or users via a dropdown menu.
* **Object Explorer**: A tree view for navigating database objects, with options to create, edit, and delete objects. Users can also view object properties and dependencies.
* **Script Management**: A dedicated tab for managing SQL scripts, allowing users to create, edit, and save scripts. Scripts can be organized into folders for better organization. SQLife integrates with Git for workspace management, enabling version control for saved files. 
* **SQL Editor**: The central area supports multiple SQL editor tabs with features like auto-completion, syntax highlighting, and formatting. SQL execution requires manual commits, ensuring safety in production environments. Rollback is also supported. Find/Replace are basic but effective.
* **Export/Import Tools**: Dedicated tabs for exporting/importing objects and data with customizable options, such as output formats and schema inclusion. Data Export supports Clob and Blob types (using base64).
* **Data Viewer**: A grid-based view for data with inline editing, multi-cell selection, clipboard support, and binary data handling.

Messages and logs are displayed at the bottom of the interface for easy monitoring. It also support backup and restore connections. password will be encrypted in the configuration file.

## Future Plans
More features are planned for future releases, including:
* Oracle Scheduler Jobs
* File Differ and History
* Enhanced Syntax Highlighting for SQL and Improved UI Element Highlighting for Better Readability
* Customizable Keyboard Shortcuts

Download and Resources

[Official Website](https://bitifyware.com/)

Email: support@bitifyware.com
