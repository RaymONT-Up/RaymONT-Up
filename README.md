```TypeScript
interface IUser {...}
const Raymont: IUser = {
  name: 'Raymont',
  role: 'Frontend React Developer',
  dateOfCreation: '17.02.2006', // Date of Birth
  dateOfDeletion: null, // Date of death
  technologies: {
    programmingLanguages: ['JavaScript', 'TypeScript'],
    frontend: ['HTML','CSS','SCSS', 'React', 'Redux (Toolkit)', 'Axios', 'Firebase','i18n'],
    developmentTools: {
      buildTools: ['Webpack','Gulp'],
      testing: ['Jest', 'React Testing Library', 'Loki', 'Storybook']
      linting: ['Stylelint', 'ESLint', 'Prettier'],
      versionControl: ['Git'],
      packageManagers: ['npm','yarn']
    };
    designTools: ['Figma', 'Adobe Photoshop', 'Adobe Illustrator', 'Photopea'],
    methodologies: ['BEM', 'DRY', 'Feature-Sliced-Design'],
    packageManagers: ['npm'],
  },
  languages: [
    { name: 'Russian', level: 'Native' },
    { name: 'English', level: 'B1'},
    { name: 'Japanese', level: 'Wakarimasen'},
    { name: 'French', level: 'Bonjour'},
  ],
  location: {
    current: 'Russia, Volgograd',
    description: 'Open for relocation'
  }
};
```