# PodsTagAndPublishScript
Simple Script which helps you tag and publish your cocoa pod sdks.

# Description
This script do one simple job: to tag your repo, write that repo tag into your podspec file and push it. It's helpful if your repo has implemented a CI/CD method.

# Usage
Copy & paste the script file to your Pods folder where the .podspec file is located. Then run the script with parameters.

|parameter|comment|
| ------------ | ------------ |
| podspec name | the file name of you pod spec file	|
| tag | the pod version you intent to update to, ie: 1.1.12a |
| branch name | the full branch name for your tag, optional |
| pod source | script use [Cocoa PodSource](https://github.com/CocoaPods/Specs.git) as default, if you need cutom source, you can verify it here |