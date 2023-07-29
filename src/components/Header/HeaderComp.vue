<script setup>
import './HeaderComp.css'
console.log('ok')
</script>

<template>
  <header class="header">
    <div class="container">
      <div class="header__wrapper">
        <router-link class="header__img-wrapper" to="/">
          <img
            src="/icons/header__logo.svg"
            alt="cinema logo"
            width="103"
            height="42"
            draggable="false"
          />
          <h1 class="header__title">CINEMAS</h1>
        </router-link>

        <nav class="nav">
          <ul class="header__nav-list">
            <li class="header__nav-item">
              <router-link class="header__nav-item-link" to="/" exact>Films</router-link>
            </li>
            <li class="header__nav-item">
              <router-link class="header__nav-item-link" to="/serials" class-active="active"
                >Serials</router-link
              >
            </li>
            <li class="header__nav-item">
              <router-link class="header__nav-item-link" to="/cartoons" class-active="active"
                >Cartoons</router-link
              >
            </li>
            <li class="header__nav-item">
              <router-link class="header__nav-item-link" to="/collections" class-active="active"
                >Collections</router-link
              >
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<style></style>
