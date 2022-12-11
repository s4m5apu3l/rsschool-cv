# Viacheslav Ignatev

![my avatar](./img/avatar.jpg "avatar")

> u get what u give

## Contacts

**Discord:** asper#9841 [diskord user URL](https://discord.com/users/419482375165313025 "asper url")
**VK:** [slava asperatuz](https://vk.com/abahu "slava vk")

## About me
 
 Two stab wounds instead of eyes;) Just started to delve into the FrontEnd. Life quote *you get, what you give*. So i will work harder in the near future.
 My purpose is to become a good programmer, who will provide at least some benefit to the society

## Skills

 |Language   | Level % |
 |:----------|:-------:|
 |HTML 	     | 90/100  |
 |CSS        | 90/100  |
 |JavaScript | 70/100  |
 |Git        | 90/100  |
 |bitrix     | 70/100  |
 |PHP        | 30/100  |


## Code Example
```js
document.addEventListener("DOMContentLoaded", function () {
  const tabs = document.querySelector(".lower-block__tabs");
  const tabsBtn = document.querySelectorAll(".tabs-btn");
  const tabsContent = document.querySelectorAll(".tabs__content");

  if (tabs) {
    tabs.addEventListener("click", function (e) {
      if (e.target.classList.contains("tabs-btn")) {
        const tabsPath = e.target.dataset.tabsPath;
        tabsBtn.forEach((el) => {
          el.classList.remove("active-btn");
        });
        document.querySelector(`[data-tabs-path="${tabsPath}"]`).classList.add("active-btn");
        tabsHandler(tabsPath);
        document.querySelector('[data-tabs-target="' + tabsPath + '"]>.list>li>button').click();
      }
    });
  }

  const tabsHandler = (path) => {
    tabsContent.forEach((el) => {
      el.classList.remove("tabs__content-active");
    });
    document.querySelector(`[data-tabs-target="${path}"]`).classList.add("tabs__content-active");
  };
```
## Experience
[Мой профиль в GitHub](https://github.com/s4m5apu3l)

## Courses

**[Stepik HTML&CSS course](https://stepik.org/38218)**
**[RSSCHOOL stage#1](https://rs.school/js/)**

## Language

 |Language   | Level            |
 |:-------   |:------:          |
 |Russian    | Good             |
 |English    | Pre-Intermediate |
 |Yakutian   | Native           |

