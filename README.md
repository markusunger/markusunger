## Hi there! 👋

I am a software engineer from Leipzig, Germany, currently working for [WTL Ventures](https://wtl.ventures/).

```typescript
export class PersonalProfile {
  readonly data = {
    firstName: "Markus",
    lastName: "Unger",
    age: 37,
  };

  constructor() {
    this.printInfo();
  }

  private printInfo() {
    console.log(JSON.stringify(this.data, undefined, 2));
    console.log(
      `Tech: ${[
        "JavaScript/TypeScript",
        "Ruby",
        "React/React Native/Redux/RxJS",
        "Node.js/Express",
        "HTML/CSS",
        "SQL/NoSQL",
      ].join(", ")}`
    );
    console.log("Other interests: 📸, 📖, 🎮, 🎲");
  }
}
```
