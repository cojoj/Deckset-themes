Theme: Business Class
text: Roboto, #53585F
text-strong: Roboto Bold, #EE783F
text-emphasis: Roboto Light Italic
header: Roboto, #53585F
header-strong: Roboto Strong,#EE783F
header-emphasis: Reklame Script, #53585F  
code: Fira Code Medium, #EE783F, #8B3D90, #2E59A2, #DF393F, #1EA8D9
background-color: #FFFFFF  
table-separator-color: #DDDEE0
footer: **#mobiconf2017** MOBICONF.ORG **|** 5-6 OCTOBER  2017
slidenumbers: true

# **Title text** </br> Subtitle

[.slidenumbers: false]
![original](assets/title_page.png)

---
# Hi, I'm **Mateusz** 👋 <br/><br/>
## ![](assets/twitter.png) [@cojoj](https://twitter.com/cojoj)
## ![](assets/website.png) https://example.com 
## ![](assets/email.png) example@example.com

![original](assets/background.png)

---
# Roboto **Roboto** _Test_

We love our users, _we really do_! **Sometimes**, when we get really excited about something, we might forget to check whether what we do actually is for them or for us.

![original](assets/background.png)

---
# Code snippet

```swift
import UIKit

protocol StoryboardIdentifiable {
    static var storyboardIdentifier: String { get }
}

extension StoryboardIdentifiable where Self: UIViewController {
    static var storyboardIdentifier: String {
        return String(describing: self)
    }

    func testFunction() -> String? {
        // We have ligatures here 🔥
        a != b
    }
}
```

![original](assets/background.png)

---
# Devices

![original right 80%](assets/iphone.png)

You can also use **device templates**!

+ `assets/iphone.png`
+ `assets/samsung.png`
+ `assets/nexus.png`

---
# Maybe **table**?

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

![original](assets/background.png)

---
# Let's go, list!

1. **Something**
1. Else
    1. Something
    1. Something
        1.1 _Something_
    1. Something

![original](assets/background.png)

---
[.slidenumbers: false]
![original](assets/qa.png)

---
[.slidenumbers: false]
![original](assets/thank_you.png)