# play-with-null-away

This is a playground to play with [NullAway](https://github.com/uber/NullAway). NullAway is an annotation preprocessor for JavaC to reduce NPEs in your code.

## current state

It is not working with Maven on JDK 9 to 13. There are mentions it working with JDK 11.
See [this null away issue](https://github.com/uber/NullAway/issues/259) to track issue.

There is apparently a [project](https://github.com/otr4j/otr4j/blob/fd42a4e73ed52d5baf7ae4f7850b6c876a1702ce/pom.xml) which got it running with JDK 9.
