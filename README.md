### 1. Advanced working mechanism

Fully stealthy execution:

Run the program via invisible.vbs to hide any windows

Set "hidden" and "system" attributes for all created files

Self-destruct the program after execution using batch files

Data compression and encryption

Data compression using the

DEFLATE algorithm with (maximum) compression level

Advanced XOR encryption with a dynamic key based on USB serial

- Integrate compression and encryption into a single process to reduce execution time

- Comprehensive data theft:

- Copy essential system folders (images, documents, downloads)

Steal browser databases (cookies, passwords, history)

Support for all major browsers

(Chrome, Firefox, Edge)
2####. Advanced technical features

Multi-threading:)

Execute copy and compression operations in parallel threads

300% speed increase compared to serial execution

- Intelligent management of system resources to prevent overloading

- Avoid detection

- Naming files using a unique USB serial

- No use of distinguishable fixed names

Disables the generation of LOG files or any side effects

Integration with the operating system

- Direct use of Windows APIs (win32api)

- Extracting system paths via IDs

CSIDL

Bypassing security policies via low-level techniques

3#### Deployment and launch mechanism

1. When USB is inserted

Automatically activate the autorun.inf file

Run the hidden program via invisible.vbs

Request program activation via a user interface
Deceptive
2 Copy Operations:

1 Shared

- Create a hidden folder using a USB serial

Copy, compress, and encrypt targeted folders

- Steal browser data in the background

3. Self-Destruct:

- Delete the main executable file after completion

- Keep only compressed and encrypted files

- Leave no traces in system logs

#### 4. Performance Metrics

Speed:

Processes 1GB of data in 90 seconds

Runs 7 parallel threads for maximum performance

Uses level 9 ZIP compression to limit size

- Camouflage

- Memory consumption does not exceed 15MB

No activity appears in Task Manager

No alarms are generated in security programs

Reliability:

- 6 error handling layers

- Continuity of operation even with 40% of files lost

- Automatic recovery from crashes
"pyinstaller--onefile --noconsole

--icon-drive.ico --add-data "drive.ico;."

--uac-admin backup_script.py"
