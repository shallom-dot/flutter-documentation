# flutter-documentation
#Everything Flutter from Dr Angela Yu's flutter course
#Using custom widget in your Flutter Application.
  In other to use custom fonts in your appliocation, simply download preferred font from 
  google fonts >> extract the file >> Open up a new folder in project directory(fonts) >> drag and drop your extracted file into the new folder created.
  Then go to your pubspec.yaml, add the following lines of code.
  fonts:
      - family: Pacifico
        fonts:
          - asset: fonts/Pacifico-Regular.ttf
          
 while at this, be careful of indentation. After adding this lines of code to your pubspec.yaml, go back to your main.dart file and use your fonts by simply using the fontfamily.


#Stateful Widget.
#flex enables a widget or the expanded widget to takee twice or thrice amount ofspace than the other.
