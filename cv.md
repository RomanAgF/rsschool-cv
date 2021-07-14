

##  Roman Agadjanyan

#### Contacts:
___

- Mobile phone: +79201118587
- Telegram: @exmuzz
- E-mail: vatavsem@gm
- Vkontakte: https://vk.com/dr.felixovichail.com

#### About Me
___

I want to become a full stack developer. I recently graduated from a Javascript training course at Orion Innovation and I defended my thesis on June 30. Before that, I was engaged in self-study, made my own projects, and helped friends with the layout of websites. During the training process I always liked programming, learning new technologies, and immediately applying them in practice. I entered this course at RSSchool because I want my dream to come true. I will make every effort to make this a reality.

#### Tech skills:
___
- HTML/CSS
- JavaScript (ES6+), jQuery
- Sass/Scss
- Canvas
- Bootstrap
- BEM
- Git/Github

#### Soft skills:
___
- Sociability
- The ability to quickly find information on the Internet to solve tasks
- Good knowledge of the English language
- Love to learn new technologies

#### Code Example:

##### HTML
```
  <div class="container">
    <div class="sidebar">
      <div style="background: linear-gradient(229.99deg, #11DEE9 -26%, #017E8B 145%);">
        <h1>Snow in the desert</h1>
        <p>Love, death & robots</p>
      </div>
      <div style="background: linear-gradient(215.32deg, #cc4042 -1%, #9E0706 124%);">
        <h1>Life Hutch</h1>
        <p>Love, death & robots</p>
      </div>
      <div style="background: linear-gradient(221.87deg, #6d1bb1 1%, #5305AF 128%);">
        <h1>Zima Blue</h1>
        <p>Love, death & robots</p>
      </div>
      <div style="background: linear-gradient(220.16deg, #ffe734 -8%, #F39102 138%);">
        <h1>Automated Customer Service</h1>
        <p>Love, death & robots</p>
      </div>
    </div>
    <div class="main-slide">
      <div style="
            background-image: url('https://images.unsplash.com/photo-1624388621600-02c079b3d6c0?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=609&q=80');
          "></div>
      <div style="
            background-image: url('https://images.unsplash.com/photo-1624132821166-91e7687cf675?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80');
          "></div>
      <div style="
            background-image: url('https://images.unsplash.com/photo-1513829596324-4bb2800c5efb?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=2550&q=80');
          "></div>
      <div style="
            background-image: url('https://images.unsplash.com/photo-1520263115673-610416f52ab6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1950&q=80');
          "></div>
    </div>
    <div class="controls">
      <button class="down-button">
        <i class="fas fa-arrow-down"></i>
      </button>
      <button class="up-button">
        <i class="fas fa-arrow-up"></i>
      </button>
    </div>
  </div>
```
##### CSS

```
@import url('https://fonts.googleapis.com/css?family=Roboto&display=swap');

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Roboto', sans-serif;
  height: 100vh;
}

.container {
  position: relative;
  overflow: hidden;
  width: 100vw;
  height: 100vh;
}

.sidebar {
  height: 100%;
  width: 35%;
  position: absolute;
  top: 0;
  left: 0;
  transition: transform 0.5s ease-in-out;
}

.sidebar > div {
  height: 100%;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: #fff;
}

.sidebar h1 {
  font-size: 40px;
  margin-bottom: 10px;
  margin-top: -30px;
}

.main-slide {
  height: 100%;
  position: absolute;
  top: 0;
  left: 35%;
  width: 65%;
  transition: transform 0.5s ease-in-out;
}

.main-slide > div {
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  height: 100%;
  width: 100%;
}
```

##### Javascript
```
const upBtn = document.querySelector(".up-button");
const downBtn = document.querySelector(".down-button");
const sideBar = document.querySelector(".sidebar");
const container = document.querySelector(".container");
const mainSlide = document.querySelector(".main-slide");

const slidesCount = mainSlide.querySelectorAll("div").length;

let activeSlideIndex = 0;

sideBar.style.top = `-${(slidesCount - 1) * 100}vh`;

upBtn.addEventListener("click", () => {
  changeSlide("up");
});
downBtn.addEventListener("click", () => {
  changeSlide("down");
});

document.addEventListener("keydown", (event) => {
  if (event.key === "ArrowUp") {
    changeSlide("up");
  } else if (event.key === "ArrowDown") {
    changeSlide("down");
  }
});

function changeSlide(direction) {
  if (direction === "up") {
    activeSlideIndex++;
    if (activeSlideIndex === slidesCount) {
      activeSlideIndex = 0;
    }
  } else if (direction === "down") {
    activeSlideIndex--;
    if (activeSlideIndex < 0) {
      activeSlideIndex = slidesCount - 1;
    }
  }
  const height = container.clientHeight;
  mainSlide.style.transform = `translateY(-${activeSlideIndex * height}px)`;
  sideBar.style.transform = `translateY(${activeSlideIndex * height}px)`;
}

```

#### Programming Experience:
___

I’ve finished a couple of freelance projects and several projects in the course of training. Latest of them are: ...

#### Education:
___

- NGMA (Nighniy Novgorod, Russia)
- Youtube courses and video (Vladilen Minin, Ivan Petrichenko)
- HTMLAcademy
- Stepik
- Orion Innovation Education Centre (Javascript)
- The Rolling Scopes School (currently)

#### English:
___

I studied at school in advanced English classes. After my schooling I got level-placed at the university. I practice a lot daily by reading and watching content in English. I also used to teach English (for a couple of months). I recently completed international English proficiency testing : https://www.efset.org/ef-set-50. My level of English is B2 Upper Intermediate according to the Common European Framework of Reference (CEFR).



