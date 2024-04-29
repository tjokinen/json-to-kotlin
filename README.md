# json-to-kotlin
Json to Kotlin data class converter

## Features:
* **JSON to Kotlin Conversion:** Converts JSON responses directly into Kotlin data classes.
* **Nested Structures:** Handles nested JSON structures and generates corresponding Kotlin classes.
* **@Parcelize Support:** Optionally adds the @Parcelize annotation to classes, including ": Parcelable" inheritance.
* **Comment Out "Any"** Properties: Automatically comments out properties of type "Any" when @Parcelize is enabled.
* **Copy to Clipboard:** Allows easy copying of the generated Kotlin data classes directly to the clipboard.
## How to Use:
1. Open the GitHub Pages site [tjokinen.github.io/json-to-kotlin](https://tjokinen.github.io/json-to-kotlin/).
2. Type in the main class name for the response data.
3. Paste the JSON response into the provided text area.
4. Check the "Add @Parcelize annotation" box if desired.
5. Click "Convert to Kotlin" to generate Kotlin data classes.
6. Review the output and click "Copy to Clipboard" to copy the classes directly to the clipboard.
