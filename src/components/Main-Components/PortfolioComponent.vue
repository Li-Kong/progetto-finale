<template>
  <div id="our-work">
    <div class="row text-center">
      <p class="we-are-megaone">We are megaone company</p>
      <h3>We have designed some</h3>
      <h3>great projects</h3>
      <p class="about-us-text">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected.</p>
    </div>
    <div class="gallery-menu">
      <a @click="filterImages('all')">All</a>
      <a @click="filterImages('graphicdesign')">graphic design</a>
      <a @click="filterImages('webdesign')">Web design</a>
      <a @click="filterImages('seo')">Seo</a>
      <a @click="filterImages('marketing')">Marketing</a>
   </div>

    <div class="gallery">
      <img v-for="(image, index) in images" :key="index" class="image" :src="image.src" :alt="image.alt" :class="image.category" v-show="showImage(image.category)">
    </div>
  </div>
</template>

<script>
export default {
        name: 'PortfolioComponent',
        data() {
    return {
        images: [
                { src: require('@/assets/work-1.jpg'), alt: 'Immagine 1', category: 'graphicdesign' },
                { src: require('@/assets/work-2.jpg'), alt: 'Immagine 2', category: 'seo' },
                { src: require('@/assets/work-4.jpg'), alt: 'Immagine 3', category: 'graphicdesign' },
                { src: require('@/assets/work-3.jpg'), alt: 'Immagine 4', category: 'seo' },
                { src: require('@/assets/work-5.jpg'), alt: 'Immagine 5', category: 'webdesign' },
                { src: require('@/assets/work-6.jpg'), alt: 'Immagine 6', category: 'marketing' },
                { src: require('@/assets/work-7.jpg'), alt: 'Immagine 7', category: 'webdesign' },
                { src: require('@/assets/work-8.jpg'), alt: 'Immagine 8', category: 'marketing' }
            ],
      currentCategory: 'all'
    };
  },
  methods: {
    filterImages(category) {
      this.currentCategory = category;
    },
    showImage(category) {
      return this.currentCategory === 'all' || category === this.currentCategory;
    }
  },
  created() {
    this.filterImages('all');
  }
    }
</script>


<style scoped>
#our-work {
  max-width: 1000px;
  padding: 80px; 
  margin: 0 auto;
}

#our-work h3 {
    font-family: 'Montserrat', sans-serif;
    color: black;
    font-size: 40px;
    position: relative;
}

#our-work p {
    font-family: 'Roboto', sans-serif; 
    color: rgb(63, 61, 61);
    line-height: 30px;
}

.we-are-megaone {
    font-weight: 20px;
    font-size: 20px;
}

.about-us-text {
    font-weight:lighter;
}

.gallery-menu {
  text-align: center;
  padding: 10px;

}

.gallery-menu a {
  text-decoration: none;
  color: #3f61e9;
  padding: 10px 20px;
  margin: 0 10px;
  cursor: pointer;
  border-radius: 5px;
  transition: background-color 0.3s ease;
}

.gallery-menu a:hover {
  background-color: #f79ec0; 
}

.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  padding: 20px;
}

.image {
  max-width: 220px;
  width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
}
</style>
