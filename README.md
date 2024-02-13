### IG_unfollow

IG_unfollow is a Python script that helps you identify users on Instagram whom you are following, but who do not follow you back.

#### How it Works

IG_unfollow parses the HTML of your "following" and "followers" pages on Instagram, extracts the usernames, and then compares the two lists to identify users whom you follow, but who do not follow you back. This script operates entirely on your local machine and does not transfer any data online. There is no risk of Instagram banning because the script does not require logging into Instagram. The user will log in on their own browser and will only copy the HTML content of the web page.

#### Content

The content of this repository includes a "main.py" file that extracts usernames from HTML files and identifies who doesn't follow you back, along with two files "following.html" and "followers.html" where the HTML content should be pasted.

#### Usage

1. **Download the IG_unfollow Repository**:
   - Download the contents of this GitHub repository to your local machine. 
     
2. **Prepare the HTML Files**:
   - Open your Instagram profile in your browser.
   - Click on "Followers" and scroll down to load all your followers.
   - Press Ctrl-Shift-I to open the HTML code inspection window.
   - Right-click on the &lt;html&gt; tag at the top and select "Edit as HTML".
   - Copy everything (to facilitate, press Ctrl-A and Ctrl-C) and paste it into the file called "followers.html", you can use any text editor, such as Notepad.
   - Repeat the procedure for the "Following" section and paste the result into the file called "following.html".

3. **Install Python**:
   - If you don't already have Python installed on your machine, download and install it from the [official Python website](https://www.python.org/).

4. **Install BeautifulSoup**:
   - Install the BeautifulSoup library using pip, the Python package manager. Open a terminal or command prompt and run the following command:
     ```bash
     pip install beautifulsoup4
     ```
     
5. **Run the Script**:
   - Open a terminal or command prompt and navigate to the directory where you downloaded the IG_unfollow repository.
   - Execute the `main.py` script from the IG_unfollow repository directory:
     ```bash
     python main.py following.html followers.html
     ```

6. **Review the Results**:
   - The script will output the usernames of users you follow but who do not follow you back.

#### Requirements

- Python 3.x
- BeautifulSoup4

#### Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

#### License

[MIT](https://choosealicense.com/licenses/mit/)
