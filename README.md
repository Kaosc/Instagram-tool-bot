# Instagram Tool

A tool with useful features that can be used for Instagram.

![console look](./assets/console.png)

## Dependencies

- ### Python Dependencies
  The tool requires **Selenium**, **Colored**, and **Pillow** library to function.

You can install them by using the following command:

```bash
pip install selenium colored pillow python-dotenv requests
```

or run the `dep-installer.py` file.

- ### Chrome Driver

Current ChromeDriver version is 116. Please check [here](https://googlechromelabs.github.io/chrome-for-testing/) for latest version.

ChromeDriver version must be the same chrome version installed on your system. You can check your installed chrome version via Settings > About Chrome.

### Installation

1. Add latest ChromeDriver to in "driver" folder.
2. Set image and driver path.

#### Note

if you don't want to pass your login information every time, please fill the "\_loginInfo" file or create
a .env file with the following variables:

```bash
USERNAME=your_username
PASSWORD=your_password
```
