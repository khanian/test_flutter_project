# test_flutter_project

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


mac brew 설치 후 virtual ruby 설치

    brew install rbenv
    brew which gem
    rbenv install -l
    rbenv install 3.2.2
    rbenv global 3.2.2
    rbenv init
add eval "$(rbenv init - zsh)" to .zshrc

    source 
    sudo gem install cocoapods
    pods --version
when errer https://stackoverflow.com/questions/77236339/after-updating-cocoapods-to-1-13-0-it-throws-error

    sudo gem uninstall activesupport
    sudo gem install activesupport -v 7.0.8

    flutter doctor

- .zshrc
```
export PATH="$PATH:/Users/kanghoonyi/app/flutter/bin"
eval "$(rbenv init - zsh)"
```
- fvm : fvm.app
```
brew tap leoafarias/fvm
brew install fvm
fvm list
fvm releases
fvm install 3.13.6
fvm list
fvm global 3.13.6
cd /Users/{user}/StudioProjects/test_flutter_project
fvm use 3.13.6
fvm list
fvm install 3.7.12
fvm use 3.7.12
fvm list
set Android Studio env
```

