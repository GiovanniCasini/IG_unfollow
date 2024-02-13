### IGUnfollow2

IGUnfollow2 is a Python script that helps you identify users on Instagram whom you are following, but who do not follow you back.

#### How it Works

IGUnfollow2 parses the HTML of your "following" and "followers" pages on Instagram, extracts the usernames, and then compares the two lists to identify users whom you follow, but who do not follow you back.

#### Usage

1. **Download the HTML Files**: Navigate to your Instagram profile, click on the "Following" and "Followers" tabs, and save the HTML of both pages to your computer.

2. **Run the Script**: Execute the `main.py` script and provide the paths to the HTML files as arguments.

    ```bash
    python main.py following.html followers.html
    ```

3. **Review the Results**: The script will output the usernames of users you follow but who do not follow you back.

#### Requirements

- Python 3.x
- BeautifulSoup4

#### Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

#### License

[MIT](https://choosealicense.com/licenses/mit/)

