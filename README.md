#clone this repo

  git clone https://github.com/avilcan/learn-react-babel
  
#run in terminal:

    npm install
    
    npm install -g browserify
    
#build the code using the following comand everytime somthing changes on your source code:

     browserify -t babelify PageContent.jsx -o bundle.js
