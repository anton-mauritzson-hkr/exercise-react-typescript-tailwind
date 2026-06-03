# Installing Node.js on Windows

**Step 1: Download Node.js**

- Go to:
  - <https://nodejs.org>
  - Go to "Get Node.Js"
  - Select prebuilt NodeJS and download the installer

**Step 2: Run the Installer**

- Double-click the downloaded .msi file.
- Click **Next**.
- Accept the license agreement.
- Click **Next**.

**Step 3: Choose the Installation Location**

The default installation path is usually:

C:\\Program Files\\nodejs\\

It is generally best to keep the default location.

Click **Next**.

**Step 4: Install**

- Click **Install**.
- If Windows asks for administrator permission, click **Yes**.
- Wait for the installation to complete.
- Click **Finish**.

**Step 6: Verify the Installation**

Open:

Command Prompt (CMD)

or

PowerShell

Run:

node -v

You should see something similar to:

v22.17.0

Now verify npm:

npm -v

Example output:

10.9.2

If both commands work, the installation was successful.

# Installing Node.js on macOS

## Step 1: Download Node.js

1. Open your web browser.
2. Go to:
   - https://nodejs.org
3. Choose one of the following versions:
   - **LTS (Long-Term Support)** – Recommended for most users.
   - **Current** – Includes the latest features but may be less stable.

Download the **LTS version** for macOS.

---

## Step 2: Run the Installer

1. Open the downloaded `.pkg` file.
2. Follow the installation wizard:
   - Click **Continue**
   - Accept the license agreement
   - Choose the installation location (the default is recommended)
   - Click **Install**
3. Enter your Mac password when prompted.
4. Wait for the installation to complete.
5. Click **Close**.

---

## Step 3: Verify the Installation

Open **Terminal**:

**Applications → Utilities → Terminal**

### Check Node.js

Run:

```bash
node -v
```

Example output:

```bash
v22.17.0
```

### Check npm

Run:

```bash
npm -v
```

Example output:

```bash
10.9.2
```

If both commands return version numbers, the installation was successful.
```
