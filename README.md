# Github-Repo-Traffic
 
## GitHub Personal Access Token Setup:

Generate a new GitHub Personal Access Token [StepByStep](https://scribehow.com/shared/Generate_Personal_Access_Token_for_GitHub_Repository__ym3EQnM1QSCvWPSMoMJ-_w)

Copy the generated token.

Open the config.ini file and add the following section:
```
[github]
token=<personal_access_token>
```
Replace <personal_access_token> with your actual token.

## Install Required Python Packages:

Open your terminal or command prompt.
Navigate to the directory containing the requirements.txt file.
Run the following command to install the required packages:
```
pip install -r requirements.txt
```
## Run the Script:

After installing the required packages, run the script using the following command:
```
python get_traffic.py
```
This will fetch the traffic statistics of all repositories associated with your GitHub account.
The traffic stats will be stored in a CSV file named <user_name>.csv, where <user_name> is your GitHub username.

Example:
![image](https://github.com/Fazlibeqir/Github-Repo-Traffic/assets/57021385/9caf101b-2805-457a-8d69-36410475c7e7)

