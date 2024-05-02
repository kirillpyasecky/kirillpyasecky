# Hello there 👋

```cpp
class SoftwareEngineer {
   public:
    SoftwareEngineer() 
        : name_{"Kirill Pyaseckiy"}
        , role_{"Software Engineer"}
        , language_spoken_{"en", "be", "ru"}
        , programming_languages_{"C++", "Python"}
        , skills_{"Assembler", "GDB", "Linux"} {
        SayHi();
    }

    void SayHi() {
        std::cout << "Thanks for dropping by, hope you find some of my work interesting.\n";
    }

   private:
    std::string name_;
    std::string role_;
    std::set<std::string> language_spoken_;
    std::set<std::string> programming_languages_;
    std::set<std::string> skills_;
};
```

## Projects

<a href="https://github.com/appa-labs/Achilles">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=appa-labs&repo=Achilles&show_icons=true&line_height=27" alt="kirillpyasecky" />
</a>
