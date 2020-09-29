# Transformation Advisor And OL Application Stack Intgration

## Inner Loop For Binary Applications

### Java 8

A custom devfile that uses an Open Liberty image using Java 8 is required. 

Run the following commands:

1. Create the custom component:

`odo create odota --devfile ./devfile.yaml`

2. Push the created component:

`odo push`

3. Access the resorts application: 

`odo url list`
```
NAME     STATE      URL                                                                 PORT     SECURE     KIND
ep1      Pushed     http://ep1-odota-service-binding-demo.apps.emez.os.fyre.ibm.com     9080     false      route
```

Use this URL: http://ep1-odota-service-binding-demo.apps.emez.os.fyre.ibm.com/resorts


### Java 11:

Run the following commands:

1. Create a new java-openliberty component:

`odo create java-openliberty odota`

2. Push the created component:

`odo push`

3. Access the resorts application:

`odo url list`
```
NAME     STATE      URL                                                                 PORT     SECURE     KIND
ep1      Pushed     http://ep1-odota-service-binding-demo.apps.emez.os.fyre.ibm.com     9080     false      route
```

Use this URL: http://ep1-odota-service-binding-demo.apps.emez.os.fyre.ibm.com/resorts


## Outter Loop For Binary Applications:

In progress ...