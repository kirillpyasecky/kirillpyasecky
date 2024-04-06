# Hello there 👋

```cpp
class SoftwareEngineer {
   public:
    SoftwareEngineer() 
        : name{"Kirill Pyaseckiy"}
        , role{"Software Engineer"}
        , language_spoken{"en", "be", "ru"}
        , programming_languages{"C++", "Python"}
        , skills{"Assembler", "GDB", "Linux"} {
        SayHi();
    }

    void SayHi() {
        std::cout << "Thanks for dropping by, hope you find some of my work interesting.\n";
    }

   private:
    std::string name;
    std::string role;
    std::set<std::string> language_spoken;
    std::set<std::string> programming_languages;
    std::set<std::string> skills;
};
```

## Projects

<a href="https://github.com/appa-labs/Achilles">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=appa-labs&repo=Achilles&show_icons=true&line_height=27" alt="kirillpyasecky" />
</a>
