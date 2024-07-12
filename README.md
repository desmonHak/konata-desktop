# Konata Desktop

Konata Desktop is an Electron application that displays konata dancing on your desktop.  
This application is designed to run on macOS and Linux operating systems.


# WARNING
This is broken rn. If you really want to use it, clone this repo, do "npm i -g konata-desktop" and use the command "kond" into the clone repo

## Installation

To install Konata Desktop, use npm:

```bash
npm install -g konata-desktop
```

## Usage

To start Konata Desktop, use the following command:

```bash
konata-desktop
```
or 
```bash
kond
```

**WARNING**: If when one of these commands are used, it says "electron: command not found" please run 
```bash
npm install -g electron
```
  

## Dependencies

- `axios`: For making HTTP requests.
- `electron`: The framework for creating the desktop application.

## Development

1. **Clone the repository**:

   ```bash
   git clone https://github.com/douxxu/konata-desktop.git
   cd konata-desktop
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Start the application**:

   ```bash
   npm start
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
