<template>
  <div class="container">
    <header class="header">
      <img src="../assets/img/logo.png" alt="trillo logo" class="logo" />
      <form action="#" class="search">
        <input type="text" class="search__input" placeholder="Search Hotel" />
        <button class="search__button">
          <svg class="search__icon">
            <use xlink:href="../assets/sprite.svg#icon-magnifying-glass"></use>
          </svg>
        </button>
      </form>

      <nav class="user-nav">
        <div class="user-nav__icon-box">
          <img
            class="user-nav__icon"
            src="../assets/SVG/bookmark.svg"
            alt="Kiwi standing on oval"
          />
          <!-- <svg class="user-nav__icon">
            <use xlink:href="../assets/SVG/bookmark.svg"></use>
          </svg> -->
          <span class="user-nav__notification">7</span>
        </div>
        <div class="user-nav__icon-box">
          <!-- <svg class="user-nav__icon">
            <use xlink:href="../assets/SVG/chat.svg"></use>
          </svg> -->
          <img
            class="user-nav__icon"
            src="../assets/SVG/chat.svg"
            alt="Kiwi standing on oval"
          />
          <span class="user-nav__notification">13</span>
        </div>
        <div class="user-nav__user">
          <img
            src="../assets/img/user.jpg"
            alt="User photo"
            class="user-nav__user-photo"
          />
          <span class="user-nav__user-name">Jonas</span>
        </div>
      </nav>
    </header>
    <div class="content">
      <nav class="sidebar">
        <ul class="side-nav">
          <li class="side-nav__item side-nav__item--active">
            <a href="#" class="side-nav__link">
              <img
                src="../assets/SVG/home.svg"
                alt="User photo"
                class="side-nav__icon"
              />
              <span>Hotel</span>
            </a>
          </li>
          <li class="side-nav__item">
            <a href="#" class="side-nav__link">
              <img
                src="../assets/SVG/aircraft-take-off.svg"
                alt="User photo"
                class="side-nav__icon"
              />
              <span>Flight</span>
            </a>
          </li>
          <li class="side-nav__item">
            <a href="#" class="side-nav__link">
              <img
                src="../assets/SVG/key.svg"
                alt="User photo"
                class="side-nav__icon"
              />
              <span>Car rental</span>
            </a>
          </li>
          <li class="side-nav__item">
            <a href="#" class="side-nav__link">
              <img
                src="../assets/SVG/map.svg"
                alt="User photo"
                class="side-nav__icon"
              />
              <span>Tours</span>
            </a>
          </li>
        </ul>

        <div class="legal">&copy; 2017 by trillo. All right reserved.</div>
      </nav>
      <main class="hotel-view">Hotel Views</main>
    </div>
  </div>
</template>
