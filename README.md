# CI-CD-Example
CI/CD Using Fastlane and Jenkins

To add Fastlane in your projetc:<br />
#Install RVM -><br />
Run this line in the terminal "\curl -sSL https://get.rvm.io | bash -s stable --ruby"<br />
To start using RVM you need to run in the terminal "source /Users/YOUR USER/.rvm/scripts/rvm"<br />

#Install the latest Xcode command-line tools:<br />
Run this line in the terminal "xcode-select --install"<br />

#Installing Fastlane ->#<br />
**Using RubyGems**<br />
sudo gem install fastlane -NV<br />
**Alternatively using Homebrew**<br />
brew install fastlane<br />
**Verify fastlane version**<br />
fastlane -v<br />

#Initialize Fastlane tool with Project<br />
Navigate to your iOS project directory and run the below command<br />
Run this line in the terminal "fastlane init"

This would let you choose setup options and accordingly a folder naming fastlane will be created, containing Fastfile, Appfile, Gemfile etc.<br />
#Fastfile<br />
— Located at ./fastlane/Fastfile<br />
— This is the most interesting file, serves as a master file that will contain all the steps and actions you would perform for the app deployments.<br />
— This file is auto-generated on setting up Fastlane for the project.<br />
#Appfile<br />
— Located at ./fastlane/Appfile<br />
— This file serves as a credential manager, will contain the keys/secrets which can be accessed as variables in the fastfile.<br />
— This file is auto-generated on setting up Fastlane for the project.<br />
#Gemfile<br />
— This is to define your dependency on fastlane, plugins.<br />
— Located at ./Gemfile<br />

