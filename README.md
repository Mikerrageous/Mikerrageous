<h1 align="center">Hi 👋, I'm Michael Kerr</h1>
<h3 align="center">A software developer with an interest in robotics</h3>

- 🔭 I’m currently working on **C++ & ROS Mobile Robots**

- 🌱 I’m currently learning **Gazebo, RViz**

- 📫 How to reach me **kerr.michaelandrew@gmail.com**

<table>
<tr>
<th>Profile.cpp</th>
<th>Profile.h</th>
</tr>
<tr>
<td>

```cpp
#include "Me.h"

std::map<std::string, std::regex> Response = {
  { HI_NAME, 
    std::regex("([Hh]i)|([Hh]ello)\\smy\\sname\\sis\\s(.+)")  },
  { IM_WELL, 
    std::regex("[Hh]ow\\sare\\syou.")},
};

int main(void)
{
  std::string Interaction;
  while (!sInteraction.empty())
  {
    std::cin >> Interaction;
    for ( auto ite = Response.begin(); 
          ite != Response.end(); ite++)
    {
      std::smatch Groups;
      if (std::regex_match(Interaction, Groups, ite->second))
      {
        switch (ite->first)
        {
        case HI_NAME:
          cout << "Hi" << Groups[1] << 
            ", my name is Mike!" << std::endl;
          break;
        case IM_WELL:
          cout << "I'm well, thanks. How are you?" << 
            std::endl;
          break;
        }
      }
    }
  }

  return 0;
}
```
</td>
<td>

```cpp
#include <Life.h>

enum class RESPONSES
{
  HI_NAME,
  IM_GREAT,
  HOW_ARE_YOU
};

class Mikerrageous : private cLife
{
private:
  std::vector<std::string> Secrets;
  std::vector<uint32_t> Passwords;    
  
protected:
  std::vector<unsigned int> PhoneNumber;

public:
  static void Email(std::string);
 
  Mikerrageous() { Birth(); };
  ~Mikerrageous() { Death(); };
};
```

</td>
</tr>
</table>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> 
  <a href="https://www.arduino.cc/" target="_blank"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> 
  <a href="https://www.gnu.org/software/bash/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Bash_Logo_Colored.svg" alt="bash" width="40" height="40"/> </a> 
  <a href="https://www.cprogramming.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" width="40" height="40"/> </a> 
  <a href="https://www.w3schools.com/cpp/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="Cplusplus" width="40" height="40"/> </a> 
  <a href="https://www.w3schools.com/cs/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="Csharp" width="40" height="40"/> </a> 
  <a href="https://cmake.org/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Cmake.svg" alt="CMake" width="40" height="40"/> </a> 
  <a href="http://gazebosim.org/" target="_blank"> <img src="http://gazebosim.org/assets/logos/gazebo_icon_pos-76b768ca51b0c24a5e5ddeb5a844baf3a3efc83e42affae355ed6ce9326707e4.svg" alt="Gazebo" width="40" height="40"/> </a> 
  <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> 
  <a href="https://www.linux.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> 
  <a href="https://www.mathworks.com/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="matlab" width="40" height="40"/> </a>  
  <a href="https://www.r-project.org/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/r-project/r-project-icon.svg" alt="R" width="40" height="40"/> </a> 
  <a href="https://www.ros.org/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/1/15/Robot_Operating_System_logo.svg" alt="ROS" width="40" height="40"/> </a> 
  <a href="https://www.python.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> 
  <a href="https://scikit-learn.org/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a>
</p>
