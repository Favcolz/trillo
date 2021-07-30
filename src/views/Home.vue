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
      <main class="hotel-view">
        <div class="gallery">
          <figure class="gellery__item">
            <img
              src="../assets/img/hotel-1.jpg"
              alt="hotel 1"
              class="gallery__photo"
            />
          </figure>
          <figure class="gellery__item">
            <img
              src="../assets/img/hotel-2.jpg"
              alt="hotel 2"
              class="gallery__photo"
            />
          </figure>
          <figure class="gellery__item">
            <img
              src="../assets/img/hotel-3.jpg"
              alt="hotel 3"
              class="gallery__photo"
            />
          </figure>
        </div>

        <div class="overview">
          <h1 class="overview__heading">Hotel Las Palmas</h1>
          <div class="overview__stars">
            <img
              src="../assets/SVG/star.svg"
              alt="User photo"
              class="overview__icon-star"
            />
            <img
              src="../assets/SVG/star.svg"
              alt="User photo"
              class="overview__icon-star"
            />
            <img
              src="../assets/SVG/star.svg"
              alt="User photo"
              class="overview__icon-star"
            />
            <img
              src="../assets/SVG/star.svg"
              alt="User photo"
              class="overview__icon-star"
            />
            <img
              src="../assets/SVG/star.svg"
              alt="User photo"
              class="overview__icon-star"
            />
          </div>
          <div class="overview__location">
            <img
              src="../assets/SVG/location-pin.svg"
              alt="User photo"
              class="overview__icon-location"
            />
            <button class="btn-inline">Albufeira, Portugel</button>
          </div>
          <div class="overview__rating">
            <div class="overview__rating-average">8.6</div>
            <div class="overview__rating-count">429 vote</div>
          </div>
        </div>
      </main>
    </div>
  </div>
</template>
