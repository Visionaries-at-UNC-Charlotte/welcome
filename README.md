# Welcome!
Please test your knowledge by editing the txt document and creating a pull request!

Absolutely! Here are the instructions converted into Markdown format:

## Instructions: Editing Text Document in GitHub Repository

1. **Clone the Repository:**

   Open your terminal or Git command prompt and navigate to the directory where you want to store the cloned repository.

   ```bash
   cd /path/to/your/desired/directory
   ```

   Clone the repository using the following command:

   ```bash
   git clone https://github.com/Visionaries-at-UNC-Charlotte/welcome.git
   ```

2. **Edit the Text Document:**

   Navigate into the cloned repository directory:

   ```bash
   cd welcome
   ```

   Locate the text document you need to edit, which could be named something like `information.txt`. Open it using a text editor:

   ```bash
   nano information.txt  # You can replace "nano" with your preferred text editor command
   ```

   Inside the text document, enter your information in the specified format:

   ```plaintext
   Nickname: YourNickname
   Major/Concentration: YourMajorOrConcentration
   Year in College: YourYearInCollege
   ```

   Replace `YourNickname`, `YourMajorOrConcentration`, and `YourYearInCollege` with your actual information.

   Save and exit the text editor.

3. **Commit Your Changes:**

   Add the modified text document to the staging area:

   ```bash
   git add information.txt
   ```

   Commit your changes with a meaningful commit message:

   ```bash
   git commit -m "Added my information"
   ```

4. **Pull Latest Changes (Optional, but Recommended):**

   Before pushing your changes, it's a good practice to pull any potential updates from the remote repository to ensure you're working with the latest code:

   ```bash
   git pull origin main
   ```

5. **Push Your Changes:**

   Push your committed changes to the remote repository:

   ```bash
   git push origin main
   ```

That's it! You've successfully edited the text document with your information and pushed your changes back to the repository. Make sure to replace "Added my information" with a meaningful commit message that reflects the changes you've made. Also, remember to adjust the file name (`information.txt`) and the branch name (`main`) as needed based on the actual repository structure.





