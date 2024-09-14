# adoption-centre-web-page
python3 -m venv venv
source ./venv/bin/activate
python -m http.server

# Good Boy Dog Fostering and Adoption Centre Website

This is a simple static website for the **Good Boy Dog Fostering and Adoption Centre**, which can be run locally on Linux, Windows, or macOS. It includes multiple pages (home, available dogs, foster, adopt, contact us) and uses standard HTML, CSS, and images.

## Prerequisites

To run this website locally, you need:

- A modern web browser (e.g., Chrome, Firefox, Edge).
- Python (for running a local HTTP server).

### Install Python

#### On Linux:
1. Open your terminal.
2. Run the following command to install Python:
   bash
   sudo apt update
   sudo apt install python3
   
3. Verify the installation:
   bash
   python3 --version
   

#### On Windows:
1. Download the latest version of Python from [python.org](https://www.python.org/downloads/).
2. Run the installer and **make sure to check the box** that says **Add Python to PATH** during installation.
3. After installation, open the **Command Prompt** and verify the installation:
   bash
   python --version
   

#### On macOS:
1. Open your terminal.
2. Run the following command to install Python using **Homebrew** (if Homebrew is installed):
   bash
   brew install python
   
   If Homebrew is not installed, install it by running:
   bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   
3. Verify the installation:
   bash
   python3 --version
   

---

## Running the Website Locally

Once Python is installed, you can serve the website locally using Python's built-in HTTP server.

### Steps for All Platforms (Linux, Windows, macOS):

1. **Download the website files**:
   You can either clone the repository or download the files manually:
   - To clone the repository using Git:
     bash
     git clone https://github.com/your-username/your-repo-name.git
     
   - Alternatively, download the ZIP file from the repository and extract it.

2. **Navigate to the project directory**:
   Open a terminal (Linux/macOS) or command prompt (Windows) and use the `cd` command to navigate to the directory containing your website files. For example:
   bash
   cd /path/to/your/website
   

3. **Start the local HTTP server**:

   - **For Python 3** (on Linux/macOS/Windows):
     bash
     python3 -m http.server
     

   - **For Python 2** (on Linux/macOS):
     bash
     python -m SimpleHTTPServer
     

   - **For Windows (Python 3)**:
     bash
     python -m http.server
     

4. **Access the website**:
   Open your web browser and navigate to `http://localhost:8000`. You should see the website served locally.

---

## File Structure


/my-website
|-- index.html                    # Home page
|-- available-dogs.html            # Available dogs page
|-- foster.html                    # Foster page
|-- adopt.html                     # Adopt page
|-- contact.html                   # Contact page
|-- header.html                    # Header component
|-- footer.html                    # Footer component
|-- /css
|   |-- styles.css                 # Main stylesheet
|   |-- red-border.css             # Stylesheet for red border toggle
|-- /images
|   |-- good-boy-logo.png          # Logo image
|   |-- dog-max.jpg                # Featured dog image


### Customization

- **CSS**: You can edit the styles in the `./css/styles.css` file.
- **Images**: Replace images in the `./images/` folder with your own to customize the content.

### Toggle Red Border Style

This website includes a button to toggle a red border around elements for debugging layout issues. You can find this button on the top right corner of the header.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Credits

- **Website Design**: Good Boy Dog Fostering and Adoption Centre
- **Developer**: [Your Name]

---

Enjoy exploring the Good Boy Dog Fostering and Adoption Centre website locally!


### How to Use the README:

- This README provides detailed steps for running the website locally across **Linux**, **Windows**, and **macOS**.
- The instructions for each platform include the steps to install Python, run the local server, and access the website.
- The file structure, customization options, and toggle for the red border are also explained.
# adoption-centre-web-page
# adoption-centre-web-page

