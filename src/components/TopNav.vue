<template>
<div>
  <header id="wide_screen_nav_menu_wrapper">
    <nav id="wide_screen_nav_menu" class="nav-menu">
      <ul>
        <li class="nav-menu-item" data-section_id="skills_section">
          <router-link to="/">CV</router-link>
        </li>
        <li class="nav-menu-item" data-section_id="skills_section">
          <router-link to="/experience">Experiencia</router-link>
        </li>
<!--         <li class="nav-menu-item" data-section_id="skills_section">
          <router-link to="/skills">Habilidades</router-link>
        </li>
        <li class="nav-menu-item" data-section_id="skills_section">
          <router-link to="/experience">Experiencia</router-link>
        </li>
        <li class="nav-menu-item" data-section_id="skills_section">
          <router-link to="/contact">Contacto</router-link>
        </li> -->
        <li class="github-nav-item">
          <a href="https://github.com/giovannyg" target="_blank">
            <i class="nav-menu-icon icomoon-github"></i>
          </a>
        </li>
      </ul>
    </nav>
  </header>
  <header id="mobile_nav_menu_wrapper">
    <div>
      <div id="hamburguer_menu_icon">
        <label id="hamburguer_menu_toggle_label" for="hamburguer_menu_toggle">
          <span></span>
          <span></span>
          <span></span>
        </label>
      </div>
      <nav id="mobile_nav_menu" class="nav-menu">
        <input id="hamburguer_menu_toggle" type="checkbox" name="check" />
        <ul id="mobile_nav_menu_list" class="mobile-menu-list-hidden">
          <li class="nav-menu-item" data-section_id="skills_section">
            <router-link to="/">CV</router-link>
          </li>
<!--           <li class="nav-menu-item" data-section_id="skills_section">
            <router-link to="/skills">Habilidades</router-link>
          </li>
          <li class="nav-menu-item" data-section_id="skills_section">
            <router-link to="/experience">Experiencia</router-link>
          </li>
          <li class="nav-menu-item" data-section_id="skills_section">
            <router-link to="/contact">Contacto</router-link>
          </li> -->
          <li class="github-nav-item">
            <a href="https://github.com/giovannyg" target="_blank">
              <i class="nav-menu-icon icomoon-github"></i>
            </a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</div>
</template>