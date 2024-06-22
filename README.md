## Immernoch: Manage your CoAP & MQTT Servers
[![made-with-bash](https://img.shields.io/badge/Made%20with-Bash-1f425f.svg?color=green)](https://www.latex-project.org/)
[![GitHub license](https://img.shields.io/badge/License-GPL_3.0-green.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html#license-text)
[![Release](https://img.shields.io/badge/Release-v1.0.0-green.svg)](https://github.com/joseareia/immernoch/releases)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-Yes-green.svg)](https://github.com/joseareia/immernoch/graphs/commit-activity)

### Description
Immernoch is a versatile tool for managing CoAP and MQTT servers, allowing for easy background operation and packet capture. It uses `Mosquitto` as the MQTT broker. For the CoAP server, a custom file was developed. It is available at `CoAP-Server/Server.py`. Modify it according to your needs.

<p float="left">
  <img src="https://github.com/joseareia/immernoch/blob/master/Assets/Immernoch.png"/>
</p>

### Usage

```
$ immernoch [options] [arguments]
```

#### Options
- `-h`, `--help`: Display help for the given command.
- `-s`, `--start-servers`: Start the CoAP and MQTT servers in the background and write to log files.
- `-x`, `--stop-servers`: Stop the CoAP and MQTT servers by killing their PIDs.
- `-p`, `--get-pids`: Get PIDs from the services running in the background.
- `-c`, `--capture`: Start a packet capture with tcpdump and print the elapsed time.

#### Available Commands
- `about`: Shows short information about Immernoch.
- `list`: List all commands and useful information. 

### Getting Help
If you have any questions regarding the tool, its usage, or encounter any errors you're struggling with, please feel free to open an issue in this repository, or contact me via email at <a href="mailto:jose.apareia@gmail.com">jose.apareia@gmail.com</a>.

### Contributing
Contributions to this tool are welcome! If you encounter any issues, have suggestions for improvements, or would like to add new features, please submit a pull request. We appreciate your feedback and contributions to make this tool even better.

### License
This project is under the [GPL 3.0](https://www.gnu.org/licenses/gpl-3.0.en.html#license-text) license.
