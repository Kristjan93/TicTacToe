# Development Manual

### How to get the project running on a fresh machine


```
1. Generate SSH Key
    - command: ssh-keygen
    - command: cd .ssh
    - command: cat id_rsa.pub
    - copy the key
    - go to Github -> settings -> SSH keys -> add SSH key
```
```
2. Download git
        - command: sudo apt-get install git
```
```
3. Set you git identifier
        - command: git config --global user.email "your@email.com"
        - command: git config --global user.name "Your Name"
```
```
4. Clone the repository to your development machine
        -command: git clone git@github.com:7kings/TicTacToe.git
```
```
5. Download java(if needed)
        command: sudo apt-get install openjdk-7-jdk
```
```
6. Build the project
        -command: ./gradlew build
```

This should build the project
