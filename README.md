# OS Information Script

This repository contains instructions for creating a script to display the operating system information on your Unix-like system.

## How to Set Up the OS Information Script

Follow these steps to create and configure the script:

### 1. Create the Script

1. Open a terminal and create a new script file:

    ```bash
    nano ~/show_os.sh
    ```

2. Copy and paste the following content into `show_os.sh`:

    ```bash
    #!/bin/bash

    # Function to display the operating system information
    show_os_info() {
        echo "You are using: $(uname -a)"
    }

    # Execute the function
    show_os_info
    ```

3. Save the file and exit the editor:
    - Press `Ctrl + X`
    - Press `Y` to confirm saving
    - Press `Enter` to exit

4. Make the script executable:

    ```bash
    chmod +x ~/show_os.sh
    ```

### 2. Run the Script

To execute the script and display the OS information:

1. Open a terminal and run:

    ```bash
    ~/show_os.sh
    ```

## License

This project is licensed under the MIT License.

## Contact

For any questions or issues, please contact [CharlieUlmanxiv@gmail.com].

