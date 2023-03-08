<template>
  <HeaderComp/>

  <div class="first-screen">
    <div class="fs__info">
      <div>Передовая IT студия</div>
      <h1>Мы создаем легкие решения сложных задач и проблем</h1>

      <button>Наши проекты</button>
    </div>
  </div>

  <div class="services">
    <div class="services__info">
      <h2>Мы создаем мобильные приложения для крупных корпораций</h2>
      <p>Lorem Ipsum - это текст-"рыба", часто используемый в печати и вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для текстов на латинице с начала XVI века. </p>
    </div>
    
    <div class="services__projects">
      <ServiceProject headtext="Создание сайтов" msg='Lorem Ipsum - это текст- "рыба", часто используе в печати и вэб-дизайне.'/>
      <ServiceProject headtext="Создание сайтов" msg='Lorem Ipsum - это текст- "рыба", часто используе в печати и вэб-дизайне.'/>
      <ServiceProject headtext="Создание сайтов" msg='Lorem Ipsum - это текст- "рыба", часто используе в печати и вэб-дизайне.'/>
    </div>

    <button>Все услуги</button>
  </div>

  <div class="about-us">
    <div class="about-us__block">
        <div class="block__info">
          <div class="block__item">
            <h2>Высокие стандарты разработки</h2>
            <p>Lorem Ipsum - это текст-"рыба", часто используемый в печати и вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для текстов на латинице с начала XVI века.  стандартной "рыбой" для текстов на латинице с начала XVI века. </p>
            <a href="">Подробнее о компании</a>
          </div>

          <img src="./assets/img/about-us.png" alt="">
        </div>
        <hr>
    </div>

    <div class="about-us__projects">
      <projectComp title="125" info="Our projects"/>
      <projectComp title="125" info="Our projects"/>
      <projectComp title="125" info="Our projects"/>
      <projectComp title="125" info="Our projects"/>
      <projectComp title="125" info="Our projects"/>
    </div>

    <div class="all-services">
      <div class="all-services__block">
        <div class="all-services__info">
          <h2>Наши работы, на которых мы специализируемся</h2>
          <button>Все услуги</button>
        </div>

        <div class="all-services__items">
          <allServicesItem number="01. " title="Исследование и упаковка" info='Lorem Ipsum - это текст-"рыба", часто используемый в печати и вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для текстов на латинице с начала XVI века.'/>
          <allServicesItem number="02. " title="Исследование и упаковка" info='Lorem Ipsum - это текст-"рыба", часто используемый в печати и вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для текстов на латинице с начала XVI века.'/>
          <allServicesItem number="03. " title="Исследование и упаковка" info='Lorem Ipsum - это текст-"рыба", часто используемый в печати и вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для текстов на латинице с начала XVI века.'/>
        </div>
      </div>
      <hr>
  </div>

    <div class="all-project">
      <h2>Наши проекты</h2>
      <p>Lorem Ipsum - это текст-"рыба", часто используемый в печати и вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для текстов на латинице с начала XVI века. </p>
    
      <div class="all-project__items">
        <allProjectItem/>
        <allProjectItem/>
        <allProjectItem/>
        <allProjectItem/>
      </div>

      <button>Все проекты</button>
    </div>
  </div>

  <div class="video">
    <h2>Видео о нашей работе</h2>
    <p>Просто посмотрите, как мы работаем</p>

    <iframe width="970" height="430"
    src="https://www.youtube.com/embed/dQw4w9WgXcQ">
    </iframe>

    <hr>
  </div>

  <div class="subscribe">
    <h2>Подпишитесь на нашу рассылку</h2>
    <p>Полезные статьи, акции, новости - получите все это сейчас!</p>
    <form action="#" method="post">
      <input name="mail" type="text" placeholder="Ваш e-mail">
      <button type="submit">Подписаться</button>
    </form>
    <p>Мы не шлем спам, и передаем никому ваши данные.</p>
  </div>

  <footer>
    <div class="footer">
      <div class="contact-info">
        <h2>Контактная информация</h2>
        <div class="footer-item">
            <img src="./assets/img/icons/footer/mail.svg" alt="">
            <p>test@test.ru</p>
        </div>

        <div class="footer-item">
            <img src="./assets/img/icons/footer/call.svg" alt="">
            <p>+8 777 555 66 99</p>
        </div>

        <div class="footer-item">
            <img src="./assets/img/icons/footer/location.svg" alt="">
            <p>Москва, Бульвар Ленина 33</p>
        </div>
      </div>

      <div class="main-links">
        <h2>Основные ссылки</h2>
        <div class="footer-item">
            <img src="./assets/img/icons/footer/arrow.svg" alt="">
            <a href="#">Главная</a>
        </div>

        <div class="footer-item">
            <img src="./assets/img/icons/footer/arrow.svg" alt="">
            <a href="#">Наши проекты</a>
        </div>

        <div class="footer-item">
            <img src="./assets/img/icons/footer/arrow.svg" alt="">
            <a href="#">Наши проекты</a>
        </div>

        <div class="footer-item">
            <img src="./assets/img/icons/footer/arrow.svg" alt="">
            <a href="#">Контакты</a>
        </div>
      </div>

      <div class="our-projects">
        <h2>Наши проекты</h2>
        <div class="footer-item">
            <img src="./assets/img/icons/footer/arrow.svg" alt="">
            <a href="#">РосНано</a>
        </div>

        <div class="footer-item">
            <img src="./assets/img/icons/footer/arrow.svg" alt="">
            <a href="#">Сколково</a>
        </div>

        <div class="footer-item">
            <img src="./assets/img/icons/footer/arrow.svg" alt="">
            <a>Проект “Восток”</a>
        </div>

        <div class="footer-item">
            <img src="./assets/img/icons/footer/arrow.svg" alt="">
            <a href="#">ТЭЦ Калининграда</a>
        </div>
      </div>

      <div class="links">
        <h2>Социальные сети</h2>
        <div class="footer-item">
            <img src="./assets/img/icons/footer/arrow.svg" alt="">
            <a href="#">VK.com</a>
        </div>

        <div class="footer-item">
            <img src="./assets/img/icons/footer/arrow.svg" alt="">
            <a href="#">Instagram</a>
        </div>

        <div class="footer-item">
            <img src="./assets/img/icons/footer/arrow.svg" alt="">
            <a href="#">Facebook</a>
        </div>

        <div class="footer-item">
            <img src="./assets/img/icons/footer/arrow.svg" alt="">
            <a href="#">Twitter</a>
        </div>
      </div>
    </div>
   <hr>
  </footer>

  <div class="copy">(с) 2019. Все права защищены.</div>
</template>

<script>
  import HeaderComp from './components/HeaderComp.vue'
  import ServiceProject from './components/ServiceProject.vue'
  import projectComp from './components/projectComp.vue'
  import allServicesItem from './components/allServicesItem.vue'
  import allProjectItem from "./components/allProjectItem.vue";
  //import footerItem from "./components/footerItem.vue";

  export default {
    name: 'App',
    components: {
      HeaderComp,
      ServiceProject,
      projectComp,
      allServicesItem,
      allProjectItem,
      //footerItem
    }
  }
</script>