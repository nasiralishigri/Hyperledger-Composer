# Hyperledger-Composer


# Prerequisites
 1. cURL — latest version
 2. Docker — version 17.06.2-ce or greater
 3. Docker Compose — version 1.14.0 or greater
 4. Golang — version 1.11.x
 5. Nodejs — version 8.x (other versions are not in support yet)
 6. NPM — version 5.x
 7. Python 2.7

  # Installing components
    # Step 1: Install the CLI tools
      There are a few useful CLI tools for Composer developers. The most important one is composer-cli, which contains all 
      the esential operations, so we'll install that first. Next, we'll also pick up generator-hyperledger-composer, composer       rest- server and Yeoman. Those last 3 are not core parts of the development environment, but they'll be useful if             you're  following the tutorials or developing applications that interact with your Business Network, so we'll get them        installed now.

Note that you should not use su or sudo for the following npm commands.

     # Essential CLI tools:

   Copy

 @     npm install -g composer-cli@0.20
   # Utility for running a REST Server on your machine to expose your business networks as RESTful APIs:

Copy
  @  npm install -g composer-rest-server@0.20
   # Useful utility for generating application assets:

Copy
@  npm install -g generator-hyperledger-composer@0.20
  
 @  Yeoman is a tool for generating applications, which utilises generator-hyperledger-composer:

Copy
@  npm install -g yo

     
