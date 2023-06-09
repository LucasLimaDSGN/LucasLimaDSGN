```java
package LucasLima;

import java.util.ArrayList;
import java.util.List;

public class About extends Me {
    public List<String> getCurrentWorkplace() {
        List<String> workplace = new ArrayList<>();
        workplace.add("Looking for my first job in Tech");
        workplace.add("Junior");
        return workplace;
    }

    public List<Class<?>> getDailyKnowledge() {
        List<Class<?>> dailyKnowledge = new ArrayList<>();
        dailyKnowledge.add(Java.class);
        dailyKnowledge.add(Javascript.class);
        dailyKnowledge.add(GoLang.class);
        dailyKnowledge.add(Python.class);
        dailyKnowledge.add(React.class);
        dailyKnowledge.add(Angular.class);
        dailyKnowledge.add(Bootstrap.class);
        dailyKnowledge.add(Sass.class);
        dailyKnowledge.add(Aws.class);
        return dailyKnowledge;
    }

    public String getFutureGoal() {
        return "To be an awesome TechLead in 8 years.";
    }
}
```
