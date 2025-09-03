<div align="center" style="line-height: 0; margin: 0; padding: 0;">
    <img src="https://github.com/user-attachments/assets/7f11b310-200c-4dd6-8021-2fd92525105b" width="1247" height="1080" alt="santiadog" style="display: block; margin: 0; padding: 0;" />
    <img src="https://github.com/user-attachments/assets/74677e8d-777f-416d-acd2-9e67a09b3641" style="display: block; margin: 0; padding: 0;" />
</div>

## About me

I'm **Santiago**, a passionate (and slightly psycho) tech enthusiast who loves diving headfirst into everything that involves **technology and code**.

```hx
class SantiagoProfile {
    public var pronouns:Array<String> = ["He", "Him"];
    public var code:Array<String> = ["Haxe", "Python", "Lua", "JavaScript", "HaxeFlixel", "OpenFL", "HTML"];
    public var askMeAbout:Array<String> = ["game dev", "UI/UX (i'm not good at ts)"];

    public var links:Map<String, String> = [
        "Twitter" => "https://x.com/santideveloper",
        "Youtube" => "https://youtube.com/@santiagocalebe",
        "Github" => "https://github.com/santiagocalebe",
        "Website" => "https://santiagocalebe.github.io/"
    ].map(e -> e);

    public var currentFocus:String = "Leading games and general development";

    public function new() {
        FlxG.log.trace("=== Santiago Profile ===");
        FlxG.log.trace("Pronouns: " + pronouns.join(", "));
        FlxG.log.trace("Languages & Tools: " + code.join(", "));
        FlxG.log.trace("Ask Me About: " + askMeAbout.join(", "));
        FlxG.log.trace("Current Focus: " + currentFocus);

        for (link in links.keys()) {
            FlxG.log.trace(link + ": " + links.get(link));
        }
    }
}
```

<div align="center">

[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white&color=000000)](https://x.com/santideveloper) [![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@santiagocalebe)  [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/santiagocalebe)  [![Website](https://img.shields.io/badge/Website-4B0082?style=for-the-badge&logo=internet-explorer&logoColor=white)](https://santiagocalebe.github.io/)

</div>
