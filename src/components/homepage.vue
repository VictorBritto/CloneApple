<script setup>
import "../assets/homepage.css";

</script>


<template>
  <header class="navbar">
    <div class="pagetop">
    <ul class="rotas">
      <img src="../assets/imagens/logo.png" alt="">
      <li><a>Loja</a></li>
      <li><a>Mac</a></li>
      <li><a>iPad</a></li>
      <li><a>Iphone</a></li>
      <li><a>Watch</a></li>
      <li><a>AirPods</a></li>
      <li><a>TV e Casa</a></li>
      <li><a>Entretenimento</a></li>
      <li><a>Acessórios</a></li>
      <li><a>Suporte</a></li>
      <li></li>
      <li><svg width="20px" height="20px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path
            d="M10 4a6 6 0 1 0 0 12 6 6 0 0 0 0-12zm-8 6a8 8 0 1 1 14.32 4.906l5.387 5.387a1 1 0 0 1-1.414 1.414l-5.387-5.387A8 8 0 0 1 2 10z"
            fill="#0D0D0D" />
        </svg></li>
      <br>
      <li><svg fill="#000000" width="20px" height="20px" viewBox="0 0 56 56" xmlns="http://www.w3.org/2000/svg">
          <path
            d="M 14.5586 51.9531 L 42.1445 51.9531 C 46.3633 51.9531 48.8008 49.5156 48.8008 44.6875 L 48.8008 20.4297 C 48.8008 15.6016 46.3398 13.1641 41.4414 13.1641 L 37.7148 13.1641 C 37.5742 8.2422 33.3086 4.0469 28.0117 4.0469 C 22.6914 4.0469 18.4258 8.2422 18.2852 13.1641 L 14.5586 13.1641 C 9.6836 13.1641 7.1992 15.5781 7.1992 20.4297 L 7.1992 44.6875 C 7.1992 49.5391 9.6836 51.9531 14.5586 51.9531 Z M 28.0117 7.6094 C 31.3164 7.6094 33.8242 10.0938 33.9414 13.1641 L 22.0820 13.1641 C 22.1758 10.0938 24.6836 7.6094 28.0117 7.6094 Z M 14.6289 48.1797 C 12.2852 48.1797 10.9726 46.9375 10.9726 44.5000 L 10.9726 20.6172 C 10.9726 18.1797 12.2852 16.9375 14.6289 16.9375 L 41.3945 16.9375 C 43.6914 16.9375 45.0274 18.1797 45.0274 20.6172 L 45.0274 44.5000 C 45.0274 46.9375 43.6914 48.1797 42.0742 48.1797 Z" />
        </svg></li>
    </ul>
  </div>
  </header>

  <div class="venda">
  <div class="listapple">
    <ul>
      <li>
        <a href="#">
          <img src="../assets/imagens/iphone_15_pro_light__diyvo6c7yu82_large.svg" alt="">
          <span>iPhone 15 Pro</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/imagens/iphone_15_pro_light__diyvo6c7yu82_large.svg" alt="">
          <span>iPhone 15</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/imagens/iphone14.svg" alt="">
          <span>iPhone 14</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/imagens/iphone_13_light__ewo3e0sf67o2_large.svg" alt="">
          <span>iPhone 13</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/imagens/iphone_se_light__fhg8duy6ffau_large.svg" alt="">
          <span>iPhone SE</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/imagens/iphone_compare_light__f4jj7brpbvm2_large.svg" alt="">
          <span>Comparar</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/imagens/airpods_light__8oj157p2476a_large.svg" alt="">
          <span>Airpods</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/imagens/airtag_light__cb2bmnv6aoeu_large.svg" alt="">
          <span>AirTag</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/imagens/accessories_light__ed5l6ipsevqu_large.svg" alt="">
          <span>Acessórios</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/imagens/iphone_ios_light__b8s4ws8o77iq_large.svg" alt="">
          <span>iOS 18</span>
          <span class="previa">Prévia</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/imagens/shop_iphone_light__b2toggskllle_large.svg" alt="">
          <span>Comparar iPhone</span>
        </a>
      </li>
    </ul>
  </div>
</div>


  <div class="parcelas">
    <p>Pague seu novo iPhone em até 12 parcelas ou economize 10% nos pagamentos à vista.<a class="link-saiba" href="https://www.apple.com/br/shop/browse/finance/installment"> Saiba mais > </a></p>
  </div>
  <div class="texto-venda">
    <h1>iPhone</h1>
    <h2>Pensado para encantar.</h2>
  </div>

  <div class="apresentacao" :style="videoStyle">
  <video 
  src="../assets/imagens/video.mp4" 
  autoplay muted loop>
  </video>
  </div>

  <div class="elemento-aparecer" ref="elemento">
    <div class="textop1">
      <h1>Conheça o iPhone.</h1>
    </div>
  </div>


</template>

<script>
export default {
  data() {
    return {
      scale: 1,
      visible: false,
    };
  },
  computed: {
    videoStyle() {
      return {
        transform: `scale(${this.scale})`,
        transition: 'transform 0.1s ease-out',
      };
    },
  },
  mounted() {
    window.addEventListener('scroll', this.handleScroll);
  },
  beforeDestroy() {
    window.removeEventListener('scroll', this.handleScroll);
  },
  methods: {
    handleScroll() {
      const scrollY = window.scrollY || document.documentElement.scrollTop;
      const newScale = Math.max(0.9, 1 - scrollY / 1000); // Ajustado para uma escala mais natural
      this.scale = newScale;

      //Parte do texto aparecendo conforme desce a pagina
      const elemento = this.$refs.elemento;
      const position = elemento.getBoundingClientRect().top;
      const windowHeight = window.innerHeight;

      if (position < windowHeight) {
        elemento.classList.add('aparecer');
      } else {
        elemento.classList.remove('aparecer');
      }
    },
  },
};
</script>
