# junior_design
CS3311/LMC3432 Junior Design Project for Team 1117


## Steps for Setting up local environment

# Part 1 - installing Amplify CLI
#### Requires Node JS and NPM 

#### Step 1. open terminal/powershell in /amplifyapp

#### Step 2. Install Amplify cli in terminal

> <code>npm install -g @aws-amplify/cli</code>

#### Step 3. Configure CLI
> <code>amplify configure</code>

#### Step 5. Initialize Amplify App (locally)
> On Amplify console, Go to **Local setup instructions** under **backend** for the app. Copy the command. Looks like:
>
> <code>amplfiy pull --appId abcdefghjklmnop --envName staging</code>
>
>Then follow the prompts as so:
>
> <code>? Choose your default editor: Visual Studio Code
? Choose the type of app that you're building: javascript
? What javascript framework are you using: react
? Source Directory Path:  src 
? Distribution Directory Path: build
? Build Command:  npm run-script build
? Start Command: npm run-script start
? Do you plan on modifying this backend? Y</code>

## The project will then be ready for adding features!

Credit: [From this aws tutorial](https://aws.amazon.com/getting-started/hands-on/build-react-app-amplify-graphql/module-two/)

### Below is deprecated(from Spring 2021)-----
INSTRUCTIONS FOR STARTING SERVER

STEP 1:
Open CMD and change directory into file where Index.HTML and main.js are. 

Step 2:
input "python -m http.server 8080" and hit enter

Step 3:
With your preferred web browser, enter "http://localhost:8080/" into the address bar. 

That's it! You should see nothing at this point. 

Everytime you make changes to the HTML, hit referesh to see the changes you made. 
