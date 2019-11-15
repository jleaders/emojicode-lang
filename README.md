# emojicode-lang
### _The storage & transmission file format of choice for Millenials_

* Smaller than a json or yaml file, great for small transfers
* Save on bytes
* More fun
* Great for texting your friends, as well as file storage

## Example

Example JSON
```json
    {  
        "employees": [{  
            "name":       "Jonny",   
            "salary":      56000,   
            "married":    true  
        },
        {  
            "name":       "Wilma",   
            "salary":      57000,   
            "married":    false  
        }]
    }  
```

Example YML
```yml
employees:
    - name: Jonny
      salary: 56000
      married: true
    - name: Wilma
      salary: 57000   
      married: false 
```

Example EmojiCode
```
👱️
   🆎️ Jonny
   💲️ 56000
   💑️ ✔️
   
   🆎️ Wilma
   💲️ 5700
   💑️ ✖️
```
_(Reminder: On windows, you can type emoji's with Win+Period, and Ubuntu via right-click in Gedit)_


### Calling for help writing parsers in all languages



# Why Emojis?

_Code Like I'm 5_

The goal of emoji Code is such that the user would be able to determine what the code did and was for without having any prior technical or coding knowledge. Therefore the user could theoretically change the code to fit their needs.

EmojiCode sits in the space between the WYSIWYG editors of old, and modern markup languages.
With the advent of emoji, hieroglyphic-like pictographs can commute complex knowledge in the space of a character, this solves two problems coming to languages:
 * **The Standards Problem**: What is an image? Is it a jpg, a png, a gif? Emoji code solves this by being so high level, it doesn't care. It assumes the user doesnt care either, so in a sense it is a DSL (domain specific language) for the user. So this is an image 📊 and this is a video: 📺 and this is a document: 📄 and the VM will figure it out
 * **The Keyword problem**: should I type `foreach`, `for`, `for x in y`, or what? Every languages uses multiple particles or spellings. Emoji code doesn't. Each emoji is the one and _only_ standard. **You cannot mispell an emoji**! Also emojis are international**.
 
 # Example Applied Usage
 Example Web Form (Actual Code):
 
 ```
 🔤 User Name
 🔒 Enter Password here
 📊 Click to upload Profile Picture
 🔠 User Bio
 ```
 
 The output is 4 field form with a the following:
 * Single line text field
 * Password field
 * Browse dialog for picture uploading
 * Multiline Description field
 
 # Proposed Ecosystem
 
 Obviously above is a DSL (domain specific language) use-case of an emojicode schema, but in the long run, we could have interpretors for a variety of use cases.
 To generalize this for various domains, a proposed pipeline for emoji schema DSL's would be:
 
 Emoji code-> Transpiler Marketplace -> Transpiler of Choice -> Output Language (Python/PHP/ObjC/C#/NodeJS/JS/Java/Haxe/Lua) + API of Choice (ReactJS,Customintelligence,Laravel,Kivy,Qt) + Storage Engine of Choice (filesystem/Amazon cloud/mysql/ssh/mongoDB/JSON/Yaml)
 `emojicode2php+mysql+customintelligence -c` will compile `*.emoji` files to PHP for example, with a mysql storage sengine, and the CustomIntelligence API.
 
 Just pick your:
 * Language
 * Storage Engine
 * API
 
 One existing framework already internally uses EmojiCode, and it works to create web forms! [The Verb FullEnd framework](https://jonathanleaders.com/portfolio/verb)
 
 But in the long run, we'd could create a transpiler marketplace that people could offer their own Domain Specific transpilers for.
