```cs
public class AboutMe
{
    private readonly string school;
    private readonly string major;
    private readonly string[] experience;
    private readonly string[] languages;

    public AboutMe(string school, string major, string[] experience, string[] languages, string[] favoriteTech)
    {
        this.school = school;
        this.major = major;
        this.experience = experience;
        this.languages = languages;
        this.favoriteTech = favoriteTech;
    }

    public static void Main(string[] args)
    {
        string school = "York University Class of 2027";

        string major = "Computer Science (Software Development Stream)";

        string[] experience = ["Software Developer Intern at Hootsuite", Software Developer Intern at RBC Borealis", "Software Developer Intern at Dayforce"];

        string[] languages = ["C#", "JavaScript", "TypeScript", "Java", "Python"];

        string[] favoriteTech = ["Amazon Web Services (AWS)", "React.js", "Apache Kafka", "Spring Boot", "Docker", "ASP.NET Core"];

        AboutMe myself = new AboutMe(school, major, experience, languages, favoriteTech);
    }
}

```

