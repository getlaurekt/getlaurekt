```ts
type Role = "Front-End" | "Back-End" | "Full-Stack";
type Languages = | "Typescript" | "Javascript" | "C#" | "C++" | "Java" | "Python" | "Ruby" | "PHP" | "Go" | "Rust" | "Swift" | "Kotlin" | "Dart";
type Styling = "Styled Components" | "CSS" | "SASS" | "LESS" | "Tailwind";
type UILibraries = | "Bootstrap" | "Material UI" | "Tailwind UI" | "Bulma" | "Materialize" | "Foundation" | "Semantic UI";
type Communication = "English" | "Polish";
type Frameworks = "React" | "Vue" | "Angular";
type Editors = "Visual Studio Code" | "Atom" | "Sublime Text" | "WebStorm";
type Tools = | "Photoshop" | "Figma" | "Adobe XD" | "Sketch" | "Bootstrap Studio" | "Git" | "GitHub" | "GitHub Desktop";

const languages: Languages[] = ["Typescript", "Javascript"];
const styling: Styling[] = ["Styled Components", "CSS", "SASS", "Tailwind"];
const uiLibraries: UILibraries[] = ["Bootstrap", "Material UI"];
const communication: Communication[] = ["English", "Polish"];
const frameworks: Frameworks[] = ["React", "Vue"];
const tools: Tools[] = ["Photoshop", "Figma", "Bootstrap Studio", "Git", "GitHub", "GitHub Desktop"];

interface Person {
  nick: string;
  role: Role;
  languages: Languages[] | Languages;
  styling: Styling[] | Styling;
  communication: Communication[] | Communication;
  frameworks: Frameworks[] | Frameworks;
  editor: Editors[] | Editors;
  tools: Tools[] | Tools;
}

const person: Person = {
  nick: "Muszkowy Potworek",
  role: "Front-End",
  languages: languages,
  styling: styling,
  communication: communication,
  frameworks: frameworks,
  editor: "Visual Studio Code",
  tools: tools,
};
```
