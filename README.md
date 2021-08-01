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

```typescript
interface IStat {
  description: string;
  skills: string[];
}

interface ICharacterSheet {
  name: string;
  class: string | string[];
  level: number;
  languages: Array<{ name: string; proficiency: 1 | 2 | 3 | 4 | 5 }>;
  traits: Array<{ name: string; greatness: 1 | 2 | 3 | 4 | 5 }>;
  stats: {
    strength: IStat;
    constitution: IStat;
    dexterity: IStat;
    intelligence: IStat;
    wisdom: IStat;
    charisma: IStat;
  };
  equipment: Array<{ icon: string; amount: number }>;
}

export default (): ICharacterSheet => ({
  name: 'Miguel Soares de Oliveira',
  class: ['Back End Developer', 'Mobile Developer'],
  level: 25,
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
    { name: 'c#', greatness: 4 },
    { name: 'css', greatness: 3 },
    { name: 'scrum', greatness: 4 },
    { name: 'sql', greatness: 4 },
    { name: 'html', greatness: 2 },
    { name: 'javascript', greatness: 5 },
    { name: 'docker', greatness: 2 },
    { name: 'jest', greatness: 3 },
  ],
  stats: {
    strength: {
      description: '[💪]: Measuring physical power and carrying capacity',
      skills: ['🏋️‍♂️'],
    },
    constitution: {
      description: '[🏃‍♂️]: Measuring endurance, stamina and good health',
      skills: ['🏊‍♂️', '🚴‍♂️'],
    },
    dexterity: {
      description: '[🤹]: Measuring agility, balance, coordination and reflexes',
      skills: ['🤾‍♂️', '🎮'],
    },
    intelligence: {
      description: '[🤓]: Measuring deductive reasoning, knowledge, memory, logic and rationality',
      skills: ['📚'],
    },
    wisdom: {
      description: '[💭]: Measuring self-awareness, common sense, restraint, perception and insight',
      skills: ['🧩'],
    },
    charisma: {
      description: '[😎]: Measuring force of personality, persuasiveness, leadership and successful planning',
      skills: ['🤝'],
    },
  },
  equipment: [
    { icon: '☕', amount: parseInt('∞', 10) },
    { icon: '🍫', amount: 10 },
    { icon: '🍕', amount: 3 },
  ],
});
```
