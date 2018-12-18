# emojicode-lang
Worlds First Userspace Language

_Code Like I'm 5_

The goal of emoji Code is such that the user would be able to determine what the code did and was for without having any prior technical or coding knowledge. Therefore the user could theoretically change the code to fit their needs.

EmojiCode sits in the space between the WYSIWYG editors of old, and modern markup languages.
With the advent of emoji, hieroglyphic-like pictographs can commute complex knowledge in the space of a character, this solves two problems coming to languages:
 * **The Standards Problem**: What is an image? Is it a jpg, a png, a gif? Emoji code solves this by being so high level, it doesn't care. It assumes the user doesnt care either, so in a since it is a DSL (domain specific language) for the user. So this is an image 📊 and this is a video: 📺 and this is a document: 📄 and the VM will figure it out
 * **The Keyword problem**: is it for each, for, for in, for as, or what? Every languages uses multiple particles or spellings. Emoji code doesn't. Each emoji is the one nd aonly standard. You cannot mispell an emoji! Also emojis are international.
 
 Example:
 
 🔠 This is a multiple text field
 
 🔤 this is a single line text field
 
 📊 this represents an image
 
 🔒 this represents a password 
 
 How it works:
 
 Emoji code-> Transpiler Marketplace -> Transpiler of Choice -> Output Language (Python/PHP/ObjC/C#/NodeJS/JS/Java/Haxe/Lua) + API of Choice (ReactJS,Customintelligence,Laravel,Kivy,Qt) + Storage Engine of Choice (filesystem/Amazon cloud/mysql/ssh/mongoDB/JSON/Yaml)
 `emojicode2php+mysql+customintelligence -c` will compile `*.emoji` files to PHP for example, with a mysql storage sengine, and the CustomIntelligence API.
 
 Just pick your:
 * Language
 * Storage Engine
 * API
 And search on the transpiler marketplace to find one for purchase.
 
 Any developer can write a transpiler!

So at fwe have one working transpiler, contact me if you're interested in writing and selling your own!
