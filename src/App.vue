<template>

  <NavbarComponent />
  <JumbotronComponent />
  <AboutusComponent />
  <ServicesComponent />
  <CountersComponent />
  <TeamComponent />
  <CentralComponent />
  <PortfolioComponent />
  <ClientsComponent />
  <BlogComponent />
  <SponsorComponent />
  <MapComponent />
  <ContactComponent />
  <FooterComponent />

</template>

<script>
import NavbarComponent from './components/Header-Components/NavbarComponent.vue'
import JumbotronComponent from './components/Header-Components/JumbotronComponent.vue'
import AboutusComponent from './components/Main-Components/AboutusComponent.vue'
import ServicesComponent from './components/Main-Components/ServicesComponent.vue'
import CountersComponent from './components/Main-Components/CountersComponent.vue'
import TeamComponent from './components/Main-Components/TeamComponent.vue'
import CentralComponent from './components/Main-Components/CentralComponent.vue'
import PortfolioComponent from './components/Main-Components/PortfolioComponent.vue'
import ClientsComponent from './components/Main-Components/ClientsComponent.vue'
import BlogComponent from './components/Main-Components/BlogComponent.vue'
import SponsorComponent from './components/Main-Components/SponsorComponent.vue'
import MapComponent from './components/Main-Components/MapComponent.vue'
import ContactComponent from './components/Main-Components/ContactComponent.vue'
import FooterComponent from './components/Footer-Components/FooterComponent.vue'

export default {
  name: 'App',
  components: {
    NavbarComponent,
    JumbotronComponent,
    AboutusComponent,
    ServicesComponent,
    CountersComponent,
    TeamComponent,
    CentralComponent,
    PortfolioComponent,
    ClientsComponent,
    BlogComponent,
    SponsorComponent,
    MapComponent,
    ContactComponent,
    FooterComponent,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
</style>
