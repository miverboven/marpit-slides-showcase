---
marp: true
title: Windows Server Essentials
theme: base-theme
style: |
  header img {
    background-color: #00a0ae;
    color: #00a0ae;
  }

  footer {
    background-color: #fff;
    color: #203f63;
    float: left;
    left: 0px;
    right: 0px;
    bottom: 0px;
    height: 80px;
    text-align: right;
    font-size: 30px;
    padding-top: 18px;
    padding-right: 122px;
  }
  
  footer img {
    position: absolute;
    padding-top: 4px;
    padding-left: 10px;
  }
---

<!--
_backgroundColor: #00a0ae
_backgroundImage: url(https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1280px-Markdown-mark.svg.png)
_backgroundSize: 250px
_backgroundPosition: 92% 5%
_backgroundOpacity: 0.5
_color: #fff
_class: startslide
_header: ![w:200](https://www.thomasmore.be/sites/www.thomasmore.be/files/tm_vignet_rgb.png)
_footer: Michiel Verboven ![h:37.625 w:88.625](https://associatie.kuleuven.be/logo/asso-logo-rgb.jpg)
-->


## <!--fit--> Markdown Slides 

# Using the Marpit framework to transform Markdown into slides


---
<!-- paginate: true -->

## Installation

- Download *Visual Studio Code*, and install
- In VSCode, add the **Marp for VSCode** extension
    - Click the square-icon on the left
    - Search for PowerShell
    - Install the extension made by Marp team
    - Click the blue “Reload” button that replaces “Install” ⚠️


![Screenshot bg right:40% 85%](./img/Extensions.png)

---

## Codeblocks

Inserting code on slides:
```python
my_list = ['p','r','o','b','e']
# Output: p
print(my_list[0])
# Output: o
print(my_list[2])
# Output: e
print(my_list[4])
```

---

## LaTeX math

Doing some Data Science? No problem! 

Render inline math such as $ax^2+bc+c$.
Or blocks such as:
$$ I_{xx}=\int\int_Ry^2f(x,y)\cdot{}dydx $$

$$
f(x) = \int_{-\infty}^\infty
    \hat f(\xi)\,e^{2 \pi i \xi x}
    \,d\xi
$$