<template>
  <div class="about-page">
    <!-- Section 1: Hero Section -->
    <section class="hero-section">
      <img src="@/assets/image1ap.jpg" alt="Qui sommes-nous ?" class="hero-image"/>
      <h1>Qui sommes-nous ?</h1>
      <p>Thé Tip Top est né d'une passion pour le thé et d'une envie de partager cette passion avec le plus grand nombre. Depuis notre première boutique ouverte en 2010, nous nous efforçons de proposer des thés d'une qualité exceptionnelle, en sélectionnant les meilleures plantations à travers le monde.</p>
    </section>

    <!-- Section 2: Nos Valeurs -->
    <section class="content-section">
      <img src="@/assets/image2ap.jpg" alt="Nos Valeurs" class="section-image left-image"/>
      <div class="text-content">
        <h2>Nos Valeurs</h2>
        <p>Nous croyons en l'authenticité, la qualité, et la durabilité :</p>
        <ul>
          <li><strong>Authenticité</strong> : Chaque thé que nous proposons est une découverte unique, sélectionnée pour ses saveurs distinctives et son histoire.</li>
          <li><strong>Qualité</strong> : Nous collaborons directement avec des producteurs de thé pour garantir la fraîcheur et l'excellence de nos produits.</li>
          <li><strong>Durabilité</strong> : Nous nous engageons à pratiquer un commerce équitable et respectueux de l'environnement.</li>
        </ul>
      </div>
    </section>

    <!-- Section 3: Nos Produits -->
    <section class="content-section reverse-section">
      <img src="@/assets/image3ap.jpg" alt="Nos Produits" class="section-image right-image"/>
      <div class="text-content">
        <h2>Nos Produits</h2>
        <p>Chez Thé Tip Top, nous proposons une vaste gamme de thés :</p>
        <ul>
          <li><strong>Thés noirs</strong> : Robustes et riches en saveurs.</li>
          <li><strong>Thés verts</strong> : Délicats et rafraîchissants.</li>
          <li><strong>Infusions</strong> : Des mélanges pour se détendre et se revitaliser.</li>
          <li><strong>Coffrets cadeaux</strong> : Pour offrir ou se faire plaisir.</li>
        </ul>
      </div>
    </section>

    <!-- Section 4: Notre Engagement -->
    <section class="commitment-section">
      <h2>Notre Engagement</h2>
      <p>Nous sommes fiers de soutenir des pratiques durables et éthiques. Chaque tasse de thé que vous savourez contribue à améliorer la vie des cultivateurs et à protéger notre planète. Rejoignez-nous dans notre mission pour un avenir meilleur, une tasse à la fois.</p>
      <div class="image-gallery">
        <img src="@/assets/image4ap.jpg" alt="Engagement Image 1" class="gallery-image"/>
        <img src="@/assets/image5ap.jpg" alt="Engagement Image 2" class="gallery-image"/>
        <img src="@/assets/image6ap.jpg" alt="Engagement Image 3" class="gallery-image"/>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'AboutPage',
}
</script>

<style scoped>
.about-page {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

/* Hero Section */
.hero-section {
  text-align: center;
  margin-bottom: 40px;
}

.hero-section .hero-image {
  width: 80%; /* Ajusté à 80% de la largeur */
  max-width: 1000px; /* Limite la largeur maximale */
  border-radius: 10px;
  margin-bottom: 20px;
}

.hero-section h1 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.hero-section p {
  font-size: 1.2rem;
  color: #555;
}

/* Content Sections */
.content-section {
  display: flex;
  align-items: center;
  margin-bottom: 40px;
}

.content-section.reverse-section {
  flex-direction: row-reverse;
}

.section-image {
  flex: 1;
  width: 40%; /* Ajusté à 40% de la largeur */
  border-radius: 10px;
  margin-right: 20px;
}

.reverse-section .section-image {
  margin-right: 0;
  margin-left: 20px;
}

.text-content {
  flex: 2;
  text-align: left; /* Aligne le texte à gauche */
}

.text-content h2 {
  font-size: 1.8rem;
  margin-bottom: 10px;
  color: #333;
}

.text-content p, .text-content ul {
  font-size: 1rem;
  color: #555;
  margin-bottom: 10px;
}

.text-content ul {
  padding-left: 20px; /* Ajoute un padding pour les listes */
}

.text-content li {
  margin-bottom: 10px;
}

/* Commitment Section */
.commitment-section {
  text-align: center;
}

.commitment-section h2 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.commitment-section p {
  font-size: 1.2rem;
  color: #555;
  margin-bottom: 20px;
}

.image-gallery {
  display: flex;
  justify-content: center;
}

.gallery-image {
  width: 30%;
  border-radius: 10px;
  margin: 0 10px;
}
</style>
