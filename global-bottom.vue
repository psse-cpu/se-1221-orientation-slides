<template>
  <footer
    class="absolute bottom-0 p-4 mt-auto flex justify-between items-center w-full text-primary dark:text-white z-10"
  >
    <div class="mb-0 flex items-center">
      <img
        src="/cpu.png"
        class="h-8 mr-1"
        alt="CPU Logo"
      />
      <img
        src="/se-logo.jpg"
        class="h-8 mr-1"
        alt="CPU Logo"
      />
      <img
        src="/engilogo.png"
        class="h-8 mr-1"
        alt="Engi Logo"
      />
    </div>
    
    <div id="socials" style="display: inline">
      <a href="https://twitter.com/myknbani"><logos-twitter /></a> 
      <a href="https://gitlab.com/myknbani"><logos-gitlab class="octocat" /></a> 
      <a href="https://github.com/myknbani"><logos-github-icon /></a> 
      @myknbani
    </div>
  </footer>
</template>

<style scoped>
#socials a {
  margin-right: 2px;
}

html:not(.dark) #socials {
  color: black;
}

html.dark #socials {
  color: white !important;
}
</style>