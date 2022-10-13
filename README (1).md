-- Go To https://github.com/

-- Create Github Account

-- Check Node.js is install in Your PC
   
    -- if not then go to https://nodejs.org/en/
    -- install for your device
    -- after downloading node.js
    -- go to CMD / terminal
    -- Type npm -v and node-v
        -- if there any showing latest verison then it is install
        -- if you facing any issue visit https://bit.ly/3yBpris

-- install Visual Studio Code (vscode)

-- create empty Folder and name that any think you want
    
    -- Folder name should be lower case

-- after completing the folder go to terimal
    
    -- check you are in the inside folder

-- in the terminal type
   
    -- npx create-react-app your-folder-name
    -- it take few minutes to install

-- go to github and create new repositories
   
    -- name that repositories same as a your react-folder

-- after completing the repositories 
   
    -- go to vscode > terminal and type
        -- npm install gh-pages --save-dev    // it install the gh-pages it help to deploy you react-app

-- after installing the package

-- go to your package.json file
   
    -- in the first row add "homepage": "http://account-name.github.io/react-project-name",
       -- //save the file
       -- add two new lines in the scripts section
        -- "predeploy": "npm run build",
        -- "deploy": "gh-pages -d build",
    -- //save the file

-- in vscode terimal type
    -- git init    // Enter
        
    -- git remote add origin http://github.com/account-name/project-name.git    // Enter

    -- git add .    // Enter

    -- git commit -m "Delpoy messgae"    // Enter

    -- npm run deploy    // Enter
        -- it will create the build folder and store in the github 
        
    -- git push -u origin master    // Enter
        -- it will push your react file and store in github
        
-- after completing the process go to the project
    
     github > setting > branch change the master > gh-pages

* You Web Site Will Be Live *

-- mantain the deploy --
    -- git stauts    // Enter

    -- git add .    // Enter

    -- git commit -m "Delpoy messgae"    // Enter

    -- npm run deploy    // Enter

    -- git push -u origin master    // Enter