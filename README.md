# streamer-analytics

## Installation Instructions

1. Download Preferred Version from the directories above
   - It is recommended to use the latest version
2. Extract the Files:
   - Right-click the downloaded ZIP file and select "Extract All..." to unpack the contents to a desired location.
3. Add to PATH (Optional):
   - To make the tool accessible from any command prompt, add its directory to the system PATH:
     - Open Control Panel > System and Security > System.
     - Click Advanced system settings > Environment Variables.
     - Under System variables, find and select the Path variable, then click Edit.
     - Click New and add the path to the extracted directory.
     - Click OK to close all dialogs.
       Run the Tool:
4. Open a Command Prompt or PowerShell window.
   - Navigate to the directory where you extracted the tool, or if added to the PATH, just type:
   ```sh
   twitch.exe --help
   ```
   
## Usage Instructions
### Basic Usage
Once installed, you can run the tool from a terminal. Below are some basic usage examples:

#### Basic Utilities:
- --help: Displays the help information.
```sh
twitch.exe --help
```

- --version: Shows the version of the tool.
```sh
twitch.exe --version
```

### Supported Commands
- view-users: Displays a list of currently onboarded users
```shell
twitch.exe view-users
```

- produce-csv: Generates a CSV file in your current directory with the Twitch data for all onboarded users
```shell
twitch.exe produce-csv
```

- add-users: Onboards new users to the tool
```shell
twitch.exe add-users -u <username1> <username2> <username3> ...
```

- delete-users: Removes users from the tool
```shell
twitch.exe delete-users -u <username1> <username2> <username3> ...
```

- get-user: Displays the Twitch data for a specific user
```shell
twitch.exe get-user -u <username>
```
