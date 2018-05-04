# LiveTemplates

Live Templates for Android Studio in the form of a settings.jar file.

To use these settings follow the instructions provided by JetBrains [here](https://www.jetbrains.com/help/idea/sharing-live-templates.html)

## What's Inside
JUnit test template written in kotlin.

```Kotlin

@Test
 fun `given $CONDITION$ return $OUTPUT$`() {
        // Arrange
        val input = $INPUT$
        val expectedOutput = $EXPECTED$

        // Act
        val actualOutput = $ACTUAL$

        // Assert
        assertTrueWithMessage(input = input,
                expectedOutput = expectedOutput,
                actualOutput = actualOutput)
 }

```
