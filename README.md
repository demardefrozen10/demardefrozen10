```cs
public class AboutMe
{
    private readonly string school;
    private readonly string major;
    private readonly string[] experience;
    private readonly string[] languages;

    public AboutMe(string school, string major, string[] experience, string[] languages)
    {
        this.school = school;
        this.major = major;
        this.experience = experience;
        this.languages = languages;
    }

    public static void Main(string[] args)
    {
        string school = "York University Class of 2027";

        string major = "Computer Science (Software Development Stream)";

        string[] experience = ["Data Engineer Intern at RBC", "Software Developer Intern at Dayforce"];

        string[] languages = ["C#", "JavaScript", "TypeScript", "Java", "Python"];

        AboutMe myself = new AboutMe(school, major, experience, languages);
    }
}

```
