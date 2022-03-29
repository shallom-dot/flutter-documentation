# flutter-documentation
#Everything Flutter from Dr Angela Yu's flutter course


#containers layout behaviour
If the widget has no child, no height, no width, no constraints, and the parent provides unbounded constraints, then Container tries to size as small as possible.

If the widget has no child and no alignment, but a height, width, or constraints are provided, then the Container tries to be as small as possible given the combination of those constraints and the parent's constraints.

If the widget has no child, no height, no width, no constraints, and no alignment, but the parent provides bounded constraints, then Container expands to fit the constraints provided by the parent.

If the widget has an alignment, and the parent provides unbounded constraints, then the Container tries to size itself around the child.

If the widget has an alignment, and the parent provides bounded constraints, then the Container tries to expand to fit the parent, and then positions the child within itself as per the alignment.

Otherwise, the widget has a child but no height, no width, no constraints, and no alignment, and the Container passes the constraints from the parent to the child and sizes itself to match the child.

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
#voidCallback

#Using flutter Packages:
Flutter packages are open source libraries of code that other people have created and you can incoporate them into your projects with minimal efforts.
they make work easier.  To add a flutter package to your project, 
1) depend on it( by adding a line of code to your dependencies in the pubspec.yaml file)
2) From the terminal: Run flutter pub get . OR From VS Code: Click Get Packages located in right side of the action ribbon at the top of pubspec. yaml 
