<h2 align="center">About Me</h2>

### Top languages
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Koen-mods&layout=compact&theme=merko)

### github stats
<img src="https://github-readme-stats.vercel.app/api?username=Koen-mods&show_icons=true&theme=merko&count_private=true" alt="Moose1301" />

```ts
type ContactInfo = [string, string];
type LifeInfo = [string[], string[]];
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
        expert: ["python", "js", "html", "processing", "css"],
        intermediate: ["arduino", "SQL", "java", "c", "lua", "rust"],
        learning: ["C++", "assembly"]
      };

      const specialties = ["full-stack developement", "ai", "minecraft modding"];
      const ide = ["vscode", "intellij", "windows notepad", "pycharm", "processing 4", "arduino IDE", "sublime text"];

      return { langs, specialties, ide };
    }
  }
}
