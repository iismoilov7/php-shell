# PHP Shell Script README

## Disclaimer

The PHP Shell Script provided in this repository is intended for educational and informational purposes only. By using this script, you acknowledge and agree to the following:

1. **Use at Your Own Risk**: The script is provided "as-is" without any guarantees or warranties of any kind. The authors and contributors are not responsible for any damages, data loss, or security breaches that may occur as a result of using this script.

2. **Security Risks**: This script allows for powerful file and command operations on the server. Improper use or exposure to unauthorized users can lead to severe security vulnerabilities, including unauthorized access to sensitive data, server compromise, or data loss. It is your responsibility to implement appropriate security measures.

3. **Not for Production Use**: This script is not intended for use in production environments. It is recommended to use this script in a controlled, secure environment, such as a local development setup.

4. **Compliance with Laws**: You are responsible for ensuring that your use of this script complies with all applicable laws and regulations. Unauthorized access to computer systems or data is illegal and can result in criminal charges.

5. **Modification and Redistribution**: If you modify or redistribute this script, you must include this disclaimer and ensure that the modified version does not pose security risks to users.

By using this script, you agree to the terms of this disclaimer. If you do not agree with these terms, you should not use this script.

## Overview

This PHP script provides a web-based shell interface that allows users to perform various file operations and execute shell commands on the server. The script supports functionalities such as downloading files, reading file contents, creating and deleting files and directories, uploading files, and executing PHP code.

## Features

- **File Operations**: Download, read, create, and delete files.
- **Directory Operations**: Download and remove directories.
- **Shell Command Execution**: Execute shell commands using different methods (`exec`, `shell_exec`, `system`).
- **File Upload**: Upload files to the server.
- **PHP Code Execution**: Execute arbitrary PHP code.

## Requirements

- A web server with PHP support (e.g., Apache, Nginx).
- PHP version 5.6 or higher.
- The `ZipArchive` extension must be enabled for folder downloading functionality.

## Usage

1. **Download a File**:
   - Input the file path in the "Директория файла" field and click "Скачать файл".

2. **Read a File**:
   - Input the file path in the "Директория файла" field and click "Прочитать файл".

3. **Remove a File**:
   - Input the file name in the "Имя файла" field and click "Удалить файл".

4. **Create a File**:
   - Input the file name in the "Имя файла" field and provide the content in the textarea, then click "Создать файл".

5. **Download a Folder**:
   - Input the folder path in the "Директория папки" field and click "Скачать папку".

6. **Remove a Folder**:
   - Input the folder path in the "Директория папки" field and click "Удалить папку".

7. **Get Directory Content**:
   - Input the directory path in the "Директория" field and click "Получить содержание директории".

8. **Execute Shell Commands**:
   - Input the command in the "Выполнить CMD команду" field, select the execution type, and click "Выполнить".

9. **Run PHP Code**:
   - Input the PHP code in the textarea and click "Выполнить PHP код".

10. **Upload a File**:
    - Choose a file using the file input and click "Загрузить".

## Security Warning

This script provides powerful functionalities that can be exploited if not properly secured. It is highly recommended to:

- Restrict access to this script to trusted users only.
- Implement authentication and authorization mechanisms.
- Consider using this script in a controlled environment, such as a local development setup, rather than in a production environment.

## Localization

The script is currently set to use the Russian locale (`ru_RU.UTF-8`). You can change the locale by modifying the `$locale` variable at the beginning of the script.

## License

This script is provided as-is without any warranty. Use it at your own risk.
