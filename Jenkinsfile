node {
  
        checkoutSource()
        helloWorld()
   
}

def mysh(cmd) {
    sh('#!/bin/sh -e\n' + cmd)
}

def checkoutSource() {
  stage ('checkoutSource') {
    copyFilesToWorkSpace()
  }
}

def copyFilesToWorkSpace() {
  mysh "cp -r /github/workspace/* $WORKSPACE"
}

def helloWorld () {
    stage ('Build') {
    echo "Testing 12345..."
    }
}
