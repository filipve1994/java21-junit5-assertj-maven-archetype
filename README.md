# Java 21 + JUnit 5 + AssertJ: Quick Start Maven Archetype

Maven archetype to create a quick start project configured for Java 21, Junit 5 and AssertJ.

## Install archetype in local repository

Once you have cloned the repository locally. Just run the maven command below to install the archetype.

``` shell
mvn clean install
```

## Example using the archetype

When the archetype has been installed locally you can create a project using the command below. Just replace the parameter values with the actual values you want to use.

``` shell
 mvn archetype:generate -DarchetypeGroupId=com.wtech.archetypes \
                        -DarchetypeArtifactId=java21-junit5-assertj-maven-archetype \
                        -DarchetypeVersion=1.0.0-SNAPSHOT \
                        -DgroupId=com.wtech.a-test-project \
                        -DartifactId=a-test-project \
                        -Dversion=1.0.0-SNAPSHOT \
                        -DinteractiveMode=false
```

## References

* [Maven](https://maven.apache.org)
* [Maven Archetype](https://maven.apache.org/guides/introduction/introduction-to-archetypes.html)
* [JUnit 5](https://junit.org/junit5/)
* [AssertJ](https://assertj.github.io/doc/)
* [Hamcrest](http://hamcrest.org/JavaHamcrest/)

## Author

* Wallace Espindola, Sr. Software Engineer / Java & Python Dev
* E-mail: wallace.espindola@gmail.com
* LinkedIn: https://www.linkedin.com/in/wallaceespindola/
* Website: https://wtechitsolutions.com/

## License

* This project is released under the Apache 2.0 License. See the [LICENSE](https://github.com/wallaceespindola/java21-junit5-assertj-maven-archetype/blob/master/LICENSE) file for details.
* Copyright © 2024 [Wallace Espindola](https://github.com/wallaceespindola/).

