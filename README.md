Certainly! A README.md file is a great way to provide information about your bash script. Here's a simple example tailored to your internsctl script:

markdown

# internsctl - Custom Linux Command

## Version: v0.1.0

`internsctl` is a custom Linux command designed to perform various system operations. It includes functionalities to retrieve CPU information, memory information, create users, list users, and get file information.

## Usage

```bash
internsctl COMMAND [OPTIONS]
Commands and Options
cpu getinfo: Get CPU information.

bash

internsctl cpu getinfo
memory getinfo: Get memory information.

bash

internsctl memory getinfo
user create <username>: Create a new user.

bash

internsctl user create <username>
user list [--sudo-only]: List all regular users or users with sudo permissions.

bash

internsctl user list
internsctl user list --sudo-only
file getinfo <file-name> [--size | -s | --permissions | -p | --owner | -o | --last-modified | -m]: Get information about a file. Options to obtain specific information.

bash

internsctl file getinfo <file-name>
internsctl file getinfo --size <file-name>
Additional Information
--help: Display help message.

bash

internsctl --help
--version: Display command version.

bash

internsctl --version
