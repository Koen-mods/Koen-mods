<h2 align="center">About Me</h2>

### Top languages
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Koen-mods&layout=compact&theme=merko)

### github stats
<img src="https://github-readme-stats.vercel.app/api?username=Koen-mods&show_icons=true&theme=merko&count_private=true" alt="stats" />

```ts
type ContactInfo = string;
type LifeInfo = [string[], string];
type CodingSkills = {
  langs: {
    expert: string[];
    intermediate: string[];
    learning: string[];
  };
  specialties: string[];
  ide: string[];
};

class Koen {
  class Attributes extends Koen {
    get contact(): ContactInfo {
      const email = "koenesmiley@gmail.com";
      return email;
    }

    get life(): LifeInfo {
      const langs = ["Dutch", "English"];
      const country = "Netherlands";
      return [langs, country];
    }

    get coding(): CodingSkills {
      const langs = {
        expert: ["python", "js", "html", "processing", "css", "C"],
        intermediate: ["arduino", "SQL", "java", "C++", "lua", "rust"],
        learning: ["assembly"]
      };

      const specialties = ["full-stack developement", "ai", "minecraft modding", "language design", "OS developement"];
      const ide = ["vscode", "intellij", "windows notepad", "pycharm", "processing 4", "arduino IDE", "sublime text", "WebStorm", "CLion"];

      return { langs, specialties, ide };
    }
  }
}
