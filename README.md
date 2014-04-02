PwdGen
======

C# pronounceable password generator

Install with NuGet:
> PM> Install-Package PwdGen 

Not my work. Originally downloaded from http://www.sloppycode.net/code-snippets/cs/password-generator.aspx

Based on Java code from http://www.multicians.org/thvv/gpw.html

Code example:
```C#
var ppg = new PwdGen.PronounceablePasswordGenerator();
var passwords = ppg.Generate(PasswordCount: 5, PasswordLength: 8);
foreach (var password in passwords)
{
  Console.WriteLine(password);
}
```

Some example generated passwords:
* harrombe
* conflain
* gensigra
* embakert
* peraticu

