## Quick Navigation

- [Installing Node.js on Windows](#installing-nodejs-on-windows)
- [Installing Node.js on macOS](#installing-nodejs-on-macos)
- [Running the Project](#running-the-project)

# Installing Node.js on Windows

**Step 1: Download Node.js**

- Go to:
  - <https://nodejs.org>
  - Go to "Get Node.js"
  - Select **Prebuilt Node.js** and download the installer

**Step 2: Run the Installer**

- Double-click the downloaded `.msi` file.
- Click **Next**.
- Accept the license agreement.
- Click **Next**.

**Step 3: Choose the Installation Location**

The default installation path is usually:

```text
C:\Program Files\nodejs\
```

It is generally best to keep the default location.

Click **Next**.

**Step 4: Install**

- Click **Install**.
- If Windows asks for administrator permission, click **Yes**.
- Wait for the installation to complete.
- Click **Finish**.

**Step 5: Verify the Installation**

Open:

- Command Prompt (CMD)

or

- PowerShell

Run:

```bash
node -v
```

You should see something similar to:

```bash
v22.17.0
```

Now verify npm:

```bash
npm -v
```

Example output:

```bash
10.9.2
```

If both commands work, the installation was successful.

---

# Installing Node.js on macOS

**Step 1: Download Node.js**

- Go to:
  - <https://nodejs.org>
  - Go to "Get Node.js"
  - Select **Prebuilt Node.js** and download the installer

**Step 2: Run the Installer**

1. Open the downloaded `.pkg` file.
2. Follow the installation wizard:
   - Click **Continue**
   - Accept the license agreement
   - Choose the installation location (the default is recommended)
   - Click **Install**
3. Enter your Mac password when prompted.
4. Wait for the installation to complete.
5. Click **Close**.

**Step 3: Verify the Installation**

Open **Terminal**:

**Applications → Utilities → Terminal**

Run:

```bash
node -v
```

You should see something similar to:

```bash
v22.17.0
```

Now verify npm:

```bash
npm -v
```

Example output:

```bash
10.9.2
```

If both commands work, the installation was successful.

---

# Running the Project

After installing Node.js, open the project folder in your terminal.

### Install Dependencies

Run:

```bash
npm install
```

This will download and install all required project dependencies.

### Start the Development Server

Run:

```bash
npm run dev
```

The development server will start and display a local URL, for example:

```text
http://localhost:3000
```

Open the displayed URL in your browser to view the application.
