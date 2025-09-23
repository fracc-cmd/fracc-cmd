## Hi there 👋
![Markdown Logo](/pc-ascii.jpg)

```c++
// -*- coding: utf-8 -*-
#include <iostream>
#include <string>

struct User {
  User(const std::string& name, const std::string& role) {
    this->name = name;
    this->role = role;
  }

  void present() {
    std::cout << "Hi! My name is " << name << ", I'm currently an " << role 
              << " with curiosity making ideas turn into real things!" << '\n'; 
  }

private:
  std::string name;
  std::string role;
};

int main() {
  User* me = new User("Cleberson", "Student");
  me->present();

  delete me;
  return 0;
}

```
