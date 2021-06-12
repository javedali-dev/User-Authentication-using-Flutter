# User authentication system using Flutter and Firebase

![Flutter and Firebase](/assets/banner.png)

#

## Build Locally

- Prerequirest:

  - Android Emulator install and working if not here is [link](https://developer.android.com/studio/run/emulator)
  - Flutter install on your machine you can verify that by using <br/> `> flutter --version`
  - Firebase account

- Clone repository on your local machine

  - Create a Folder and navigate to new folder
    - open your terminal and type:<br/>
      `> mkdir Testing_Project`
    - navigate to new folder:<br/>
      `> cd Testing_Project`
  - Clone repository<br/>
    ` > git clone https://github.com/javedali-dev/User-Authentication-using-Flutter.git`
  - Navigate to clone repository:<br/>
    `> cd User_authentication_using_Flutter`
  - Open with your favorite text editor if you are using vscode you can open it by:<br/>
    `> code .`

- Create and configure project in [firebase](https://firebase.google.com/):
  - Create a account:
    - Go to [Firebase](https://firebase.google.com/) website and click on **Get started** button
  - Onced you login Click on **Add Project**
  - Now choose your project type. For this project select **Android**.
  - Register your project
    - Android package name: go to `AndroidManifest.xml` file and there you can find the package name. for this case give `com.example.todo`
  - Download Config file: Now download the config file(google-services.json) into `android`->`app`<br/>
    ![Download config file](/assets/1.png)
  - Add Firebase SDK:<br/>
    You need to add firebase SDK in order to talk to firebase api. it is preety simple and well documented on firebase website. I added some of screenshot in case you need them.<br/>
    ![Configure on project level](/assets/2.png)<br/>
    ![Configure on app level](/assets/3.png)
- Build and Run locally:<br/>
  - Make sure your emulator is running.
  - Go to `lib`->`main.dart` file and press `ctrl+F5` or you can do it manually. Go to `Run`-> `Run without Debugging`. It will install the app inside the emulator and run it.

## Result:
