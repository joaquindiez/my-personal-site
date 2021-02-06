<template>
  <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="about">
    <div class="w-100">
      <h1 class="mb-0">
        Joaquin
        <span class="text-primary">Diez</span>
      </h1>
      <div class="subheading mb-5">
        You can usually find me  in Madrid · Chamberi · 
        <a
          href="mailto:me@joaquindiez.com"
        >me at joaquindiez.com</a>
      </div>
      <p
        class="lead mb-5"
      >I am experienced in Amazon AWS, Java, Kotlin and some Vue.js. Tools that I use to help building amazing products like  

       <a
          href="https://finect.com"
          target="_blank"
          rel="noopener noreferrer"
        >Finect (Unience)</a>,  

      <a
          href="https://devo.com"
          target="_blank"
          rel="noopener noreferrer"
        >Devo</a>,  

         <a
          href="https://clarity.ai"
          target="_blank"
          rel="noopener noreferrer"
        >Clarity.ai</a>.
      
       I focus on solving problems, not only technical problems but organization problems, latelly I having more focus in management  as VP of Engineering 
       <a
          href="https://clarity.ai"
          target="_blank"
          rel="noopener noreferrer"
        >Clarity.ai</a>.
       </p>

       <p>
        
        Sometimes I write a newsletter, if you are interested 
        <a
          href="https://joaquindiezjournal.substack.com/"
          target="_blank"
          rel="noopener noreferrer"
        >Subscribe here</a>.

       

        </p>
    
      <div class="social-icons">
        <a href="https://linkedin.com/in/joaquindiez" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn Profile">
          <font-awesome :icon="['fab', 'linkedin']"/>
        </a>
        <a href="https://github.com/joaquindiez" target="_blank" rel="noopener noreferrer" aria-label="GitHub Profile">
          <font-awesome :icon="['fab', 'github']"/>
        </a>
        <a href="https://twitter.com/joaquindiez" target="_blank" rel="noopener noreferrer" aria-label="Twitter Profile">
          <font-awesome :icon="['fab', 'twitter']"/>
        </a>
        <!--
        <a href="https://loke.dev" target="_blank" rel="noopener noreferrer" aria-label="Loke.dev">
          <font-awesome :icon="['fas', 'rss']"/>
        </a>
        -->
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.social-icons a {
  cursor: pointer;
  display: inline-block;
  height: 3.5rem;
  width: 3.5rem;
  background-color: var(--secondary);
  color: #fff !important;
  border-radius: 100%;
  text-align: center;
  font-size: 1.5rem;
  line-height: 3.5rem;
  margin-right: 1rem;

  @media (max-width: 380px) {
    margin-right: 0.5rem;
  }

  @media (max-width: 350px) {
    margin-right: 0.2rem;
  }
}

.social-icons a:last-child {
  margin-right: 0;
}

.social-icons a:hover {
  background-color: var(--primary);
}
</style>
