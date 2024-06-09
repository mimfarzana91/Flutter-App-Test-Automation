**Process with Flutter Driver:**

Download android studio from https://developer.android.com/studio

Install android studio.

Download flutter from https://flutter.dev/docs/get-started/install

Set the environment variable for flutter using the same link.

Open Android Studio > Go to File > Setting > Languages and Frameworks > Flutter > Set the path for flutter. 

Open the terminal on android studio > writer flutter doctor > Press Enter

Make sure there is no issue.

Now pull the project (APP) from the git. 

Create folder test_driver inside the project folder if not automatically created.

Go to that folder and pull the automation code from the git or create two file naming app.dart and app_test.dart.

Open the project on android studio. 

Open the pubspec.yaml file > Add dependency

Open the terminal on android studio and type flutter pub get wait for some time until the process is finished. Then type flutter pub upgrade and again wait for the process to be ended.

To update the flutter open the terminal on android studio and type flutter upgrade.

After writing the test scripts if you want to run the test then Open the terminal and type 

flutter drive --target=test_driver/Test_Cases_Login/app.dart --flavor automation --debug

If you want to run a different test case then change the Test_Cases_Login to your desired folder name. 




