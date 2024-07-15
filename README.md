## Hi, I'm Utpal Anand ! 👋

I am a research student and in my 2nd year of Integrated BS-MS (Basic Sciences) dual degree course at [IISER PUNE](https://www.iiserpune.ac.in/).
I haven't yet decided my major subject but I have interest in Physics and Biology.
I do programming/coding for integrating scientific studies to it with my own flexibility.<br>




### 🔗 Social Media Handles
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://theutpalanand.github.io/) 
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/theutpalanand)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/theutpalanand)
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://reddit.com/user/theutpalanand)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/theutpalanand)<br>
[![Pinterest](https://img.shields.io/badge/Pinterest-%23E60023.svg?style=for-the-badge&logo=Pinterest&logoColor=white)](https://in.pinterest.com/theutpalanand/)
[![Quora](https://img.shields.io/badge/Quora-%23B92B27.svg?style=for-the-badge&logo=Quora&logoColor=white)](https://quora.com/profile/TheUtpalAnand)
[![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/26378845/theutpalanand)
[![YouTube](https://img.shields.io/badge/Youtube-FF0000?style=for-the-badge&logo=YouTube&logoColor=white)](https://www.youtube.com/@theutpalanand)

---

### 🔗My Skills
```Matlab
classdef Researcher
    properties
        Name = 'Utpal Anand'
        Pronouns = ["He", "Him"]
        Role = 'Researcher & '
        Skills = {"", "Archery", "Potion Making", "Alchemy"}
        Tools = {"Matlab", "Github", "Python", "Desmos", "LateX"}
        AskMeAbout = {"Physics", "Osho", "Philosophy", "Research", "Biology"}
        DailyRoutine = struct('morning', 'Training in the enchanted forest', ...
                              'afternoon', 'Exploring ancient ruins', ...
                              'evening', 'Studying arcane texts', ...
                              'night', 'Meditation and potion brewing')
        Knowledge = struct('combat', {"Swordsmanship", "Archery", "Defense Tactics"}, ...
                           'alchemy', {"Potion Making", "Herbal Remedies", "Transmutation"}, ...
                           'magic', {"Elemental Spells", "Enchantments", "Illusions"}, ...
                           'exploration', {"Cartography", "Survival Skills", "Mystic Compass Usage"}, ...
                           'misc', {"Ancient Languages", "Magical Creatures"})
        CurrentFocus = 'Physics and Research'
        FunFact = '🔮|| Philosophy is the unreal version of Spirituality ||🔮'
    end
    
    methods
        function obj = startDay(obj)
            fprintf('Good morning! He is ready for another day of Research!\n', obj.Name);
            obj.followRoutine();
        end
        
        function followRoutine(obj)
            routineFields = fieldnames(obj.DailyRoutine);
            for i = 1:numel(routineFields)
                timeOfDay = routineFields{i};
                activity = obj.DailyRoutine.(timeOfDay);
                fprintf('In the %s, %s is usually %s.\n', timeOfDay, obj.Name, activity);
            end
        end
        
        function performSkill(obj, skill)
            if ismember(skill, obj.Skills)
                fprintf('%s expertly performs %s.\n', obj.Name, skill);
            else
                fprintf('%s doesn''t know how to %s yet.\n', obj.Name, skill);
            end
        end
    end
end

% Create an instance of Researcher
Researcher = Researcher();
Researcher.Name = 'Utpal Anand';
Researcher.Pronouns = ["He", "Him"];
Researcher.CurrentFocus = 'Mastering Physics and Research';

% Simulate a day in the life of the Researcher
Researcher.startDay();
Researcher.performSkill('Start with Science and Research');

% Enchant the world with love (this function would need to be implemented)
enchantWorldWithLove();
```
