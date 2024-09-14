# COMS 4156: Advanced Software Engineering Individual Assignment 1

## NAME: AJIT SHARMA KASTURI
## UNI: ak5055

* I used the following plugin for pmd static bug analyzer.
```declarative
<plugin>
    <groupId>org.apache.maven.plugins</groupId>
    <artifactId>maven-pmd-plugin</artifactId>
    <version>3.25.0</version>
    <configuration>
        <rulesets>
            <ruleset>/rulesets/java/maven-pmd-plugin-default.xml</ruleset>
        </rulesets>
    </configuration>
</plugin>
```
* As shown above, I used the maven-pmd-plugin-default.xml ruleset for static bug finder and ran "mvn pmd::check" command to detect those (if any).
* I made sure to fix all the styling issues raised by "mvn checkstyle:check".
* I documented all the bugs in bugs.txt file.
* I did around 97% of branch coverage while writing test cases.
* I used Mockito as required while writing unit tests especially in cases we need to mimic the file database object.
* I made sure all the testcases worked as expected (mvn test).