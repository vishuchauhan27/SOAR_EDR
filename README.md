# SOAR & EDR Integration Project: Automated Threat Detection and Response 🚨🤖

## Overview 📋

This project demonstrates the integration of **Security Orchestration, Automation, and Response (SOAR)** with **Endpoint Detection and Response (EDR)**. By combining the automation power of SOAR and the detection capabilities of EDR, the system automatically detects and responds to potential security threats, reducing manual intervention and improving response times.

## Key Components 🧩

- **EDR**: [LimaCharlie](https://limacharlie.io/) – A robust tool for endpoint detection and response.
- **SOAR**: [Tines](https://www.tines.com/) – An automation platform that orchestrates security workflows.
- **Simulated Threat**: [Lazagne](https://github.com/AlessandroZ/LaZagne) – Used for testing the detection system (password recovery tool).
- **Environment**: [Windows VM](https://www.microsoft.com/en-us/windows-server) hosted on VMware.

## Features ✨

- **Custom Detection Rules**: Define specific threat detection rules.
- **Automated Alerts**: Instantly generate and distribute alerts upon threat detection.
- **Multi-Channel Notifications**: Deliver alerts via Slack and Email.
- **User-in-the-Loop**: Human decision-making for critical actions.
- **Automated Responses**: Isolate compromised machines or flag for investigation.
- **Event Logging**: Maintain detailed logs for forensic analysis.

## Workflow 🔄

1. **Threat Detection**: Detect potential threats on endpoints.
2. **Alert Processing**: Generate and process security alerts.
3. **Information Extraction**: Distribute alerts with relevant details.
4. **User Decision**: Prompt for human intervention if necessary.
5. **Automated Response**: Take action (e.g., isolate the machine) based on predefined rules.

## Project Benefits 🎉

- **Rapid Threat Response**: Decrease the time between threat detection and response.
- **Consistent Incident Management**: Ensure uniformity in handling incidents.
- **Scalability**: Capable of handling multiple threats simultaneously.
- **Adaptable**: Easily configured for new or evolving threats.
- **Increased Visibility**: Detailed logs provide insights into security events.

## Setup Instructions 🚀

### Prerequisites

- **Windows VM**: A virtual machine running on VMware.
- **LimaCharlie Account**: [Sign up here](https://limacharlie.io/).
- **Tines Account**: [Sign up here](https://www.tines.com/).
- **Slack and Email Notifications**: Ensure integrations are available for alerting.

### Step-by-Step Setup

1. **Deploy Windows VM**:
   - Set up a Windows virtual machine using VMware.
   - Ensure the machine is properly networked and secured.

2. **Install LimaCharlie**:
   - Follow [LimaCharlie’s documentation](https://docs.limacharlie.io/) to install and configure endpoint detection.

3. **Set Up Tines**:
   - Configure the Tines platform to create automation workflows for alert processing and response. Refer to [Tines Documentation](https://www.tines.com/docs) for guidance.

4. **Test with Lazagne**:
   - Download and run the [Lazagne tool](https://github.com/AlessandroZ/LaZagne) to simulate a security threat and trigger the EDR detection.

5. **Configure Notifications**:
   - Set up multi-channel notifications (e.g., Slack, Email) to receive real-time alerts.

6. **Define Response Workflows**:
   - Create SOAR workflows that trigger automated actions based on threat detection (e.g., isolating a compromised machine).

## Resources 📚

- [LimaCharlie Documentation](https://docs.limacharlie.io/)
- [Tines Documentation](https://www.tines.com/docs)
- [Lazagne GitHub Repository](https://github.com/AlessandroZ/LaZagne)
- [Windows Server Documentation](https://learn.microsoft.com/en-us/windows/)


### Contributing 🤝

Feel free to contribute by submitting issues or pull requests. We welcome any feature requests or suggestions to help improve the project. Let us know how we can make it better!

### Contributors 🫂

- [Smyle](https://github.com/vishuchauhan27)
- [lovish](https://github.com/lovish83)
