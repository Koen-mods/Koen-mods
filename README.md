<h2 align="center">About Me</h2>

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
        expert: ["python", "js", "html", "processing"],
        intermediate: ["arduino", "SQL", "java", "css"],
        learning: ["c", "lua"]
      };

      const specialties = ["full-stack developement", "ai", "minecraft modding"];
      const ide = ["vscode", "intellij", "windows notepad", "pycharm"];

      return { langs, specialties, ide };
    }
  }
}

