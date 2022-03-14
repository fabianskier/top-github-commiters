# top-github-commiters

See your countries leaderboard for most GitHub commits!

|Country|
|-------|
|[Albania](output/albania.md)|

## 🤔 Why am I not here?

One of the reasons might be that you dont have your country in your `location` part of your GitHub profile. Another might be that the list might not be updated to the latest time, to update it, look futher down this document.

## 📕 How do I add my country?

Its simple to add a country;

- Fork this repo.
- Clone it locally.
- Edit `main.js`; change the country (make sure its all lower case, change spaces with _ character)
- Change the `seconds_to_grab_data` variable in `main.js` with how many seconds you would like to grab data for; you can see the comments in that line to get an idea of how many minutes you want to set this to.
- CREATE THE FILE FIRST!!! You will lose the data you got if you dont create the file first. The file must be named the same as the `country` variable in `main.js`. Example `output/country.md`.
- Create a access token.
- Run the script with the access token as a command line option; Example; `node main.js ghp_9uhjpIgozqmbuM5M1b***********`, you can also add another command line option; country; Example: `node main.js ghp_9uhjpIgozqmbuM5M1b*********** country`.
- Wait until the script finishes, you will see the names and how many followers you are on right now in the command line.
- Push the changes to GitHub, open a PR.