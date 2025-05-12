# Linux Recon Tool

Linux Recon Tool is a command-line utility designed for reconnaissance and enumeration tasks in cybersecurity. This tool provides an easy-to-use interface for leveraging popular reconnaissance frameworks and tools such as Recon-ng, Amass, Nmap, and Sublist3r.
![image](https://github.com/user-attachments/assets/ff0d3b7a-cfa1-4e88-a8ae-fbbcba4f7264)


## Features

- **Recon-ng**: A powerful web reconnaissance framework that provides a variety of modules for gathering information.
- **Amass**: A tool for DNS enumeration and network mapping, useful for discovering subdomains and other related information.
- **Nmap**: A network scanning tool that allows users to discover hosts and services on a computer network.
- **Sublist3r**: A fast subdomain enumeration tool that helps in finding subdomains of a target domain.

## Installation

To install the required dependencies, run the following command:

```
python -m venv venv
source venv/bin/activate 
pip install -r requirements.txt
```

## Usage

To run the tool, execute the following command:

```
cd src 
python3 main.py
```

Follow the on-screen instructions to select the desired reconnaissance or enumeration option.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
