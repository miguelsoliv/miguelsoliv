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
enum Language {
  ENGLISH, PORTUGUESE,
};
enum Proficiency {
  BASIC, INTERMEDIATE, ADVANCED, PROFICIENT, FLUENT,
};
enum Greatness {
  NOVICE, APPRENTICE, VETERAN, MASTER, GRANDMASTER,
};

export const generateMyCharacterSheet = () => ({
  name: 'Miguel Soares de Oliveira',
  class: ['Full Stack Developer', 'Mobile Developer'],
  level: new Date().getFullYear() - 1996,
  race: [
    { name: Language.PORTUGUESE, knowledge: Proficiency.FLUENT },
    { name: Language.ENGLISH, knowledge: Proficiency.ADVANCED },
  ],
  skills: [
    { name: 'Scrum/Kanban/Scrumban', greatness: Greatness.GRANDMASTER },
    { name: 'JavaScript/TypeScript', greatness: Greatness.GRANDMASTER },
    {
      name: 'Node.js',
      greatness: Greatness.GRANDMASTER,
      passives: [
        { name: 'AdonisJS', greatness: Greatness.MASTER },
        { name: 'Express.js', greatness: Greatness.GRANDMASTER },
        { name: 'Fastify', greatness: Greatness.MASTER },
        { name: 'Mongoose', greatness: Greatness.MASTER },
        { name: 'Nest.js', greatness: Greatness.GRANDMASTER },
        { name: 'Prisma', greatness: Greatness.VETERAN },
        { name: 'TypeORM', greatness: Greatness.GRANDMASTER },
      ],
    },
    {
      name: 'React',
      greatness: Greatness.MASTER,
      passives: [
        { name: 'Next.js', greatness: Greatness.VETERAN },
        { name: 'Redux/Zustand', greatness: Greatness.VETERAN },
      ],
    },
    { name: 'React Native', greatness: Greatness.VETERAN },
    { name: 'HTML', greatness: Greatness.VETERAN },
    {
      name: 'CSS',
      greatness: Greatness.MASTER,
      passives: [
        { name: 'CSS-in-JS', greatness: Greatness.MASTER },
        { name: 'Panda CSS', greatness: Greatness.APPRENTICE },
        { name: 'Tailwind CSS', greatness: Greatness.MASTER },
      ],
    },
    {
      name: 'Git',
      greatness: Greatness.GRANDMASTER,
      passives: [
        { name: 'Gitflow', greatness: Greatness.GRANDMASTER },
        { name: 'Trunk-Based Development', greatness: Greatness.GRANDMASTER },
      ],
    },
    {
      name: 'SQL',
      greatness: Greatness.VETERAN,
      passives: [
        { name: 'MySQL', greatness: Greatness.VETERAN },
        { name: 'PostgreSQL', greatness: Greatness.VETERAN },
      ],
    },
    {
      name: 'NoSQL',
      greatness: Greatness.GRANDMASTER,
      passives: [
        { name: 'MongoDB', greatness: Greatness.GRANDMASTER },
        { name: 'Redis', greatness: Greatness.GRANDMASTER },
      ],
    },
    {
      name: 'Event-Driven Architecture',
      greatness: Greatness.GRANDMASTER,
      passives: [
        { name: 'BullMQ', greatness: Greatness.GRANDMASTER },
        { name: 'Kafka', greatness: Greatness.GRANDMASTER },
        { name: 'RabbitMQ', greatness: Greatness.GRANDMASTER },
      ],
    },
    {
      name: 'Unit/Integration Tests',
      greatness: Greatness.GRANDMASTER,
      passives: [
        { name: 'Jest', greatness: Greatness.GRANDMASTER },
        { name: 'Supertest', greatness: Greatness.GRANDMASTER },
        { name: 'TS Mockito', greatness: Greatness.VETERAN },
      ],
    },
    { name: 'AWS/GCP', greatness: Greatness.VETERAN },
    { name: 'Swagger', greatness: Greatness.GRANDMASTER },
    { name: 'Docker', greatness: Greatness.APPRENTICE },
  ],
  stats: {
    strength: ['🏋️‍♂️'],
    constitution: ['🏊‍♂️', '🚴‍♂️', '🏃‍'],
    dexterity: ['🤾‍♂️', '🎮'],
    intelligence: ['📚', '👓'],
    charisma: ['😎', '😁', '🤝'],
  },
  equipment: ['☕', '🍫', '🍕', '🧉'],
});
```
