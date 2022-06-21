About this template
-----

This **Example Page** shows different features available in this this template.

Emoji Support
-----

This template works :100: with emojis!

Tabs
-----

You can add Tabs to your documentation. This is very usefull when showing how to do something in different programming languages.

```markdown
    <!-- tabs:start -->
    #### **Swift**

    ```swift
    struct Person {
        let firstName: String
        let lastName: String
    }
    ``` 

    #### **Objective C**

    ```objc
    @interface Person : NSObject
    @property (readonly) NSString *firstName;
    @property (readonly) NSString *lastName;
    @end
    ```

    #### **Kotlin**

    ```kotlin
    data class Person(val firstName: String, val lastName: String)
    ```

    <!-- tabs:end -->
```

renders as follows:

<!-- tabs:start -->
#### **Swift**

```swift
struct Person {
    let firstName: String
    let lastName: String
}
``` 

#### **Objective C**

```objc
@interface Person : NSObject
@property (readonly) NSString *firstName;
@property (readonly) NSString *lastName;
@end
```

#### **Kotlin**

```kotlin
data class Person(val firstName: String, val lastName: String)
```

<!-- tabs:end -->

Images with Zoom
-----

You can paste images and enoy a nice zoom in/out automatically. Mouse over, or tap, over the following image.

![Milky way image](big_image.jpeg)

JSON and XML
-----

Render JSON and XML using standard Markdown.

#### JSON
```json
{
    "glossary": {
        "title": "example glossary",
		"GlossDiv": {
            "title": "S",
			"GlossList": {
                "GlossEntry": {
                    "ID": "SGML",
					"SortAs": "SGML",
					"GlossTerm": "Standard Generalized Markup Language",
					"Acronym": "SGML",
					"Abbrev": "ISO 8879:1986",
					"GlossDef": {
                        "para": "A meta-markup language, used to create markup languages such as DocBook.",
						"GlossSeeAlso": ["GML", "XML"]
                    },
					"GlossSee": "markup"
                }
            }
        }
    }
}
```

#### XML
```xml
<note>
<to>Tove</to>
<from>Jani</from>
<heading>Reminder</heading>
<body>Don't forget me this weekend!</body>
</note>
```