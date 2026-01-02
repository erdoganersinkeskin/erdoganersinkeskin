<!-- ⚡ 'Simplicity is the ultimate sophistication'-->

<p align="center">
  <img src="assets/me_in_rivendell_animation.gif" alt="Erdogan Ersin Keskin" size="80%"/>
</p>

<!-- About Me Section with Gradient Border -->

<div align-items="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900" />
</div>

```csharp
public class AboutMe
{
    public string CreatorName { get; } = "Erdogan Ersin Keskin";
    public string CreatorTitle { get; } = "Electronics and Communication Engineer | .NET Enthusiast | Content Creator";
    public string CreatorOneLineIntroducer { get; } = "An engineer who tries to build meaningful things as a solo";
    public string CreatorLocation { get; } = "Rivendell, Middle-earth"; // in my mind :)
    public string CreatorFocus { get; } = "Human-centric tools for good | Sustainability";
    public string CreatorApproach { get; } = "Building robust and useful things that do not die";
    
    public List<string> CreatorInventory { get; } = new List<string> 
    { 
        "C#", 
        ".NET", 
        "Modern technologies when needed"
    };

    internal (string Name, string Definition, List<string> Tools) GetCurrentProject()
    {
        var projectName = "Project: A4B2D7";
        var projectDefinition = string.Empty;
        var projectTools = new List<string> { "VS Code", "GitHub Copilot", "Visual Studio" };

        return (projectName, projectDefinition, projectTools);
    }

    internal Dictionary<string, string> GetNearFutureAims()
    {
        return new Dictionary<string, string>
        {
            { "🤖 MCP Experience", "Creating useful MCPs for tiny daily problems" },
            { "☁️ Life-cycle", "Longevity-based tools development" },
            { "⚡ Launch", "First launch with B2C concept" }
        };
    }
}
```

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=erdoganersinkeskin&color=orange&style=flat&label=Profile+Views" alt="Profile Views" />
</p>

