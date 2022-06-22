Syntax highlighting
-----

Syntax Highlighting is implemented using [**prism**](https://prismjs.com/). Languages are autoloaded, so there is no need to modify **index.html**.

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
