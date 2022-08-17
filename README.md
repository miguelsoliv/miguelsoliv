<a href="https://www.linkedin.com/in/miguelsoliv">
  <img alt="Miguel Oliveira's LinkedIn" src="https://img.shields.io/badge/-LinkedIn-222222?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/miguelsoliv">
</a>
<a href="https://www.facebook.com/miguelosoares">
  <img alt="Miguel Oliveira's Facebook" src="https://img.shields.io/badge/-Facebook-222222?style=flat-square&logo=Facebook&logoColor=white&link=https://www.facebook.com/miguelosoares">
</a>
<a href="mailto:miguelosoares1@hotmail.com">
  <img alt="Miguel Oliveira's Email" src="https://img.shields.io/badge/Email-222222?style=flat-square&logo=gmail&logoColor=white">
</a>

<h2>Hi there <img src="https://github.com/miguelsoliv/miguelsoliv/blob/master/.github/hi.gif" width=20 /> Hope you are doing great today!</h2>

```ts
interface ICharacterSheet {
  name: string;
  class: string[];
  level: number;
  languages: Array<{ name: string; proficiency: 1 | 2 | 3 | 4 | 5 }>;
  traits: Array<{ name: string; greatness: 1 | 2 | 3 | 4 | 5 }>;
  statsSkills: {
    strength: string[];
    constitution: string[];
    dexterity: string[];
    intelligence: string[];
    charisma: string[];
  };
  equipment: string[];
}

export default (): ICharacterSheet => ({
  name: 'Miguel Soares de Oliveira',
  class: ['Back End Developer', 'Mobile Developer'],
  level: 26,
  languages: [
    { name: 'portuguese', proficiency: 5 },
    { name: 'english', proficiency: 3 },
  ],
  traits: [
    { name: 'nodejs', greatness: 5 },
    { name: 'expressjs', greatness: 5 },
    { name: 'git', greatness: 5 },
    { name: 'react-native', greatness: 4 },
    { name: 'uml', greatness: 4 },
    { name: 'java', greatness: 2 },
    { name: 'typescript', greatness: 5 },
    { name: 'css', greatness: 4 },
    { name: 'scrum/kanban', greatness: 5 },
    { name: 'sql', greatness: 2 },
    { name: 'html', greatness: 3 },
    { name: 'javascript', greatness: 5 },
    { name: 'docker', greatness: 2 },
    { name: 'jest', greatness: 5 },
    { name: 'supertest', greatness: 4 },
  ],
  statsSkills: {
    strength: ['🏋️‍♂️'],
    constitution: ['🏊‍♂️', '🚴‍♂️', '🏃‍'],
    dexterity: ['🤾‍♂️', '🎮'],
    intelligence: ['📚', '👓'],
    charisma: ['😎', '😁', '🤝'],
  },
  equipment: ['☕', '🍫', '🍕', '🧉'],
});
```
