# RemoteCommander

**RemoteCommander** is a Python-based tool for remote command execution and file management between two machines over a network.

## Features

- **Command Execution:** Run shell commands on the remote machine.
- **File Download:** Download files from the remote machine to the local machine.
- **System Information:** Retrieve basic system information from the remote machine.
- **Change Directory:** Navigate through directories on the remote machine.
- **List Files:** Get a list of files in the current directory on the remote machine.
- **Forkbomb (Caution!):** Execute a simple forkbomb on the remote machine.

## Usage

1. Clone the repository:
  ```git clone https://github.com/yourusername/RemoteCommander.git```
2. Install the required module:
  ```pip install colorama==0.4.4```
4. Run the server Script on remote machine:
  ```python server.py```
5. Run the client script on local machine:
  ```python client.py```
6. **Enter Commands:**
   - Once the client and server are connected, you can enter various commands on the client side. Here are some examples:

     - **List Files:**
       ```bash
       list
       ```
       This command will display a list of files in the current directory on the remote machine.

     - **Change Directory:**
       ```bash
       cd [directory]
       ```
       Change the current directory on the remote machine.

     - **System Information:**
       ```bash
       sysinfo
       ```
       Retrieve basic system information from the remote machine.

     - **Download File:**
       ```bash
       download [file]
       ```
       Download a file from the remote machine to the local machine.

     - **Exit:**
       ```bash
       exit
       ```
       Terminate the connection.

**Notes:**
   - The project is designed for educational purposes only. Be cautious when using forkbomb or executing commands on unfamiliar systems.

**Contributing:**
  - Contributions are welcome! If you have improvements or bug fixes, feel free to submit pull requests.

**License:**
  - This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
