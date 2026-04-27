# 🏭 IIoT-Edge-Gateway - Connect Devices, Data, and Systems

[![Download](https://img.shields.io/badge/Download-Visit%20the%20GitHub%20page-blue?style=for-the-badge)](https://github.com/sads223/IIoT-Edge-Gateway)

## 🚀 Getting Started

IIoT-Edge-Gateway helps you connect industrial devices, collect data, and move that data to other systems. It runs on Windows and gives you one place to manage device links, data flow, and access control.

Use this guide if you want to:

- Connect to PLCs, meters, and other field devices
- Read data through Modbus, OPC UA, HART, BACnet, and SNMP
- Send data to MQTT, PI System, or other apps
- Set up user access with roles
- Apply license control for your setup

## 📥 Download and Install

### 1. Visit the download page

Open this link in your browser:

[Download IIoT-Edge-Gateway](https://github.com/sads223/IIoT-Edge-Gateway)

### 2. Get the app

On the GitHub page, look for the latest release or the main download files. Download the Windows version to your PC.

### 3. Open the file

If the download is a zip file:

- Right-click the file
- Select **Extract All**
- Choose a folder you can find again, such as `Downloads` or `Desktop`

If the download is an installer file:

- Double-click the file
- Follow the setup steps on the screen
- Keep the default options if you are not sure what to change

### 4. Start the app

After install or extract, open the program from:

- The folder where you unpacked it
- The Start menu
- A desktop shortcut, if one was created

## 💻 Windows Requirements

IIoT-Edge-Gateway is designed for a Windows PC used in an industrial or office setting.

A good setup includes:

- Windows 10 or Windows 11
- 8 GB RAM or more
- At least 2 GB free disk space
- Network access for device links and system connectors
- Admin rights on the machine during setup

For larger device networks, use a machine with more memory and a stable wired network.

## 🔧 What This App Does

This app acts as a bridge between shop-floor devices and software systems. It helps you move data from equipment into tools that can use it.

Common uses include:

- Reading data from field devices
- Mapping device points into clean data tags
- Sending live values to MQTT topics
- Forwarding data to PI System or similar tools
- Managing access for different users
- Handling license checks for deployed systems

## 🧭 Main Parts

### 🖧 Device Connections

Connect to common industrial protocols such as:

- Modbus
- OPC UA
- HART
- BACnet
- SNMP

This lets you pull data from different device types in one place.

### 🔁 Data Pipeline

Use the data pipeline to move values from one place to another. It can help you:

- Clean up raw device data
- Rename fields
- Shape data for downstream apps
- Route data based on rules

### 📡 Northbound and Southbound Flow

The app follows the common industrial edge model:

- Southbound links connect to devices and controllers
- Northbound links send data to higher-level systems

This makes it easier to keep field data organized from the source to the destination.

### 🔐 Access Control

Set user roles so people only see what they need. This helps with:

- Operator access
- Engineer access
- Admin access
- Controlled changes to setup and data links

### 🪪 Licensing

The app supports licensing for managed deployments. This helps you keep the software tied to the right use case and setup.

## 🪟 First Run on Windows

When you open the app for the first time, follow these steps:

1. Launch the program
2. Wait for the main screen to load
3. Check that the service or local process starts
4. Open the settings area
5. Add your device connection details
6. Save the setup
7. Test the link to your device

If the app asks for network or firewall access, allow it so it can reach your devices and destination systems.

## 🛠️ Basic Setup Steps

### 1. Add a device source

Choose the protocol that matches your device, such as Modbus or OPC UA.

Enter the usual connection details:

- Device address or IP
- Port
- Device ID or node name
- Polling interval

### 2. Map the data

Set the points or tags you want to read. Keep names simple so you can find them later.

### 3. Choose where to send data

Pick your output path. Common options include MQTT and PI System connectors.

### 4. Test the flow

Run a small test first. Check that:

- The device responds
- Values appear in the app
- Data reaches the next system

### 5. Save your settings

Save the project or profile after everything works.

## 📶 Supported Industrial Use Cases

This gateway fits many common factory and building tasks:

- Machine data collection
- SCADA data routing
- PLC point reading
- Energy and utility monitoring
- Building automation links
- Asset data transfer
- Protocol conversion between systems

## 🧩 File and Folder Tips

Keep the app in a simple folder path, such as:

- `C:\IIoT-Edge-Gateway`
- `C:\Apps\IIoT-Edge-Gateway`

Do not place it in a deep folder with many levels. That can make it harder to find logs, settings, or support files.

If you use a zip file, keep the original zip in case you need to set it up again.

## 🔌 Connector Notes

The app is built for industrial data exchange. You may use connectors for:

- MQTT brokers
- PI System links
- Device gateways
- Factory systems
- Data historians

For best results, match each connector to the system you already use in your plant or site.

## 🔒 Access and Safety

Set strong user passwords if the app asks for accounts. Limit admin access to people who need it. In a plant setting, this helps prevent unwanted changes to device links and data routes.

If your network blocks outside access, check with your IT team before opening ports or changing firewall rules.

## 🧪 Quick Test Checklist

After setup, check these items:

- The app opens without errors
- The device shows as connected
- Data values update
- The output system receives data
- User login works
- The license status shows as valid

If one part fails, start with the device address, port, and protocol type.

## 🗂️ Topics Covered by This Project

- bacnet
- data-acquisition
- edge-computing
- edge-gateway
- emqx-neuron
- hart-protocol
- hmi
- iiot
- industrial-automation
- iot
- json-ld
- modbus
- mqtt
- nextjs
- opc-ua
- plc
- protocol-conversion
- scada
- snmp
- typescript

## 🆘 Common Setup Problems

### The app does not open

- Check that you downloaded the full file
- Try running it again as an admin
- Make sure Windows did not block the file

### The device does not connect

- Check the IP address
- Check the port number
- Check the protocol type
- Make sure the device is on the same network

### Data does not move to the next system

- Check the output settings
- Verify the broker, server, or PI System target
- Confirm the tag or topic name
- Test one point at a time

### The app asks for permission

- Allow access for local network use
- Let it pass through the firewall if needed
- Keep IT informed in managed environments

## 📄 Suggested Folder Layout

If you manage more than one setup, use a clean layout like this:

- `IIoT-Edge-Gateway`
  - `config`
  - `logs`
  - `backups`
  - `exports`

This makes it easier to review settings and keep copies of working profiles.

## 📌 Use in a Plant or Building

A typical setup may look like this:

- Connect to a PLC over Modbus
- Read data from an OPC UA server
- Pull a meter value from HART or BACnet
- Send live data to MQTT
- Forward key values to PI System
- Control access with roles

That gives you one edge point for device links and data flow.

## 📦 Download Again

If you need to get the app again, use this link:

[Visit the GitHub page to download IIoT-Edge-Gateway](https://github.com/sads223/IIoT-Edge-Gateway)