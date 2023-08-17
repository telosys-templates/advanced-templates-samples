Set of advanced templates examples 

- $loader to use specific Java classes in the templates (Java sources are in "classes" folder)    
  - MyData.java (in default Java package)   
  - org.foo.FooData.java   
  - MyFooClass.java (using Apache-Commons classes located in lib/commons-lang3-3.4.jar)   
  Java classes can be compiled with "build.xml" ant file or with "compile.sh|bat"
   
- $generator to launch a child generator process from a template file
   
- literal values with $values, $fn.buildValues, etc
   
- standard objects usage (string, map, etc )


