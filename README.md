# llp-jooq_codeGenerationTool

- This project for jooq Tables and Records object creation.
- In joust we are using jooq-3.4.4 so jooq query require to create tables and records object based on this version.

## Database and Location Setup
- Open joust.xml and setup jdbc configurations.
- Replace {LOCATION} with your target location (Location at you want to generate code)
  - Like, /home/llp/Joust/src/main/java 
  
## How to generate code in linux and window machine.
- ## For Linux use this command line: 
      java -classpath jooq-3.4.4.jar:jooq-meta-3.4.4.jar:jooq-codegen-3.4.4.jar:mysql-connector-java-5.1.26.jar:. org.jooq.util.GenerationTool joust.xml
 
- ## For Windows use this command line: 
      java -classpath jooq-3.4.4.jar;jooq-meta-3.4.4.jar;jooq-codegen-3.4.4.jar;mysql-connector-java-5.1.26.jar;. org.jooq.util.GenerationTool joust.xml 
