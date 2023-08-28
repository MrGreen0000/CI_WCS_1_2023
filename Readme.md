# Quest 1729

Launch the app with the following command: `docker-compose -f docker-compose.dev.yml up --build`

# GitHub CLI

check the process step by step

gh auth login :

? What account do you want to log into? GitHub.com
? What is your preferred protocol for Git operations? HTTPS
? Authenticate Git with your GitHub credentials? Yes
? How would you like to authenticate GitHub CLI? Login with a web browser

! First copy your one-time code: 0E86-3D7B
Press Enter to open github.com in your browser...
✓ Authentication complete.
✓ Configured git protocol
✓ Logged in as MrGreen0000

gh repo create CI_WCS_1_2023

git clone https://github.com/MrGreen0000/CI_WCS_1_2023.git

git add .

git commit -m "first commit"

git push

cd .\wns-docker-compose-app-main\

code .
