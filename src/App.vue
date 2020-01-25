<template>
  <div id="app">
    <Nav/>
    <Home/>
    <Team/>
    <About/>
    <Klien/>
    <Produk/>
    <Kontak/>
    <Footer/>
  </div>
</template>

<script>
import Nav from './components/Navbar'
import Home from './components/Home'
import Team from './components/Team'
import About from './components/About'
import Klien from './components/Klien'
import Produk from './components/Produk'
import Kontak from './components/Kontak'
import Footer from './components/Footer'

export default {
  name: 'app',
  components: {
    Nav,Home,Team,About,Klien,Produk,Kontak,Footer
  },
}
</script>

<style>

</style>
