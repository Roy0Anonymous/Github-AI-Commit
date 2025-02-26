# Github-AI-Commit

This script helps you create a detailed commit message with AI.

1. To use it, download the script and give it executable permissions `chmod +x aicommit` and move it to `/usr/local/bin`, you can do `sudo mv aicommit /usr/local/bin`
2. You would also require a Gemini API key, you can generate one from here https://aistudio.google.com/apikey
3. After getting the key, you need to export it, so for that in MacOS, you can open the file `vim ~/.zprofile` and add `export GEMINI_API_KEY="your-api-key"` at the bottom and save it
4. Now, when you are in the repository directory and want to make a commit, simply type `aicommit` in the terminal and it would add all the files, generate a commit message and push your code to your branch.

## Points to note

If you don't have GPG keys setup, you might want to remove `-S` from the commit command if you face and error.
