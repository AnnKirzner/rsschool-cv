# Anna Kirzner

## Contact info
* 📞 **phone:** +375(29)679-29-18
* 📧 **email:** anna.kirzner@gmail.com
---
## Briefly about myself
I am a driven individual with a passion for learning and expanding my knowledge base. My primary goal is to acquire new information and insights in various fields, making me a curious and inquisitive individual.

My strengths lie in my diligent and responsible work ethic, my attention to detail and strive for perfection, as well as my strong communication and responsiveness skills. These qualities make me a valuable team player and an asset to any project.

In terms of work experience, I currently work in the development of thermal-mechanical components for boiler design. My experience in this field has allowed me to gain valuable insights into the world of engineering and design.

Overall, my unwavering commitment to learning and improving myself, combined with my strong work ethic and valuable skills, make me a well-rounded and capable individual in both my professional and personal life.

---
## Skills and Proficiency
* C# (WPF)
* HTML
* SQL
* C
---
## Code exmaple

Function `GetTMaxFromClimateId` retrieves temperature from `climate` that is stored in given `heatsource`.  

```C#

public static int GetTMaxFromClimateId(Heatsource heatsource) 
{ 
    int tMax;
    int climateId = 0;
    using (EntityContext db = new EntityContext())
    {
        var calcHeatsources = db.Heatsources.Where(h => h.HeatsourceName == heatsource.HeatsourceName);
        foreach (Heatsource h in calcHeatsources) 
         climateId = h.ClimateId;
        var climate = GetClimatesById(climateId);
        tMax = climate.TWinter;
    }
    return tMax;
}
```
---
## Working experience
I don't have practical experience that comes with commercial work. Despite this, I am committed to investing time and effort into learning and developing my programming skills through personal projects, online courses, and other resources available to me.

---
## Education
1. BNTU (thermal power engineer)
2. Retraining in BSUIR (software engineer)
---
